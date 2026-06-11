# Distance to zone
This template sensor calculates the distance of a person to a specific zone. Useful helper for creating "coming home automations".
Unit of measurement: km
deviceclass: distance
stateclass: measurement


Value template:
```
{%- set person_lat = state_attr('person.me', 'latitude') -%}
{%- set person_lon = state_attr('person.me', 'longitude') -%}
{%- set zone_lat  = state_attr('zone.home', 'latitude') -%}
{%- set zone_lon  = state_attr('zone.home', 'longitude') -%}
{{ distance(person_lat, person_lon, zone_lat, zone_lon) | round(3) }}
```

Availability template:
```
{{
  state_attr('person.me', 'latitude') is not none and
  state_attr('person.me', 'longitude') is not none and
  state_attr('zone.home', 'latitude') is not none and
  state_attr('zone.home', 'longitude') is not none
}}
```
