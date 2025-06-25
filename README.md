# JWT
## To get the Secret key 
>>>import secrets
>>>secret_key = secrets.token_hex(32)
>>>print(secret_key)

## To check whether API is running or not after running FLask
curl -X POST http://127.0.0.1:5000/login -H "Content-Type: application/json" -d "{\"username\":\"admin\",\"password\":\"password\"}" (Windows CMD)
