# Demo Video Link: 👉 [Watch Here](https://drive.google.com/file/d/1mfMGn62flYE-QgX_TSpyN_Ov0helJjku/view?usp=sharing)

<video width="600" controls>
  <source src="https://github.com/akashb2003/ms-lab/blob/main/MS%20Project.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

# Expense Tracker

This project is an **Expense Tracker** application that allows users to manage their expenses by adding, viewing, editing, and deleting items. The frontend is built using **React** and the backend is developed using **Spring Boot**.

## Features

- Add an expense with details such as item name, amount, and category.
- View the list of all expenses.
- Edit existing expenses.
- Delete expenses from the list.
- Intuitive user interface with dynamic data handling.

## Getting Started

### Prerequisites

- Node.js and npm installed for the React frontend.
- Java and Maven installed for the Spring Boot backend.
- A compatible database (e.g., MySQL, PostgreSQL) with schema created for storing expenses.

### Installation

#### Clone the Repository
```bash
git clone https://github.com/akashb2003/ms-lab
```

#### Setup Frontend
```bash
cd expense-tracker/frontend
npm install
```

#### Setup Backend
1. Navigate to the backend directory:
   ```bash
   cd expense-tracker/backend
   ```
2. Create an `application.properties` file in the `src/main/resources` directory and configure your database connection:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your_database
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   spring.jpa.hibernate.ddl-auto=update
   ```
3. Build the Spring Boot project:
   ```bash
   mvn clean install
   ```

### Running the Application

#### Start the Backend Server
```bash
cd expense-tracker/backend
mvn spring-boot:run
```
The backend server will start at [http://localhost:8080](http://localhost:8080).

#### Start the Frontend
```bash
cd expense-tracker/frontend
npm start
```
The React development server will start at [http://localhost:3000](http://localhost:3000).

## Usage

1. **Add Expense**: Use the form on the app's homepage to add a new expense by specifying the item name, amount, and category.
2. **View Expenses**: View a list of all added expenses.
3. **Edit Expense**: Modify details of an existing expense.
4. **Delete Expense**: Remove an expense from the list.

## Project Structure

- **frontend/**: Contains the React code for the user interface.
- **backend/**: Contains the Spring Boot code for handling API requests and managing the database.
- **database/**: Contains database schema and migration scripts (if any).

## Technologies Used

- **Frontend**: React, HTML5, CSS3, JavaScript
- **Backend**: Spring Boot, Java
- **Database**: MySQL (or any preferred relational database)
- **Build Tools**: npm, Maven

## Learn More

To learn React, check out the [React documentation](https://reactjs.org/). 
To learn Spring Boot, refer to the [Spring Boot documentation](https://spring.io/projects/spring-boot).

## Contribution

Feel free to contribute to this project by opening issues or pull requests. Your contributions are welcome!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
