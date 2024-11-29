# Electronics_test_hub
Collection of scripts and resources for testing electronic components and PCBs. Includes test procedures, circuit configurations, and detailed README files for setup and usage.

---

### **Contributing Test Scripts**

When adding a test script for a specific component or PCB, please ensure the following are included:

1. **Code**: The script itself, well-commented for clarity.

2. **Short README**:

       - A KiCAD schematic of the test circuit.
       - A picture of the assembled test circuit (if possible).
       - Any explanations or details necessary to understand and reproduce the test.

This helps maintain consistency and ensures tests are easy to use and understand by other team members.

You're absolutely right! Users need to have Git installed on their system first. Here's an updated guide:  

---

### **Guide to Updating the Repository**  

#### **Step 1: Install Git**  
If Git isn't installed, download and install it:  
- **Windows**: [Download Git for Windows](https://git-scm.com/download/win) and follow the setup wizard. Use **Git Bash** for terminal commands.  
- **Linux**: Install Git via your package manager:  
  ```bash
  sudo apt install git       # Debian/Ubuntu
  sudo dnf install git       # Fedora
  sudo pacman -S git         # Arch
  ```  
- **Mac**: Install Git using Homebrew:  
  ```bash
  brew install git
  ```  

---

#### **Step 2: Open a Terminal/Shell**  
- **Windows**: Open **Git Bash** or **PowerShell** (search for it in the Start menu).  
- **Linux**: Open the terminal (shortcut: `Ctrl + Alt + T`).  
- **Mac**: Open **Terminal** via Spotlight (`Cmd + Space`, type `Terminal`).  

---

#### **Step 3: Clone the Repo**  
```bash
git clone <repo-url>
cd <repo-name>
```

#### **Step 4: Create a New Branch**  
```bash
git checkout -b <branch-name>
```
Use a descriptive branch name, e.g., `test-esc-update`.

#### **Step 5: Make Changes**  
- Add your files or edit existing ones.  
- Include a short README for new tests.

#### **Step 6: Stage and Commit Changes**  
```bash
git add .
git commit -m "Description of your changes"
```

#### **Step 7: Push Your Branch**  
```bash
git push origin <branch-name>
```

#### **Step 8: Create a Pull Request (PR)**  
1. Go to the repository on GitHub.  
2. Click **"Compare & pull request"**.  
3. Add a description of your changes and request a review.

#### **Step 9: Review and Merge**  
- Wait for a reviewer to approve your PR.  
- Once approved, the reviewer will merge it into the main branch.

#### **Step 10: Update Your Local Main Branch**  
```bash
git checkout main
git pull origin main
```

---