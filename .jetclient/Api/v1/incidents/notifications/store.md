```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/events/notifications'
sortWeight = 2500000
id = '238d5e2a-621b-42ca-aa18-2aa3248ee0f2'

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
