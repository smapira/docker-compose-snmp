# docker-compose-snmp

No install and instantly connect, to communicate with snmp.

## Usage

```shell
docker-compose up -d
docker-compose exec app bash

snmpwalk -v1 -c public 192.168.0.2 .
```