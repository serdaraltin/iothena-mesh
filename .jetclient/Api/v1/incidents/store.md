```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/events'
sortWeight = 3000000
id = '7d53fc5e-f605-4dd0-a416-30d4b56d3b41'

[body]
type = 'JSON'
raw = '''
{
  "type": "warning",
  "operation": "restart",
  "source_type": "device",
  "source": {"id": "ESP32_101", "address": "192.168.1.10:8080"},
  "title": "Device Restarted",
  "details": "The ESP32 device was restarted successfully.",
  "additional": {"module_version": "v1.2.0"},
}
'''
```
