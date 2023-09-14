# inr_geo_map
GeoJSON file per mappe INR

Server che ospita gestionaleinr.it
- definito cron che lancia lo script export_geojson_piazze con parametro type NAZ
- definito cron che lancia lo script export_geojson_piazze con parametro type 365

Lo script genera due geoJson distinti per le piazze Nazionali e per Io Non Rischio 365 depositandoli nelle due cartelle distinte
