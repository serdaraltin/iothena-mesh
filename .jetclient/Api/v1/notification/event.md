```toml
name = 'event'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/notifications/event'
sortWeight = 3000000
id = '2d62a394-a65a-43ae-a7fb-b7cfcd554eaf'

[body]
type = 'JSON'
raw = '''
{
  "device_id": 1,
  "priority": "high",
  "transcript": "yarrağımı yemek tatlı geldi demi",
  "human_count": 2,
  "bad_word_ids": [1,2],
  "additional": {
    "details": "Fall detected near room 12. Patient unresponsive."
  },
}'''
```
