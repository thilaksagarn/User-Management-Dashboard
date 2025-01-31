# 🏢 User Management Dashboard  

## 📌 Overview  
The **User Management Dashboard** is a simple web application that allows users to **view, add, edit, and delete** user details by interacting with the **JSONPlaceholder API**.

---

Our site is live at [ usermanagementdashboardbythilaksagarn.netlify.app](https://usermanagementdashboardbythilaksagarn.netlify.app/)
## 📸 Screenshots
![image](https://github.com/user-attachments/assets/2a7be88a-240e-40e8-a728-db6d5dbee860)


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
5. Open http://localhost:3000/ in a browser to run the application:

 
## 🔗 API Endpoints Used  

| Action       | Method | Endpoint |
|-------------|--------|------------------------------------------|
| **Fetch Users** | GET    | `https://jsonplaceholder.typicode.com/users` |
| **Add User**   | POST   | `https://jsonplaceholder.typicode.com/users` |
| **Edit User**  | PUT    | `https://jsonplaceholder.typicode.com/users/{id}` |
| **Delete User**| DELETE | `https://jsonplaceholder.typicode.com/users/{id}` |

---

## 📂 Folder Structure 
 ![Screenshot 2025-01-31 112903](https://github.com/user-attachments/assets/86624df6-f32b-496f-b42a-c8d458e820d0)


### ⚠️ Challenges Faced
  1. Mock API Limitations: JSONPlaceholder does not persist changes.
  2. State Management: Handling form state for user modifications.
  3. Error Handling: Ensuring smooth user experience.

### 🎯 Future Improvements
  1. Implement a real backend (Node.js + Express + MongoDB).
  2. Add authentication (Login & Role-based access control).
  3. Enhance user experience with search & filtering.
