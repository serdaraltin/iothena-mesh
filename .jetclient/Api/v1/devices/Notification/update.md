```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/devices/statuses'
sortWeight = 3000000
id = '0c20562e-4e20-438e-be5d-d9257ed1de2d'

[body]
type = 'JSON'
raw = '''
{
  "id": 1,
  "device_id": 1,
  "status": "offline",
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
