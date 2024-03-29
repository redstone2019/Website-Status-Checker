## Website-Status-Checker 
This tool will use the command line to tell you information. 
![Example of a Program Run](https://cdn.discordapp.com/attachments/757644490952540331/818684107490984006/unknown.png)
*Example of a Program Run*
## Installing
In order to run it download by clicking [releases](https://github.com/redstone2019/Website-Status-Checker/releases/latest). **Take note of where it downloads to.**
## Using The Tool
If you just run the exe it will default to google.com. 
### Windows
| To use a different url open a cmd.exe window |
|----------------------------------------------|

Go to the directory of the file `cd C:\"Where you downloaded the program to"`

Run `wsc_win.exe -url="URL beginning with http:// or https://"`
### Other OS Types
| Currently this tool only supports Microsoft Windows but I plan to add more OS types in the future. |
|----------------------------------------------------------------------------------------------------|
## HTTP Status Codes [More About Them Here](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)
This section will tell you what each code from the software means.
## 10.2 Successful 2xx
This class of status code indicates that the client's request was successfully received, understood, and accepted.
### 10.2.1 200 OK
The request has succeeded.
### 10.2.3 202 Accepted
The request has been accepted for processing, but the processing has not been completed.
## 10.5 Server Error 5xx
Response status codes beginning with the digit "5" indicate cases in which the server is aware that it has erred or is incapable of performing the request.
### 10.5.1 500 Internal Server Error
The server encountered an unexpected condition which prevented it from fulfilling the request.
### 10.5.2 501 Not Implemented
The server does not support the functionality required to fulfill the request. This is the appropriate response when the server does not recognize the request method and is not capable of supporting it for any resource.
### 10.5.3 502 Bad Gateway
The server, while acting as a gateway or proxy, received an invalid response from the upstream server it accessed in attempting to fulfill the request.
### 10.5.4 503 Service Unavailable
The server is currently unable to handle the request due to a temporary overloading or maintenance of the server.
### 10.5.5 504 Gateway Timeout
The server, while acting as a gateway or proxy, did not receive a timely response from the upstream server specified by the URI or some other auxiliary server it needed to access in attempting to complete the request.
### 10.5.6 505 HTTP Version Not Supported
The server does not support, or refuses to support, the HTTP protocol version that was used in the request message.

## Unofficial HTTP Status Codes
This section will tell you what each rare code from the software means.
### 522 Connection Timed Out
(Cloudflare Usage) Cloudflare is unable to reach the origin web server and the request timed out.

## Any Other Questions, Requests, or Problems?
Make an issue if you want to suggest a feature, have a question or have found a bug.
