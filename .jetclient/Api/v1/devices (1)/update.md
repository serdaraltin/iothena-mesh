```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/events'
sortWeight = 4000000
id = 'e72b45af-205c-49fb-8d45-68bb73d0794e'

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
