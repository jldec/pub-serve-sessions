## pub-serve-sessions

cookie-based session plugin for [pub-server](https://github.com/jldec/pub-server) and [pub-gatekeeper](https://github.com/jldec/pub-gatekeeper).

- boilerplate sessions using express-session
- optionally uses redis for session and log persistence
- extends server with ACL interface at server.isAuthorized()
- includes options for per-session request log and global system log
