# gitbase rpm generate

> use fpm tools

## cmd

```code
fpm -s dir -t rpm -n gitbase --rpm-os linux -v v0.24.0-rc2 \
  ./gitbase-linux=/usr/bin/ \
  ./gitcode=/var/lib/gitbase \
  ./gitbase.service=/usr/lib/systemd/system/gitbase.service \
  ./gitbase=/etc/gitbase/gitbase
```