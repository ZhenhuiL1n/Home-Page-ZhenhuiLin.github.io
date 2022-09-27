sudo chown -R $(whoami):$(whoami) /home/zhenhui/Desktop/Home-Page-ZhenhuiLin.github.io



sudo curl -fsSL curl.haxx.se/ca/cacert.pem -o "$(ruby -ropenssl -e 'puts OpenSSL::X509::DEFAULT_CERT_FILE')"