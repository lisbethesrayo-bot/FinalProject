## How to Run

1. Clone the repository:
   git clone https://github.com/lisbethesrayo-bot/FinalProject.git
2. Navigate to the project folder:
   cd studyflow-task-manager

3. Install dependencies:
   npm install

4. Start the server:
   npm start

5. Open your browser and go to:
   http://localhost:3000
   
   ## Project Structure
- server/ → Backend (Node.js + Express API)
- public/ → Frontend (HTML, CSS, JavaScript)
- data/ → JSON file for storing tasks
- docs/ → Project documentation

## API Endpoints

- GET /api/tasks → Get all tasks
- POST /api/tasks → Add new task
- PUT /api/tasks/:id → Toggle task completion
- DELETE /api/tasks/:id → Delete a task

- ## Notes

This project uses a JSON file for data persistence instead of a database, making it simple and easy to run locally.
