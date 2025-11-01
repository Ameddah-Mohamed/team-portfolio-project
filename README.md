# Team Portfolio Project

A collaborative static website showcasing our team's profiles and technical skills, built using industry-standard Git workflows and deployed via GitHub Pages.

## 🚀 Live Demo

**[View Live Website](https://ameddah-mohamed.github.io/team-portfolio-project/)**

## 📋 Project Overview

This project demonstrates our team's ability to collaborate effectively using distributed version control with Git and GitHub. We followed professional development workflows including feature branching, pull requests, code reviews, and continuous deployment to create a cohesive team portfolio website.

## 👥 Team Members

| Name | Role | GitHub Profile |
|------|------|----------------|
| Ameddah Mohamed | Team Lead & Repository Administrator | [@ameddah-mohamed](https://github.com/ameddah-mohamed) |
| Boutiche Serine | Developer | [@bouticheserine](https://github.com/bouticheserine) |
| Gadiri Amina | Developer | [@aminagadiri-ui](https://github.com/aminagadiri-ui) |

## 🛠️ Technical Stack

- **Frontend:** HTML5, CSS3
- **Version Control:** Git, GitHub
- **Workflow:** Feature Branching, Pull Requests, Code Reviews
- **Deployment:** GitHub Pages (Automated)
- **Collaboration:** Conventional Commits, Branch Protection Rules

## 📁 Project Structure

```
team-portfolio-project/
├── index.html                      # Main team navigation page
├── members-portfolios/             # Individual profile pages
│   ├── ameddah-mohamed.html
│   ├── boutiche-serine.html
│   └── gadiri-amina.html
├── assets/
│   ├── css/                        # Stylesheets
│   │   ├── main.css
│   │   ├── ameddah-mohamed.css
│   │   ├── boutiche-serine.css
│   │   └── gadiri-amina.css
│   └── images/                     # Profile images and assets
│       ├── mohamed.jpg
│       ├── serine.jpg
│       └── amina.jpg
├── README.md                       # Project documentation
└── .gitignore                      # Git ignore rules
```

## 🔧 Development Workflow

Our team followed these industry-standard practices throughout the project:

### Branch Strategy

- **`main`** - Production-ready code (protected branch)
- **`develop`** - Integration branch for testing (protected branch)
- **`feature/*`** - Individual feature development branches
  - `feature/ameddah-profile`
  - `feature/boutiche-profile`
  - `feature/gadiri-profile`
  - `feature/index-page`

### Collaboration Process

#### 1. Feature Development
- Create feature branches from `develop`
- Work independently on individual features
- Regular commits with meaningful messages

#### 2. Code Review
- Open pull requests from feature branches to `develop`
- Mandatory peer reviews with 2+ approvals
- Address feedback and suggestions
- Ensure no merge conflicts

#### 3. Quality Gates
- Branch protection rules enforced on `main` and `develop`
- No direct commits to protected branches
- All changes via reviewed pull requests

#### 4. Continuous Deployment
- Merge `develop` into `main` after testing
- Automatic deployment to GitHub Pages
- Live updates within minutes

### Commit Convention

We followed the **Conventional Commits** specification:

- `feat:` - New features or functionality
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `style:` - Code formatting (CSS, HTML structure)
- `refactor:` - Code restructuring without changing functionality
- `chore:` - Maintenance tasks

**Example commits:**
```
feat: add Mohamed's profile page with skills section
fix: correct navigation links on index page
style: improve responsive design for mobile devices
docs: update README with deployment instructions
```

## 🎯 Features

### Website Features

- **Responsive Design:** Mobile-first approach ensuring compatibility across all devices
- **Accessible:** Semantic HTML5 and proper ARIA attributes
- **Professional Profiles:** Each member has a dedicated page featuring:
  - Professional biography
  - Technical skills and expertise
  - GitHub profile integration
  - Contact information
- **Team Overview:** Central navigation hub with member cards
- **Clean UI/UX:** Consistent design system across all pages

### Technical Features

- **Static Site:** Fast loading, no backend required
- **GitHub Pages:** Free, reliable hosting with custom domain support
- **Version Controlled:** Complete project history in Git
- **Collaborative:** Multiple contributors with clear ownership

## 🚀 Getting Started

### Prerequisites

- Git installed on your machine
- GitHub account
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)

### Local Development

```bash
# Clone the repository
git clone https://github.com/ameddah-mohamed/team-portfolio-project.git

# Navigate to project directory
cd team-portfolio-project

# Open in browser
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

### Making Changes

```bash
# Create a new feature branch from develop
git checkout develop
git pull origin develop
git checkout -b feature/your-feature-name

# Make your changes, then commit
git add .
git commit -m "feat: description of your changes"

# Push to GitHub
git push origin feature/your-feature-name

# Open a pull request on GitHub to merge into develop
```

## 📚 Learning Outcomes

Through this project, our team gained hands-on experience with:

- **Git Fundamentals:** Branching, merging, conflict resolution
- **GitHub Collaboration:** Pull requests, code reviews, issue tracking
- **Professional Workflows:** Feature branching, branch protection, CI/CD
- **Web Development:** HTML5, CSS3, responsive design principles
- **Documentation:** Technical writing, README best practices
- **Team Communication:** Asynchronous collaboration, peer feedback

## 🔒 Branch Protection Rules

Our protected branches (`main` and `develop`) enforce:

- ✅ Require pull request reviews before merging
- ✅ Require at least 2 approving reviews
- ✅ Dismiss stale pull request approvals when new commits are pushed
- ✅ Require status checks to pass before merging
- ✅ Require branches to be up to date before merging
- ✅ Restrict who can push to matching branches

## 📈 Project Timeline

1. **Week 1:** Repository setup, branch strategy, initial structure
2. **Week 2:** Individual profile page development
3. **Week 3:** Integration, code reviews, bug fixes
4. **Week 4:** Final testing, documentation, deployment

## 🤝 Contributing

While this is a closed academic project, we welcome feedback! If you notice any issues:

1. Open an issue describing the problem
2. If you'd like to suggest improvements, feel free to fork and submit a pull request
3. All contributions will be reviewed by the team lead

## 📄 License

This project is created for educational purposes as part of our coursework. All rights reserved by the team members.

## 📞 Contact

**Project Maintainer:** Ameddah Mohamed  
**GitHub:** [@ameddah-mohamed](https://github.com/ameddah-mohamed)  
**Project Repository:** [team-portfolio-project](https://github.com/ameddah-mohamed/team-portfolio-project)

For questions, issues, or collaboration opportunities, please open an issue on GitHub or contact the repository administrator.

---

**Built with ❤️ by Team Portfolio Project Contributors**

