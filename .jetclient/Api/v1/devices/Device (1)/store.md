```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/devices/statuses'
sortWeight = 2500000
id = 'bd90a521-3ea8-40b6-80ed-e3ea561e9dc7'

[body]
type = 'JSON'
raw = '''
{
  "device_id": 1,
  "status": "active",
  "health": "4",
  "temperature": "20",
  "battery_level": "20",
  "cpu_usage": "20",
  "memory_usage": "20",
  "disk_usage": "20",
  "services": "[{\"name\": \"Service 1\", \"version\": \"1.0.0\", \"status\": \"running\"}, {\"name\": \"Service 2\", \"version\": \"1.1.0\", \"status\": \"stopped\"}]",
  "last_checked": "2024-12-28 08:15:00",
}'''
```
