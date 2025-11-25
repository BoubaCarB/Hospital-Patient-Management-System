# C++ Hospital Patient Management System  
**Priority Queue • File I/O • Transaction Logging • Daily Analytics**

A full-featured patient management system for a multi-department hospital, built in C++

- **Priority queue** implementation: Critical patients automatically jump ahead of regular patients (custom linked-list-style logic using `vector` with insertion rules)
  
- Loads initial patients from `patient.csv` with full validation (clinic code, numeric SSN, capacity limits)
  
- Interactive menu system for three clinics (Heart, Pulmonary, Plastic Surgery)
  
- Supports: Add regular/critical patients • Operate (serve next patient) • Cancel by SSN • List current queue
  
- Complete transaction logging to `transaction.log` (every action, error, and patient movement)
  
- **End-of-day analytics summary** — shows patients treated, critical cases prioritized, and remaining patients per clinic
  
- Generates `patient_next_day.csv` for continuity


### Demo Screenshots

#### 1. Main Clinic Selection Menu
<img width="593" height="92" alt="Screenshot 2025-11-24 at 11 37 29 PM" src="https://github.com/user-attachments/assets/c7e17363-dd85-4852-8f31-90b7f2a97cd5" />

#### 2. Heart Clinic Menu + Patient List
<img width="380" height="177" alt="Screenshot 2025-11-24 at 11 39 52 PM" src="https://github.com/user-attachments/assets/dc78e2c9-5e0a-428c-9442-a577e107336e" />

#### 3. Adding a Critical Patient (Priority Jump)
<img width="589" height="177" alt="Screenshot 2025-11-24 at 11 49 32 PM" src="https://github.com/user-attachments/assets/6609d264-1b1d-4881-b536-5d5ad20fd036" />

#### 4. Operating on Patients
<img width="632" height="35" alt="Screenshot 2025-11-24 at 11 52 11 PM" src="https://github.com/user-attachments/assets/f34071dc-e2ce-441e-9238-0989b8b9dad0" />

#### 5. End-of-Day Analytics Summary
<img width="726" height="257" alt="Screenshot 2025-11-24 at 11 53 21 PM" src="https://github.com/user-attachments/assets/40a1f77e-92e1-488d-8300-aae88c07bd50" />
