# 🚗 Parking Slot Management System

A browser-based **Parking Slot Management System** with a visual parking grid, built using pure HTML, CSS, and JavaScript.

## 📋 Features

- 🗺️ **Visual Parking Grid** — 3×5 grid showing slot status (white = free, green = occupied)
- 🚘 **Park a Vehicle** — Assign a vehicle to the next available slot automatically
- 🔓 **Remove a Vehicle** — Free up a slot by entering the vehicle number
- 📊 **Parked Vehicles Table** — Lists all currently parked vehicles with their assigned slot
- 🔢 **Live Slot Counter** — Displays the number of available parking slots in real time

## 🚀 Getting Started

No installation needed. Open directly in any modern browser:

```
PARKING/index.html
```

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & Layout |
| CSS3 | Grid styling and colour-coded slot status |
| JavaScript (Vanilla) | Parking logic & DOM updates |

## 📁 Project Structure

```
PARKING/
└── index.html    # All-in-one HTML file (HTML + CSS + JS)
```

## 🅿️ Parking Layout

The parking lot has **3 rows × 5 slots = 15 slots total**:

```
Row A:  A1  A2  A3  A4  A5
Row B:  B1  B2  B3  B4  B5
Row C:  C1  C2  C3  C4  C5
```

| Colour | Status |
|--------|--------|
| ⬜ White | Free / Available |
| 🟩 Green | Occupied |

## 💡 How to Use

1. **Park a Vehicle** — Enter the vehicle number and click **Park**
   - The system assigns the first available slot automatically
2. **Remove a Vehicle** — Enter the vehicle number and click **Remove**
   - The slot is freed and the grid updates immediately

## ✅ Validations

- Vehicle number cannot be empty
- Duplicate vehicle numbers are detected and rejected
- If the parking lot is full, a "PARKING FULL" message is shown
- If the vehicle is not found during removal, an error message is displayed

## 📌 Notes

- Vehicle numbers are stored in UPPERCASE automatically
- Data is stored in-memory and resets on page refresh
- No external dependencies or internet connection required
