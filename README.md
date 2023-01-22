# convms

Converter Vmess CLI untuk openwrt
```
wget --no-check-certificate "https://raw.githubusercontent.com/alkhanet26/convms/main/inconvms" -O /tmp/inconvms && chmod +x /tmp/inconvms
```

lalu ketik
```
cd /tmp && sh inconvms
```

tunggu sampai selesai

ketika sudah selesai di coba ketik
```
tools
```
lalu akan muncul perintah untuk convert nya
```
tools v
```
dan akan muncul perintah masukan url / link encode vmess

setelah selesai,,,
config ``vmess.yaml`` akan berada di folder ``/etc/openclash/vmess.yaml``
atau ketik di terminal
```
cat /etc/openclash/vmess.yaml
```
silahkan di copy isinya untuk di paste dan disesuaikan dengan format config vmess di openclash


Credit
- Script v2ray-tools by [kltk](https://github.com/kltk)
- Script jsontoyaml by [drbild](https://github.com/drbild)
