# Basic Static IP Network Lab

Bu lab çalışmasında Cisco Packet Tracer üzerinde iki bilgisayarın aynı ağ içerisinde switch aracılığıyla haberleşmesi test edilmiştir.

## Kullanılan Araçlar

- Cisco Packet Tracer
- 2 PC
- 1 Switch
- Copper Straight-Through kablo

## Ağ Yapısı

| Cihaz | IP Adresi | Subnet Mask |
|---|---|---|
| PC0 | 192.168.10.10 | 255.255.255.0 |
| PC1 | 192.168.10.20 | 255.255.255.0 |

## Yapılan İşlemler

- Cisco Packet Tracer üzerinde basit bir LAN topolojisi oluşturuldu.
- PC0 ve PC1 aynı ağ bloğunda olacak şekilde statik IP adresleriyle yapılandırıldı.
- Cihazlar switch üzerinden birbirine bağlandı.
- PC0 üzerinden PC1'e ping testi yapıldı.

## Test Sonucu

PC0 üzerinden PC1'e ping atılarak bağlantı testi yapılmıştır.

```bash
ping 192.168.10.20
```

Test sonucunda iki cihazın aynı ağ içerisinde başarılı şekilde haberleştiği görülmüştür.

## Ekran Görüntüleri

### Topoloji

![Topology](screenshots/topology.png)

### Ping Testi

![Ping Test](screenshots/ping-test.png)
