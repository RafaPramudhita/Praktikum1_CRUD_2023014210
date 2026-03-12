## 🌐 Tampilan Web Interface

![Web Interface]<img width="1920" height="1080" alt="Screenshot 2026-03-04 110804" src="https://github.com/user-attachments/assets/9c8f4a2e-32c7-4eb1-abdc-44aea59bc6d0" />


### 1️⃣ Create User

**Method:** `POST`  
**Endpoint:** `/api/users`

**Request Body:**
```json
{
  "name" : "rafa pramudhita",
  "age" : 20
}

```
Response Body (success):
```json
{
    "data": {
        "age": 20,
        "id": "cd64542a-6b3e-4bab-8a50-c52e3ac1f5aa",
        "name": "rafa pramudhita"
    },
    "status": "success"
}
```
Response Body (failed):
```json
{
    "timestamp": "2026-03-04T04:43:25.248Z",
    "status": 500,
    "error": "Internal Server Error",
    "path": "/api/users"
}
```
### 2️⃣ Update User

**Method:** `PUT`  
**Endpoint:** `/api/users/{id}`

**Request Body:**
```json
{
  "name" : "rafa pramudhita",
  "age" : 23
}
```
Response Body (success):
```json
{
    "data": {
        "age": 23,
        "id": "cd64542a-6b3e-4bab-8a50-c52e3ac1f5aa",
        "name": "rafa pramudhita"
    },
    "status": "success"
}
```

### 3️⃣ Get User

**Method:** `GET`

**Endpoint:** `/api/users`

**Response Body (success):**
```json
{
    "data": [
        {
            "Id": "be26ef62-4fd8-4040-90fc-b77e19621847",
            "age": 23,
            "name": "asep kurniawan"
        },
        {
            "Id": "cd64542a-6b3e-4bab-8a50-c52e3ac1f5aa",
            "age": 23,
            "name": "Rafa Pramudhita"
        }
    ],
    "status": "success"
}
```
### 4️⃣ Delete User

**Method:** `DELETE`

**Endpoint:** `/api/users/{id}`

**Response Body (success):**
```json
{
    "status": "success delete user with id a0fdf9ad-7043-4103-ad5e-ac4bd89a6182"
}
```
DATABASE
<img width="1920" height="1080" alt="Screenshot 2026-03-12 220925" src="https://github.com/user-attachments/assets/1a1341d3-51c1-4050-8847-0adb0b5969b3" />
<img width="1920" height="1080" alt="Screenshot 2026-03-12 221039" src="https://github.com/user-attachments/assets/99a5c3f4-2927-4cf1-b872-7988a05fca21" />

