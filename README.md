# python-calendarific
Official Python library for [Calendarific](https://calendarific.com) Global Holiday API

## Installation

```shell
pip install python-calendarific
```

## Usage

```python
import calendarific

calapi = calendarific.v2('_REPLACE_WITH_API_KEY_')

parameters = {
	# Required
	'country': 'US',
	'year':    2019,
}

holidays = calapi.holidays(parameters)
```
