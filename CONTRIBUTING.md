# Contributing to the Mergington High Extra-Curricular Activities Website

🎉 Thank you for your interest in improving our school's website!  
Whether you're adding your club's activities, fixing a bug, or suggesting new features, this guide will help you get started.

---

## 🛠 Development Setup

1. Clone the repository to your computer:
   ```bash
   git clone https://github.com/felipeln/skills-introduction-to-repository-management.git
   cd skills-introduction-to-repository-management
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the development server:
   ```bash
   python src/app.py
   ```

4. Open your browser and visit:  
   👉 [http://localhost:8000](http://localhost:8000)

---

## ✨ Making Changes

1. Create a new branch for your changes:
   ```bash
   git checkout -b your-branch-name
   ```
   - Use descriptive names like `art-gallery-feature` or `fix-chess-signup`.

2. Make your changes and test them locally:
   - Use sample student data in `src/sample_data.json` or preview it with the MongoDB extension.

3. Run code checks (optional but encouraged):
   ```bash
   flake8 src/
   ```

4. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Brief description of your changes"
   git push origin your-branch-name
   ```

5. Create a pull request via GitHub.  
   - Be sure to describe *what* you changed and *why*.

---

## 🧼 Code Style

- Follow [PEP 8](https://pep8.org/) for Python code.
- Use clear, descriptive variable names (`student_name`, `start_time`, etc.)
- Add comments to explain logic, especially non-obvious code.
- Avoid hardcoding values — use configuration or constants where possible.

---

## 🤝 Need Help or Have Ideas?

- **Check existing issues** first:
  - If your idea or problem is already listed, comment or upvote it.
  - If not, create a new issue — be as detailed as possible.

- **Weekly IT Club Office Hours**:  
  Thursdays at lunch in Room 203

- **Contact the Tech Team**:  
  📧 techclub@mergingtonhigh.example.edu

Thanks again for contributing! You're helping make our school better for everyone. 💙
