# BITCollege_ADU

BITCollege_JW is a web application developed using ASP.NET. This project aims to provide a platform for managing various college-related activities. 

## Features

- User authentication and authorization
- Student management
- Course management
- Enrollment tracking
- Tuition rate adjustments

## Project Structure

The main components of the project are organized as follows:

- `App_Data`: Database files and other data-related assets
- `App_Start`: Configuration settings for the application
- `Content`: CSS and other static files
- `Controllers`: MVC controllers handling HTTP requests
- `Data`: Data access layer
- `Migrations`: Database migrations
- `Models`: Application data models
- `Scripts`: JavaScript files
- `Views`: Razor views for the MVC pattern
- `Global.asax` & `Global.asax.cs`: Application startup logic
- `Web.config`: Main configuration file for the application

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/BITCollege_JW.git
    ```

2. Open the solution file `BITCollege_JW.sln` in Visual Studio.

3. Restore the NuGet packages:
    ```sh
    dotnet restore
    ```

4. Update the database:
    ```sh
    dotnet ef database update
    ```

5. Run the application:
    ```sh
    dotnet run
    ```

## Usage

Once the application is running, you can access it in your web browser at `http://localhost:5000`.

### User Authentication

- Register a new account or log in with an existing one.
- Access different functionalities based on your role (Admin, Student, Instructor).

### Managing Students and Courses

- As an admin or instructor, you can add, update, or remove students and courses.
- Track student enrollments and course completions.

### Tuition Rate Adjustments

- Adjust tuition rates based on various criteria.
- Ensure that the changes are reflected across the system.

## Running Tests

The project includes a set of tests to ensure the reliability of the application. To run the tests, use the following command in the terminal:

```sh
dotnet test

