# Resumex

A LaTeX resume template with automated PDF generation and versioning through GitHub Actions. Never lose track of your resume versions again!

## 🚀 Quick Start

1. Fork this repository
2. Edit `resume.tex` with your information
3. Commit and push to main branch
4. GitHub Actions will automatically:
   - Generate a PDF
   - Create a new release
   - Attach the PDF to the release

## 📝 How to Use

### 1. Fork and Setup
- Click the "Fork" button at the top right of this repository
- Enable GitHub Actions in your forked repository (if not already enabled)

### 2. Customize Your Resume
- Open `resume.tex`
- Replace the placeholder content with your information:
  - Personal details (name, contact, links)
  - Professional summary
  - Work experience
  - Skills
  - Education
  - Languages
  - Certifications

### 3. Preview Changes
You can build locally to preview changes before pushing:

1. Install requirements:
   - A LaTeX distribution (e.g., TeX Live, MiKTeX)
   - Required packages: geometry, hyperref, enumitem, helvet

2. Build locally:
```bash
pdflatex resume.tex
```
### 4. Publish Updates
Whenever you want to update your resume:

```bash
git add resume.tex
git commit -m "Updated resume content"
git push origin main
```

The GitHub Action will automatically:
- Build the PDF
- Create a new version
- Publish a release with the date and version number
- Attach the generated PDF

## 🔄 Versioning

- Automatic version increments using semantic versioning
- Each update creates a dated release
- Access all versions in the [Releases](../../releases) section

## 📄 Latest Version

Find your latest resume in the [Releases](../../releases/latest) section.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest enhancements
- Submit pull requests

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

Feel free to reach out to me:
- GitHub: [github.com/nizarcan](https://github.com/nizarcan)
- Email: nizarcan@yahoo.com
- LinkedIn: [linkedin.com/in/nizarcan](https://linkedin.com/in/nizarcan)
