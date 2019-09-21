## Vue-LTA Project##

### Basix Admin Project ###
see basix-admin/README.md

### LTA-API
headers = {
 'AccountKey' : 'fpMbyoB/QFmt2tHAsUJJ6Q==',
 'accept' : 'application/json'
} #this is by default

### API parameters
uri = 'http://datamall2.mytransport.sg/' ###Resource URL
path = '/ltaodataservice/BusRoutes?' 

### Example
Bus Route
```
curl   --header -H "accept:application/json" -H "AccountKey:fpMbyoB/QFmt2tHAsUJJ6Q=="   'http://datamall2.mytransport.sg/ltaodataservice/BusRoutes?147'
```

Bus Stops
```
curl   --header -H "accept:application/json" -H "AccountKey:fpMbyoB/QFmt2tHAsUJJ6Q=="   'http://datamall2.mytransport.sg/ltaodataservice/BusStops'
```
