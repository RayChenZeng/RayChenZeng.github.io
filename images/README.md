# Images Directory Structure

This directory contains all images for the portfolio website, organized by section.

## Folder Structure

- **about/** - Profile photos and about section images
- **activities/** - Images for all activity subsections
  - **frc/** - FIRST Robotics Competition photos (robot builds, team photos, competitions)
  - **ftc/** - FIRST Tech Challenge photos (robot builds, team photos, competitions)
  - **harvard/** - Harvard research photos (lab, projects, research team)
  - **volleyball/** - Volleyball photos (games, team photos, tournaments)
  - **deca/** - DECA photos (competitions, presentations, awards)
  - **singing/** - Singing and music performance photos (performances, group photos, events)
- **achievements/** - Award and achievement photos
- **gallery/** - General gallery images from all activities
- **resume/** - Resume-related images or documents

## How to Add Images

1. Place your images in the appropriate folder
2. Use descriptive filenames (e.g., `frc_robot_2024.jpg`, `harvard_lab_team.jpg`)
3. Supported formats: JPG, PNG, GIF, WebP
4. Recommended: Optimize images for web (compress to reasonable file sizes)

## Usage in HTML

To use images in the website, replace the placeholder `<div class="image-placeholder">` elements with actual `<img>` tags:

```html
<!-- Replace this -->
<div class="image-placeholder">FRC Robot Image</div>

<!-- With this -->
<img src="images/activities/frc/robot_2024.jpg" alt="FRC Robot 2024">
```

## Image Optimization Tips

- Resize images to appropriate dimensions (max 1920px width for full-width images)
- Compress images to reduce file size
- Use WebP format for better compression
- Add descriptive alt text for accessibility
