# ProxyAwareRemoteIpValve
RemoteIpValve with patch applied.

## 57665 support x-forwarded-host
Patch from here: https://bz.apache.org/bugzilla/show_bug.cgi?id=57665#c13

Allow x-forwarded-host header to be evaluated by RemoteIpValve and RemoteIpFilter.
