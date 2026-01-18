```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/events'
sortWeight = 4000000
id = 'd3643568-46be-4bf4-9f1b-ac8966cc590f'

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
