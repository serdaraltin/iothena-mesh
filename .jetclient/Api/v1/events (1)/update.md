```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/incidents'
sortWeight = 4000000
id = 'a5ba4aaf-d7f6-4b13-9a86-e273aa35153c'

[body]
type = 'JSON'
raw = '''
{
  "id": 21,
  "device_id": 1,
  "priority": "low",
  "status": "open",
  "transcript": "A patient fell in the hallway. Immediate assistance required.",
  "human_count": 3,
  "additional": "{\"details\": \"Fall detected near room 12. Patient unresponsive.\"}",
}'''
```
