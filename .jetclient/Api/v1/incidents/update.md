```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/events'
sortWeight = 4000000
id = 'a5ba4aaf-d7f6-4b13-9a86-e273aa35153c'

[body]
type = 'JSON'
raw = '''
{
  "id" : 16,
  "type": "info",
  "operation": "create",
  "source_type": "device",
  "source": {"id": "ESP32_200", "address": "192.168.1.10:8080"},
  "title": "Device Restarted",
  "details": "The ESP200 device was restarted successfully.",
  "additional": {"module_version": "v1.2.0"},
}
'''
```
