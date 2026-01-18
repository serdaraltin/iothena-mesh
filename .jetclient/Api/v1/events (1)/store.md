```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/incidents'
sortWeight = 3000000
id = '7d53fc5e-f605-4dd0-a416-30d4b56d3b41'

[body]
type = 'JSON'
raw = '''
{
  "device_id": 1,
  "priority": "high",
  "status": "open",
  "transcript": "A patient fell in the hallway. Immediate assistance required.",
  "human_count": 1,
  "additional": {"details": "Fall detected near room 12. Patient unresponsive."},
}'''
```
