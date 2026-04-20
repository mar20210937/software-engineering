## Use Case Descriptions

### UC-01: View Available Parking Spaces

| Field | Description |
|------|------------|
| Use Case ID | UC-01 |
| Use Case Name | View Available Parking Spaces |
| Primary Actor | Driver/User |
| Description | The user checks available parking spaces using the system. |
| Preconditions | System is running and data is available |
| Postconditions | Available spaces are displayed |
| Main Flow | 1. User opens app 2. System retrieves data 3. System displays spaces |
| Alternative Flow | If no spaces available → system shows "Full" |

---

### UC-02: Reserve Parking Spot

| Field | Description |
|------|------------|
| Use Case ID | UC-02 |
| Use Case Name | Reserve Parking Spot |
| Primary Actor | Driver/User |
| Description | User reserves an available parking space |
| Preconditions | User logged in and space available |
| Postconditions | Spot is reserved |
| Main Flow | 1. User selects space 2. System checks availability 3. Reservation confirmed |
| Alternative Flow | If space unavailable → choose another |

---

### UC-03: Receive Guidance

| Field | Description |
|------|------------|
| Use Case ID | UC-03 |
| Use Case Name | Receive Guidance |
| Primary Actor | Driver/User |
| Description | System guides user to parking spot |
| Preconditions | Spot reserved |
| Postconditions | User gets directions |
| Main Flow | 1. User requests guidance 2. System calculates route 3. Displays directions |
| Alternative Flow | If spot taken → assign new spot |

---

### UC-04: Pay Parking Fee

| Field | Description |
|------|------------|
| Use Case ID | UC-04 |
| Use Case Name | Pay Parking Fee |
| Primary Actor | Driver/User |
| Supporting Actor | Payment Gateway |
| Description | User pays parking fee |
| Preconditions | Parking session completed |
| Postconditions | Payment recorded |
| Main Flow | 1. User requests payment 2. System calculates fee 3. Payment processed |
| Alternative Flow | Payment fails → retry |

---

### UC-05: Detect Entry/Exit

| Field | Description |
|------|------------|
| Use Case ID | UC-05 |
| Use Case Name | Detect Entry/Exit |
| Primary Actor | Camera System |
| Description | System detects vehicle entering/exiting |
| Preconditions | Camera active |
| Postconditions | Entry/exit recorded |
| Main Flow | 1. Vehicle detected 2. Data sent to system 3. System updates record |
| Alternative Flow | Plate not recognized → manual check |

---

### UC-06: Update Parking Availability

| Field | Description |
|------|------------|
| Use Case ID | UC-06 |
| Use Case Name | Update Parking Availability |
| Primary Actor | Sensor System |
| Description | System updates space status |
| Preconditions | Sensors working |
| Postconditions | Availability updated |
| Main Flow | 1. Sensor detects change 2. Sends data 3. System updates |
| Alternative Flow | Sensor fails → fallback method |

---

### UC-07: Manage Parking Spaces

| Field | Description |
|------|------------|
| Use Case ID | UC-07 |
| Use Case Name | Manage Parking Spaces |
| Primary Actor | Admin |
| Description | Admin manages parking spaces |
| Preconditions | Admin logged in |
| Postconditions | Data updated |
| Main Flow | 1. Admin edits data 2. System validates 3. Saves changes |
| Alternative Flow | Invalid input → error |

---

### UC-08: Manage Pricing

| Field | Description |
|------|------------|
| Use Case ID | UC-08 |
| Use Case Name | Manage Pricing |
| Primary Actor | Admin |
| Description | Admin sets pricing rules |
| Preconditions | Admin logged in |
| Postconditions | Pricing updated |
| Main Flow | 1. Admin enters pricing 2. System saves |
| Alternative Flow | Conflict → revise |

---

### UC-09: View Occupancy

| Field | Description |
|------|------------|
| Use Case ID | UC-09 |
| Use Case Name | View Occupancy |
| Primary Actor | Admin |
| Description | Admin views parking usage |
| Preconditions | Data available |
| Postconditions | Occupancy displayed |
| Main Flow | 1. Admin opens dashboard 2. System shows data |
| Alternative Flow | Data unavailable → error |

---

### UC-10: Generate Reports

| Field | Description |
|------|------------|
| Use Case ID | UC-10 |
| Use Case Name | Generate Reports |
| Primary Actor | Admin |
| Description | Admin generates reports |
| Preconditions | Admin logged in |
| Postconditions | Report generated |
| Main Flow | 1. Select report 2. System generates 3. Display/export |
| Alternative Flow | No data → empty report |