```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/incidents/notifications'
sortWeight = 3000000
id = '9bac775b-c40c-49a3-8fd3-819a30ede88a'

[body]
type = 'JSON'
raw = '''
{
  "id": 17,
  "incident_id": 1,
  "type": "critical",
  "priority": "high",
  "title": "test",
  "message": "test",
  "recipient_id": 101,
  "recipient_type": "user",
  "delivered": true,
  "delivery_method": "push",
  "delivery_time": "2024-12-28 08:05:00",
}'''
```
