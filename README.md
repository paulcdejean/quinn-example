### Steps to reproduce

`cargo run -- $(pwd)/root/`

In another window:

`/opt/homebrew/opt/curl/bin/curl --http3-only -k -v https://localhost:4433/`

Curl version:

> curl 8.16.0 (aarch64-apple-darwin24.4.0) libcurl/8.16.0 OpenSSL/3.6.0 zlib/1.2.12 brotli/1.1.0 zstd/1.5.7 >AppleIDN libssh2/1.11.1 nghttp2/1.67.1 ngtcp2/1.16.0 nghttp3/1.12.0 librtmp/2.3
> elease-Date: 2025-09-10
> Protocols: dict file ftp ftps gopher gophers http https imap imaps ipfs ipns ldap ldaps mqtt pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp ws wss
> Features: alt-svc AsynchDNS brotli GSS-API HSTS HTTP2 HTTP3 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM SPNEGO SSL threadsafe TLS-SRP UnixSockets zstd
