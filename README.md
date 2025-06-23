# 🚀 Prodigy-BD-01: Basic REST API with CRUD Operations

## 📄 Task Objective

Build a RESTful API with CRUD operations (Create, Read, Update, Delete) on a users resource.

---

## 📝 Task Details

- Create endpoints to handle CRUD operations.
- Each user should have:
  - id (UUID)
  - name
  - email
  - age
- Use an *in-memory data structure* (like a list or object) for storage.
- Validate inputs (e.g., check if email is valid).
- Implement proper HTTP status codes:
  - 201 – Created
  - 200 – Success
  - 400 – Bad Request
  - 404 – Not Found

---

## 💻 Tech Stack

- Language: Node.js with Express (or Python Flask if you prefer)
- Tool: Postman for API testing
- Storage: In-memory (No DB)

---

## 🚀 How to Run (Node.js Example)

```bash
# Clone the repository
git clone https://github.com/your-username/PRODIGY_BD_01.git

# Go to task folder
cd PRODIGY_BD_01/Task-01

# Install dependencies
npm install

# Start the server
node index.js
