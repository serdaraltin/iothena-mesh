```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/devices'
sortWeight = 4000000
id = '325a920e-40f2-44f2-9bf0-90968897a38a'

[body]
type = 'JSON'
raw = '''
{
  "uuid": "9582126b-e94a-48f4-b74e-adf1ff7359a4",
  "type": "Sentinel",
  "model": "Raspberry_Pi_4",
  "name": "Test 12",
  "location": "Test 501",
  "room_size": 18,
  "base_noise_level": "30",
  "threshold": "55",
  "ip_address": "192.168.1.13",
  "port": 8000,
  "mac_address": "00:1A:2B:3C:4D:02",
}'''
```
