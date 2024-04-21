# Pillminder

## Description
Pillminder is an Android application designed to help users remember to take their medication on time. Users can input the time they need to take their pills, and the app orginize them with visual photo of the pill.

## Features
- Set multiple pill reminders with customizable times.
- Add the next reminders accrding to frequency of taking the pill in a day.
- Visual photo of the pill
- Easily manage and edit your pill reminders.
- User-friendly interface for intuitive navigation.

## Technologies Used
- Firebase Database: For storing user data and pill reminder information securely.
- Glide Library: For efficient image loading and caching.
- Lottie Library: For adding attractive and engaging animations to the app.

## Installation
1. Clone or download the repository from [GitHub](https://github.com/Shlomi89/PillMinderApp).
2. Open the project in Android Studio.
3. Connect the project to Firebase by adding your google-services.json file to the app directory.
4. Build and run the application on your Android device or emulator.

## Usage
1. Sign up or log in to your Pillminder account.
2. Add your medication by specifying the pill name and the time you need to take it.
3. And that's it!

## Screenshots
![Login](https://private-user-images.githubusercontent.com/81170162/323940296-f00047d8-059f-4eaa-ace9-a804a4c8ff55.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTM1MjYzOTIsIm5iZiI6MTcxMzUyNjA5MiwicGF0aCI6Ii84MTE3MDE2Mi8zMjM5NDAyOTYtZjAwMDQ3ZDgtMDU5Zi00ZWFhLWFjZTktYTgwNGE0YzhmZjU1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE5VDExMjgxMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQzMzgwZmVmNDFjNTdlYzJhMmZmMzM5MWMzZjg3ZjAwOWFiMDdjNTljNDFmMTJmYWIzMTgwYzE5ZjcyYmUxOWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.g5ywiaO8Y5LlEqIXdjjJV1N7Ll9lEkpuOViXE20GJ8Q)
![Menu](https://private-user-images.githubusercontent.com/81170162/323940390-5d138f77-a681-4b5b-b8f3-ff78bc4505e6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTM1MjYzOTIsIm5iZiI6MTcxMzUyNjA5MiwicGF0aCI6Ii84MTE3MDE2Mi8zMjM5NDAzOTAtNWQxMzhmNzctYTY4MS00YjViLWI4ZjMtZmY3OGJjNDUwNWU2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE5VDExMjgxMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWYwNGEzMDM3OTFkOThlOWYwN2QzZDhiZTdhOWNiZTc1NDllMzg2ZGM3YjVlYjNiZDI3NTJiMGMxM2RmM2VjYjMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.tfbzrCBYAoVW8OOx-aBonNx8dFZIjeVhtywLCE6KUmI)
![Add New Pill](https://private-user-images.githubusercontent.com/81170162/323940417-3cc1ed58-8e9c-4daf-847c-8167d465968c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTM1MjYzOTIsIm5iZiI6MTcxMzUyNjA5MiwicGF0aCI6Ii84MTE3MDE2Mi8zMjM5NDA0MTctM2NjMWVkNTgtOGU5Yy00ZGFmLTg0N2MtODE2N2Q0NjU5NjhjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE5VDExMjgxMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPThhYjgwYjA3NTM2NTJmMGU0ZGM0NDQ3NzMyNWNhZWNjNWUxOTIwMjY2Mjk3OWRhZmFiODgxMzg5NDRlZTI5NzkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.TF_92L9gE90nD28083VTEgswlVnCm-HrQxll20ClbqE)






## Contributors
- [Shlomi Saidian](https://github.com/yourusername)