> ## 🤔 What is this template all about?
>
> - This template can be used as a base layer for a GitHub profile page.
> - Make the project easy to maintain with **7 issue templates**.
> - Quick-start documentation with an extraordinary README structure.
> - Manage issues with **20 issue labels**.
> - Make _community healthier_ with all the guides like code of conduct, contributing, support, security...
> - Learn more with the [official GitHub guide on creating repositories from a template](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template).
> - To start using it, click **[Use this template](https://github.com/IQKV/standard-dotgithub-profile-layout/generate)** to create your new repository.

---

# ✨ GitHub Profile Template

Default Community Health Files for the organization on GitHub

---

<a name="changelog"></a>

## 📆 Changelog

Conventional changelog located [here](CHANGELOG.md).

<a name="acknowledgments"></a>

## 👍 Acknowledgments

...

<a name="contributing"></a>

## 🙏 Community & Contributions

Please follow [Contributing](.github/CONTRIBUTING.md) page.

<a name="codeofconduct"></a>

## 📙 Code of Conduct

Please follow [Code of Conduct](.github/CODE_OF_CONDUCT.md) page.

<a name="troubleshooting"></a>

## 💥 Troubleshooting

...

## 📑 License

This project is licensed under the Apache License. See the [LICENSE](LICENSE) file for more details.

---

## _GitHub Project Tooling Overview_

### **Package Management**

- **pnpm** - Package manager with `pnpm-lock.yaml`
- **Node.js** - Engine requirement `>=22.13.0`

### **Development Scripts**

- `lint` - Run stylelint for CSS files
- `lint:stylelint` - Stylelint with caching
- `formatter:check` - Check code formatting
- `formatter:write` - Format code
- `release` - Release with release-it (CI mode)
- `node_modules:cleanup` - Clean dependencies
- `prepare` - Setup husky hooks

### **Code Quality Tools**

- **oxfmt** - Code formatting (`.prettierrc`, `.prettierignore`)
- **Stylelint** - CSS/SCSS linting with standard config
- **EditorConfig** - Cross-editor consistency
- **Husky** - Git hooks management
- **lint-staged** - Pre-commit linting
- **Commitizen** - Conventional commit messages

### **Git & Release Management**

- **Commitlint** - Enforce conventional commits
- **Release-it** - Automated releases with conventional changelog
- **Husky pre-commit hooks** - Quality checks before commits

### **GitHub Workflow Checks**

- **PR Title Validation** - Ensure conventional PR titles
- **Commit Message Validation** - Check commit conventions
- **Node.js Build Pipeline** - Project build validation
- **Template Usage** - Setup workflow for template users

### **Community Health Files**

- Issue templates (7 templates)
- Pull request template
- Code of conduct, contributing guidelines
- Security policy, support documentation
- Issue labeling automation (20+ labels)
- CODEOWNERS for review assignments
