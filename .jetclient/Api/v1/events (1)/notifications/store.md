```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/incidents/notifications'
sortWeight = 2500000
id = '238d5e2a-621b-42ca-aa18-2aa3248ee0f2'

[body]
type = 'JSON'
raw = '''
{
  "incident_id": 1,
  "type": "critical",
  "priority": "high",
  "title": "Patient Fall Detected",
  "message": "A patient fell in the hallway near room 12. Immediate assistance required.",
  "recipient_id": 101,
  "recipient_type": "user",
  "delivered": true,
  "delivery_method": "push",
  "delivery_time": "2024-12-28 08:05:00",
}'''
```
