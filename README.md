## 📋 GUI App for Data Entry

A simple yet powerful Python GUI application built with Tkinter and OpenPyXL that allows users to enter and save student details directly into an Excel file (wb.xlsx).

This project is useful for small institutes, teachers, or individuals who want a lightweight tool for managing student information without needing complex database systems.



## 🚀 Features

📝 Form-based Data Entry for student details.

📂 Automatic Excel File Handling

Creates wb.xlsx with proper headers if it doesn’t exist.

Appends new entries on each submission.

⚡ Keyboard Navigation → Press Enter to move to the next field.

🖥️ Simple GUI Interface with a clean layout.

🔔 Success & Error Messages using Tkinter messagebox.




## 🛠️ Tech Stack

Python 3.x

Tkinter → for GUI design

OpenPyXL → for Excel integration




## 📂 File Structure

GUI_App_for_Data_Entry/

│-- GUI_App_for_Data_Entry.py   # Main application script

│-- wb.xlsx                     # Auto-generated Excel file (after first run)

│-- README.md                   # Project documentation





## 📸 Screenshots

## Students Data Entry UI

![image_alt](https://github.com/khushbu0130/GUI_App_for_Data-Entry/blob/24a4654da97e9dfd96af3531058507b900918ec8/Screenshots/Students%20Data%20Entry%20UI.png)

## Students Details

![image_alt](https://github.com/khushbu0130/GUI_App_for_Data-Entry/blob/85f56ac6d445949f24d48bf016b0cc85cc1d4042/Screenshots/Details%20of%20Students%20Data.png)

## ✅ Data Saved Successfully

![image_alt](https://github.com/khushbu0130/GUI_App_for_Data-Entry/blob/9df8486ffc503c8edc802476381c8b3be9199678/Screenshots/Data%20Saved%20Successfully.png)

(Your app shows a confirmation popup when data is saved.)




## ▶️ How to Run

Clone the repository or download the files.

git clone https://github.com/your-username/GUI_App_for_Data_Entry.git
cd GUI_App_for_Data_Entry


Install dependencies:

pip install openpyxl


Run the application:

python GUI_App_for_Data_Entry.py




## 📝 Example Fields

Name

Course

Semester

Form No.

Contact Number

Email-ID

Address




## 📊 Output in Excel

Each submission is stored in wb.xlsx like this:

Name	Course	Semester	Form No.	Contact Number	Email-ID	Address
John Doe	B.Tech	5	12345	9876543210	john@example.com
New Delhi, IN




## 🌟 Future Enhancements

Add search & update functionality

Export data to CSV or PDF

Enhanced form validation (email, phone number)

Dark mode UI 🎨




## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

📧 Contact

Developed by [Your Name]
📩 Email: your.email@example.com

🌐 GitHub: your-username
