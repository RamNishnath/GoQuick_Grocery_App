# GoQuick_Grocery_App
GoQuick Grocery App description
Overview
Hello!! Welcome to GoQuick, a fullstack grocery application designed to provide a seamless shopping experience. Built using Angular 18 for the frontend and .NET 8 with C# for the backend, GoQuick offers robust features for managing grocery items, orders, payments, and user authentication. This project showcases modern web development practices, combining a powerful frontend with a scalable backend.

Tech Stack
Frontend: Angular 18 & TypeScript
Backend: .NET 8 with C#
Database: SQL Server (managed with SQL Server Management Studio)
Authentication: JWT-based authentication
Payment Integration: Stripe
Feedback System: EmailJS for contact and feedback
Extra Packages: @auth0/angular-jwt , xng-breadcrumb@9.0
API Communication: RESTful API with JSON data format
Build Tools: Visual Studio 2022, Visual Studio Code,Figma (UI/UX Design), Postman (API Testing), Swagger UI, Microsoft SQL Management Studio, Stripe Payment API, Angular CLI, .NET CLI, Git (Version Control)
Features
User Authentication

JWT-based authentication: Secure login and token management.
Registration and Login: New users can register and existing users can log in securely.
Product Management

Product Details: View detailed information for each product including name, price, description, and image.
Shopping Basket

Add to Basket: Users can add items to their shopping basket.
Update Basket: Adjust quantities of items in the basket.
Remove Items: Option to remove items from the basket.
Persistent Basket: The shopping basket persists between sessions.
Order and Checkout

Order Creation: Users can place an order after reviewing their basket.
Delivery Methods: Choose from different delivery options.
Payment Integration: Payments are securely processed using Stripe for a seamless checkout experience.
Responsive Design

Optimized for both mobile and desktop, offering a great user experience across devices.
Real-time Updates

Products and basket contents are updated in real-time using efficient API calls.
Concurrency control for basket updates to avoid conflicts.
Single Page Application
Feedback/Contact Us

Integrated with EmailJS to provide a simple and efficient way for users to send feedback or contact support directly via email.
Setup Instructions
Backend (.NET 8 + C#)
Install the .NET 8 SDK from the official .NET website.
Clone the repository:
git clone git@github.com:WangchukSherpa/GrocAppCP.git
Navigate to the backend project directory:
cd goquick-backend
Restore the required packages:
dotnet restore
Update the appsettings.json file with your database connection string and Stripe API keys.
Run the project:
dotnet run
Frontend (Angular v18.0)
Install Node.js and Angular CLI if not already installed:
npm install -g @angular/cli
Clone the frontend repository:
git clone https://github.com/yourusername/goquick-frontend.git
Navigate to the frontend project directory:
cd goquick-frontend
Install dependencies:
npm install
Configure EmailJS for the contact form in the frontend.
Start the Angular development server:
ng serve
Open a browser and go to http://localhost:4200/ to view the app.
Database
Set up a SQL Server database using SQL Server Management Studio.
Update the connection string in the appsettings.json file.
Run database migrations (if any) using Entity Framework.
Run the Master_Query.sql file
Payment Integration (Stripe)
Set up a Stripe account at https://stripe.com/.
Retrieve your Stripe API keys and add them to the backend configuration in appsettings.json.
