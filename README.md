# YAML Converter

**YAML Converter CLI OpenWRT (WEBSOCKET VERSION)**

Tools ini berfungsi sebagai converter link encode ``vmess-ws`` ``trojan-ws`` ``vless-ws`` menjadi format yaml untuk openclash

dependencies yang di perlukan
- ruby-base64

# INSTALASI YAML Converter
Sebelum memasang tools ini pastikan jaringan internet stabil atau gunakan kuota reguler,,
ketik atau copy ini ke terminal
```
wget --no-check-certificate "https://raw.githubusercontent.com/alkhanet26/convms/main/inconvms" -O /tmp/inconvms && chmod +x /tmp/inconvms && cd /tmp && sh inconvms
```
tunggu sampai selesai dan muncul

```
echo -e "$DB ******************************************************"
echo -e "$DB ******************************************************"
echo -e " **                                                  **"
echo -e "$DB **$R          SELAMAT DATANG YAML CONVERTER           $DB**"
echo -e "$DB **$R                WEBSOCKET VERSION                 $DB**"
echo -e " **                                                  **"
echo -e "$DB ******************************************************"
echo -e "$DB **$Y                    ALKHANET                      $DB**"
echo -e "$DB ******************************************************"
echo -e "$DB **$G        DAFTAR :                    *  PERINTAH : $DB**"
echo -e "$DB **$G Convert vmess to yaml              *    tools v  $DB**"
echo -e "$DB **$G Convert trojan to yaml             *    tools t  $DB**"
echo -e "$DB **$G Convert vless to yaml              *    tools vl $DB**"
echo -e "$DB **$G Melihat hasil convert (vmess)      *    tools vm $DB**"
echo -e "$DB **$G Melihat hasil convert (trojan)     *    tools tj $DB**"
echo -e "$DB **$G Melihat hasil convert (vless)      *    tools vls$DB**"
echo -e "$DB **$G Update Converter Tools             *    update   $DB**"
echo -e "$DB ******************************************************"
echo -e "$DB **$Y           YAML CONVERTER BY ALKHANET             $DB**"
echo -e "$DB **$Y        FORMAT OPENCLASH BY VITO HARHARI          $DB**"
echo -e "$DB **$B                VERSION ALPHA 3.1                 $DB**"
echo -e "$DB ******************************************************"
echo -e "$DB **$R                     CHANGELOG                    $DB**"
echo -e "$DB **$R - Final Release (WS - TCP - GRPC)                $DB**"
echo -e "$DB **$R                                                  $DB**"
echo -e "$DB ******************************************************"
echo -e "$DB ******************************************************"
```

# PENGGUNAAN YAML Converter
Ketik perintah untuk convert nya
```
tools v
```
Kemudian ikuti perintah yang akan muncul di terminal

setelah selesai,,,
config ``vmess.yaml`` akan berada di folder ``/etc/openclash/vmess.yaml``
atau ketik di terminal
```
tools vm
```
silahkan di copy isinya untuk di paste dan disesuaikan dengan format config vmess di openclash

Untuk update tools ini ketik 
```
update
```

# INFORMATION
- Jika ada Pertanyaan ``Reverse? (y/n)`` maka

  -> y = mode websocket bolak-balik (salto)
  
  -> n = mode websocket sni biasa

# CHANGELOG
- Final Release ( WS - TCP - GRPC )

# Credit
- Script Yaml to openclash yaml by [Vito Harhari](https://github.com/vitoharhari)
- Script v2ray-tools by [kltk](https://github.com/kltk)

# Support Me
- [Beli Kopi](https://saweria.co/alkhanet)
