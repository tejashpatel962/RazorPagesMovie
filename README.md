# RazorPagesMovie

RazorPagesMovie is a movie database management web application built using **ASP.NET Core Razor Pages** and targeting **.NET 8**. This project allows users to manage movie records by performing CRUD operations (Create, Read, Update, Delete). The application provides a user-friendly interface for managing movie data while leveraging the power of **Entity Framework Core** for database interactions.

## Key Features
- **Movie Management**: Add, view, edit, and delete movie records in the database.
- **Filtering & Searching**: Easily filter movies by genre and title, providing an intuitive search experience.
- **Responsive UI**: Built with Razor Pages, ensuring a dynamic and responsive user interface for all devices.
- **Database Integration**: Utilizes **Entity Framework Core** for seamless communication with an **SQL Server** database.
- **Data Validation**: Both client-side and server-side validation to maintain data integrity and provide real-time feedback to users.

## Project Structure
- **Pages/Movies**: Contains Razor Pages (Index, Create, Edit, Details, Delete) for managing movies.
- **Data**: Contains the `RazorPagesMovieContext` class, which serves as the **Entity Framework Core** database context.
- **Models**: Contains the `Movie` model class, representing the movie entity in the database.

## Technologies Used
- **ASP.NET Core Razor Pages**
- **.NET 8**
- **Entity Framework Core**
- **SQL Server**
- **HTML, CSS, JavaScript** for front-end development

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/RazorPagesMovie.git
    ```

2. Navigate to the project directory:
    ```bash
    cd RazorPagesMovie
    ```

3. Build the project:
    ```bash
    dotnet build
    ```

4. Run the application:
    ```bash
    dotnet run
    ```

The application will be accessible at `https://localhost:5001`.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.
