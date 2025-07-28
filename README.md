# VS Code Profile Assignment

**Objective**: Import and activate the `wdi.code-profile` file to set up your VS Code environment for web development.

## Why Use This Profile?

This profile contains both essential extensions and optimized settings for web development.

### Extensions Included

This profile includes three essential extensions that every web developer should have:

### 1. HTMLHint
- **What it does**: Analyzes your HTML code and flags errors, bad practices, and accessibility issues
- **Why web developers need it**: Catches common HTML mistakes before they become problems (missing alt attributes, unclosed tags, invalid markup). Professional web developers use linters to maintain code quality and ensure websites work properly across all browsers and devices.

### 2. Live Server
- **What it does**: Creates a local web server with live reload functionality
- **Why web developers need it**: See your HTML/CSS/JavaScript changes instantly in the browser without manually refreshing the page. This speeds up development workflow and testing during web development.

### 3. Stylelint
- **What it does**: Analyzes your CSS/SCSS code for errors, enforces coding standards, and suggests improvements
- **Why web developers need it**: Prevents CSS errors, maintains consistent code style, and helps you write better, more maintainable stylesheets. Essential for professional CSS development, especially when working in teams or on large projects.

### Settings Included

This profile also includes carefully configured settings that:
- **Enable auto-formatting** on save to keep your code clean
- **Set consistent indentation** (4 spaces) for all file types
- **Configure Git integration** for easier version control
- **Optimize file handling** with auto-save and whitespace cleanup
- **Set up proper validation** for HTML, CSS, and JavaScript
- **Configure Live Server** with appropriate defaults for local development

These settings create a professional development environment that follows industry best practices.

## Instructions

### Step 1: Import the Profile

1. **Open VS Code** (any project or empty window is fine)

2. **Access the Profiles panel**
   - Look for the **gear icon** (⚙️) in the bottom-left corner of VS Code
   - Click the gear icon
   - Select **"Profiles"** from the menu

3. **Import the profile**
   - In the Profiles panel, look for **"Import Profile..."** 
   - Click **"Import Profile..."**
   - In the Import Profile dialog, navigate to your repository folder
   - Select the `wdi.code-profile` file
   - Click **"Open"**

4. **Create the profile**
   - The Profile creation form will open with the profile contents pre-selected
   - Review the profile contents and click **"Create"** to import the profile

### Step 2: Activate the Profile

1. **Make it active**
   - The imported profile will now be available in your Profiles list
   - Click **"Use this Profile for Current Window"** to activate it
   - VS Code will reload with the new profile settings and extensions

2. **Verify it's active**
   - Look in the bottom-left corner of VS Code - the gear icon should now show a **graduation cap** (🎓) instead of the regular gear
   - This mortar board icon indicates that "Web Dev I for GRID" is your active profile
   - Check Extensions (Ctrl+Shift+X) - you should see HTMLHint, Live Server, and Stylelint installed

### Step 3: Download the Missing Image File

The `index.html` file in your repository references an image that needs to be downloaded:

1. **Download the welcome image**
   - Right-click on this link: [welcome-cats-dots.svg](https://raw.githubusercontent.com/RVCC-IDMX/shared-assets/main/welcome-cats-dots.svg)
   - Select **"Save link as..."** or **"Download linked file as..."**
   - Save the file as `welcome-cats-dots.svg` directly in your repository folder (the same folder as `index.html`)
   - **Important**: Make sure the filename is exactly `welcome-cats-dots.svg`

2. **Test with Live Server**
   - Right-click on `index.html` in VS Code
   - Select **"Open with Live Server"**
   - Your browser should open showing the welcome page with the cat animation
   - If you see the image, everything is working correctly!

## Assignment Complete!

Once you've successfully imported and activated the profile, you have completed this assignment. Your VS Code is now configured with professional web development tools.

## Beginner's Guide

**What is a VS Code Profile?** Think of it like a "preset" for your text editor - it contains specific tools, colors, and settings all bundled together.

**What are Extensions?** Extensions are like apps for VS Code that add new features and capabilities.

**Why do we all use the same setup?** Having the same VS Code setup makes learning easier and more consistent across the class.

## Contributing

If you encounter issues with this profile setup, please discuss with your instructor during class or office hours.

## License

This project is licensed under the MIT License.