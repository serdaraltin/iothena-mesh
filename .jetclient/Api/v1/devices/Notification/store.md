```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/devices/statuses'
sortWeight = 2500000
id = '623d9617-f6dd-4def-a672-14520d33fe6a'

[body]
type = 'JSON'
raw = '''
{
  "device_id": 2,
  "status": "active",
  "health": 15,
  "temperature": 20,
  "battery_level": 20,
  "cpu_usage": 20,
  "memory_usage": 20,
  "disk_usage": 20,
  "services": "[{\"name\": \"Service 1\", \"version\": \"2.0.0\", \"status\": \"running\"}, {\"name\": \"Service 4\", \"version\": \"1.1.0\", \"status\": \"stopped\"}]",
  "last_checked": "2024-12-31 08:15:00",
}'''
```
