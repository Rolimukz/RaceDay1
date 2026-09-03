# RaceDay1
RaceDay Event Management System

#  RaceDay - South African Event Management System

Welcome to **RaceDay**! This is a full-stack web application built to help manage road running, walking, and cycling events across South Africa. Whether you're organising the Comrades Marathon or a small community park run, RaceDay makes it easier.

---

## What RaceDay Does

Think of RaceDay as your all-in-one event management tool. It helps:

- **Event Organisers** create and manage events, track participants, and record results
- **Participants** find events, sign up, and track their personal race history

---

## Who's Using RaceDay?

### 🎯 Event Organisers
- Create and manage events (like marathons, cycle tours, and walks)
- Add different race categories (e.g., 5km, 10km, Half Marathon, Full Marathon)
- View who has signed up for your events
- Record finishing times and positions
- Manage route information

### Participants
- Browse and search for upcoming events
- Register for events and choose your category
- View your registration history
- Track your race results and personal bests
- View event details like routes and start times

---

## How the System is Built

| Layer | Technology |
|-------|------------|
| **Backend API** | C# / .NET 8 Web API |
| **Database** | SQL Server |
| **Frontend** | (Coming in Part 2) |
| **Containerization** | Docker (Part 3) |
| **Cloud Deployment** | Azure or AWS (Part 3) |

---

## The Database at a Glance

The system uses **7 core tables** to keep everything organised:

| Table | What It Stores |
|-------|----------------|
| **Roles** | User types (Admin, Organiser, Participant) |
| **Users** | All system user accounts |
| **Events** | Race and event information |
| **EventRoutes** | Route details like distance, start/end points, and maps |
| **Categories** | Different race categories within an event |
| **Enrolments** | Who is registered for which event |
| **Results** | Finishing times and positions for participants |

---

## Project Structure
