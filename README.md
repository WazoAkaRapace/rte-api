# Python wrapper for RTE API
Friendly wrapper to login and retrieve information from RTE.

```python
from rte-api import rteApi

api = rteApi("token")
calendar = api.get_calendar()
print(calendar[0]) #today (BLUE,WHITE,RED)
print(calendar[1]) #tomorrow (BLUE,WHITE,RED,UNKNOWN)
```