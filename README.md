# URL Shortener Project

This repository contains an URL shortener application with an ASP.NET Core backend and an Angular frontend.

## Structure

- `UrlShortener`: ASP.NET Core MVC project
- `urlShortenerClient`: Angular project

## Setup

### Backend

1. Navigate to the `UrlShortener` directory.
2. Restore NuGet packages:
    ```sh
    dotnet restore
    ```
3. Apply migrations and update the database:
    ```sh
    dotnet ef database update
    ```
4. Run the application:
    ```sh
    dotnet run
    ```

### Frontend

1. Navigate to the `urlShortenerClient` directory.
2. Install npm packages:
    ```sh
    npm install
    ```
3. Start the Angular application:
    ```sh
    npm start
    ```


