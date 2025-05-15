# AI-Powered Scheduling Assistant

This project aims to develop an AI-powered scheduling assistant that helps users seamlessly book medical appointments with multiple doctors, leveraging integration with Google Calendar and an intuitive conversational interface.

## Project Overview

The **AI-Powered Scheduling Assistant** is a collaborative effort, with each team member contributing different components of the solution. My focus was primarily on developing the **interface** of the application, which allows users to interact with the system and schedule appointments with multiple doctors. The interface is built with Gradio, a Python library that allows rapid prototyping of machine learning models and AI-driven applications.

### **Role and Contribution** (Trayshawn Mitchell)

As the **Interface Developer** for this project, I was responsible for:

- Designing and implementing the **user interface** using **Gradio**, allowing users to input their information and interact with the system.
- Integrating the interface with backend components such as Google Calendar, enabling users to book appointments with doctors by checking availability and managing time slots.
- Creating a **seamless user experience** by ensuring that the interface is easy to use and interactive, allowing for simple appointment scheduling across multiple doctors.

### **Key Features of the Interface**:

- **User-Friendly Input**: Users can easily enter details about their appointments, such as the type of consultation (e.g., mental health, primary care) and preferred time slots.
- **Real-Time Availability Check**: The interface checks both the user's personal calendar and the doctor's availability, ensuring that the recommended time slots are optimal for all parties involved.
- **Back-to-Back Appointment Scheduling**: The system suggests suitable times for consecutive appointments (e.g., scheduling a primary care appointment followed by a specialist consultation).
- **Referral Tracking**: For certain types of appointments, the system tracks the referral process and schedules specialist appointments only after the required referrals are made.

### **About the Project**

The project is divided into three main components, each handled by a different team member:

- **Trayshawn Mitchell** (Interface Developer): Designed and implemented the user interface using Gradio, focusing on creating an interactive and intuitive user experience.
- **Josh** (Data Exchange): Managed the integration of the backend using **FHIR** to retrieve medical appointment data and sync it with Google Calendar for scheduling.
- **Yusuf** (Backend & Google Integration): Built the backend system that communicates with Google Calendar, ensuring that both the user's and doctors' calendars are properly synced and appointment slots are managed efficiently.

## Installation and Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/tmmitch25/AI-Powered-Scheduling-Assistant-Architecture.git
