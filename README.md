# Reversed-Discord
Reverse-engineering of Discord

## Discord Account Registration

Method: POST

Endpoint: https://discord.com/api/v9/auth/register

Payload: 
```
{
  "fingerprint":"1212310596452622378*****",
  "email":"*****",
  "username":"****",
  "global_name":"****",
  "password":"****",
  "invite":null,
  "consent":true,
  "date_of_birth":"YYYY-MM-DD",
  "gift_code_sku_id":null,
  "promotional_email_opt_in":true
}
```

This will return site ID and more and more.

hCapthca Site ID: 4c672d35-0701-42b2-88c3-78380b0db560

https://github.com/avengy/hcaptcha-bypass-discord/blob/main/hcapbypass.py

https://hcaptcha.com/checksiteconfig?host=discord.com&sitekey=4c672d35-0701-42b2-88c3-78380b0db560&sc=1&swa=1

https://zenn.dev/marketer/articles/c5ca49e831805e
