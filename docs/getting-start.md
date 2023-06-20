---
layout: default
title: Getting Started
nav_order: 3
---

## Getting Started

To get started with Git, follow these steps:

### Step 1: Install Git

First, you need to install Git on your computer. Git provides installers for different platforms, including Windows, macOS, and Linux. Here's how to install Git:

1. Visit the [official Git website](https://git-scm.com/) and navigate to the download section.
2. Download the installer for your operating system.
3. Run the installer and follow the installation instructions.
4. Once the installation is complete, open a new terminal or command prompt window and type `git --version` to verify that Git is installed correctly.

### Step 2: Configure Git

After installing Git, you should configure it with your name and email address. Git uses this information to associate your commits with your identity. Follow these steps to configure Git:

1. Open a terminal or command prompt window.
2. Set your name using the following command, replacing `Your Name` with your actual name:

   ```bash
   git config --global user.name "Your Name"
   ```

3. Set your email address using the following command, replacing `your-email@example.com` with your actual email address:

   ```bash
   git config --global user.email your-email@example.com
   ```

### Step 3: Create a Git Repository

Once Git is installed and configured, you can create a new Git repository. A Git repository is a directory where Git tracks your project's files and their changes. Follow these steps to create a Git repository:

1. Open a terminal or command prompt window.
2. Navigate to the directory where you want to create the repository. You can use the `cd` command to change directories.
3. Use the following command to initialize a new Git repository:

   ```bash
   git init
   ```

   This command creates a hidden `.git` directory in your current directory, which is where Git stores the repository data.

Congratulations! You have now set up Git on your computer and created your first Git repository. You're ready to start using Git to track changes, create branches, collaborate with others, and more.

Continue reading the other sections of this documentation to learn more about Git's features and best practices.
