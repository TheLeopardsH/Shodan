# Shodan
For Github syntax: https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

Filters for Shodan Search engine to find vulnerbilities devices connected to internet

Basic Search Filters
```
#port: Search by specific port
example: port:21
```
~[](https://github.com/TheLeopardsH/Shodan/blob/master/port.PNG)
```
#ssl: finding ssl certificates
example: ssl:"target"
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/sl.PNG)
```
#net: Search based on an IP/CIDR
example : net:210.214.0.0/16
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/net.PNG)
```
#hostname: Locate devices by hostname
example: hostname:"ethz.ch"
```
![Hostname_shodan](https://github.com/TheLeopardsH/Shodan/blob/master/hostname.PNG)
```
#City: Locate devices by city
example:  city:"Islamabad"
```
![City](https://github.com/TheLeopardsH/Shodan/blob/master/city.PNG)
```
#Country: Locate devices by country
example: country:"PK"
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/country.PNG)
```
#geo: Locate devices by coordinates
example: geo:"33.6429,72.9927"   //33.6429° N, 72.9927° E
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/geo.PNG)
```
#server:For finding servers
example: server: "gws"
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/servers.PNG)
```
#os :search based on operating system
os:"windows 10"
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/os.PNG)
```
org: Search by organization
example org:nestle
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/org.PNG)
before/after: Timeframe delimiter

hash: Search based on banner hash
```
has_screenshot:true Filter search based on a screenshot being present
example: has_Screenshot:true country:"US"
```
![](https://github.com/TheLeopardsH/Shodan/blob/master/has_screenshot.PNG)
```
title: Search based on text within the title
example: title:"tesla"
``` 
~[](https://github.com/TheLeopardsH/Shodan/blob/master/title.PNG)



