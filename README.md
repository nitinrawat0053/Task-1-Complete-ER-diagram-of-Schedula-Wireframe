# 📱 Appointment Booking System - ER Diagram  
### Pre-Internship Task 1 Submission   
---


## Entities Included

The ER Diagram includes the following main entities:

- **Users**
- **Patients**
- **Doctors**
- **Specializations**
- **Doctor_Availability**
- **Slots**
- **Appointments**
- **Appointment_Medical_Details**
- **Payments**
- **Chat_Messages**
- **Feedback**
- **Notifications**

---

## Relationships Covered

- A User can be either a Patient or Doctor.
- A Patient can book multiple Appointments.
- A Doctor can create multiple Availability schedules.
- A Doctor can generate multiple Slots.
- Each Appointment is linked to:
   One Patient
   One Doctor
   One Slot
- Each Doctor belongs to one Specialization.
- Each Appointment may have one Payment record.
- Notifications are linked to Users.
- Chat messages are linked to Appointments.


---

## Key Design Decisions

- Introduced a centralized Users table for authentication.
- Implemented slot-based booking for better scalability.
- Maintained referential integrity using foreign keys.
- Used timestamp-based appointment scheduling.
- Designed system to support future features like:
   Multi-role access
   Appointment reminders
   Advanced reporting
   Audit logs

---
