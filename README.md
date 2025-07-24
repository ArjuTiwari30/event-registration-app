# 📅 Event Registration App – Trailhead Project

This project is part of the **Build an Event Registration App** module on [Salesforce Trailhead](https://trailhead.salesforce.com/content/learn/projects/build-an-event-registration-app). It simulates how an organization manages events and registrations using custom objects, relationships, and Flow automation inside Salesforce.


## 📌 Project Summary

The Event Registration App allows users to register attendees for different events via a **Screen Flow**. It creates or finds a Contact and then associates them with an Event through a Registration object.


## 🛠️ Key Features

- 🧱 Custom Objects:
  - **Event** (Parent)
  - **Event Registration** (Child)
- 🔗 Lookup Relationship between Contact and Event
- 📄 Page Layout customizations
- 🎯 Flow to automate attendee registration
- ⚠️ Conditional logic to check for duplicates
- 🧪 Validations and decision-based actions


## 🧠 Flow Highlights

- **Screen Elements**: To collect attendee name, email, and selected event
- **Get Records**: To check if Contact already exists
- **Create Records**: To add new Contacts and Registrations
- **Assignment Element**: To map values for record creation
- **Decision Element**: To branch logic based on conditions


## 💡 Key Learnings from This Project

- Created Custom Objects: `Event` and `Event Registration`
- Built Lookup Relationships between `Event`, `Event Registration`, and `Contact`
- Designed and implemented a **Screen Flow** with:
  - Get Records
  - Decision
  - Assignment
  - Create Records
- Understood how to use automation to reduce manual work
- Practiced real-world data modeling using Salesforce platform


## 📸 Screenshots

### Trailhead Badge: Event Registration App
<img width="1920" height="1080" alt="Screenshot 2025-07-24 222237" src="https://github.com/user-attachments/assets/1982ec82-9960-451e-b938-b5bc8aac2d42" /><img width="1920">

### Session Object – Registration Record
 <img height="1080" alt="Screenshot 2025-07-25 001205" src="https://github.com/user-attachments/assets/66029a3a-12a3-4119-a06e-2634c7db49a0" />

### Flow Builder – Event Registration Flow Logic
<img width="1920" height="1080" alt="Screenshot 2025-07-25 001036" src="https://github.com/user-attachments/assets/2a84e7ce-358a-4797-ac8c-dae92e8fdb61" />

