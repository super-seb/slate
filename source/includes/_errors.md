# Errors

Nuonic APIs use the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request is invalid
401 | Unauthorized -- Your API key is invalid
403 | Forbidden -- You are not authorized to access the resource you have requested
404 | Not Found -- The requested resource could not be found
405 | Method Not Allowed -- You have used an invalid method for this endpoint
406 | Not Acceptable -- You requested a format that isn't json
429 | Too Many Requests -- Slow down
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarially offline for maintanance. Please try again later.
