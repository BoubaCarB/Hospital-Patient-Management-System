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
