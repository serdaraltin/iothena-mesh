```toml
name = 'device'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/notifications/device'
sortWeight = 1000000
id = '2e90132e-096c-4c6c-b56d-c99d516c2cb1'

[body]
type = 'JSON'
raw = '''
{
  "notification_type": "incident",
  "source": "device",
  "id": 1,
  "priority": "high",
  "status": "open",
  "human_count": 2,
  "bad_word": 1,
  "transcript": "yarrağımı yemek tatlı geldi demi"
}'''
```
