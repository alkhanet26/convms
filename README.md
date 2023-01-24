# convms

Converter Vmess CLI untuk openwrt
Tools ini berfungsi sebagai converter link encode vmess menjadi format yaml untuk openclash
dependencies yang di perlukan
- node-npm
- python3
- python3-pip

Sebelum memasang tools ini pastikan jaringan internet stabil atau gunakan kuota reguler,,
ketik atau copy ini ke terminal
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
tools cvms
```
silahkan di copy isinya untuk di paste dan disesuaikan dengan format config vmess di openclash

Untuk update tools ini ketik 
```
toos up
```

Next development

 - converter for trojan and vless

Credit
- Script Yaml to openclash yaml by [Vito Harhari](https://github.com/vitoharhari)
- Script v2ray-tools by [kltk](https://github.com/kltk)
- Script jsontoyaml by [drbild](https://github.com/drbild)
