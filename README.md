# Maths Progress Tracker

A modern, responsive web app for tracking completion of the full Class 11 and Class 12 Maths syllabus, along with NDA-relevant maths topics.

## Live App Structure

- `index.html`: Full working app in one file
- `.nojekyll`: Ensures GitHub Pages serves the site as a plain static app

## Features

- Full Class 11 Maths syllabus
- Full Class 12 Maths syllabus
- NDA-focused maths revision topics
- Expand/collapse chapter cards
- Left-aligned checkboxes for subtopics
- Chapter-wise progress tracking
- Overall completion percentage
- Animated progress bars
- Save Progress button for each chapter
- Mark All as Complete button for each chapter
- Reset Progress button
- Local storage support so progress stays after refresh
- Mobile-friendly responsive design

## Publish On GitHub Pages

1. Create a new repository on GitHub.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the root of that repository.
3. Open the repository on GitHub.
4. Go to `Settings` -> `Pages`.
5. Under `Build and deployment`, choose:
   Source: `Deploy from a branch`
6. Under branch settings, choose:
   Branch: `main`
   Folder: `/ (root)`
7. Click `Save`.
8. Wait a minute or two for GitHub Pages to publish the site.
9. Your website will appear at:
   `https://your-github-username.github.io/your-repository-name/`

## Notes

- Progress is saved in the browser using `localStorage`, so each device/browser keeps its own saved state.
- If you later want a custom domain, you can connect one in the GitHub Pages settings.

