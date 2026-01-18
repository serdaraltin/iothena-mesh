```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/devices'
sortWeight = 3000000
id = '6bef0c51-9a2a-474a-8693-b363ef7afbb3'

[body]
type = 'JSON'
raw = '''
{
  "uuid": "8582126c-e94a-48f4-b74e-adf1ff7359a2",
  "type": "Sentinel",
  "model": "Raspberry_Pi_4",
  "name": "Test create",
  "location": "test 5555",
  "room_size": 18,
  "base_noise_level": "30",
  "threshold": "55",
  "ip_address": "192.168.1.101",
  "port": 8000,
  "mac_address": "00:1A:2B:3C:4D:02",
}'''
```
