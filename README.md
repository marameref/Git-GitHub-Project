# Practical Software Engineering : Integration and Version Control with Git (Woolf University X GMC School of Technology)

## Git & GitHub Project (MSC Software Engineering)
---

````markdown
# 🧠 Learn Git: Hands-On Git Workflow Practice

---

## 📌 Project Description

This project is a hands-on checkpoint to reinforce your understanding of the basic Git workflow. It includes file creation, repository initialization, staging, committing, viewing logs, deleting files, and modifying global Git configurations. This is an essential exercise for beginners and intermediate developers looking to solidify their Git fundamentals.

> 💡 Bonus: You will also learn how to document your work, take screenshots of Git commands, and push them to your GitHub repository.

---

## 🚀 Git Practice Workflow: What You're Aiming For

Now that you've grasped the fundamentals of Git, it's time to reinforce your understanding by walking through the core Git workflow independently.

> 📸 **Note:** As part of this checkpoint, take screenshots for each step listed below and push them to your GitHub repository for documentation and review.

---

## 🧭 Instructions

Follow the steps below using your terminal or Git Bash on Windows:

1. **Create a new project directory**  
   ```bash
   mkdir learn_git
   cd learn_git
````

2. **Create a new file**

   ```bash
   touch third.txt
   ```

3. **Initialize a Git repository**

   ```bash
   git init
   ```

4. **Stage the file**

   ```bash
   git add third.txt
   ```

5. **Commit the staged file**

   ```bash
   git commit -m "adding third.txt"
   ```

6. **View the commit log**

   ```bash
   git log
   ```

7. **Create another file**

   ```bash
   touch fourth.txt
   ```

8. **Stage and commit the new file**

   ```bash
   git add fourth.txt
   git commit -m "adding fourth.txt"
   ```

9. **Remove the first file**

   ```bash
   rm third.txt
   ```

10. **Stage the deletion and commit**

    ```bash
    git add .
    git commit -m "removing third.txt"
    ```

11. **Review the commit history again**

    ```bash
    git log
    ```

12. **Update global Git settings**
    Disable Git’s default pager to display command output in full:

    ```bash
    git config --global core.pager cat
    ```

13. **List all global Git configurations**

    ```bash
    git config --global --list
    ```

---

## ✅ Submission Checklist

* [X] Screenshots of each command execution.
* [X] All screenshots pushed to the GitHub repository.
* [X] `README.md` updated (this file) as documentation for your Git learning process.

---

## 👤 Author

**Engr. Amarachi Crystal Omereife**
📧 Email: [mirrorprojectsltd@gmail.com](mailto:mirrorprojectsltd@gmail.com)
🌐 GitHub: [https://github.com/marameref](https://github.com/marameref)

---
