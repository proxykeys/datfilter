# DatFilter Geo Files

Оптимизированные GeoSite / GeoIP файлы для Xray-core и совместимых клиентов.

## Включённые категории

### GeoSite
- `private` - частные сети и локальные домены
- `ru-blocked` - заблокированные в России домены
- `category-ru` - российские домены
- `category-gov-ru` - российские государственные домены
- `category-ru-non-ru` - российские сервисы вне `.ru/.su/.рф`, поддерживаемые вручную
- `category-ads-ru` - канонический российский adblock-список для direct-ветки клиентов

### GeoIP
- `private` - частные IP-адреса
- `ru` - российские IP-адреса
- `re-filter` - IP из re:filter

## Источники
- GeoIP база: [runetfreedom/russia-v2ray-rules-dat](https://github.com/runetfreedom/russia-v2ray-rules-dat)
- GeoSite base: [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- `ru-blocked`: [runetfreedom/russia-blocked-geosite](https://github.com/runetfreedom/russia-blocked-geosite)
- `category-ru-non-ru`: [proxykeys/filter](https://github.com/proxykeys/filter)
- `category-ads-ru`: [proxykeys/filter/release/canonical-ru-ads.txt](https://github.com/proxykeys/filter)
- Обрезка итоговых файлов: [xray-geodata-cut](https://github.com/yichya/xray-geodata-cut)
