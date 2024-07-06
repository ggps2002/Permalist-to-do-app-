# Permalist App

Permalist is a web application that helps users create and manage permanent, shareable lists. Users can add items to their lists, mark items as completed, and share their lists with others. This application is built using EJS (Embedded JavaScript), PostgreSQL, Node.js, and CSS.

## Features

- **Create Lists**: Easily create new lists for any purpose.
- **Manage Items**: Add, edit, delete, and mark items as completed.
- **Share Lists**: Generate shareable links to share your lists with others.

## Technology Stack

- **Frontend**: EJS (Embedded JavaScript)
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Styling**: CSS

## Installation

### Prerequisites

- Node.js and npm installed
- PostgreSQL installed and running

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/permalist-app.git
    cd permalist-app
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up the database**:
    - Create a PostgreSQL database.
    - Run the SQL script provided in `db/schema.sql` to set up the database schema.
    - Create a `.env` file in the root directory and add your database connection details:
      ```env
      PG_HOST=localhost
      PG_USER=yourusername
      PG_PASSWORD=yourpassword
      PG_DATABASE=permalist
      PORT=3000
      ```

4. **Start the application**:
    ```bash
    npm start
    ```

5. **Open your browser** and go to `http://localhost:3000`.

## Usage

1. **Create a List**:
    - Navigate to the homepage.
    - Click on "Create New List" and enter a name for your list.
2. **Add Items**:
    - Select a list and click on "Add Item".
    - Enter the item details and save.
3. **Manage Items**:
    - Mark items as completed.
    - Edit or delete items as needed.

