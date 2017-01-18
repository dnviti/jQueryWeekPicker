# jQueryWeekPicker
Week Picker element for jQuery UI

To use it on a SQL select here's the pattern:

```sql
select
'<span class="displayWeek">'
|| week_field
|| '</span><input type="hidden" value="week_field" id="id_field" />'
|| '<i class="fa fa-calendar showCalendar" aria-hidden="true"
    style="cursor:pointer;margin-left: 10px;"
    onclick="javascript:showWeekCalendar(this, additionalFunction);"></i>'
as "WeekPicker"
from dual
```
