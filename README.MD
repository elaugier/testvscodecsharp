# Create a good repository

1. Choose your repository organization.

   You should choice your repository structure:

   - Single solution with a main project and his dependencies projects
   - Single solution and multiple components projects (Monorepo - Monostack)
   - Single solution with a main project which host one or more frontends
   - Monorepo multi-stacks

2. create the local repository

```console
git init --initial-branch=main
```

3. create the gitignore

```console
dotnet new gitignore
```

# Manage your repository

## Use Clear and Concise Commit Messages

When making changes to a codebase, it’s important to use clear and concise commit messages that describe what changes you made and why.

A good commit message should provide enough information to understand the context of the change without being too long or verbose. Clear and concise commit messages make it easier for other developers to understand what you changed and why, which is particularly important when reviewing changes or investigating issues.
