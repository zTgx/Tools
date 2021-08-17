```shell
curl -o /dev/null -s -w "http_code: %{http_code}\ntime_connect: %{time_connect}\ntime_starttransfer: %{time_starttransfer}\ntime_namelookup:%{time_namelookup}\ntime_total:%{time_total}\n" https://www.baidu.com
```

--->
output:
```shell
http_code: 200
time_connect: 0.049425
time_starttransfer: 0.137039
time_namelookup:0.033465
time_total:0.137167
```
