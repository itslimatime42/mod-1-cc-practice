## Deliverables

### Appointment

- Appointment.all
- appointment#doctor
  - Returns this appointment's doctor instance
- appointment#patient
  - Returns this appointment's patient instance

### Doctor

- Doctor.all
- Doctor.name
- doctor#appointments
  - Gets a list of all the appointments (instances) that belong to this doctor (use "select")
- doctor#patients
  - Gets a list of all the patients (instances) that belong to this doctor (use "map")

### Patient

- Patient.all
- Patient.name
- patient#appointments
  - Gets a list of all the appointments (instances) that belong to this patient
- patient#doctors
  - Gets a list of all the doctors (instances) that belong to this patient
- patient#create_appointment
  - Takes a doctor as an argument
