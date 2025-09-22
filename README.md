# VS Code Profile Assignment

**Objective**: Import and activate a VS Code profile specifically designed for
web development with essential extensions and settings.

**Important**: This assignment assumes you have already completed the GitHub
Classroom assignment and have this repository cloned to your local computer
using VS Code.

## What You'll Accomplish

By completing this assignment, you will:

- Import and activate a professional VS Code profile for web development
- Set up essential extensions: HTMLHint and Live Server
- Download and integrate project assets from external sources
- Test your development environment with Live Server
- Submit your completed work via GitHub repository URL

## Why Use This Profile?

This profile contains both essential extensions and optimized settings for web
development.

**Extensions Included:**

- **HTMLHint** - Analyzes your HTML code and flags errors, bad practices, and
  accessibility issues
- **Live Server** - Creates a local web server with live reload functionality

**Settings Included:** Auto-formatting on save, consistent indentation, Git
integration, and optimized validation for HTML, CSS, and JavaScript.

## Instructions

### Step 1: Import the Profile

1. **Open VS Code**
   - Be sure you are in the repo from Part 2 and you can see the same file listing inside VS Code Explorer
   - In case it doesn't show up, then select **File → Recent** and click on it

2. **Access the Profiles panel**
   - Look for the **gear icon** (⚙️) in the bottom-left corner of VS Code
   - Click the gear icon
   - Select **"Profiles"** from the menu - you will Add a New Profile

3. **Import the profile**
   - In the Profiles panel, look for **"Import Profile..."**
   - Click **"Import Profile..."**
   - In the Import Profile dialog, navigate to your repository folder
   - Select the `wdi.code-profile` file
   - Click **"Open"**

4. **Create the profile**
   - The Profile creation form will open with the profile contents pre-selected
   - Review the profile contents and click **"Create"** to import the profile

**✓ Success Check:** You should see a profile named "Web Dev I" in your Profiles list.

### Step 2: Activate the Profile

1. **Make it active**
   - The imported profile will now be available in your Profiles list
   - Click the **gear icon** (⚙️) again, select **"Profiles"**, then click on
     **"Web Dev I"** to activate it (you'll see a checkmark next to
     the active profile)
   - VS Code will reload with the new profile settings and extensions

2. **Verify it's active**
   - Look in the bottom-left corner of VS Code - the gear icon should now show
     a **graduation cap** (🎓) instead of the regular gear
   - This icon indicates that "Web Dev I" is your active profile
   - Check Extensions (Ctrl+Shift+X) - you should see HTMLHint and Live Server
     installed

**✓ Success Check:** Look for the graduation cap (🎓) icon in the bottom-left corner, see a checkmark next to "Web Dev I" in the Profiles menu, and confirm HTMLHint and Live Server appear in your Extensions panel.

### Step 3: Download the Missing Image File

The `index.html` file in your repository references an image that needs to be
downloaded:

1. **Download the welcome image**
   - Right-click on this link:
     [welcome-cats-dots.svg](https://raw.githubusercontent.com/RVCC-IDMX/shared-assets/main/welcome-cats-dots.svg)
   - Select **"Save link as..."** or **"Download linked file as..."**
   - Save the file as `welcome-cats-dots.svg` directly in your repository
     folder (the same folder as `index.html`)
   - **Important**: Make sure the filename is exactly `welcome-cats-dots.svg`

2. **Test with Live Server**
   - Right-click on `index.html` in VS Code
   - Select **"Open with Live Server"**
   - Your browser should open showing the welcome page with the cat animation
   - If you see the image, everything is working correctly!

**✓ Success Check:** Your browser should open automatically and show the welcome page with a cat animation. If the image appears, Live Server is working perfectly!

### Step 4: Commit and Push Your Changes

Since you've added a new file (`welcome-cats-dots.svg`) to your repository,
you need to commit and push it:

1. **Stage the new file**
   - Open the Source Control panel (click the branch icon in the left sidebar)
   - You should see `welcome-cats-dots.svg` listed under "Changes"
   - Click the **+** button next to the filename to stage it

2. **Create a commit**
   - Type a commit message in the text box: `Add welcome image for Live Server demo`
   - Click the **checkmark** button (✓) to commit

3. **Push to GitHub**
   - Click the **three dots** (...) in the Source Control panel
   - Select **"Push"** from the menu
   - Your changes will be uploaded to GitHub

**✓ Success Check:** Visit your repository on GitHub in your browser - you should see your new commit and the welcome-cats-dots.svg file in the file list.

### Step 5: Submit Your Repository URL

Now that you've completed all the work and pushed your changes to GitHub, you
need to submit your repository URL in Canvas:

1. **Verify your changes are on GitHub**
   - Go to your repository page on GitHub
   - Refresh the page to see your latest changes
   - You should see your commit message `"Add welcome image for Live Server demo"`
     in the commit history
   - You should see the `welcome-cats-dots.svg` file in your repository file list

2. **Copy your repository URL**
   - Copy the complete URL from your browser's address bar
   - The URL should be the main page of your repository on GitHub

3. **Submit in Canvas**
   - Return to the Canvas assignment page
   - Paste your repository URL in the text submission box
   - Click **"Submit Assignment"** to complete your submission

## Assignment Complete

Once you've successfully imported and activated the profile, downloaded the
image file, viewed the working webpage in Live Server, pushed your changes to
GitHub, and submitted your repository URL in Canvas, you have completed this
assignment. Your VS Code is now configured with professional web development
tools.

## Beginner's Guide

**What is a VS Code Profile?** Think of it like a "preset" for your text
editor - it contains specific tools, colors, and settings all bundled together.

**What are Extensions?** Extensions are like apps for VS Code that add new
features and capabilities.

**Why do we all use the same setup?** Having the same VS Code setup makes
learning easier and more consistent across the class.

## Contributing

If you encounter issues with this profile setup, please discuss with your
instructor during class or office hours.

## License

This project is licensed under the MIT License.
