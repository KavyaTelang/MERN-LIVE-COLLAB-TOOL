# MERN-LIVE-COLLAB-TOOL

**COMPANY** : CODTECH IT SOLUTIONS

**NAME** : KAVYA TELANG

**INTERN ID** : CT6WKLY

**DOMAIN** : MERN STACK WEB DEVELOPMENT 

**BATCH DURATION** : January 20th, 2025 to March 5th, 2025

**MENTOR NAME** : Neela Santosh

### Real-Time Collaboration Tool

### Overview
This project is a real-time collaborative drawing application that allows multiple users to draw simultaneously with instant updates across all connected clients. The application leverages WebSocket communication to ensure synchronization and a seamless user experience. Developed using React, Redux Toolkit, and Tailwind CSS for the frontend and Node.js with Express for the backend, the project prioritizes performance, responsiveness, and scalability.

### Features
- **Real-Time Collaboration:** Multiple users can draw simultaneously with live updates.
- **Drawing Tools:** Brush customization with various sizes and colors.
- **Undo/Redo Functionality:** Users can easily modify their drawings.
- **Download Artwork:** Users can save their creations with a single click.
- **Responsive Design:** Ensures a seamless experience across different devices and screen sizes.

### Technology Stack
- **Frontend:** React, Redux Toolkit, Tailwind CSS, Socket.io-client.
- **Backend:** Node.js, Express, Socket.io.
- **Development Tools:** ESLint, Babel.

### Implementation of Real-Time Drawing
The core functionality of this application is real-time drawing synchronization using WebSocket technology:
- **Client-Side:** The drawing board component captures user input and emits socket events (`beginDraw`, `endDraw`). These events ensure that drawing actions are transmitted and reflected across all connected users in real time.
- **Server-Side:** The backend listens for drawing-related events and broadcasts updates to all active clients, maintaining synchronization across different users.

### Development Process
#### Frontend Development
- Designed an intuitive user interface using React and Tailwind CSS to enhance the drawing experience.
- Implemented the drawing board component using the HTML5 Canvas API to handle user interactions dynamically.
- Integrated Redux Toolkit for efficient state management to ensure smooth real-time updates.

#### Backend Development
- Developed a Node.js server using Express to handle WebSocket connections via Socket.io.
- Implemented event listeners to manage drawing actions and synchronize updates across multiple clients.
- Integrated error handling and reconnection mechanisms to ensure application stability.

#### Real-Time Communication
- Upon initiating a drawing action, a `beginDraw` event is emitted to the server, which then relays it to other connected clients.
- As users continue drawing, `endDraw` events update the canvas in real time, ensuring an accurate representation of the ongoing drawing.
- Custom event listeners manage undo/redo functionality and tool modifications, ensuring consistency across user interactions.

### Future Enhancements
- **User Authentication:** Implementation of account-based access and private drawing sessions.
- **Cloud Storage:** Ability to save and retrieve drawings from a database.
- **Advanced Drawing Tools:** Introduction of shape tools, layering, and enhanced brush effects.

# Resources 
--> GITHUB
--> CHATGPT

# OUTPUT OF TASK 

![image](https://github.com/user-attachments/assets/6b5c42c6-afe3-4b18-9216-770e0c505fb4)
