# Installation

- WhatsApp API using Docker environment.

# How to use?

- Execute `docker-compose up -d`
- Open browser and go to address `http://localhost:8000`
- Scan the QR Code
- Enjoy!

# How to send my first message?

```
curl -X POST \
  'http://localhost:8000/send-message' \
  --header 'Content-Type: application/x-www-form-urlencoded' \
  --data-urlencode 'number=559999999999' \
  --data-urlencode 'message=Hello!!!!'
```

# API Repository

https://github.com/ngekoding/whatsapp-api-tutorial
