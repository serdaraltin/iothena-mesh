```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/events'
sortWeight = 3000000
id = '817d8c72-7c10-4c16-b6c3-4d641a915c94'

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
