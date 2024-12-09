# ASP.NET CuaHangCafe Project

## Overview
This project is an ASP.NET MVC application designed to manage a coffee shop. It includes both a public-facing website and an administrative backend for managing various aspects of the coffee shop, such as products, bills, and news.

## Key Features
- **Public Website:**
  - Home Page: Displays the main content and navigation for the coffee shop.
  - Product Page: Lists available products with details.
  - Product Details Page: Provides detailed information about a specific product.
  - Cart Page: Allows customers to add products to their cart and manage their orders.
  - Checkout Page: Facilitates the checkout process for customers.

- **Admin Backend:**
  - Home Admin Page: Provides an overview and navigation for the admin section.
  - Bill Management: Allows admins to view and manage customer bills.
  - Product Management: Enables admins to add, edit, and delete products.
  - News Management: Allows admins to manage news articles and updates.

## Screenshots
- **Home Page**
  ![Home Page](https://github.com/ngquy02/ASP.NET_CuaHangCafe/assets/85392867/d434e9a6-9241-45e3-bea1-6914a3f987d4)

- **Product Page**
  ![Product Page](https://github.com/ngquy02/ASP.NET_CuaHangCafe/assets/85392867/a5386a74-56d2-484c-ad6b-95799873e89f)

- **Product Details Page**
  ![Product Details Page](https://github.com/ngquy02/ASP.NET_CuaHangCafe/assets/85392867/8acbc68e-40e8-4d31-bef3-0c22b469b7eb)

- **Cart Page**
  ![Cart Page](https://github.com/ngquy02/ASP.NET_CuaHangCafe/assets/85392867/af99f488-15df-4b48-95c2-cf1fcd26cd80)

- **Checkout Page**
  ![Checkout Page](https://github.com/ngquy02/ASP.NET_CuaHangCafe/assets/85392867/888390d5-4da7-4df3-a70e-57346b40dd26)

- **Admin Home Page**
  ![Admin Home Page](https://github.com/ngquy02/ASP.NET_CuaHangCafe/assets/85392867/b959ecf8-a95c-49f8-a113-733d889cec0d)

## Project Structure
- **.gitattributes**: Configuration file for Git to handle file attributes.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **README.md**: This file, containing a detailed description of the project.
- **Web_CuaHangCafe.sln**: Solution file for the ASP.NET MVC project.
- **Web_CuaHangCafe/**: Main directory of the ASP.NET MVC project.

### Web_CuaHangCafe Directory
- **Areas/**: Contains the admin backend areas.
  - **Admin/**: Admin-specific views and controllers.
    - **Views/**: Razor views for the admin backend.
      - **Bill/**: Views for managing customer bills.
        - **Index.cshtml**: List of customer bills.
        - **Search.cshtml**: Search functionality for customer bills.
      - **HomeAdmin/**: Views for the admin home page.
        - **Details.cshtml**: Detailed view of the admin home page.
        - **Index.cshtml**: Main admin home page.
        - **Search.cshtml**: Search functionality for the admin home page.
      - **NewsManage/**: Views for managing news articles.
        - **Details.cshtml**: Detailed view of a news article.
        - **Index.cshtml**: List of news articles.

- **Controllers/**: Contains the controllers for the MVC application.
- **Models/**: Contains the data models for the MVC application.
- **Views/**: Contains the Razor views for the public-facing website.
- **wwwroot/**: Contains static files such as CSS, JavaScript, and images.
- **App_Start/**: Contains configuration files for the application.
- **Global.asax**: Application startup file.
- **Web.config**: Configuration file for the web application.

## Setup and Running the Project
1. **Prerequisites:**
   - .NET SDK installed.
   - Visual Studio or any other IDE that supports ASP.NET MVC.

2. **Clone the Repository:**
   ```sh
   git clone https://github.com/ngquy02/ASP.NET_CuaHangCafe.git
   ```

3. **Navigate to the Project Directory:**
   ```sh
   cd ASP.NET_CuaHangCafe
   ```

4. **Open the Solution:**
   ```sh
   Web_CuaHangCafe.sln
   ```

5. **Run the Application:**
   - In Visual Studio, press `F5` to run the application.
   - Alternatively, you can use the .NET CLI:
     ```sh
     dotnet run
     ```

6. **Access the Application:**
   - Open your web browser and navigate to `http://localhost:5000` (or the port specified by your development environment).

## Additional Notes
- The project uses ASP.NET MVC for the backend and Razor views for the frontend.
- The admin backend is located in the `Areas/Admin` directory.
- The public website is located in the main `Web_CuaHangCafe` directory.
- Ensure that your database is set up and configured correctly before running the application.
