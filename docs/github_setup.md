# GitHub setup / Configuración inicial de GitHub

## Create the remote repository / Crear el repositorio remoto

1. Sign in to GitHub.
2. Create a new repository named `Cartesian-Welding-Robot`.
3. Set visibility to **Private**.
4. Do not initialize it with a README, `.gitignore`, or license because these are already included in this scaffold.
5. Add the remote URL to this local repository and push the initial commit.

## Local commands / Comandos locales

Run these commands from the extracted `Cartesian-Welding-Robot` directory:

```bash
git init
git add .
git commit -m "Initial repository structure"
git branch -M main
git remote add origin <YOUR_PRIVATE_REPOSITORY_URL>
git push -u origin main
```

Replace `<YOUR_PRIVATE_REPOSITORY_URL>` with the URL shown by GitHub. Do not paste access tokens into source files or commit history.

## CAD and Git LFS decision / Decisión sobre CAD y Git LFS

Before adding SolidWorks assemblies or large simulation files:
1. Measure representative file sizes.
2. Check current GitHub repository and Git LFS limits for your account.
3. Decide which extensions need LFS.
4. Install and configure Git LFS before the first commit containing those files.

Do not enable LFS patterns retroactively without planning how existing tracked binary files will be migrated.
