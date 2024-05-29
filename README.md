# Cloudflare SSE Experimentation

Passing a readstream inside of the response object lets you stream data. CloudFlare does limit your CPU time to 50ms, so after you exceed that time, the connection is closed.
So this closing of the connection could occur pretty frequently.
