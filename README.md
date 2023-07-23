# Npm Cheatsheet

This is a cheatsheet for npm.

---
# Commands
## Init Project

```bash
# Initialize a project.
npm init

# Instantly initialize a project.
npm init --yes
```

## Install Package

```bash
# Install all packages defined in package.json.
npm install

# An alias of npm install.
npm i

# Install a package.
npm install <package-name>

# Install a package. (Same as npm install <package-name> after npm 5.0.0)
npm install <package-name> --save

# Install a package as a dev dependency.
npm install <package-name> --dev-save

# Install a package globally.
npm install <package-name> -g

# Install a package of a specific version.
npm install <package-name>@<version>

# Install via github repo.
npm install <github-repo-url>

# Install via a file path.
npm install <file-path>

# Install via tar package over https, e.g., https://site.com/archive.tgz.
npm install <http-tar-package-url>
```

## Uninstall

```bash
# Remove a package.
npm rm <package-name>
```

## List And View Package

```bash
# List installed packages.
npm list

# An alias of npm list.
npm ls

# List globally installed packages.
npm list -g

# List outdated packages.
npm outdated

# List the latest versions of a package.
npm view <package-name>
```

## Run

```bash
# Run a script defined in package.json.
npm run <script-name>
```

[Back to Cheatsheets Page](https://phucbone.github.io/Cheatsheets/)

[Back to Main Page](https://phucbone.github.io/)
