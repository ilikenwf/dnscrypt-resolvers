# opennic

Resolvers from the [OpenNIC](https://www.opennic.org/) project.

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'opennic']
    urls = ['https://raw.githubusercontent.com/DNSCrypt/dnscrypt-resolvers/master/v2/opennic.md', 'https://download.dnscrypt.info/resolvers-list/v2/opennic.md']
    minisign_key = 'RWQf6LRCGA9i53mlYecO4IzT51TGPpvWucNSCh1CBM0QTaLn73Y7GFO3'
    cache_file = 'opennic.md'

--

## doh-ibksturm

doh-server (nginx - doh-httpproxy - unbound backend), DNSSEC / Non-Logged / Uncensored, OpenNIC and Root DNS-Zone Copy
Hosted in Switzerland on by ibksturm, aka Andreas Ziegler

sdns://AgcAAAAAAAAADDE3OC44Mi4xMDMuNQAUaWJrc3R1cm0uc3lub2xvZ3kubWUKL2Rucy1xdWVyeQ

## ibksturm

dnscrypt-server (nginx-dnscrypt-wrapper-unbound backend), DNSSEC / Non-Logged / Uncensored, OpenNIC and Root DNS-Zone Copy
Hosted in Switzerland by ibksturm, aka Andreas Ziegler

sdns://AQcAAAAAAAAADDE3OC44Mi4xMDMuNSCSGtweo8iPa3iWOyYqf0bJsHf3zo5_ASOgufNPWRaybxgyLmRuc2NyeXB0LWNlcnQuaWJrc3R1cm0

## publicarray-au

DNSSEC • OpenNic • Non-logging • Uncensored - hosted at vultr.com
Maintained by publicarray - https://dns.seby.io

sdns://AQcAAAAAAAAADDQ1Ljc2LjExMy4zMSAIVGh4i6eKXqlF6o9Fg92cgD2WcDvKQJ7v_Wq4XrQsVhsyLmRuc2NyeXB0LWNlcnQuZG5zLnNlYnkuaW8

## publicarray-au-doh

DNSSEC • OpenNic • Non-logging • Uncensored - hosted on GCP
Maintained by publicarray - https://dns.seby.io

sdns://AgcAAAAAAAAADDQ1Ljc2LjExMy4zMSA-GhoPbFPz6XpJLVcIS1uYBwWe4FerFQWHb9g_2j24OBBkb2guc2VieS5pbzo4NDQzCi9kbnMtcXVlcnk

## opennic-bongobow

Non-logging OpenNIC resolver in Munich, Germany

sdns://AQYAAAAAAAAAEjUuMTg5LjE3MC4xOTY6NTM1MyBUNSxVQDuC7pPEB_3CNESXDZpW7yK_z_nskJzNMiQyaygyLmRuc2NyeXB0LWNlcnQubnMxNi5kZS5kbnMub3Blbm5pYy5nbHVl

## opennic-bongobow-ipv6

Non-logging OpenNIC resolver in Munich, Germany

sdns://AQYAAAAAAAAAIFsyYTAyOmMyMDc6MjAwODoyNTIwOjUzOjoxXTo1MzUzIFQ1LFVAO4Luk8QH_cI0RJcNmlbvIr_P-eyQnM0yJDJrKDIuZG5zY3J5cHQtY2VydC5uczE2LmRlLmRucy5vcGVubmljLmdsdWU

## opennic-R4SAS

Non-logging OpenNIC resolver in France

sdns://AQYAAAAAAAAAETE1MS44MC4yMjIuNzk6NDQzIO4Y9lZnORlvodxu39dnm6mFruwTRnlmovbEga4Fyw3TIDIuZG5zY3J5cHQtY2VydC5vcGVubmljLmkycGQueHl6

## opennic-R4SAS-ipv6

Non-logging OpenNIC resolver in France

sdns://AQYAAAAAAAAAG1syMDAxOjQ3MDoxZjE1OmI4MDo6NTNdOjQ0MyDuGPZWZzkZb6Hcbt_XZ5upha7sE0Z5ZqL2xIGuBcsN0yAyLmRuc2NyeXB0LWNlcnQub3Blbm5pYy5pMnBkLnh5eg
