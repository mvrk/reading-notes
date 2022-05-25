
## Local storage history

- cookies
- userData
- 2002 flash cookies local shared objects
- 2007 Google Gears provides an API to an embedded SQL database.
- dojox.storage

## HTML5 STORAGE

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 

- Track changes of storage area
  >you can trap the storage event. The storage event is fired on the window object whenever ```setItem()```, ```removeItem()```, or ```clear()``` is called and actually changes something. 


  
- LIMITATIONS IN CURRENT BROWSERS
  >5 megabytes
  >QUOTA_EXCEEDED_ERR
  >no browser supports any mechanism for web developers to request more storage space.
  - with HTML5 Storage, we can save the progress locally, within the browser itself.
  - IndexDB
  - Web SQL Database