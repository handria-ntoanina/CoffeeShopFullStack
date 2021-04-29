# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.

This project target is to demonstrate newly learned skills by creating a full stack drink menu application. The application can:

1. Display graphics representing the ratios of ingredients in each drink.
2. Allow public users to view drink names and graphics.
3. Allow the shop baristas to see the recipe information.
4. Allow the shop managers to create new drinks and edit existing drinks.

Details of implementation can be found in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

### Backend

The `./backend` directory contains a completed Flask server with SQLAlchemy module. It has the required endpoints, configuration, and integration with Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. The environment variables found within (./frontend/src/environment/environment.ts) reflects the Auth0 configuration details set up for the backend app.

[View the README.md within ./frontend for more details.](./frontend/README.md)
