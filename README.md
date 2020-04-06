# Covid19 Cuba Data

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg?label=license)](https://opensource.org/licenses/MIT) [![Last commit](https://img.shields.io/github/last-commit/covid19cuba/covid19cuba.github.io.svg?style=flat)](https://github.com/covid19cuba/covid19cuba.github.io/commits) [![GitHub commit activity](https://img.shields.io/github/commit-activity/m/covid19cuba/covid19cuba.github.io)](https://github.com/covid19cuba/covid19cuba.github.io/commits) [![Github Stars](https://img.shields.io/github/stars/covid19cuba/covid19cuba.github.io?style=flat&logo=github)](https://github.com/covid19cuba/covid19cuba.github.io) [![Github Forks](https://img.shields.io/github/forks/covid19cuba/covid19cuba.github.io?style=flat&logo=github)](https://github.com/covid19cuba/covid19cuba.github.io) [![Github Watchers](https://img.shields.io/github/watchers/covid19cuba/covid19cuba.github.io?style=flat&logo=github)](https://github.com/covid19cuba/covid19cuba.github.io) [![GitHub contributors](https://img.shields.io/github/contributors/covid19cuba/covid19cuba.github.io)](https://github.com/covid19cuba/covid19cuba.github.io/graphs/contributors) ![.github/workflows/main.yml](https://github.com/covid19cuba/covid19cubadata.github.io/workflows/.github/workflows/main.yml/badge.svg)

Fork of https://covid19cubadata.github.io to check data and generate other more comfortable and versioned data from the original data using GitHub Actions.

## Endpoints

> IMPORTANT!!! All the JSON displayed in the README are only to show the structure, they do not correspond to real data. To see the real data of the endpoints consult them.

### Affected municipalities ordered from highest to lowest

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/affected_municipalities.json

```json
[
  {"value": 10, "name": "Boyeros", "province": "La Habana", "total": 350},
]
```

### Affected provinces ordered from highest to lowest

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/affected_provinces.json

```json
[
  {"value": 108, "name": "La Habana", "total": 350},
]
```

### Cases diagnosed by contagion mode

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/cases_by_mode_of_contagion.json

```json
{
  "imported": {"name": "Importados", "value": 140},
  "inserted": {"name": "Introducidos", "value": 206},
  "autochthonous": {"name": "Autóctonos", "value": 0},
  "unknown": {"name": "Desconocidos", "value": 4}
}
```

### Cases diagnosed by nationality (cubans, foreign, unknown)

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/cases_by_nationality.json

```json
{
  "foreign": {"name": "Extranjeros", "value":32},
  "cubans": {"name": "Cubanos", "value":318},
  "unknown": {"name": "No reportados", "value":0}
}
```

### Cases diagnosed by sex

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/cases_by_sex.json

```json
{
  "men": {"name": "Hombres", "value": 180},
  "women": {"name": "Mujeres", "value": 170},
  "unknown": {"name": "No Reportados", "value": 0}
}
```

### Comparison of accumulated cases diagnosed from Cuba with other countries.

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/comparison_of_accumulated_cases.json

```json
{
  "countries": {
      "Afghanistan": [281,299,349],
      "Albania": [304,333,361],
      "Cuba": [288,320,350]
  },
  "updated":"2020/04/5"
}
```

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/distribution_by_age_ranges.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/distribution_by_nationality_of_foreign_cases.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/evolution_of_cases_by_days.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/evolution_of_deaths_by_days.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/evolution_of_recovered_by_days.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/list_of_tests_performed.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/map_data.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/note.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/resume.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/tests_by_days.json
https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/updated.json

https://covid19cuba.github.io/covid19cubadata.github.io/api/v1/all.json
