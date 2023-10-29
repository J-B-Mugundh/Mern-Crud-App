# MERN CRUD Application

A simple MERN stack CRUD (Create, Read, Update, Delete) application for managing data. This project demonstrates how to build a web application using the MongoDB, Express.js, React, and Node.js stack.

![MERN-CRUD](https://github.com/J-B-Mugundh/Mern-Crud-App/assets/98593517/bc93e810-5f23-449a-a392-aee53f59e042)

## Features

- Create, Read, Update, and Delete data items.
- User-friendly web interface built with React.
- RESTful API powered by Express.js and Node.js.
- Data storage and retrieval using MongoDB.
- Real-time updates using WebSockets (Socket.io).
- Error handling and validation for a smooth user experience.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed.
- MongoDB database connection.
- A code editor (e.g., Visual Studio Code).

## Getting Started

1. **Clone the repository:**

  ```bash
git clone https://github.com/your-username/MERN-CRUD-Application.git
```
  
2. Navigate to the project directory:
  ```bash
cd MERN-CRUD-Application
```

3. Install the dependencies for the client:

```bash
cd client
npm install vite
```

4. Install the dependencies for the server:
```bash
cd server
npm install -y
```

6. Create a .env file in the server directory and configure the following environment variables:

```bash
MONGODB_URI=your_mongodb_connection_string
PORT=your_server_port
```

6. Start the client:
```bash
cd client
npm run dev
```

7. Start the server:
```bash
cd server
npm start
```

8. Open your web browser and access the application at http://localhost:5173

## Usage

To create a new data item, click the "Add Item" button and fill out the form.
To view or edit an existing item, click on the item in the list.
To delete an item, click the "Delete" button when viewing an item.
Real-time updates are supported, so changes made by one user will be reflected to other connected users.

## Contributing
1. Fork the project.
2. Create your feature branch: git checkout -b feature/your-feature
3. Commit your changes: git commit -m 'Add some feature'
4. Push to the branch: git push origin feature/your-feature
5. Submit a pull request.

## Acknowledgments
Special thanks to the open-source community for the amazing tools and libraries that make projects like this possible.

## Contact

If you have any questions or suggestions, feel free to contact:
- Mugundh J B: [LinkedIn](https://linkedin.com/in/mugundhjb) 😄
