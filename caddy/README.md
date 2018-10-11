Este script instala o servidor web Caddy com os seguintes plugins em nossa distribuição padrão:

* http.cache
* http.cgi
* http.expires
* http.filemanager
* http.forwardproxy
* http.git
* http.login
* http.minify
* http.realip
* http.upload

Os seguintes provedores DNS estarão disponíveis para obtenção de certificados via LetsEncrypt:

* tls.dns.googlecloud

Os serviços de sistema também serão instalados de forma automática. Este script tem como alvo hosts Debian (e derivados) e RHEL (e derivados).