# SimplePing

A Swift implementation of `SimplePing` using Foundation.

The current implementation has a memory leak related to `CFHost` during hostname resolution. Removing the host-resolution step eliminates the leak.

Contributions, fixes, and suggestions for resolving the `CFHost` memory issue are welcome.
