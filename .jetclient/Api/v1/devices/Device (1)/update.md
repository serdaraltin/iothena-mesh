```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/devices/statuses'
sortWeight = 3000000
id = 'e3d887b5-874e-41ea-87bd-12d63dbdc949'

[body]
type = 'JSON'
raw = '''
{
  "id": 1,
  "device_id": 1,
  "status": "active",
  "health": "15",
  "temperature": "20",
  "battery_level": "20",
  "cpu_usage": "20",
  "memory_usage": "20",
  "disk_usage": "20",
  "services": "[{\"name\": \"Service 1\", \"version\": \"1.0.0\", \"status\": \"running\"}, {\"name\": \"Service 2\", \"version\": \"1.1.0\", \"status\": \"stopped\"}]",
  "last_checked": "2024-12-28 08:15:00",
}'''
```
