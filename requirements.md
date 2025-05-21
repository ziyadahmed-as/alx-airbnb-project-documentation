# Airbnb Clone - Backend Requirements Word Document

This template covers the business and technical aspects of working in the back end of the Airbnb Clone Project.  

---  

## 1. User Authentication  

### 🔹 Description:  

Manages user sign-up, sign-in, and access control at application level including session management.  

### 🔸 Functional Requirements:  

- Users can sign up as guests or hosts.  

- Users can sign-in with email and password or via OAuth providers such as Google or Facebook.  

- The system generates JSON Web Tokens (JWT) for authenticated sessions.  

- Passwords will be hashed and salted (using bcrypt for example).  

### 🔸 API Endpoints:  

| Method | Endpoint        | Description                 |  
|:------ |:------------------|:----------------------- |  
| POST   | `/api/register` | Creates new user         |  
| POST   | `/api/login`    | Login for registered user |  
| GET    | `/api/profile`  | Returns profile of authenticated user |  

### 🔸 Input/Output Example  

**POST /api/login**  

```json  

Request:  

{  

  "email": "user@gmail.com",  

  "password": "userPass123"  

}  

Response:  

{  
  "token": "<JWT_TOKEN>",  
  "user": {  
    "id": 1,  
    "role": "host",  
    "email": "user@gmail.com"  
  }  
}  
```

