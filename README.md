# Notion-clone

This project is a simplified clone of the popular productivity application, Notion. It's designed to replicate some of the core features of Notion, providing a platform where users can create, edit, and organize their notes in a flexible and intuitive interface.

It uses Convex as the backend, which is a real-time database that allows for instant data updates. The application also uses Edgestore, a distributed key-value store, to manage the images and files uploaded by the users.The user authentication is handled by Clerk, a secure and scalable user authentication API.

## Features
### **Productivity and Organization**
- Notion-style editor for seamless note-taking
- Infinite children documents for hierarchical organization
- Expandable and fully collapsible sidebar for easy navigation
- Customizable icons for each document, updating in real-time
- Trash can with soft delete and file recovery options

### **User Experience**
- Light and Dark mode to suit preferences
- Full mobile responsiveness for productivity on the go
- Landing page for a welcoming user entry point
- Cover image for each document to add a personal touch

### **Data Management**
- Real-time database for instant data updates
-  File upload, deletion, and replacement options

### **Security and Sharing**
- Authentication to secure notes
- Option to publish your note to the web for sharing

## Technologies Used
The project utilizes various modern technologies for efficient development and user experience:

- **Next.js** – React framework for server-side rendering and static site generation.
- **Shadcn-ui** – UI component library for styling.
- **TypeScript** – Typed JavaScript for better maintainability.
- **Tailwind CSS** – Utility-first CSS framework for styling.
- **Clerk** – Authentication management.
- **Convex** – Real-time database for data management.
- **Edgestore** – File storage and management.
- **Blocknote** – Rich text editor for seamless note-taking.
