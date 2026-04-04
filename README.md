<div align="center">

# 📚 Course Experiments Guide

*A comprehensive guide for Full Stack Development course experiments, assignments, and attendance*
</div>

---
## 📑 Table of Contents

- [📖 Course Materials](#-course-materials)
- [🎯 Assignment Structure & Grading](#-assignment-structure--grading)
- [📤 Submission](#-submission)
  - [🎥 Demo Video](#-demo-video)
  - [📋 Requirements](#-requirements)
  - [📋 Project Submission Guidelines](#project-submission-guidelines)
- [🧪 Experiment Guides](#-experiment-1-guides)
  - [🧪 Experiment 7 Guides](#-experiment-7-guides)
  - [🧪 Experiment 6 Guides](#-experiment-6-guides)
  - [🧪 Experiment 5 Guides](#-experiment-5-guides)
  - [🧪 Experiment 4 Guides](#-experiment-4-guides)
  - [🧪 Experiment 3 Guides](#-experiment-3-guides)
  - [🧪 Experiment 2 Guides](#-experiment-2-guides)
  - [🧪 Experiment 1 Guides](#-experiment-1-guides)
  - [🧪 MST Experiment Guides](#-mst-experiment-guides)

---

## 📖 Course Materials

All source materials for the course are available at: <a href="https://github.com/orgs/cu-fsd2/repositories">github.com/orgs/cu-fs1/repositories</a>

## 🎯 Assignment Structure & Grading

## Experiment Evaluation Scheme

### Marks Distribution

| Component | Marks |
|----------|-------|
| Worksheet/Assignment | 5 |
| Viva | 10 |
| Conduct | 15 |
| MaxMarks | 30 |



### 🎥 Demo Video

<div align="center">
  <a href="https://vimeo.com/1156013385?share=copy&fl=sv&fe=ci">
    <img src="https://img.shields.io/badge/Watch%20Submission%20Demo-1bB7EA?style=for-the-badge&logo=vimeo&logoColor=white" alt="Watch Submission Demo" />
  </a>
</div>

---
## Project Submission Guidelines

## 1. Repository Structure & Format 📂
- Ensure that the **repository name** and **structure** match the example shown in the reference image provided.

## 2. Deployment Link 🌐
- Please **format the deployment link** correctly. If you're facing any issues with this, refer to the provided reference for changing the link format.

## 3. Exclude `node_modules` ❌
- Do **not** include the **`node_modules`** folder in the zip file. This is important for clean submissions and avoids unnecessary bloat.

## 4. Update README 📝
- Make sure your **README** is up-to-date and provides clear information about the project.
- Include a **folder** within the repository to store **screenshots** of the various web pages created for the project. Ideally, **2-3 screenshots** are sufficient.

## 5. Authentic Submission ✅
- Avoid making **fake GitHub submissions**. Ensure that the repository is legitimate, with relevant files and proper project documentation.


### 📋 Requirements


### 🏠 For WorkSheet/Assignments

You must submit the following inside a Google Form:

#### 1️⃣ Name

Your full name as registered in the course.

**Example:** `Navkaran Singh`

---

#### 2️⃣ UID (University ID)

Your university identification number.

**Example:** `24BDA70021`

---

#### 3️⃣ GitHub Repository Link

Link to your GitHub repository containing the experiment code.

**Example:** `https://github.com/navkaran/exp-1b`

---

#### 4️⃣ Deployment Link

Host your code on **Vercel** or **Netlify** using the naming convention:

```
{uid}-{experiment-part}-{name}.vercel.app
```

**Example:**
- **UID**: `24BDA70021`
- **Experiment**: `1b`
- **Name**: `Navkaran Singh`
- **Result**: `24bda70021-1b-navkaran-singh.vercel.app`

---

#### 5️⃣ How to Setup Vercel with GitHub

Follow these steps to deploy your project using Vercel with GitHub integration:

##### **Step 1: Create a GitHub Repository**

1. Go to <a href="https://github.com">GitHub</a> and sign in
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. Name your repository (e.g., `24bda70021-1b-navkaran-singh`)
5. Leave the default settings (Public)
6. Click on Add README button
7. Click **"Create repository"**


##### **Step 2: Sign Up for Vercel**

1. Go to <a href="https://vercel.com">Vercel</a>
2. Click **"Sign Up"**
3. Choose **"Continue with GitHub"**
4. Authorize Vercel to access your GitHub account

##### **Step 3: Import Your GitHub Repository**

1. On the Vercel dashboard, click **"Add New..."** → **"Project"**
2. You'll see a list of your GitHub repositories
3. Find your experiment repository and click **"Import"**

##### **Step 4: Configure Your Project**

1. **Project Name**: Change it to follow the naming convention:
   ```
   {uid}-{experiment-part}-{name}
   ```
   Example: `24bda70021-1b-navkaran-singh`

2. Click **"Deploy"**

##### **Step 5: Wait for Deployment**

- Vercel will build and deploy your project
- This usually takes 30-60 seconds
- Once complete, you'll see a success message with your live URL

##### **Step 6: Copy Your Deployment Link**

Your project will be live at:
```
https://24bda70021-1b-navkaran-singh.vercel.app
```

Copy this link and submit it in the Google Form!

> [!TIP]
> **Automatic Deployments**: Every time you push changes to your GitHub repository, Vercel will automatically redeploy your project with the updates!

---

#### 6️⃣ README.md File

Create a comprehensive README equivalent to your practical file:

- ✅ Include code snippets with syntax highlighting
- ✅ Add detailed explanations
- ✅ Document your implementation approach
- ✅ Include screenshots or demos (if applicable)

# 🧪 Experiment 7 Guides

## 🚨 Important Instructions
- **Deadline**: **07 April 2026, Evening**

### 📝 Google Form

Please submit your project details using the following link:

<div align="center">
  <a href="https://forms.gle/jSNYGcN7d5kmBSpZ9">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

---

## 📌 Assessment Topic
Implement **Role-Based Authorization (RBAC)** in your backend using **Spring Boot**.

Your application must support:
- **User authentication** using Spring Security
- **Role-based access control** such as `ADMIN` and `USER`
- **Protected APIs** that can only be accessed based on assigned roles
- Testing and demonstration of authorization using **Postman**

You must **demonstrate** how authorization works by showing that:
- a normal user can access only permitted endpoints
- an admin can access admin-only endpoints
- unauthorized or forbidden requests are blocked correctly

---

## ✅ Submission Requirements

### 1. Backend Implementation
Implement **role-based authorization** in Spring Boot.

Your backend should include:
- User login/authentication
- Role assignment for users
- Endpoint protection based on roles
- Proper HTTP responses for unauthorized and forbidden access

### 2. Mandatory Screenshots
You must include **at least 4 screenshots** in your project.

Required screenshots:
1. **Login request** with valid credentials
2. **Successful response** after login (or successful access to secured endpoint)
3. **USER role accessing a user endpoint successfully**
4. **USER role denied access to ADMIN endpoint** or **ADMIN role successfully accessing ADMIN endpoint**

Recommended extra screenshots:
- Invalid login attempt
- Request without token returning `401 Unauthorized`
- Access denied response returning `403 Forbidden`

> You will be evaluated based on your implementation, screenshots, project structure, and the quality of your **README**.

### 3. GitHub Project Structure
Follow a clean and organized Spring Boot project structure. Keep screenshots and documentation in appropriate folders.

---

## 🎯 Objective
By completing this experiment, you will learn how to:
- Implement **authentication and authorization** in Spring Boot
- Restrict API access using **roles**
- Configure **Spring Security** for secured endpoints
- Test protected APIs using **Postman**
- Understand the difference between **401 Unauthorized** and **403 Forbidden**

---

## 🧩 Project Requirements

### **Backend Functionality**
Your application should support the following features:

#### 1. Authentication
- Authenticate users with username and password
- Store users with roles such as `ROLE_USER` and `ROLE_ADMIN`
- Use Spring Security for login/session handling or token-based access if implemented

#### 2. Authorization
- Create endpoints accessible by specific roles only
- Example:
  - `/api/public/**` → accessible to everyone
  - `/api/user/**` → accessible to `USER` and `ADMIN`
  - `/api/admin/**` → accessible to `ADMIN` only

#### 3. Access Control Rules
- If no authentication is provided, return **401 Unauthorized**
- If authentication is valid but the role is insufficient, return **403 Forbidden**

#### 4. Database / User Storage
You may use:
- H2 database
- MySQL
- PostgreSQL
- In-memory user configuration for demo purpose

However, using a database is preferred for better demonstration.

---

## 📁 Recommended Folder Structure
Use a Spring Boot structure similar to the following:

```text
src/
├── main/
│   ├── java/
│   │   └── com/example/experiment7/
│   │       ├── config/
│   │       │   └── SecurityConfig.java
│   │       ├── controller/
│   │       │   ├── AuthController.java
│   │       │   ├── UserController.java
│   │       │   └── AdminController.java
│   │       ├── dto/
│   │       │   ├── LoginRequest.java
│   │       │   └── LoginResponse.java
│   │       ├── entity/
│   │       │   ├── User.java
│   │       │   └── Role.java
│   │       ├── repository/
│   │       │   └── UserRepository.java
│   │       ├── service/
│   │       │   ├── CustomUserDetailsService.java
│   │       │   └── AuthService.java
│   │       └── Experiment7Application.java
│   └── resources/
│       ├── application.properties
│       └── data.sql
├── test/
└── pom.xml
```

You may also create a `screenshots/` folder in your repository:

```text
screenshots/
├── 01-login-success.png
├── 02-user-endpoint-success.png
├── 03-admin-endpoint-success.png
└── 04-access-denied.png
```

---

## 📚 Library Installation & Setup

### 1. Create Spring Boot Project
Create a Spring Boot project using **Maven** from Spring Initializr.

### 2. Add Required Dependencies
Add these dependencies:
- Spring Web
- Spring Security
- Spring Data JPA
- H2 / MySQL Driver
- Lombok (optional)

### 3. Example `pom.xml` Dependencies

```xml
<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>

    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-security</artifactId>
    </dependency>

    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>

    <dependency>
        <groupId>com.h2database</groupId>
        <artifactId>h2</artifactId>
        <scope>runtime</scope>
    </dependency>

    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <optional>true</optional>
    </dependency>

    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
</dependencies>
```

---

## 🔐 Role-Based Authorization Design

### Example Roles
- `ROLE_USER`
- `ROLE_ADMIN`

### Example Access Rules
| Endpoint | Access Role |
|----------|-------------|
| `/api/public/hello` | Public |
| `/api/user/profile` | USER, ADMIN |
| `/api/admin/dashboard` | ADMIN only |

### Example Security Rules in Spring Boot
You may configure authorization using `SecurityFilterChain`:

```java
@Bean
public SecurityFilterChain securityFilterChain(HttpSecurity http) throws Exception {
    http
        .csrf(csrf -> csrf.disable())
        .authorizeHttpRequests(auth -> auth
            .requestMatchers("/api/public/**").permitAll()
            .requestMatchers("/api/user/**").hasAnyRole("USER", "ADMIN")
            .requestMatchers("/api/admin/**").hasRole("ADMIN")
            .anyRequest().authenticated()
        )
        .httpBasic(Customizer.withDefaults());

    return http.build();
}
```

---

## 👤 Example Users for Testing
You can create demo users in the database or in-memory.

### Example
| Username | Password | Role |
|----------|----------|------|
| `user1`  | `user123` | USER |
| `admin1` | `admin123` | ADMIN |

> If passwords are encoded using BCrypt, store them in encoded format.

---

## 🌐 Suggested API Endpoints

### 1. Public Endpoint
**GET** `/api/public/hello`

Response:
```json
{
  "message": "This is a public endpoint"
}
```

### 2. User Endpoint
**GET** `/api/user/profile`

Accessible by:
- USER
- ADMIN

Response:
```json
{
  "message": "Welcome, authenticated user"
}
```

### 3. Admin Endpoint
**GET** `/api/admin/dashboard`

Accessible by:
- ADMIN only

Response:
```json
{
  "message": "Welcome, admin"
}
```

---

## 🧪 Postman Testing Guide
Use Postman to verify authentication and authorization.

### Case 1: Access Public Endpoint
- **Method**: `GET`
- **URL**: `http://localhost:8080/api/public/hello`
- Expected result: Success without login

### Case 2: Login / Authenticate
Depending on your implementation, use either:
- Spring Security default login/session
- HTTP Basic Auth in Postman
- Custom login endpoint

If using HTTP Basic in Postman:
- Go to **Authorization** tab
- Select **Basic Auth**
- Enter username and password

### Case 3: USER Accessing User Endpoint
- **Method**: `GET`
- **URL**: `http://localhost:8080/api/user/profile`
- **Auth**: Login as `user1`
- Expected result: `200 OK`

### Case 4: USER Accessing Admin Endpoint
- **Method**: `GET`
- **URL**: `http://localhost:8080/api/admin/dashboard`
- **Auth**: Login as `user1`
- Expected result: `403 Forbidden`

### Case 5: ADMIN Accessing Admin Endpoint
- **Method**: `GET`
- **URL**: `http://localhost:8080/api/admin/dashboard`
- **Auth**: Login as `admin1`
- Expected result: `200 OK`

### Case 6: No Authentication
- Try accessing `/api/user/profile` without login
- Expected result: `401 Unauthorized`

---

## 📸 Screenshot Checklist
Include screenshots for the following:

- [ ] Project folder structure
- [ ] Database users/roles table or in-memory user config
- [ ] Public endpoint response
- [ ] USER login/authentication
- [ ] USER accessing `/api/user/profile`
- [ ] USER getting `403 Forbidden` on `/api/admin/dashboard`
- [ ] ADMIN accessing `/api/admin/dashboard`

At minimum, include the four required screenshots mentioned above.

---

## 🛠️ Implementation Steps

### Step 1: Create Entity Classes
Create `User` and optionally `Role` entities.

Example fields for `User`:
- `id`
- `username`
- `password`
- `role`

### Step 2: Create Repository
Create `UserRepository` to fetch user details by username.

### Step 3: Create Custom UserDetailsService
Implement `UserDetailsService` to load user information from database.

### Step 4: Configure Password Encoder
Use BCrypt password encoder.

```java
@Bean
public PasswordEncoder passwordEncoder() {
    return new BCryptPasswordEncoder();
}
```

### Step 5: Configure Security
Set URL access rules using roles.

### Step 6: Create Controllers
Create:
- `AuthController` (optional if custom login is used)
- `UserController`
- `AdminController`
- `PublicController`

### Step 7: Test in Postman
Verify all success and failure cases.



## 🧪 Experiment 6 Guides

## 🚨 Important Instructions
- **Deadline**: **17 March 2026**

### 📝 Google Form

Please submit your project details using the following link:

<div align="center">
  <a href="https://forms.gle/AVsDjUZPe5VwxfjG7">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

---

## 📌 Assessment Topic
Implement **JWT Authentication** in your backend. The system should support user login, session management, and generate a JWT token for authenticated sessions.

You must **demonstrate** the functionality of the JWT token by showcasing how authentication works with **Postman**.

### **Submission Requirements:**
1. **Backend Implementation**:
   - Implement JWT authentication in the backend using springboot framework.
   - **Mandatory**: Screenshots showing the following:
     - Successful **login request** and receiving the JWT token.
     - **Access protected routes** by providing the JWT token.
     - **Logout process** (optional but recommended to show token invalidation).

   **At least 3 screenshots** are required. You will be marked based on these screenshots and the **README** explaining the implementation.

2. **Project Structure**:
   - Follow the **recommended folder structure** when pushing to GitHub.
   - Screenshots and relevant documents should be stored in an appropriate folder.

   Example of folder structure:
   ```
   src/
   ├── controllers/
   │   └── authController.js
   ├── middleware/
   │   └── authMiddleware.js
   ├── routes/
   │   └── authRoutes.js
   ├── models/
   │   └── userModel.js
   ├── server.js
   └── .env
   ```

3. **Postman Screenshots**:
   - Screenshots should show:
     - **Login request** with username and password.
     - **JWT Token received** upon successful authentication.
     - **Access to protected route** using the token in the authorization header.


## 🎯 Objective
- Implement **JWT Authentication** in a backend application.
- Manage user sessions using JWT.
- Understand how to use **Postman** for testing authentication processes.
- Learn about **session management** and **token validation** in web applications.

---

## 🧩 Project Requirements

### **Backend Functionality**:
- **Login**: Authenticate users using username and password, then generate and send a JWT token.
- **Protected Routes**: Secure certain routes using the JWT token.
- **Session Handling**: Ensure the JWT token is valid and handle user logout (token invalidation).

### **Postman Testing**:
- Use **Postman** to demonstrate the following steps:
  1. Send a login request with user credentials and get a JWT token.
  2. Use the token to access a protected route.
  3. Optional: Show token invalidation or logout process.

---

## 📁 Recommended Folder Structure
Ensure your backend is structured appropriately for easy maintenance and deployment. Below is a suggested structure:

```
src/
├── controllers/
│   ├── authController.js  # Handles login, logout, token generation
├── middleware/
│   └── authMiddleware.js  # Verifies JWT tokens for protected routes
├── models/
│   └── userModel.js  # Defines user schema for authentication
├── routes/
│   └── authRoutes.js  # Routes for login and protected endpoints
├── server.js  # Main server file to configure routes and start server
└── .env  # Environment variables (DB, JWT_SECRET, etc.)
``` id="ch2pqq"

---

## 📚 Library Installation & Setup

1. **Backend Setup**:
   - Create a new Spring Boot project with **Maven** using [Spring Initializr](https://start.spring.io/).
   - Add dependencies: **Spring Web**, **Spring Security**, **Spring Data JPA**, **JWT**, and your database (e.g., H2).
   
2. **Add Maven Dependencies**:
   In `pom.xml`, add:
   ```xml
   <dependency>
       <groupId>io.jsonwebtoken</groupId>
       <artifactId>jjwt</artifactId>
       <version>0.11.2</version>
   </dependency>
   <dependency>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-starter-security</artifactId>
   </dependency>

3. **API Routes**:
   - **Login Route**:
     - Send a POST request with the user's username and password.
     - On successful login, return the JWT token.
   - **Protected Route**:
     - Secure routes using JWT authentication middleware.
     - The JWT token should be included in the Authorization header for protected routes.

---

## **Example of Postman Request**
### 1. **Login Request (POST /login)**
- **URL**: `http://localhost:5000/login`
- **Body** (raw, JSON):
  ```json
  {
    "username": "user123",
    "password": "password123"
  }
  ```
- **Response**:
  ```json
  {
    "token": "your_jwt_token_here"
  }
  ```

### 2. **Access Protected Route (GET /protected)**
- **URL**: `http://localhost:5000/protected`
- **Headers**:
  ```
  Authorization: Bearer your_jwt_token_here
  ```



## 🧪 Experiment 1 Guides

> [!IMPORTANT]
> **Deadline:** 22 January 2026

---

## 📤 Submission

### 📝 Google Form

Please submit your project details using the following link:

<div align="center">
  <a href="https://forms.gle/3Cac7xx1GJdnwHNz6">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

---

### 🛠️ Installation and Setup

#### Step 1: Install Git
Download and install <a href="https://git-scm.com/downloads">Git</a> for version control

**Why Git?**
- Track changes in your code
- Collaborate with others
- Push your projects to GitHub

#### Step 2: Install VSCode
Download and install <a href="https://code.visualstudio.com/">Visual Studio Code</a>

#### Step 3: Install Live Server Extension
Install the **Live Server** extension in VSCode (an improved version of Live Server)

1. Open VSCode
2. Go to Extensions (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for "Five Server"
4. Click Install


### 🛠️ Installation and Setup

#### Step 1: Install Node.js

Download and install **Node.js** from the <a href="https://nodejs.org/en/download">official website</a>

> [!IMPORTANT] 
> Installing Node.js also installs **npm** (Node Package Manager)

**What you get:**
- **Node.js**: JavaScript runtime built on Chrome's V8 engine, used to run JavaScript outside the browser
- **npm**: Node Package Manager; manages JavaScript libraries and tools

---

#### Step 2: Install pnpm Globally

Open **PowerShell** or **Command Prompt** and run:

```bash
npm i -g pnpm
```

**Command breakdown:**
- `npm` — Node Package Manager CLI
- `i` — Short for `install`; tells npm to install a package
- `-g` — Short for `--global`; installs the package globally so it can be used from any folder
- `pnpm` — **Performant NPM**, an alternative fast package manager that uses a content-addressable store to save disk space

---

#### Step 3: Fix Execution Policy (Windows Only)

> [!WARNING]
> If you encounter an execution policy error on Windows, follow these steps:

Open **PowerShell as current user** and run:

```powershell
Set-ExecutionPolicy Unrestricted -Scope CurrentUser
```

**Command breakdown:**
- `Set-ExecutionPolicy` — PowerShell command that changes the script execution policy
- `Unrestricted` — Allows all scripts to run, but shows a warning before running scripts from the internet
- `-Scope CurrentUser` — Applies this policy only to the current user, not system-wide


## 🧪 Experiment 2 Guides  

> ❗
> **Deadline:** 4 February 2026  
> **Viva:** Will be conducted in the upcoming classes from today onwards 

### 📝 Google Form

Please submit your project details using the following link:

<div align="center">
  <a href="https://forms.gle/wiF7sEw1qocrrEUh9">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

---

### 🚨 Important Instructions

1. **Please Check the Folder Structure Before Pushing to GitHub**  
   Ensure that your project follows the recommended folder structure as provided in the guides. Incorrect folder structure may lead to issues when reviewing or deploying your project.

2. **Format Deployment Link as Provided in Experiment 1 Guide**  
   When deploying your project, make sure your deployment link follows the naming convention as shown in the **Experiment 1 Guide**. For example:  
   `{uid}-{experiment-part}-{name}.vercel.app`  
   Ensure that the link is formatted correctly to avoid submission errors.
--

### 📌 Assessment Topic  

Design a **modern, sleek, and visually appealing web page** using UI component libraries.

You must use **any one or a combination** of the following:
- **Bootstrap**
- **Material UI (MUI)**

---

### 🎯 Objective  

- Learn component-based UI design  
- Understand folder structuring in React  
- Build a meaningful, real-world webpage  
- Apply modern UI/UX principles  

---

### 🧩 Project Requirements  

#### ✅ UI & Design  
- Clean and modern layout  
- Proper spacing, typography, and colors  
- Responsive design (mobile + desktop)  

#### ✅ Functionality  
- Page should be meaningful, not random  

**Example ideas:**
- Portfolio website  
- Product landing page  
- College event page  
- Dashboard UI  
- Startup homepage  

---

### 📁 Recommended Folder Structure  

```bash
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── HeroSection.jsx
│   └── CardComponent.jsx
│
├── pages/
│   ├── Home.jsx
│
├── App.jsx
├── main.jsx
└── index.css
```
### 📚 Library Installation & Setup

#### 1. **React Setup**
- Run `npm create vite@latest` to create a new React project choose framework.
- Navigate into the project folder using `cd your-project-name`.
- Start the React app by running `npm start`.

#### 2. **Bootstrap Setup**
- Run `npm install react-bootstrap bootstrap` to install Bootstrap into your project.
- In your **main.jsx**  file, import the Bootstrap CSS by adding:
  `import 'bootstrap/dist/css/bootstrap.min.css';`  
  This will apply Bootstrap's styles globally across your project.

#### 3. **Material UI (MUI) Setup**
- Run `npm install @mui/material @emotion/react @emotion/styled` to install Material UI.
- Now, you can start using Material UI components like buttons, cards, etc., in your project by importing them into your React components.

## 🧪 Experiment 3 Guides  

> ⚠️ **Deadline:** 11 February 2026  
> **Viva:** Will be conducted in the upcoming classes and will be conveyed prior to one class 

---
### 📝 Google Form

Please submit your project details using the following link:

<div align="center">
  <a href="https://forms.gle/aUdYcz85aJ6YkBVVA">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

### 📌 Assessment Topic  

This is an **extension of Experiment 2**. Create **one more webpage** related to your previously chosen design, topic, or theme and build upon it.

You need to:
- Choose a second page that fits with your first page.
- **Use React Router** to navigate between the pages.

---

### 🎯 Objective  

- Understand the use of **React Router**  
- Create **multiple pages** in a React application  
- Extend the webpage to include more content and structure  

---

### 🧩 Project Requirements  

#### ✅ UI & Design  
- Maintain **consistent design** with the first page  
- Ensure **clean UI/UX** across pages  
- Use **React Router** for page navigation  

#### ✅ Functionality  
- Create a second page that is related to your initial project  
- Navigate between the pages using **React Router**  
- The second page should provide more **information or functionality** based on your theme  

**Example ideas:**
- **Portfolio website** → Add a **Projects** page  
- **Product landing page** → Add a **Contact** or **Pricing** page  
- **College event page** → Add an **RSVP** or **Event Details** page  
- **Dashboard UI** → Add an **Analytics** or **Settings** page  

---

### 📁 Recommended Folder Structure  

```bash
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── HeroSection.jsx
│   └── CardComponent.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── Projects.jsx     # New page for Experiment 3
│   └── Contact.jsx      # New page for Experiment 3
```

## 🧪 Experiment 4 Guides  

> ⚠️  
> **Deadline:** 20 February 2026  


### 📝 Google Form

Please submit your project details using the following link:

<div align="center">
  <a href="https://forms.gle/CncLobN4a4Ny7k228">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

---

### 🚨 Important Instructions

1. **This is an Extension of Experiment 3**  
   You must update your Experiment 3 project (multi-page + React Router) and add the required Experiment 4 features.

2. **Please Check the Folder Structure Before Pushing to GitHub**  
   Ensure your project follows the recommended folder structure. Incorrect structure may lead to issues in review or deployment.

3. **Format Deployment Link as Provided in Experiment 1 Guide**  
   `{uid}-{experiment-part}-{name}.vercel.app`  
   Example: `24bda70021-4-navkaran-singh.vercel.app`

4. **Exclude `node_modules`**  
   Do not include `node_modules` in the zip file.

5. **Update README.md**  
   Mention Experiment 4 changes clearly and add 2–3 screenshots in a `/screenshots` folder.

---

### 📌 Assessment Topic  

Enhance your existing **Experiment 3** React project by implementing:

- **useContext** (global state management)
- **useReducer** (structured state updates)
- **useMemo** (performance optimization)
- Add **one new page** connected using **React Router**

---

### 🎯 Objective  

- Understand global state using **Context API**  
- Manage complex state transitions using **useReducer**  
- Optimize derived calculations using **useMemo**  
- Extend a multi-page React project while maintaining consistent UI/UX  

---

### 🧩 Project Requirements  

#### ✅ UI & Design  
- Maintain consistent design from Experiment 3  
- Clean and modern layout  
- Proper spacing, typography, and colors  
- Responsive design (mobile + desktop)

#### ✅ Functionality (Must Include All)
1. **React Router (Already from Exp 3, must remain)**
   - At least **3 total pages** after Experiment 4 update  
   - Example: `Home`, `Projects`, `Analytics`

2. **useContext**
   - Create a global context provider and wrap the app
   - Use context in **at least 2 components**
   - Context must store meaningful global state such as:
     - theme (light/dark), OR
     - user profile (mock), OR
     - favorites/cart/bookmarks

3. **useReducer**
   - Implement a reducer for meaningful state management
   - Must include **minimum 3 actions**
   - Example features:
     - cart (add/remove/update qty)
     - favorites (add/remove/clear)
     - tasks (add/toggle/delete)

4. **useMemo**
   - Use `useMemo` to optimize derived data computation
   - Example:
     - total price calculation
     - filtered + searched list
     - analytics summary counts

5. **New Page (Experiment 4 Page)**
   - Add one page that demonstrates reducer + memo + context usage
   - Example pages:
     - Portfolio → `Skills` / `Experience`
     - Product site → `Cart` / `Pricing`
     - Event site → `RSVP` / `Schedule`
     - Dashboard → `Analytics` / `Reports`

---

### 📁 Recommended Folder Structure  

```bash
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── HeroSection.jsx
│   ├── CardComponent.jsx
│   ├── ThemeToggle.jsx
│   └── FilterBar.jsx
│
├── context/
│   └── AppContext.jsx
│
├── reducer/
│   └── appReducer.js
│
├── pages/
│   ├── Home.jsx
│   ├── Projects.jsx / Contact.jsx   # From Experiment 3
│   └── Analytics.jsx / Cart.jsx / RSVP.jsx  # New page for Experiment 4
│
├── App.jsx
├── main.jsx
└── index.css
```

# 🧪 Experiment 5 Guides

> ⚠️ **Deadline:** **07 March 2026**
### **This is an Extension of Experiment 4**  

---

## 📝 Google Form

Submit your project details using this link:

<div align="center">
  <a href="https://forms.gle/PZGGWEdcG4427KeV8">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

---

## 🚨 Important Instructions

1. **This is an Extension of Experiment 4**  
   Update your **Experiment 4** project and add the required **Experiment 5** features.

2. **Check Folder Structure Before Pushing to GitHub**  
   Follow the recommended structure below. Incorrect structure may cause review/deployment issues.

3. **Deployment Link Format (same as Experiment 1)**  
   `{uid}-{experiment-part}-{name}.vercel.app`  
   **Example:** `24bda70021-5-navkaran-singh.vercel.app`

4. **Exclude `node_modules`**  
   Do **NOT** include `node_modules` in the zip.

5. **Update `README.md`**  
   Clearly mention Experiment 5 changes and add **2–3 screenshots** inside a `/screenshots` folder.

---

## 📌 Assessment Topic

Enhance your existing **Experiment 4** React project by implementing:

- **Redux Toolkit** (state management) ✅ *(replaces useReducer)*
- **useContext** (global state — theme/user/etc.)
- **useMemo** (performance optimization)
- Add **one new page** connected using **React Router**

---

## 🎯 Objective

- Learn structured, scalable state management using **Redux Toolkit**
- Use **Context API** for app-wide concerns (theme/auth/profile)
- Optimize derived calculations using **useMemo**
- Extend a multi-page React app while maintaining consistent UI/UX

---

## 🧩 Project Requirements

### ✅ UI & Design
- Maintain consistent design from Experiment 4
- Clean and modern layout
- Proper spacing, typography, and colors
- Responsive design (mobile + desktop)

---

### ✅ Functionality (Must Include All)

#### 1) **React Router (Must remain from Exp 3/4)**
- Minimum **3 total pages**
- Add **1 new page** for Experiment 5 (example: `Reports`, `Cart`, `Schedule`, `Pricing`, etc.)
- Routes must work properly with Navbar links

**Example Pages**
- `Home`
- `Projects` / `Contact` (from Exp 3)
- `Analytics` (from Exp 4)
- **NEW (Exp 5):** `Reports` / `Cart` / `Schedule` / `Pricing`

> You can keep previous pages and just **add one new page** for Experiment 5.

---

#### 2) **useContext**
- Create a global context provider and wrap the app
- Use context in **at least 2 components**
- Context must store meaningful global state such as:
  - theme (light/dark), OR
  - user profile (mock), OR
  - language toggle / layout preference

---

#### 3) **Redux Toolkit (Replaces useReducer)**
Implement Redux Toolkit for meaningful state management.

✅ **Requirements**
- Configure a Redux store using `configureStore`
- Create at least **1 slice** using `createSlice`
- Slice must include **minimum 3 actions** (reducers)

✅ **Example Features (pick one)**
- **cart:** `addItem`, `removeItem`, `updateQty`  
- **favorites:** `addFavorite`, `removeFavorite`, `clearFavorites`  
- **tasks:** `addTask`, `toggleTask`, `deleteTask`

✅ **Redux must be used in UI**
- Dispatch actions using `useDispatch`
- Read state using `useSelector`
- Use in **at least 2 components** (e.g., page + card component)

---

#### 4) **useMemo**
Use `useMemo` to optimize derived computations based on Redux/Context state.

✅ **Examples**
- total cart price calculation
- filtered + searched list
- analytics summary counts (completed, pending, totals)

> Your `useMemo` should depend on state and recompute only when dependencies change.

---

#### 5) **New Page (Experiment 5 Page)**
Add one page that demonstrates:
- Redux Toolkit state usage (selector + dispatch)
- `useMemo` for derived data
- Context usage (theme/user/etc.)

**Examples**
- Portfolio → `Pricing` / `Experience`
- Product site → `Cart` / `Checkout`
- Event site → `Schedule` / `RSVP`
- Dashboard → `Reports` / `Insights`

---

## 📁 Recommended Folder Structure

```bash
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── ThemeToggle.jsx
│   ├── CardComponent.jsx
│   └── FilterBar.jsx
│
├── context/
│   └── AppContext.jsx
│
├── redux/
│   ├── store.js
│   └── slices/
│       └── appSlice.js   # (or cartSlice.js / taskSlice.js etc.)
│
├── pages/
│   ├── Home.jsx
│   ├── Projects.jsx / Contact.jsx     # From Experiment 3
│   ├── Analytics.jsx / Cart.jsx       # From Experiment 4
│   └── Reports.jsx / Pricing.jsx      # ✅ New page for Experiment 5
│
├── App.jsx
├── main.jsx
└── index.css
```

---

## ✅ Setup Checklist (Submission Ready)

- [ ] App runs without errors (`npm install` → `npm run dev`)
- [ ] React Router works with at least **3 pages**
- [ ] **Context Provider** wraps the app and is used in **2+ components**
- [ ] **Redux Toolkit** store + slice created with **3+ actions**
- [ ] Redux state is used in **2+ components**
- [ ] `useMemo` used for derived data optimization
- [ ] Added **1 new page** for Experiment 5 and linked via Router
- [ ] README updated + `/screenshots` folder added (2–3 images)
- [ ] Deployed on Vercel with proper naming format
- [ ] `node_modules` excluded from zip

---

## 📤 What to Submit

1. **GitHub Repository Link**
2. **Vercel Deployment Link** (formatted correctly)
3. **Google Form Submission** (above)

---

## 🧾 README Update Template (What to write in your repo)

Add a short section like:

- **Experiment 5 Updates**
  - Implemented Redux Toolkit (`store`, `slice`, `actions`)
  - Added new page: `__________`
  - Added `useMemo` for `__________`
  - Implemented Context for `__________`
  - Added screenshots in `/screenshots`

---

### ✅ Example Screenshot Folder

```
screenshots/
├── home.png
├── new-page.png
└── redux-feature.png
```

---
## 🧪 MST Experiment Guides  

> ⚠️  
> **Deadline:** 10 March 2026  


### 📝 Google Form

Please submit your project details using the following link:

<div align="center">
  <a href="https://forms.gle/6BeeM7dkTrgJuHNd9">
    <img src="https://img.shields.io/badge/Submit%20to%20Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Submit to Google Form" />
  </a>
</div>

