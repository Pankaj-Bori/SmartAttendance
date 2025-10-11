# System Architecture

- Devices (ESP32/Raspberry Pi with RFID and GPS) send attendance and location data to backend API.
- Backend (Spring Boot) processes and stores data in PostgreSQL database.
- Mobile app fetches attendance and bus location data from backend, showing to parents.
- Admin dashboard visualizes attendance reports and live bus tracking.
- Notifications are sent through Firebase and SMS gateways.
