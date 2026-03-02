# 📱 Appointment Booking System - ER Diagram  
### Pre-Internship Task 1 Submission   
---


## Entities Included

The ER Diagram includes the following main entities:

- **Patients**
- **Doctors**
- **Specializations**
- **Doctor_Availability**
- **Time_Slots**
- **Appointments**
- **Payments**

---

## Relationships Covered

- A Patient can book multiple Appointments.
- A Doctor can have multiple Availability slots.
- Each Appointment is linked to:
  - One Patient
  - One Doctor
  - One Time Slot
- Each Doctor belongs to one Specialization.
- Each Appointment may have one Payment record.

---

## Loom Explanation Video

Loom link - https://www.loom.com/share/f45dde4f0e114cbe9c0cca1d1ca8fe13

---

## Key Design Decisions

- Used separate Availability and Time Slot tables to maintain flexibility.
- Ensured referential integrity using foreign keys.
- Designed scalable structure for future features like:
  - Reviews
  - Notifications
  - Multi-specialization doctors

---
