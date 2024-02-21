## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Shreyashs98/Skill_lab_assignment_2.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm start
   ```

## API Endpoints

### Authentication

#### 1. Login

- **Method:** POST
- **URL:** `http://localhost:3000/api/auth/login`
- **Body (JSON):**
  ```json
  {
    "username": "YourUsername",
    "password": "YourPassword"
  }
  ```

#### 2. Register

- **Method:** POST
- **URL:** `http://localhost:3000/api/auth/register`
- **Body (JSON):**
  ```json
  {
    "username": "YourUsername",
    "password": "YourPassword"
  }
  ```

### Blogs

#### 3. Create New Blog

- **Method:** POST
- **URL:** `http://localhost:3000/api/blogs/create`
- **Body (JSON):**
  ```json
  {
    "title": "Blog Title",
    "content": "Blog Content",
    "category": "Blog Category"
  }
  ```

#### 4. Retrieve All Blogs

- **Method:** GET
- **URL:** `http://localhost:3000/api/blogs/all`

#### 5. Retrieve Blog by ID

- **Method:** GET
- **URL:** `http://localhost:3000/api/blogs/get/{blogId}`
  - Replace `{blogId}` with an actual ID.

#### 6. Search Blogs

- **Method:** GET
- **URL:** `http://localhost:3000/api/blogs/search/:query`
  - Replace `:query` with your search title.

#### 7. Update Blog by ID

- **Method:** PUT
- **URL:** `http://localhost:3000/api/blogs/update/{blogId}`
  - Replace `{blogId}` with an actual ID.
- **Body (JSON):**
  ```json
  {
    "title": "Updated Blog Title",
    "content": "Updated Blog Content",
    "category": "Updated Blog Category"
  }
  ```

#### 8. Delete Blog by ID

- **Method:** DELETE
- **URL:** `http://localhost:3000/api/blogs/delete/{blogId}`
  - Replace `{blogId}` with an actual ID.

### User

#### 9. Retrieve All Users

- **Method:** GET
- **URL:** `http://localhost:3000/api/auth/all-users`

#### 10. Retrieve User by ID

- **Method:** GET
- **URL:** `http://localhost:3000/api/auth/get-user/:userId`
  - Replace `{userId}` with an actual ID.

#### 11. Delete User by ID

- **Method:** DELETE
- **URL:** `http://localhost:3000/api/auth/delete-user/:userId`
  - Replace `{userId}` with an actual ID.
```

