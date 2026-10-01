# Git PR Conflict Lab

## Step 1: Fork the Repository

1. Open the GitHub repository.
2. Click **Fork**.
3. Select your GitHub account as the **Owner**.
4. Keep the repository name unchanged.
5. Uncheck **Copy the main branch only**.
6. Click **Create fork**.
   <img width="951" height="311" alt="image" src="https://github.com/user-attachments/assets/094f34c9-0f7f-42b4-8eef-51d179faf386" />


Your fork will contain all the branches, including:

```text
feature/Jira-01_student-A
feature/Jira-02_student-B
```
Create a Pull Request from `main` to `feature/Jira-01_student-A`.

When you try to merge the PR, a **merge conflict** will occur because the changes from `feature/Jira-02_student-B` have already been merged into `main` and both branches contain changes to the same code.
