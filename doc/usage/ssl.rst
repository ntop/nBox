SSL Certificate
===============

The nBox UI is based on Cockpit, which requires SSL/TLS to communicate with the 
Web browser. Cockpit listens for both HTTP and HTTPS connections on the same port, 
by default 9090. If an HTTP connection is made, Cockpit will redirect that connection 
to HTTPS.

By default a self-signed certificate is used, please refer to the Cockpit documentation
at https://cockpit-project.org/guide/latest/https to properly configure a certificate
for production use.

