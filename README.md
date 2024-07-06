# new-project

## Steb-by-Step Instructions

### 1. Create a new directory and initialize a Git repository

```sh
mkdir new-project
cd new-project
git init
```

### 2. Create a README.md file and add initial content

```sh
echo "# new-project" > README.md
git add README.md
git commit -m "init"
```

### 3. Create a new branch called 'development' and switch to it

```sh
git checkout -b development
```

### 4. Open a README.md file and add this instructions

```sh
echo "Step-by-step instructions for the 'new-project'" >> README.md
git add README.md
git commit -m "Add instructions to README.md"
```

### 5. Merge changes from the 'development' branch into the 'main' branch

```sh
git checkout main
git merge development
```

### 6. Push changes to the remote repository

```sh
git remote add origin <remote-repository-URL>
git push -u origin main
```