# Resume PDF Setup Instructions

## How to Add Your Resume PDF

1. **Create/Export your resume as PDF**:
   - Use any word processor (Word, Google Docs, LaTeX, etc.)
   - Export/Save as PDF format
   - Name the file `resume.pdf`

2. **Add the PDF to your portfolio**:
   - Place the `resume.pdf` file in the same folder as your `index.html`
   - The file structure should look like:
     ```
     portfolio/
     ├── index.html
     ├── styles.css
     ├── script.js
     ├── resume.pdf          ← Your resume goes here
     └── README.md
     ```

3. **Test the download**:
   - Open your portfolio in a browser
   - Click the "Download Resume" button in the hero section
   - Or click the PDF icon in the contact section
   - Your resume should download automatically

## Alternative Options

If you don't have a resume PDF ready, you can:

### Option 1: Remove the resume buttons temporarily
Edit `index.html` and comment out or remove the resume button lines:
```html
<!-- <a href="resume.pdf" class="btn btn-resume" download>Download Resume</a> -->
```

### Option 2: Link to an online resume
Replace `resume.pdf` with a link to:
- Google Drive public link
- Dropbox public link
- LinkedIn profile
- Online resume builder link

Example:
```html
<a href="https://drive.google.com/file/d/YOUR_FILE_ID/view" class="btn btn-resume" target="_blank">View Resume</a>
```

### Option 3: Create a simple resume template
Use online tools like:
- Canva
- Resume.io
- Zety
- Google Docs templates
- LaTeX Overleaf templates

## Tips for a Great Resume PDF

- Keep it to 1-2 pages maximum
- Use a clean, professional design
- Include contact information
- Highlight your skills matching your portfolio
- Use consistent formatting
- Save with a meaningful filename like "Saksham_Resume.pdf"
- Ensure text is selectable (not just an image)

## File Size Considerations

- Keep PDF under 2MB for faster downloads
- Optimize images if included
- Use PDF compression tools if needed

---

**Note**: The current portfolio is set up to look for a file named `resume.pdf` in the same directory. Make sure your resume file has exactly this name, or update the file name in the HTML accordingly.
