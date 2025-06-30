### Elvis Muchiri 146497 

### Key Concepts Learned

###  Git Branching
- Created a personal branch (`Elvis`) to work independently without affecting `main`.
- Understood how to create, switch, and push a branch:
  ```bash
  git checkout -b Elvis
  git push origin Elvis
  ```

---

###  Pulling & Merging
- Merged another teammate’s branch (`origin/Lenga`) into mine to stay up-to-date.
- Resolved a **merge conflict** in `index.html` by combining both our contributions manually.
- Learned about:
  - `<<<<<<<`, `=======`, `>>>>>>>` markers
  - Cleaning up conflicts and committing the resolution.

---

###  Pull Requests (PRs)
- Opened a pull request to propose merging my changes into `main`.
- Understood the purpose of PRs:
  - Code review
  - Safe collaboration
  - Clear history of work
- Added meaningful titles and descriptions following [Conventional Commits](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13):
  ```bash
  feat: add Elvis's section with avatar and layout consistency
  ```

---

### Reviewers & Assignees
- **Reviewer**: Teammate or instructor who checks and approves the PR.
- **Assignee**: Person responsible for the task (usually myself).
- Learned how to assign these roles within a PR for team clarity.

### Martin Lenga 150160

## Key Concepts from the GitHub Crash Course

Throughout the crash course, I developed a practical understanding of GitHub's collaborative tools and version control workflows. Below are the major lessons I took away:

---

### Merge Conflict Resolution
- Learned that merge conflicts are a natural part of collaborative development.
- Understood conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) and how to manually resolve them.
- Gained confidence in resolving conflicts locally before merging branches.
- Realized that conflicts often happen when multiple people edit the same line or file.

---

### Markdown & Documentation
- Discovered how Markdown simplifies writing structured documentation on GitHub.
- Learned syntax like:
  - `#` for headings
  - `-` or `*` for bullet lists
  - `**bold**` and `*italic*` for emphasis
  - `![Alt Text](image-url)` for embedding screenshots
- Used Markdown to create a clean, readable `Assignment.md` with screenshots and explanations.
- Helped me present my work professionally and consistently.

---

### Structured Commits (Conventional Commits)
- Adopted commit message structure like:  
  `type(scope): short description`
- Used different commit types including:
  - `feat` - new features
  - `fix` - bug fixes
  - `docs` - documentation updates
  - `style` - visual or format changes
  - `refactor` - internal code restructuring
  - `chore` - non-code tasks (e.g., image uploads, config)
- Helped keep commit history clean, understandable, and traceable to issues or PRs.

---

### Project Board (Kanban)
- Set up a project board with columns: `To Do`, `In Progress`, and `Done`.
- Added issues to the board and updated their status as tasks progressed.
- Helped track my workflow visually and stay organized.
- Provided a clear snapshot of the project’s progress for both me and potential reviewers.
