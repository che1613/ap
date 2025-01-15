# FastAPI File Upload API

This is a simple FastAPI application that allows users to:
1. Upload image files.
2. Check the status of uploaded files.
3. Retrieve uploaded files by their unique ID.

---

## Features

- Uploads and saves image files.
- Validates that only image files can be uploaded.
- Provides endpoints to check file status and retrieve files.
- Stores files in the `uploads/` directory.

---

## Endpoints

### 1. Upload File
**POST** `/upload/`

- **Request Body:** 
  - File: An image file to upload.
  
- **Response Example:**
  ```json
  {
    "file_id": "123e4567-e89b-12d3-a456-426614174000",
    "filename": "example.jpg"
  }
