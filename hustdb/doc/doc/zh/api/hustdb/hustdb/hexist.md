## hexist ##

**接口:** `/hustdb/hexist`

**方法:** `GET`

**参数:** 

*  **tb** （必选）  
*  **key** （必选）  

**使用范例A:**

    curl -i -X GET "http://localhost:8085/hustdb/hexist?tb=test_table&key=test_key"

**结果范例A1:**

	HTTP/1.1 412 Precondition Failed //tb maybe not hash，reject hash request；or tb not exist
	Version: 0
	VerError: false

**结果范例A2:**

	HTTP/1.1 404 Not Found
	Version: 0
	
**结果范例A3:**

	HTTP/1.1 200 OK
	Version: 1

[上一级](../hustdb.md)

[根目录](../../../index.md)