# 🏢 User Management Dashboard  

## 📌 Overview  
The **User Management Dashboard** is a simple web application that allows users to **view, add, edit, and delete** user details by interacting with the **JSONPlaceholder API**.

---

## 🚀 Features  

✔️ **View Users** – Fetch and display users from the `/users` endpoint.  
✔️ **Add Users** – Submit new user details to the API.  
✔️ **Edit Users** – Modify user information and update it via the API.  
✔️ **Delete Users** – Remove users by sending a DELETE request.  
✔️ **Error Handling** – Displays messages in case of API failures.  

### 🎁 Bonus Features (Optional)  
➕ **Pagination** for large user lists.  
➕ **Client-side validation** for input forms.  
➕ **Responsive design** for all screen sizes.  

---

## 🏗️ Technologies Used  

| Technology | Purpose |
|------------|---------|
| **React.js** | Frontend framework for building UI components |
| **Axios** | Simplifies HTTP requests to the API |
| **JSONPlaceholder** | Mock backend API for testing |
| **CSS / Bootstrap / Tailwind** | Styling for a clean and responsive UI |

---

## 📦 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/thilaksagarn/User-Management-Dashboard.git
2. Navigate to the project directory:
    ```bash
    cd User-Management-Dashboard
3. Install dependencies:
   ```bash
   npm install
4.  Start the application:
    ```bash
    npm start
4. Open http://localhost:3000/ in a browser to run the application:


## 🔗 API Endpoints Used  

| Action       | Method | Endpoint |
|-------------|--------|------------------------------------------|
| **Fetch Users** | GET    | `https://jsonplaceholder.typicode.com/users` |
| **Add User**   | POST   | `https://jsonplaceholder.typicode.com/users` |
| **Edit User**  | PUT    | `https://jsonplaceholder.typicode.com/users/{id}` |
| **Delete User**| DELETE | `https://jsonplaceholder.typicode.com/users/{id}` |

---

## 📂 Folder Structure 
user-management-dashboard/
├── src/
│   ├── components/
│   │   ├── AddUser.js
│   │   ├── EditUser.js
│   │   ├── UserList.js
│   ├── App.js
│   ├── index.js
│   ├── App.css
|   ├── App.test.js
│   ├── index.css
|   ├── logo.svg
|   ├── reportWebVitals.js
|   ├── setupTests.js
├── package.json
├── README.md

### ⚠️ Challenges Faced
  1. Mock API Limitations: JSONPlaceholder does not persist changes.
  2. State Management: Handling form state for user modifications.
  3. Error Handling: Ensuring smooth user experience.

### 🎯 Future Improvements
🔹 Implement a real backend (Node.js + Express + MongoDB).
🔹 Add authentication (Login & Role-based access control).
🔹 Enhance user experience with search & filtering.
