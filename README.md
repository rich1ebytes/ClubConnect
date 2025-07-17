Follow these steps to clone, set up, and contribute to this project without conflicts.

---

### 🚀 1. Clone the Repository

```bash
git clone https://github.com/rich1ebytes/ClubConnect.git
cd ClubConnect
```

---

### 🛠 2. Create a New Branch

Never commit directly to `main`. Instead, create a new branch for your feature or fix.

```bash
git checkout -b feature/your-feature-name
```

Examples:

```bash
git checkout -b feature/event-form-ui
git checkout -b fix/venue-overlap-bug
```

---

### 🧪 3. Make Your Changes

* Work on your assigned module or task
* Run and test your changes locally

---

### ✅ 4. Stage and Commit Your Work

```bash
git add .
git commit -m "Add: short description of what you did"
```

Example:

```bash
git commit -m "Add: Event creation form with validation"
```

---

### ⬆️ 5. Push to Your Branch

```bash
git push origin feature/your-feature-name
```

---

### 🔁 6. Open a Pull Request (PR)

1. Go to the repo on GitHub: [https://github.com/rich1ebytes/ClubConnect](https://github.com/rich1ebytes/ClubConnect)
2. Click on **"Compare & Pull Request"**
3. Add:

   * A meaningful title
   * A short description of your changes
4. Assign it to a reviewer (e.g., team lead)

---

### 🧹 7. Keep Your Branch Updated (Recommended)

If someone else has merged changes into `main`, update your branch:

```bash
git checkout main
git pull origin main

git checkout feature/your-feature-name
git rebase main
```

---

### 📌 Contribution Rules

* One feature/bug per branch
* Never push directly to `main`
* Always pull latest `main` before starting
* Always open a PR for review

---

### 🧑‍💼 Git Branch Naming Convention

| Type     | Example                    |
| -------- | -------------------------- |
| Feature  | `feature/event-form-ui`    |
| Fix      | `fix/venue-booking-bug`    |
| Refactor | `refactor/dashboard-cards` |
| Docs     | `docs/update-readme`       |

---
