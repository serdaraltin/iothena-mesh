```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/events/notifications'
sortWeight = 2500000
id = 'eab8245c-7eb9-408a-8790-5ccb7371df87'

[body]
type = 'JSON'
raw = '''
{
"event_id": 1,
"type": "info",
"priority": "medium",
"title": "Test Test",
"message": "Test test tres",
"recipient_id": 1,
"recipient_type": "device",
"delivered": true,
"delivery_method": "email",
"delivery_time": "2024-12-28 08:20:00",
}'''
```
