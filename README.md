🩺 Health Tracker App
A comprehensive Flutter application for tracking diabetes (glucose) and blood pressure readings with local database storage, data visualization, and PDF report generation.

📱 Features
    👥 User Management
        Register new users with Name, Date of Birth, Sex, Phone, Address

        Edit existing user details

        Delete users (cascades to delete all their health records)

        View all registered users on home screen

    🩸 Health Readings
        Glucose Tracking (mandatory)

        Add glucose readings with date

        Edit/delete existing readings

        Color-coded status: Low, Normal, Borderline, High, Very High

        Blood Pressure Tracking (optional)

        Add BP readings (systolic/diastolic) with date

        Edit/delete existing readings

        Color-coded status: Normal, Elevated, High

    📊 Data Visualization
        Line charts for both glucose and BP trends

        Date range filter for customized view

        Target range indicators (70-139 mg/dL for glucose, 120/80 for BP)

        Left-to-right chronological display

        Responsive chart with non-overlapping date labels

    📄 PDF Reports
        Generate comprehensive health reports

        Patient information summary

        Glucose and BP statistics (min, max, average, trend)

        Detailed readings table with status colors

        Trend analysis (improving, stable, needs attention)

        Direct WhatsApp/Share as PDF document

    💾 Local Storage
        SQLite database for offline storage

        Persistent user and reading data

        Cascade delete for data integrity

    🛠️ Tech Stack
        Technology	Purpose
        Flutter	UI Framework
        SQLite (sqflite)	Local Database
        fl_chart	Data Visualization
        pdf + printing	PDF Generation
        share_plus	Share PDF via WhatsApp
        intl	Date Formatting
        path	Database Path Management


    🎯 Usage Guide
        1. Register a User
        Tap the + FAB button

        Fill in: Full Name, Date of Birth, Sex, Phone, Address

        Tap REGISTER NOW

        2. Add Health Readings
        Select a user from the list

        Tap + FAB in dashboard

        Choose Glucose or BP Reading

        Enter value and select date

        Tap Save

        3. View Charts
        Glucose and BP tabs show line charts

        Use Select Date Range to filter data

        Tap clear icon to reset filter

        4. Edit/Delete Readings
        Tap ⋮ icon on any reading

        Choose Edit or Delete

        Confirm deletion

        5. Generate PDF Report
        Tap 📄 PDF icon in app bar

        Report includes:

        Patient details

        Date range summary

        Glucose statistics & trend

        BP statistics

        Detailed readings table

        Share via WhatsApp/Email

        6. Edit/Delete Users
        From home screen, tap ⋮ on user card

        Choose Edit or Delete

        Confirm deletion (removes all associated readings)

    📊 Health Ranges
        Glucose (mg/dL)
        Range	Status	Color
        < 70	Low	Blue
        70 - 139	Normal	Green
        140 - 199	Borderline	Orange
        200 - 270	High	Red
        > 270	Very High	Purple

        Blood Pressure (mmHg)
        Range	Status	Color
        < 120/80	Normal	Green
        120-129/<80	Elevated	Orange
        ≥ 130/80	High	Red
    📄 License
        This project is licensed under the MIT License - see the LICENSE file for details.

    👨‍💻 Author
        JAYANTA DUTTA

        GitHub: @jayantadutta-code

        Email: jayantadutta.india@gmail.com

