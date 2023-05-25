<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

# SyntheticDataGenerator

SyntheticDataGenerator: A Python library for data analysts to generate synthetic datasets

# Example usage

```
column_specs = [
    ('Column1', 'int'),
    ('Column2', 'float'),
    ('Column3', 'str'),
    ('Column4', 'date'),
    ('Column5', 'int_uniq'),
    ('Column6', 'bool')
]
num_rows = 10
include_nulls = False
str_categories = ['apple', 'banana', 'cherry', 'orange']
start_date = '2022-01-01'
end_date = '2022-12-31'

df = generate_synthetic_data(column_specs, num_rows, include_nulls, str_categories, start_date, end_date)

print(df)
```

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/sonne2023"><img src="https://avatars.githubusercontent.com/u/129782624?v=4?s=100" width="100px;" alt="Natalia Chernikova"/><br /><sub><b>Natalia Chernikova</b></sub></a><br /><a href="https://github.com/eeealesha/SyntheticDataGenerator/commits?author=sonne2023" title="Code">💻</a> <a href="#content-sonne2023" title="Content">🖋</a> <a href="https://github.com/eeealesha/SyntheticDataGenerator/issues?q=author%3Asonne2023" title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
