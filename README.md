Karmic Canteen Management System

This is a small web app I made to help manage daily meals in a workplace canteen. It’s built using basic HTML, CSS, and JavaScript, and uses Firebase to store data and handle logins.
There are two parts: one for employees to book their meals, and one for admins to update the menu and check bookings.

---------------------------------------------

What’s included

- Employee.html — for employees to log in, see the menu, choose meals, and pay using a QR code.
- Admin.html — for admins to update the menu, view bookings by date, and look up bookings by email.

-----------------------------------------------

How to set it up

1. Clone this project to your computer:
   git clone https://github.com/your-username/karmic-canteen.git

2. Go to firebase.google.com and create a new project.

3. Enable Firestore and Authentication in Firebase.

4. Copy your Firebase config and paste it into both HTML files (look for the firebaseConfig section).

5. In Firestore, create two collections:
   - dailyMenus — stores the menu for each day (named by date like 07-11-2025)
   - mealBookings — stores each employee’s meal choices and payment info (document ID is their email)

------------------------------------------------

Features

For employees:
- Login with email and password
- See today’s menu
- Choose breakfast, lunch, and/or dinner
- See total cost and scan a QR code to pay

For admins:
- Login with a password
- Update today’s menu with items and prices
- View all bookings for a selected date
- Look up bookings by employee email

-------------------------------------------------

Tech used

- HTML, CSS, JavaScript
- Firebase Firestore
- Firebase Authentication
- QR Code API (from goqr.me)

------------------------------------------------

Things I might add later

- Booking history for employees
- Proper admin login using Firebase
- Language toggle (English/Kannada)
- Notifications when the menu is updated
- Better mobile layout

---------------------------------------------------

Contributions

If you’d like to help improve this, feel free to fork the repo or open an issue. Suggestions and pull requests are always welcome.

---------------------------------------------------

License

This project is under the MIT License — free to use, modify, and share.
