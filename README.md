# 4d-tips-get-index-information
Example of running VERIFY CURRENT DATA FILE from a client and parsing its contents. 

About
---
v14 Component (only v14 feature used is ```object variable``` to print the results).

1. Runs [VERIFY CURRENT DATA FILE](http://doc.4d.com/4Dv15/4D/15/VERIFY-CURRENT-DATA-FILE.301-2007576.en.html) on server. 

2. Parses the resulting XML.

3. Create a JSON array containing the index type, number and array of table / field names.

**Note**: Until v13, the ```_INDEX_ID``` [system virtual field](http://doc.4d.com/4Dv15/4D/15/System-Tables.300-2288116.en.html) contained the UUID, not number. 

Example
---
![](https://github.com/miyako/4d-tips-get-index-information/blob/master/images/json.png)
