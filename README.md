# PlanZilla : The Beast of Calendar Management

PlanZilla is a web application that simplifies calendar management by integrating with Google Calendar. It provides an intuitive interface to view, filter, and manage events effortlessly.

---

## Features

### **Authentication**
- Secure Single Sign-On (SSO) login using Google.

### **Event Dashboard**
- Displays upcoming events in a table format.
- Provides detailed event information, including:
  - **Date**
  - **Time**
  - **Location/Meet Link**
  - **Event Title**

### **Filtering and Searching**
- Filter events by:
  - Specific Date
  - Month
- Search for events using:
  - Event Name
  - Location Name
  - Day Name

### **Pagination**
- Navigate through large event lists with pagination.

### **Detailed Event View**
- Click on a table row to view:
  - Guests Invited
  - Meet Link
  - Event Description
  - All-Day Event Indicator

---

## Tech Stack

### **Backend**: Node.js
- Scalable and efficient for handling API requests.
- Built-in support for asynchronous operations ensures smooth integration with Google Calendar API.

### **Frontend**: HTML, CSS, JavaScript
- **HTML**: Structures the web content.
- **CSS**: Delivers a responsive and visually appealing design.
- **JavaScript**: Adds interactivity and dynamic functionality.

### **Google Calendar API**
- Fetches real-time event data for authenticated users.
- Enables robust event management capabilities.

## Local Installation
- Clone the repo
- cd backend
- npm install
- node server.js

## Usage

- **Log in** using your Google account.
- View your upcoming events in the dashboard.
- Use filters or the search bar to find specific events.
- Click on any event for detailed information.

---
