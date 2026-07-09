## Project Structure

```
/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   └── App.js          # Main application component
│   └── package.json        # Frontend dependencies
│
└── server/                 # Node.js backend
    ├── config/             # Configuration files
    ├── controllers/        # API controllers
    ├── data/               # Data storage directory
    │   ├── backups/        # Database backups
    │   ├── exports/        # Data exports
    │   └── logs/           # Application logs
    ├── middlewares/        # Express middlewares
    ├── routes/             # API routes
    ├── .env                # Environment variables
    ├── db_setup.sql        # Database setup script
    ├── index.js            # Server entry point
    └── package.json        # Backend dependencies
```

## Tech Stack

- **Frontend**: React.js, Chart.js
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL