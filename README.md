# Online Judge System (OJ-Project)

A full-featured Online Judge system built with **Django** that allows users to solve coding problems, run code with custom input, submit for evaluation against hidden test cases, and even receive AI-powered feedback on their solutions.

## 🔧 Tech Stack

- **Backend:** Django
- **Frontend:** HTML, CSS, Bootstrap
- **Code Execution:** Python & C/C++ using `subprocess` in Docker containers
- **AI Review:** Code feedback based on problem description
- **Containerization:** Docker


---

## 👥 User Types

1. **Normal User**
   - Register and log in
   - View all coding problems
   - Track progress: see how many problems are solved (e.g., "3/10 Solved")
   - Use the editor to:
     - `Run` code with custom input
     - `Submit` code for hidden test case validation
     - Get `AI Review` on solution quality
   - View submissions in **My Submissions**
   - View personal info in **My Profile**

2. **Problem Setter**
   - Normal User functionality
   - Add new coding problems
   - Add hidden test cases for problem evaluation
   - View all user submissions

3. **Admin**
   - Full control over the platform (extendable)

---

## 🚀 Features

- 🔐 **Authentication:** Role-based login system (normal user, problem setter, admin)
- 📚 **Problem List:** View all problems, solved status, and problem-specific details
- 👨‍💻 **Code Editor:** Supports C, C++, Python
- ⚙️ **Run Code:** Executes code with user-provided input
- ✅ **Submit Code:** Validates code with hidden test cases, returns verdict
- 🤖 **AI Review:** Provides code review based on problem description
- 📈 **Progress Tracking:** Shows solved tag and number of problems solved
- 👁️ **Submission History:** Users can view all their past submissions
- 🧪 **Docker Integration:** Isolates code execution for safety

---

## 🐳 Docker Usage

To run code securely in isolated environments, the platform uses Docker. Make sure Docker is installed and running.


