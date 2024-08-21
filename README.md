# mohesh.yml
# Configuration for MyApplication

application:
  name: MyApp
  version: 1.0.0
  description: A sample application to demonstrate YAML configuration.

server:
  host: localhost
  port: 8080
  ssl: true

database:
  type: mysql
  host: db.example.com
  port: 3306
  username: admin
  password: secret
  name: myapp_db

logging:
  level: info
  file: /var/log/myapp.log
  maxSize: 10MB
  maxBackupIndex: 5

features:
  authentication: true
  caching: true
  monitoring: false

api:
  baseURL: https://api.example.com/v1
  timeout: 30  # in seconds
  retries: 3

# List of supported languages
languages:
  - en
  - es
  - fr

# Nested example
nestedExample:
  item1:
    name: "First Item"
    value: 100
  item2:
    name: "Second Item"
    value: 200
