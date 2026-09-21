# Positron Setup

# Set Up Codex with Positron and GitHub

This guide explains how to activate your Codex account, install Positron, connect Codex to Positron, and connect your GitHub account.

## Before you begin

You will need:

- A Rutgers-provided Codex activation link (should be in your email)
- A GitHub account
- A computer running Windows, macOS
- Permission to install software on your computer (hopefully not an issue with students)

## 1. Activate your Codex account

1. Open the email containing Rutgers Codex activation link or follow the link below:

[Rutgers Chat GPT Log In](https://software.rutgers.edu/software/license/156771/)

2. Use NETID@rutgers.edu as your username.

3. Complete Rutgers single sign-on and Duo 2FA.

4. When activation is complete, open Codex and confirm that you can access the Codex workspace.

5. Optional - install chatGPT desktop app. 


## 2. Confirm you have a Github account. If you don't already have a GitHub account, please create one

1. Go to [GitHub](https://github.com/).

2. Select **Sign up** or **Sign in**.

3. Use an email address you can access.

4. Verify your email address if GitHub asks you to do so.

5. Record your GitHub username. You will use it when connecting repositories and sharing code.


## 3. Download and install Positron

Positron is a development environment for working with R, Python, notebooks, and other data-science projects.

1. Go to the official [Positron download page](https://positron.posit.co/download).

2. Download the installer for your operating system:

   - **macOS:** Choose Apple Silicon for M-series Macs or Intel for older Macs.
   - **Windows:** Choose the installer that matches your computer.

3. Run the installer.

4. Accept the license agreement and use the default installation settings unless your instructor provides different instructions.

5. Open Positron after installation.

Positron should work immediately after installation but you may also need to install or update R or Python if you haven't already.

## 4. Install the Codex extension in Positron

Positron supports many Visual Studio Code extensions. However, Positron uses open source package galleries rather than Microsoft’s Visual Studio Code Marketplace. As a result, the Codex extension may not appear in every Positron installation. Let me know if you can't find it after following the instructions below.

1. Open Positron.

2. Select the **Extensions** icon on the left side of the window.

3. Search for:

   ```text
   Codex
   ```

4. Locate the official Codex extension **published by OpenAI**.

5. Select **Install**.

6. Restart Positron if prompted.

7. Look for a Codex icon or Codex command in the activity bar or Command Palette.

### If Codex does not appear

Do not install an extension with a similar name unless the publisher is verified.

If the official Codex extension is unavailable in Positron. Tell me! **Do not download an unofficial extension or executable.**

## 5. Connect Codex to your account

1. In Positron, open the Codex panel.

2. Select **Sign in**, **Log in**, or **Connect account**.

3. A browser window should open.

4. Sign in using the Codex account you activated in Step 1.

5. Approve the connection if prompted.

6. Return to Positron.

7. Confirm that the Codex panel shows you as signed in.


## 6. Connect Positron to GitHub

1. Select the **Extensions** icon on the left side of the window.

3. Select the GitHub Pull Requests extension.

4. Your browser will open. Sign in to GitHub.

5. Enter the authorization code shown by Positron, if requested.

6. Approve access.

7. Return to Positron.

GitHub may show an authorization screen. Review the requested permissions before selecting **Authorize**. See GitHub’s documentation on [authorizing OAuth apps](https://docs.github.com/en/apps/oauth-apps/building-oauth-apps/authorizing-oauth-apps).


## 7. Test the setup

In Positron, verify that:

- The Codex panel opens.
- Your Codex account shows as connected.
- Your GitHub account is authenticated.
- A GitHub repository opens successfully.
- The Source Control panel detects changes.
- Codex can read the project files when you explicitly ask it to do so.

For a simple test, open a project file and ask Codex:

> Explain what this file does without changing it.

