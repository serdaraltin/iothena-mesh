```toml
name = 'incident'
method = 'POST'
url = 'http://telekom.datakapan.tr/api/v1/notifications/incident'
sortWeight = 2000000
id = '7dbd1b48-f59c-4508-aaef-e67472a5961e'

[[body.formData]]
key = 'device_uuid'
value = '75b8dc5c-d9e3-4c31-a4f0-7932282b6215'

[[body.formData]]
type = 'FILE'
key = 'audio'
value = 'tests/Media/4/INC-20250113115556-1594ce6f_audio.wav'

[[body.formData]]
type = 'FILE'
key = 'photo'
value = '/home/main/Pictures/Me/My_3.jpg'

[[body.formData]]
key = 'transcript'
value = 'Tam bir yarrak kafalı'

[[body.formData]]
key = 'priority'
value = 'critical'

[[body.formData]]
key = 'bad_words[]'
value = 'yarrak'

[[body.formData]]
key = 'human_count'
value = '2'

[[body.formData]]
key = 'bad_words[]'
value = 'salak'
disabled = true
```
