```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/events/notifications'
sortWeight = 3000000
id = '922c7014-7266-4276-be14-255a56e31318'

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
