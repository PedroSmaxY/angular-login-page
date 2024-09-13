# Angular Login and Registration System

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](https://opensource.org/licenses/MIT)
<br />
![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

## Overview

This project is a **login and registration system** built with **Angular** and **TypeScript**, using **JWT (JSON Web Tokens)** for authentication. It is designed to integrate seamlessly with my [**login-auth-api**](https://github.com/PedroSmaxY/login-auth-api), which handles backend services such as user registration, login, and authentication management.

## Table of Contents

- [Features](#Features)
- [Screenshots](#screenshots)
- [Technologies used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [JWT Authentication Flow](#jwt-authentication-flow)
- [License](#license)
- [Contributing](#contributing)

## Features

- **User Login:** Allows users to log in with valid credentials.
- **User Registration:** A registration form for new users.
- **JWT Authentication:** After a successful login, a JWT token is issued for subsequent requests.
- **Protected Routes:** Routes are secured and accessible only with valid authentication tokens.

## Screenshots

### Login Page
![image](https://github.com/user-attachments/assets/05c156f6-a27f-447a-9e40-e8e87a1f4850)

### Signup Page
![image](https://github.com/user-attachments/assets/8843bebb-e2ef-4b02-ba9f-592c74dbf66c)

## User Page (Authenticated)
![image](https://github.com/user-attachments/assets/87d10eed-42ca-4aa9-81b8-b02a21a7ec5f)


## Technologies Used

- ![Angular](https://img.shields.io/badge/Angular-red?style=for-the-badge&logo=angular)
- ![TypeScript](https://img.shields.io/badge/typescript-white?style=for-the-badge&logo=typescript)

## Prerequisites

To run this project locally, you'll need:

- [**Node.js**](https://nodejs.org/en)
- [**Angular CLI**](https://angular.dev/tools/cli): Version 18.x or higher

## Getting Started

1. **Clone the Repository:**

```bash
git clone https://github.com/PedroSmaxY/angular-login-page.git
```

2. **Navigate to the Project Directory**

```bash
cd angular-login-page
```

3. **Install Dependencies:**

```bash
npm install
```

4. **Run the Application:**

```bash
ng serve
```

1. **Open `http://localhost:4200/`** on your browser.

## API Endpoints

Make sure to either integrate this application with your own backend or use mock APIs for authentication. Alternatively, you can clone and run my [login-auth-api](https://github.com/PedroSmaxY/login-auth-api), specifically designed to work with this application. Example endpoints include:

- Login Endpoint: `/login`
- Register Endpoint: `/signup`
- Protected Route: `/user`

# JWT Authentication Flow

1. The user logs in with their email and password.
2. The server validates the credentials and returns a JWT token.
3. The token is stored locally (e.g., in `localStorage`).
4. For every request to a protected route, the token is sent in the authorization header.

## License

### angular-login-page is licensed under the [MIT License](https://github.com/PedroSmaxY/angular-login-page/blob/master/LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request to the repository.

When contributing to this project, please follow the existing code style, [commit conventions](https://www.conventionalcommits.org/en/v1.0.0/), and submit your changes in a separate branch.
