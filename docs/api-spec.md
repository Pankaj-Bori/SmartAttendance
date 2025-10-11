# API Specification

## POST /api/attendance
- Description: Receive attendance data from devices.
- Request Body: { "rfid": "string", "timestamp": "ISO8601 datetime" }
- Response: 200 OK with success message.

## GET /api/bus/location
- Description: Fetch latest bus location.
- Response: { "busId": "string", "latitude": "float", "longitude": "float", "timestamp": "ISO8601 datetime" }

## POST /api/notifications/send
- Description: Send notification to parent users.
- Request Body: { "userId": "string", "message": "string" }
- Response: 200 OK
