# 🤝 Contribution Guide

**Everyone can contribute to this project!** I'm happy to receive contributions from anyone who wants to help grow the United Nerds movement.

## 🌟 Why contribute?

United Nerds is an open movement that seeks to stop discrimination against nerds. Your contribution, no matter how small, can make a big difference. You can help in several ways:

- 🐛 Report bugs
- 📝 Improve documentation
- 🎨 Improve design and styles
- 🌐 Translate content

## 🚀 How to Contribute

### 1. Fork the Repository

First, fork the repository to your GitHub account:

1. Click the "Fork" button in the top-right corner
2. This will create a copy of the repository in your account

### 2. Clone the Repository

Clone your fork locally:

```bash
git clone https://github.com/YOUR-USERNAME/United-nerds.git
cd United-nerds
```

### 3. Set up the Project

Install dependencies:

```bash
pnpm install
```

If you don't have `pnpm` installed, you can install it with:

```bash
npm install -g pnpm
```

### 4. Create a Branch

Create a new branch for your contribution:

```bash
git checkout -b feature/new-feature
```

**Branch naming tips:**
- `fix/bug-name` - For bug fixes
- `feat/new-feature` - For new features
- `docs/docs-improvement` - For documentation improvements
- `style/style-improvement` - For visual improvements
- `translate/language` - For translations

### 5. Make Changes

Now you can make your changes:

- Edit the necessary files
- Test changes locally by running `pnpm dev`
  - Note for VS Code users: the dev server usually starts automatically via `.vscode/tasks.json` (task `pnpm: dev`) when you open the folder. You can also trigger it from “Tasks: Run Task”.

### 6. Commit Changes

Commit your changes with clear and descriptive messages:

```bash
git add .
git commit -m "Clear description of what you did"
```

**Commit message tips:**
- **Write them in English**
- Be clear and descriptive
- Use the imperative mood ("Add feature X" not "Added feature X")
- Keep them concise (max 50 characters for the first line)
- **Examples:**
  - `fix: resolve navigation bar styling issue`
  - `feat: add new About section component`
  - `docs: update README with contribution guidelines`
  - `style: improve button hover effects`

### 7. Push and Pull Request

Push your changes to your fork:

```bash
git push origin feature/new-feature
```

Then, create a Pull Request:

1. Go to your fork on GitHub
2. Click "Compare & pull request"
3. Fill out the Pull Request form:
   - **Title**: Clear description of the change
   - **Description**: Explain what you did and why
   - Link any related issue with `closes #number`

### 8. Review

I will review your Pull Request and may ask for changes or clarifications. Don't worry, this is a normal part of the process!

## 📋 Code Style

While there is no strict style defined, try to:

- Keep code clean and readable
- Use descriptive names for variables and functions
- Comment complex code when necessary
- Follow the existing project style

## 🧪 Test Before Contributing

Before creating a Pull Request, make sure that:

- ✅ The development server works: in VS Code it auto-starts via `.vscode/tasks.json` (task `pnpm: dev`), otherwise run `pnpm dev` manually
- ✅ The changes work correctly
- ✅ You haven't introduced new errors

## 💬 Questions?

If you have any questions or doubts:

- Open an issue in the repository

## 🙏 Thank you!

Thank you for considering contributing to United Nerds. Your help is greatly appreciated and helps grow the movement to end discrimination against nerds!
