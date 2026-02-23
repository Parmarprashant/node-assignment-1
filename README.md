# Student Management API

## Objective
The objective of this project is to practice building a RESTful API using Node.js and Express.js, focusing specifically on the `GET` method. It demonstrates how to manage and retrieve student data through various endpoints, including filtering by branch, finding toppers, and calculating averages.

## List of Implemented Routes

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/students` | Retrieves a list of all students. |
| `GET` | `/students/:id` | Retrieves details of a specific student by their `ID`. |
| `GET` | `/students/topper` | Returns the student with the highest CGPA. |
| `GET` | `/students/average` | Calculates and returns the average CGPA of all students. |
| `GET` | `/students/count` | Returns the total count of students in the records. |
| `GET` | `/students/branch/:branchname` | Returns a list of students belonging to a specific branch. |

## Sample API URLs

- **Get all students**: `http://localhost:3000/students`
- **Get student by ID**: `http://localhost:3000/students/1`
- **Get student with highest CGPA**: `http://localhost:3000/students/topper`
- **Get average CGPA**: `http://localhost:3000/students/average`
- **Get total student count**: `http://localhost:3000/students/count`
- **Get students in CSE branch**: `http://localhost:3000/students/branch/CSE`

## Steps to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd Assignment-1
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Server**:
   You can start the server using `nodemon` (recommended for development):
   ```bash
   npm test
   ```
   Or use standard `node`:
   ```bash
   node index.js
   ```

4. **Access the API**:
   The server will be running at `http://localhost:3000`.

## Deployed Link
[Click here to view the deployed application](https://your-deployment-link.netlify.app/) *(Replace with actual link if available)*
