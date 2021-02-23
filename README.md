# modx-store-locator

> MODX 2.8 - MIGX Db Store Locator

1. Install MIGX
2. Follow the guide to install my package - https://docs.modx.com/3.x/en/extras/migxdb/migxdb.tutorials/create-a-basic-gallery-management-from-scratch-with-migxdb
3. For a table listing use this on your template

```
[[!migxLoopCollection? 
&packageName=`storelocator` 
&classname=`storelocatorItem` 
&sortConfig=`[{"sortby":"id","sortdir":"ASC"}]` 
&where=`{"state":"AL","published":"1"}`
&tpl=`locator-rows`
]]
```
