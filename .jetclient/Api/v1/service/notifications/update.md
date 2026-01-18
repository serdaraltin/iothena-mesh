```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/events/notifications'
sortWeight = 3000000
id = '96f680e3-4ced-4b7d-8d67-89e971cedc04'

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
