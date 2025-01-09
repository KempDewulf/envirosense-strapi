# Strapi-CMS

## Project Overview
This project is a content management system (CMS) using Strapi. In our case it's used as a database management system.

By using Strapi we get an out-of-the-box REST API for our database.

## Setup Instructions

### Prerequisites
- Node.js
- npm or yarn

### Installation
1. Clone the repository:
    ```sh
    git clone git@gitlab.ti.howest.be:ti/2024-2025/s5/ccett/projects/group-14/strapi-cms.git
    cd strapi-cms
    ```

2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

### Environment Variables
Create a `.env` file in the root directory of your project by copying the `.env.example` file:
```sh
cp .env.example .env
```

Replace the placeholder values with your actual database credentials and JWT secret.

### Running the Project in development mode
To start the development server, run:
```sh
npm run develop
# or
yarn develop
```

### Running the Project in Production mode
To run the project in production mode, follow these steps:

1. Build the project:
    ```sh
    npm run build
    # or
    yarn build
    ```

2. Start the project:
    ```sh
    npm run start
    # or
    yarn start
    ```

Ensure that your environment variables are correctly set up in the `.env` file before starting the project in production mode.
