# Backend Directory Structure for AI Chatbot Project

## Directory Structure
.
├── config
│   ├── config.js
│   └── db.js
├── controllers
│   ├── UserController.js
│   └── ChatController.js
├── models
│   ├── User.js
│   └── Message.js
├── routes
│   ├── userRoutes.js
│   └── chatRoutes.js
├── services
│   └── ChatService.js
├── utils
│   └── logger.js
└── app.js

## Explanation
- **config/**: Contains configuration files.
- **controllers/**: Contains request handler functions.
- **models/**: Contains database models.
- **routes/**: Contains route definitions.
- **services/**: Contains business logic related to the chatbot.
- **utils/**: Contains utility functions.
- **app.js**: Main file to start the server.
