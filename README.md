# Guest-Reservation-System
# Hostel Guest Room Reservation System

A beginner-friendly **Python GUI project** built using **Tkinter** for managing hostel guest room reservations. This system helps in handling guest bookings, room allocation, check-in/check-out, cancellation, and daily reporting efficiently.

---

## Features

* Add new guest reservations
* Update existing reservations
* Cancel reservations
* Search bookings by Student ID or Guest Name
* Automatic room allocation
* Check-In and Check-Out management
* Daily booking report generation
* Policy validation for guest relation and stay duration
* File handling for permanent data storage
* Simple notification system using message boxes and console messages

---

## Technologies Used

* **Python**
* **Tkinter** (GUI)
* **File Handling** (`.txt` file storage)
* **Functions**
* **Lists and Dictionaries**
* **Treeview (ttk)** for displaying records

---

## Project Structure

```text
system.py          # Main Python project file
bookings.txt       # Stores all booking records
README.md          # Project documentation
```

---

## Booking Details Stored

The system stores the following details:

* Student ID (used as Booking ID)
* Guest Name
* Relation (Father / Mother / Guardian)
* Room Number
* Number of Stay Days
* Booking Status (Booked / Checked In / Checked Out)

---

## Rules Implemented

### Guest Policy

Only the following relations are allowed:

* Father
* Mother
* Guardian

### Stay Duration Limit

* Maximum allowed stay: **3 days**

---

## How to Run

### Step 1: Install Python

Make sure Python is installed on your system.

### Step 2: Save the Project Files

Keep `system.py` and `bookings.txt` in the same folder.

### Step 3: Run the Program

```bash
python system.py
```

### Step 4: Use the GUI

The Tkinter window will open where you can manage reservations.

---

## Sample Functionalities

### Add Reservation

Enter:

* Student ID
* Guest Name
* Relation
* Days

The system will:

* Validate policy
* Allocate room automatically
* Save booking

### Update Reservation

Modify guest name or stay duration.

### Cancel Reservation

Delete booking using Student ID.

### Check-In / Check-Out

Update guest stay status.

### Daily Report

Shows:

* Total bookings
* Checked In guests
* Checked Out guests
* Currently booked guests

---

## Future Improvements

* Admin Login System
* Database Integration using MySQL or SQLite
* Email/SMS Notifications
* Advanced Reporting Dashboard
* Export Reports to PDF/Excel
* Improved UI Design

