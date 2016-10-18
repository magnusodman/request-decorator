# request-decorator
Reverse proxy that can add headers to requests. Great for mocking.

Syntax:

decorate -localport 1080 -destination http://localhost:1090 -H "XX-Cc-CN: modman2"
