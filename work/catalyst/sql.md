Convert BIGINT to datetime
```sql

select API_ID, API_NAME,
dateadd(s, convert(bigint, DEPRECATION_DATE) / 1000, convert(datetime, '1-1-1970 00:00:00'))
from CATALYST_APIS_VERSION cav
order by api_name;
```