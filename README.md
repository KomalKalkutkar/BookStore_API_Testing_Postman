# 📘 BookStore API Testing – Postman Project

This project demonstrates real-world API testing using **Postman** on [ToolsQA BookStore API](https://bookstore.toolsqa.com/swagger/). It includes user registration, token-based login, book assignment, deletion, and data-driven testing with CSV.

---

## ✅ Tools & Features

- Postman Collections & Environments
- JWT Authentication (Bearer Token)
- Request Chaining using Variables
- CRUD Operations on User & Book modules
- Dynamic Assertions using pm.expect()
- Data-Driven Testing with CSV (Collection Runner)

---


## 📁 Folder Structure
```
BookStore_Postman_Project/
├── Postman_Collections/
│   └── BookStore_Collection.json
├── Postman_Environments/
│   └── BookStore_Environment.json
├── TestData/
│   └── BookStoreUsers.csv
├── Screenshots/
│   
├── README.md
```


---

## ▶️ How to Run

1. Import `BookStore_Collection.json` into Postman  
2. Import `BookStore_Environment.json`  
3. Select environment → Run requests step-by-step  
4. To run data-driven tests:  
   - Open Collection Runner  
   - Select `BookStoreUsers.csv`  
   - Choose `Create User` request  
   - Run and observe results

---

## ✅ Covered APIs

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /Account/v1/User | Create new user  
| POST   | /Account/v1/GenerateToken | Get JWT Token  
| POST   | /Account/v1/Login | Login User  
| GET    | /BookStore/v1/Books | Get all books  
| POST   | /BookStore/v1/Books | Assign book to user  
| DELETE | /BookStore/v1/Book | Delete assigned book  
| DELETE | /Account/v1/User/{UUID} | Delete user  

---

