# Blood Bank Management System

A web-based application to manage blood donations, requests, and stock efficiently for both donors and patients, with admin control over all operations.

---

## Features

### Admin
- Create and manage admin accounts.
- View dashboard with blood stock, donor count, requests, and approvals.
- Manage donors and patients (view, update, delete).
- Approve or reject blood donation requests; approved donations update the blood stock.
- Approve or reject blood requests from donors or patients; approved requests reduce the stock.
- Update blood units of specific blood groups.
- View the history of all blood requests.

### Donor
- Register and log in with personal details.
- Request to donate blood; blood is added to stock after admin approval.
- Request blood from the stock.
- View donation and blood request history with statuses (Pending, Approved, Rejected).
- View dashboard stats for requests made, approved, pending, or rejected.

### Patient
- Register and log in without admin approval.
- Request blood of a specific group and units from the stock.
- View request history with statuses (Pending, Approved, Rejected).
- View dashboard stats for requests made, approved, pending, or rejected.

---

## How to Run

1. Install Python (3.7 or later).
2. Download and extract the project.
3. Open the project folder in a terminal.
4. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt


## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :

```
python -m pip install -r requirements. txt
```

```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

