## Структура проекта

```
lab7/
├── docker-compose.yml          
├── Jenkinsfile                 
├── requirements.txt    
├── artifacts        
├── tests/            
│   ├── locustfile.py
│   ├── test_redfish.py
│   └── tests_openbmc.py
├── romulus/                   
    └── obmc-phosphor-image-romulus-20250902012112.static.mtd
```

## Запуск

### 1. Запуск Jenkins в Docker

```bash
# Запуск контейнеров
docker-compose up -d

# Проверка статуса
docker-compose ps

# Просмотр логов
docker-compose logs -f jenkins
```