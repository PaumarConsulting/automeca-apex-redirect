# automeca.com apex redirect
GitHub Pages site bound to the bare domain `automeca.com`. Every path (and query/hash) is sent to
`https://www.automeca.com<same path>` (index.html for `/`, 404.html for everything else).
Exists because GoDaddy domain forwarding drops paths (QR codes to arrancatucarrera.com → automeca.com/arrancatucarrera were 404).
DNS (GoDaddy, unchanged nameservers): `@` A → 185.199.108.153, .109.153, .110.153, .111.153. MX/TXT/www untouched.
