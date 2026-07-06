# Troubleshooting Guide

## Overview

This guide helps resolve common issues that may occur while setting up or running the **UdayFoodie Landing Page** project.

---

# Issue 1: CSS Is Not Loading

## Symptoms

- The page appears without styling.
- Content is displayed as plain HTML.

## Possible Causes

- Incorrect CSS file path.
- Missing `style.css` file.
- Browser cache.

## Solution

- Verify that `style.css` exists in the project root.
- Check the `<link>` tag in `index.html`.
- Refresh the browser using **Ctrl + Shift + R**.

---

# Issue 2: Images Are Not Displayed

## Symptoms

- Broken image icons appear.
- Images fail to load.

## Possible Causes

- Incorrect file path.
- Missing image file.
- Incorrect filename or extension.

## Solution

- Verify images exist inside:

```text
assets/Images/
```

- Check that filenames match exactly.
- Ensure the correct file extension is used.

---

# Issue 3: Live Server Is Not Working

## Symptoms

- Website does not open.
- Live Server fails to start.

## Solution

- Install the **Live Server** extension in VS Code.
- Restart Visual Studio Code.
- Right-click `index.html`.
- Select **Open with Live Server**.

---

# Issue 4: Layout Looks Incorrect

## Symptoms

- Sections overlap.
- Spacing is inconsistent.
- Elements appear misaligned.

## Possible Causes

- Browser zoom level.
- CSS modifications.
- Unsupported browser features.

## Solution

- Reset browser zoom to **100%**.
- Review recent CSS changes.
- Test in another browser.

---

# Issue 5: Changes Are Not Visible

## Symptoms

- Edited content does not appear.

## Solution

- Save all files before refreshing.
- Perform a hard refresh (**Ctrl + Shift + R**).
- Clear the browser cache if necessary.

---

# Issue 6: Git Push Fails

## Possible Causes

- Authentication issue.
- Remote repository mismatch.
- Network connectivity problem.

## Solution

Run:

```bash
git status
git add .
git commit -m "Update documentation"
git push origin main
```

If authentication fails, verify your GitHub credentials or Personal Access Token.

---

# Frequently Recommended Checks

Before reporting an issue, verify:

- All files are saved.
- File paths are correct.
- Images exist.
- CSS is linked correctly.
- Browser cache is cleared.
- Git repository is synchronized.

---

# Additional Resources

- HTML Documentation
- CSS Documentation
- Visual Studio Code Documentation
- Git Documentation
- GitHub Documentation

---

# Summary

Most issues can be resolved by checking file paths, verifying project structure, and ensuring all project files are present. Keeping the repository organized helps prevent common development problems.