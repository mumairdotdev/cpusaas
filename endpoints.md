## API Endpoints

### Authentication

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login a user
- `GET /api/auth/profile` - Get user profile

### Process Sets

- `POST /api/process` - Create a new process set
- `GET /api/process` - Get all process sets
- `GET /api/process/:processSetId` - Get a specific process set
- `PUT /api/process/:processSetId` - Update a process set
- `DELETE /api/process/:processSetId` - Delete a process set

### Simulations

- `POST /api/simulate/run` - Run a simulation
- `GET /api/simulate` - Get all simulations
- `GET /api/simulate/:simulationId` - Get a specific simulation