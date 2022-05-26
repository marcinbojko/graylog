# Changelog

## 2022-05-26 1.3.0

* bump `elasticsearch` to version 7.17.4
* bump `filebeat` to version 7.17.4
* bump `traefik` to version 2.7.0
* bump `graylog` to version 4.3.0-1-jre11
## 2022-02-17 1.2.3

* bump `graylog` to version 4.2.6-1-jre11
* bump `traefik` to version 2.6.1
* bump `elasticsearch` to version 7.16.3
* bump `filebeat` to version 7.16.3

## 2021-12-17 1.2.2

* bump `graylog` to version 4.2.4-1

## 2021-12-13 1.2.1

* bump `elasticsearch` and `filebeat` to version 7.16.1

## 2021-12-11 1.2.0

* bump `graylog` to version 4.2.3-1 due to [https://nvd.nist.gov/vuln/detail/CVE-2021-44228](https://nvd.nist.gov/vuln/detail/CVE-2021-44228)
* bump `elasticsearch` and `filebeat` to version 7.16.0
* bump to `traefik` 2.5.5
* added `Dlog4j2.formatMsgNoLookups=true` to `ES_JAVA_OPTS`

## 2021-11-17 1.1.1

* change graylog image to `jre11` version

## 2021-11-13 1.1.0

* bump to `graylog` 4.2.1-1
* bump to `traefik` 2.5.4
* fixes in README.md - default passwords for traefik and graylog dashboards
* dropped travis-ci support in favor of github actions

## 2021-02-03 1.0.1

* bump `traefik` to 2.4.2
* bump `graylog` to 4.0.2

## 2021-01-23 1.0.0

* Initial setup
