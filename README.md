# Smart Attendance and Transport Monitoring System

This project implements an automated school attendance and transport safety system using RFID/QR/mobile attendance capture, GPS bus tracking, and real-time parent notifications via push and SMS. It improves child safety by enabling parents and administrators to monitor attendance and school bus locations live.

## Features
- Automatic attendance capture via RFID cards, QR codes, or mobile app.
- Real-time GPS bus tracking to monitor routes and timings.
- Push and SMS notifications to parents about their child's attendance and bus status.
- Admin dashboard with attendance reports and live bus maps.

## Installation

### Backend Setup
1. Install Java 17 and PostgreSQL.
2. Clone the repo and navigate to the `backend/` folder.
3. Configure `application.properties` with your database credentials.
4. Build and run the Spring Boot backend.

### Mobile App
1. Open the `mobile/` folder in Android Studio.
2. Build and run the app on an emulator or physical device.

### Device (Hardware)
1. Connect RFID readers and GPS modules to ESP32 or Raspberry Pi.
2. Flash device code to send attendance and GPS data to backend.

## Usage

- Admin logs in to the web dashboard to monitor attendance and bus locations.
- Parents log in on the mobile app to see live updates and receive notifications.
- Attendance is captured automatically via RFID/QR cards or manually by staff.

## Folder Structure

SmartAttendance/
backend/ # Java Spring Boot backend source code
mobile/ # Mobile app source (Android Java or Flutter)
hardware/ # Device code for RFID and GPS modules
dashboard/ # Admin dashboard source code (React)
docs/ # Documentation files
testdata/ # Sample data and test files


## Contributing

Contributions are welcome! Please open issues for bugs or feature requests, and submit pull requests with improvements.

## Maintainers

- Pankaj Bori — [GitHub profile](https://github.com/Pankaj-Bori)
- Divyansh Sharma - [GitHub profile](https://github.com/DivyAnSHas)
- Abhishek Sharma - [GitHub profile](https://github.com/AbhishekSharma7977)
- Nethavat Jagadish -[Github profile](https://github.com/
- Chasang tsering Bhutia - [GitHub profile](https://github.com/ChasangBhutia)
- Sammer Pratab Singh

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
