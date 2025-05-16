# 🐙 Octocat .NET Awakening

This repository contains an automated workflow using **GitHub Actions** to build a .NET project. Every time Octocat feels a movement in the code ocean (or every hour), it wakes up from its nap and gets to work!

## ⚙️ What does the workflow do?

- Runs when there is a **push to the `main` branch**.
- Also runs **automatically every hour**.
- Uses official GitHub actions:
  - `actions/checkout` to clone the repository.
  - `actions/setup-dotnet` to set up the .NET 8 environment.
- Restores project dependencies.
- Builds the .NET project.
- Displays a custom message from Octocat 🐙.

## 📄 Project Path

Make sure the path to your `.csproj` file is correctly set in the workflow. Example used:

src/github4women/github4women.csproj


## 📁 Workflow File

The workflow file is located at:

.github/workflows/dotnet-build.yml

## 📣 Final message from the workflow

> "Build completed successfully!  
> Octocat is now ready to conquer the code ocean!" 🌊
