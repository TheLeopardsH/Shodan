# Shodan
For Github syntax: https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

Filters for Shodan Search engine to find vulnerbilities devices connected to internet

Basic Search Filters
```
#port: Search by specific port
example: port:21
```
```
#ssl: finding ssl certificates
example: ssl:"target"
```
```
#net: Search based on an IP/CIDR
example : net:210.214.0.0/16
```
```
#hostname: Locate devices by hostname
example: hostname:"ethz.ch"
```
![Hostname_shodan](https://github.com/TheLeopardsH/Shodan/blob/master/hostname.PNG)

#City: Locate devices by city
example:  city:"Islamabad"

#Country: Locate devices by country
example: country:"PK"

#geo: Locate devices by coordinates
example: geo:"33.6429,72.9927"   //33.6429° N, 72.9927° E

#server:For finding servers
example: server: "gws"

#os :search based on operating system
os:"windows 10"

org: Search by organization
example org:nestle

before/after: Timeframe delimiter

hash: Search based on banner hash

has_screenshot:true Filter search based on a screenshot being present
example: has_Screenshot:true country:"US"
title: Search based on text within the title
example: title:"citrix gateway"
``` 



