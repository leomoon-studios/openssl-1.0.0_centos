## Introduction
This is a build of OpenSSL 1.0.0.

## How to Install
```bash
wget https://raw.githubusercontent.com/leomoon-studios/openssl-1.0.0_centos/master/libssl.so.1.0.0.tar.gz -O /tmp/libssl.tar.gz #download libssl
wget https://raw.githubusercontent.com/leomoon-studios/openssl-1.0.0_centos/master/libcrypto.so.1.0.0.tar.gz -O /tmp/libcrypto.tar.gz #download libcrypto
tar -zxf /tmp/libssl.tar.gz -C /usr/lib64/ #extract libssl
tar -zxf /tmp/libcrypto.tar.gz -C /usr/lib64/ #extract libcrypto
rm -rf /tmp/libssl.tar.gz
rm -rf /tmp/libcrypto.tar.gz
```
## Compatibility
Tested with CentOS 7.5