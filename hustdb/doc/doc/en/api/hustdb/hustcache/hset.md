## hset ##

**Interface:** `/hustcache/hset`

**Method:** `GET | POST`

**Parameter:** 

*  **tb** (Required)  
*  **key** (Required)  
*  **val** (Required, GET: val is argument or POST: val is body)  

**Sample A:**

    curl -i -X GET "http://localhost:8085/hustcache/hset?tb=test_table&key=test_key&val=test_val"

**Result A1:**

	HTTP/1.1 200 OK

[Previous](../hustcache.md)

[Home](../../../index.md)