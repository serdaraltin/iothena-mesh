```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/events/notifications'
sortWeight = 2500000
id = '70dbf2a4-0bc6-493d-8eff-ab546e3cd497'

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
