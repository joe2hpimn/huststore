## keys ##

**Interface:** `/keys`

**Method:** `GET`

**Parameter:** 

*  **peer** (Required)  
This represents the indexes of backend servers. See more details in [peer_count](peer_count.md)
*  **offset** (Required) 
*  **size** (Required)
*  **file** (Required)
*  **start** (Optional)
*  **end** (Optional)
*  **noval** (Optional)
*  **async** (Optional)

This interface is a proxy interface for `/hustdb/keys`. See more details in [here](../hustdb/hustdb/keys.md).  

**Sample:**

See more details in the example test script:  
Script path: `hustdb/ha/nginx/test/fetch.py`

[Previous](../ha.md)

[Home](../../index.md)