# EDIT_HERE — Ziad Ali Portfolio

This is a plain HTML/CSS/JS portfolio. You can edit it without any framework.

## 1) Change text, title, bio, services, skills, experience, projects
Open `index.html` in VS Code or Notepad++ and use **Ctrl + F** to search for the exact text you want to change.

Examples:
- `Ziad Ali` → your display name
- `AI & Machine Learning Engineer` → your headline
- `What I can help you build.` → Services heading
- `Predictive Machine Learning` → service name
- `Healthcare & Clinical Data Analysis Pipeline` → project name
- Experience entries are inside `<section id="experience">`
- Education is inside `<section id="education">`

## 2) Add / replace certificate images (no code needed)
Put your JPG/PNG certificate files inside `assets/certificates/` and use these exact filenames:

- `HCIA-AI.jpg`
- `HCIA-BigData.jpg`
- `Huawei-BigData-Associate.jpg`
- `AI-Fundamentals-Data-Analysis.jpg`

The cards automatically display the image. If you want more certificates, copy one `<article class="cert">...</article>` card in `index.html`, change its title and image filename, and add the new image to the same folder.

## 3) Change project images
Replace these files with your own JPG/PNG/SVG files while keeping the filenames:
- `assets/projects/healthcare.svg`
- `assets/projects/enterprise.svg`
- `assets/projects/sales.svg`

## 4) Change service images
Replace files in `assets/services/` while keeping the same filenames.

## 5) Change your profile photo
Replace `assets/profile.jpg` with your new photo. Keep the same filename.

## 6) Change CV
Replace `Ziad_Ali_CV.pdf` with the new PDF using the same filename.

## 7) Change GitHub / LinkedIn / email
Use Ctrl + F in `index.html` to search for the old URL/email and replace it.

## Recommended section order
Hero → About → Services → Skills → Experience → Projects → Engineering Approach → Education → Certifications → Availability → Contact

## Important
Do not open `index.html` by itself after moving files. Keep the whole folder structure together so images, certificate files and CV links continue to work.
