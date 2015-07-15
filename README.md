## pub-serve-sessions

module for serving express sessions pub-server and pub-gatekeeper

- boilerplate sessions using express-session
- configured via config opts.session
- uses redis if enabled via opts.redis
- includes options for per-session request log and global system log
- provides server.isAuthorized() with acls

recommend using with redis
1. so that sessions survive pub-server restarts and
2. as a simple way to collect logs for tracking and analytics
