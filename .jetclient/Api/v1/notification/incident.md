```toml
name = 'incident'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/notifications/incident'
sortWeight = 2000000
id = '7dbd1b48-f59c-4508-aaef-e67472a5961e'

[body]
type = 'JSON'
raw = '''
{
  "device_uuid": "ec5cb81a-40d2-46da-8ccf-3151424d301e",
  "priority": "high",
  "transcript": "yarrağımı yemek tatlı geldi demi",
  "human_count": 2,
  "bad_words": ["yavşak", "salak"],
  "additional": {
    "details": "Fall detected near room 12. Patient unresponsive."
  },
}'''
```
