# Git workflow demo

Practice the workflow used in the real assignment. Nothing here is graded.

1. **Fork** this repository on the hosting site (button at the top right).
2. **Clone your fork** (use your fork's URL, not this one's):
   ```
   git clone <url-of-your-fork>
   cd <repo-name>
   ```
3. **Check out your branch**, named after your student ID:
   ```
   git checkout <your-student-id>
   ```
4. **Edit** `student_number.txt`: write your student number after the prompt.
5. **Commit** with a meaningful message:
   ```
   git add student_number.txt
   git commit -m "Add my student number"
   ```
6. **Push** to your fork:
   ```
   git push origin <your-student-id>
   ```
7. **Open a pull request** from your fork's `<your-student-id>` branch to the
   `<your-student-id>` branch of this repository (not `main`).

Only touch your own branch and only `student_number.txt`.
