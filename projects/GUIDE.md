# Adding New Projects to Your Portfolio

This guide explains how to add new projects to your portfolio repository.

## Quick Start

1. **Create Project Directory**
   ```bash
   mkdir projects/your-project-name
   ```

2. **Copy Template**
   ```bash
   cp projects/PROJECT_TEMPLATE.md projects/your-project-name/README.md
   ```

3. **Fill in Project Details**
   - Edit the README.md file
   - Add screenshots to a `screenshots/` subdirectory
   - Include any diagrams or documentation

4. **Update Main README**
   - Add your project to the Featured Projects section
   - Follow the existing format

## Project Structure

Each project should follow this structure:

```
projects/your-project-name/
├── README.md              # Main project documentation
├── screenshots/           # Project screenshots (optional)
│   ├── screenshot1.png
│   └── screenshot2.png
├── diagrams/             # Architecture/flow diagrams (optional)
│   ├── architecture.png
│   └── database-schema.png
└── docs/                 # Additional documentation (optional)
    ├── api.md
    └── setup.md
```

## Adding to Main README

When adding a new project to the main README.md, use this format:

```markdown
### [Project Number]. [Project Name]
*Status: [In Development/Completed/Research Project]*

[Brief description of the project]

**Key Features:**
- Feature 1
- Feature 2
- Feature 3

**Technologies Used:**
- Technology 1
- Technology 2
- Technology 3

📁 [View Project Details](./projects/project-directory/README.md)

---
```

## Best Practices

### Documentation
- Keep project descriptions clear and concise
- Use bullet points for easy scanning
- Include visual elements (screenshots, diagrams)
- Document setup and installation steps
- Explain the problem the project solves

### Project Organization
- One project per directory
- Use lowercase with hyphens for directory names
- Keep related files together
- Include a comprehensive README

### Visual Assets
- Take high-quality screenshots
- Show key features in action
- Include before/after comparisons if applicable
- Optimize image sizes for faster loading

### Code Examples
- Include relevant code snippets
- Add comments to explain complex logic
- Show API usage examples
- Provide configuration examples

## Showcasing Your Work

### Highlight Impact
- Explain the problem you solved
- Quantify results when possible
- Describe the users or beneficiaries
- Share feedback or testimonials

### Technical Details
- Explain your technical choices
- Discuss challenges and solutions
- Share lessons learned
- Mention performance optimizations

### Demonstrate Growth
- Show project evolution
- Explain new technologies you learned
- Highlight improvements over time

## Tips for Resume Projects

When adding projects you want to highlight on your resume:

1. **Focus on Results**
   - What problem did you solve?
   - What was the impact?
   - What technologies did you use?

2. **Show Your Skills**
   - Demonstrate technical competency
   - Highlight problem-solving abilities
   - Show system design skills

3. **Make It Professional**
   - Clean, well-organized code
   - Comprehensive documentation
   - Professional presentation

4. **Keep It Current**
   - Update dependencies
   - Fix deprecated code
   - Add recent features

## Examples

Check out these existing projects as examples:
- [UST IPEA Event Reservation System](./ust-ipea-event-reservation/README.md)
- [Contextualizing Retinal Vessel Segmentation](./retinal-vessel-segmentation/README.md)

## Need Help?

If you have questions or need assistance:
- Review the PROJECT_TEMPLATE.md
- Check existing project documentation
- Refer to GitHub's documentation formatting guide

---

Happy documenting! 🚀
