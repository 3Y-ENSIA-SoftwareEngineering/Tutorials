# Tutorials Repository

This repository contains various tutorial sections, each organized in its own folder.

## Getting Started

### Clone the Repository

```bash
git clone <repository-url>
cd Tutorials
```

### Repository Structure

The repository is organized with separate folders for each tutorial section:

```
Tutorials/
├── Tuto_1_../
├── Tuto_2../
├── Tuto_3.../
└── ...
```

### Adding Files

All commands should be executed from within the `Tutorials` directory.

1. Add a specific file:
```bash
git add <filename>
```

2. Add all new files in a specific tutorial section:
```bash
git add SectionName/*
```

3. Add all changes:
```bash
git add .
```

4. Commit your changes:
```bash
git commit -m "Your commit message"
```

5. Push changes to the repository:
```bash
git push origin main
```

## Contributing

1. Create a new branch for your changes:
```bash
git checkout -b feature/your-feature-name
```

2. Make your changes and commit them
3. Push your branch to the repository
4. Create a Pull Request from your branch

## Note

Make sure you're in the `Tutorials` directory when executing git commands to properly manage the repository structure.
