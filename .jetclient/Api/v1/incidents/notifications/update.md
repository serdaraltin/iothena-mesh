```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/events/notifications'
sortWeight = 3000000
id = '9bac775b-c40c-49a3-8fd3-819a30ede88a'

[body]
type = 'JSON'
raw = '''
{
  "id": 5,
  "event_id": 1,
  "type": "info",
  "priority": "medium",
  "title": "aaaaa",
  "message": "bbbbbbb",
  "recipient_id": 1,
  "recipient_type": "device",
  "delivered": false,
  "delivery_method": "email",
  "delivery_time": "2024-12-28 08:20:00",
}'''
```
