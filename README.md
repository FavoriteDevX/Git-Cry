<img width="1600" height="669" alt="image_ad20b192" src="https://github.com/user-attachments/assets/eb8c1ad4-0707-4454-923c-8452e6ef0323" />

`git-cry` is a custom Git extension for those dark moments when a merge conflict ruins your day, destroys your codebase, and leaves you staring at `<<<<<<< HEAD` in pure despair. 

Instead of throwing your laptop, just type `git cry` to vent, scream, or get some aggressive motivation.

## How It Works

When you run `git cry`:
1. It checks if your current repository is actually in a merge conflict state.
2. If it **is** in a conflict, it randomly selects a venting mechanism (a dramatic ASCII art cry, a screaming prompt, or a chaotic piece of advice).
3. If it **is not** in a conflict, it congratulates you for having a peaceful day.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com
   cd git-cry
   ```

2. Make the script executable:
   ```bash
   chmod +x git-cry
   ```

3. Install it globally by moving it to your system PATH (or linking it):
   ```bash
   sudo ln -s "\$(pwd)/git-cry" /usr/local/bin/git-cry
   ```

Now, you can use it anywhere on your machine just like a native Git command: `git cry`.

## Usage

Simply run the following command inside any Git repository:
```bash
git cry
```
