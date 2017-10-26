# バージョン
ix2005-ms-8.3.44.ldc

# 参考
- etherip_ipv6
https://i.open.ad.jp/config/nec.aspx

- 公式？
http://jpn.nec.com/univerge/ix/Manual/EX/IX1-3K-EX-9.5.pdf
すごい読みにくいしコピペしにくいから嫌い

# memo
### EtherIPの速度
- 1GbEのLAN内においてiperfを用いて計測

|       | EtherIP | EtherIP+IPsec |
|-------|---------|---------------|
| ping  | １~2ms  | 1~4ms         |
| iperf | 90Mbps  | 30Mbps        |
