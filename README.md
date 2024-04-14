### docker_container_monitoring

## Overview
コンテナのCPU使用率、メモリ使用量、メモリ使用率、ネットワーク使用量の監視、監視データの保管を行う

## Tested Environments
以下の環境で動作確認を行っています：
 - m3 MacBook Air
   Mac OS Sonoma 14.4.1

## Usage
    ```sh
    docker-compose up -d
    ```

## Technology used
 - Docker
 - influxdb 2.7-
 - telegraf 1.30
 - grafana

## Grafana Dashboard Screenshots
<img width="1242" alt="スクリーンショット 2024-04-15 0 06 59" src="https://github.com/taiki-kuraishi/docker_container_monitoring/assets/131664944/494c4c0c-e8f3-4e85-98dd-867f6bd673df">


## Author
- [Kuraishi Taiki](https://github.com/taiki-kuraishi)

## Licence
DesktopExcelToPDFConverter is licensed under [the MIT License](https://github.com/taiki-kuraishi/docker_container_monitoring/blob/d62e697afe0f6e71449cd10e47624d0229fb19c0/LICENSE).
