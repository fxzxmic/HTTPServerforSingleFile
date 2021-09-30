# HTTPServerforSingleFile
A simple HTTP server for serving a single file (Based on Windows HTTP Server API)

## Detail
Detailed documentation on this API: [https://docs.microsoft.com/en-us/windows/win32/http/http-api-start-page](https://docs.microsoft.com/en-us/windows/win32/http/http-api-start-page).

The sample program, based on Microsoft's official documents, has been modified to provide a simple function of returning only a single file when accessed over HTTP.

## Notice
When accessed from outside the localhost, the listening port is not this program, but this process: `ntoskrnl.exe`, so note the firewall rules.