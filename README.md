# Discord Clone

Welcome to the Discord Clone repository! This project aims to replicate the functionality of Discord, providing real-time messaging, voice, and video communication in a sleek and customizable interface.

## Key Features

- **Real-time Messaging:** Utilizing Socket.io for seamless and instant communication between users.

- **Attachments:** Send attachments as messages using UploadThing for a rich messaging experience.

- **Message Management:** Delete and edit messages in real-time for all users.

- **Voice and Video Calls:** Create text, audio, and video call channels. Enable 1:1 conversations and video calls between members.

- **Member Management:** Manage your server efficiently with features like kicking members and changing roles (Guest/Moderator).

- **Invite System:** Generate unique invite links and implement a full working invite system for easy server sharing.

- **Infinite Loading:** Load messages in batches of 10 for optimal performance using @tanstack/query.

- **Server Customization:** Allow users to create and customize servers to suit their preferences.

- **Beautiful UI:** Implement a visually appealing user interface using TailwindCSS and ShadcnUI.

- **Responsivity:** Ensure a seamless user experience with full responsiveness and a mobile-friendly UI.

- **Light/Dark Mode:** Provide users with the option to choose between light and dark modes for a personalized experience.

- **Websocket Fallback:** Implement a fallback mechanism with polling and alerts to ensure uninterrupted communication.

- **ORM and Database:** Utilize Prisma as the Object-Relational Mapping (ORM) tool, backed by a MySQL database using Planetscale.

- **Authentication:** Implement secure authentication using Clerk.

## Getting Started

Follow these steps to get the Discord Clone up and running on your local machine or server:

1. Clone the repository: `git clone https://github.com/kundnanl/discord-clone.git`
2. Install dependencies: `npm install`
3. Configure your database and authentication settings.
4. Run the application: `npm start`

Happy Coding!
