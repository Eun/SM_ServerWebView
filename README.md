# ServerWebView
Provides the posibility to view some metadata about your sourcemod driven server, via HTTP.

ConVars

    sm_swv_version -- Prints the SWV Version
    sm_swv_port -- HTTP Port to use (0 = tv_port) 
    sm_swv_update -- Update data every x minutes (lazy call)


# Some Notes
The data is only updated if one a client requests data. (lazy, passive mode)  
Done in 4 hours, so please be nice!  
There is a lot todo e.g.:
* Make a HTTP Server module
* Get the requested path
* Block invalid calls
* ...

If you want to help out, please do so!
