# DevOps Troubleshooting
Всем хай! Я Junior DevOps-инженер. Здесь собраны разборы реальных технических кейсов, с которыми я столкнулся при развертывании и эксплуатации как чужой, так и своей инфраструктуры

Технологический стек:    
Оркестрация: Kubernetes, Docker, Docker Compose    
Мониторинг/Логи: ELK Stack (Elasticsearch, Logstash, Kibana), Grafana + Prometheus, Filebeat, Fluentd           
ОС/Система: Linux (Ubuntu/Debian), Windows    

Контактная информация:    
Telegram: @FX_7500G    
Email: alekcwdsa@gmail.com    

## Кейсы 

<details>
<summary>🐳 Docker </summary>

| Проблема | Решение | Ссылка |
| :--- | :--- | :--- |
| Ошибка 'no such host' (IPv6) | Отключение IPv6 и настройка DNS | [Решение](./Docker-troubleshooting/combating-IPv6-priotization.md) |

</details>

<details>
<summary>⎈ Kubernetes</summary>
  
| Проблема | Решение | Ссылка |
| :--- | :--- | :--- |
| Динамически не настроились PVC и таймауты при деплое GitLab | Редактирование StorageClass, ручное создание бакетов и фикс MTU | [Решение](./K8s-troubleshooting/gitlab-k8s-pvc-network-fix.md) |
| Недоступность APT-репозиториев K8s | Установка бинарников напрямую, настройка containerd, ручное создание systemd-unit | [Решение](./K8s-troubleshooting/K8s-binary-installing.md)
</details>

<details>
  <summary> CI/CD </summary>

  
  
</details>

<details>
  <summary> Linux </summary>

    
</details>

<details>
  <summary> Сети </summary>

    
</details>

<details>
  <summary>📊 Мониторинг и парсинг логов  </summary>

| Проблема | Решение | Ссылка |
| :--- | :--- | :--- |
| Падение Es при старте из-за Race Condition | Внедрение Healthcheck и Sequential Startup | [Решение](./ELK-troubleshooting/fix-race-condition-elasticsearch.md) |
    
 
</details>
