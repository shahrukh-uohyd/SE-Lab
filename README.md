# Software Engineering Lab Website

Professional website for the Software Engineering Lab at School of Computer and Information Sciences, University of Hyderabad.

## 📋 Overview

This is a Jekyll-based static website hosting research lab information including:
- Lab overview and mission
- Research areas and focus
- Publications and links
- Faculty and team members
- News, seminars, and activities
- Contact information

## 🚀 Quick Start

### Local Development

```bash
# Clone the repository
git clone https://github.com/shahrukh-uohyd/SE-Lab.git
cd SE-Lab

# Install dependencies
bundle install

# Run Jekyll server
bundle exec jekyll serve

# Visit http://localhost:4000
```

### Enable GitHub Pages

1. Go to: https://github.com/shahrukh-uohyd/SE-Lab/settings/pages
2. Under "Build and deployment":
   - Source: `Deploy from a branch`
   - Branch: `main` / `(root)`
   - Click **Save**

Website will be live at: https://shahrukh-uohyd.github.io/SE-Lab/

## 📁 File Structure

```
SE-Lab/
├── _config.yml                  # Jekyll configuration
├── Gemfile                      # Ruby dependencies
├── index.md                     # Home page
├── research.md                  # Research areas
├── publications.md              # Publications
├── members.md                   # Team members
├── activities.md                # News & activities
├── contact.md                   # Contact information
├── _layouts/
│   └── default.html            # Page template
├── assets/
│   ├── css/
│   │   └── style.css           # Responsive stylesheet
│   └── images/                 # Lab logo and images
├── _activities/                # Activity/post files
└── README.md                   # This file
```

## 🎨 Customization

### Colors
Edit `assets/css/style.css`:
- `--primary-color`: #003D7A (Navy blue)
- `--secondary-color`: #D4A574 (Gold)

### Lab Information
Edit `_config.yml`:
```yaml
lab_name: "Software Engineering Lab"
school: "School of Computer and Information Sciences"
university: "University of Hyderabad"
email: "Salman@uohyd.ac.in"
```

### Pages Content
- `index.md` - Home page
- `research.md` - Research areas
- `publications.md` - Publications
- `members.md` - Team members
- `activities.md` - Activities
- `contact.md` - Contact info

## 📝 Adding Content

### Add Team Members
Edit `members.md`:
```markdown
| Name | Role | Year | Status |
|------|------|------|--------|
| John Doe | PhD Student | 2024 | Active |
```

### Add Publications
Edit `publications.md`:
```markdown
**2025** | Author | "[Paper Title](DOI)" | *Journal*, Vol. X
```

### Add Activities/News
Create new file in `_activities/`:
```markdown
---
layout: activity
title: "Seminar Title"
date: 2026-05-06
excerpt: "Short description"
---
Full content here...
```

### Upload Images
1. Place images in `assets/images/`
2. Reference in markdown:
```markdown
![Alt text]({{ site.baseurl }}/assets/images/image.png)
```

## 🌐 Responsive Design

- **Desktop**: Optimized for 1000px+ width
- **Tablet**: Optimized for 768px+ width
- **Mobile**: Optimized for 480px+ width
- Print-friendly styles included

## 📚 Pages

| Page | Purpose |
|------|---------|
| Home | Lab overview, news, quick links |
| Research | Research areas and focus |
| Publications | Publication listings and profiles |
| Members | Faculty, students, alumni |
| Activities | News, seminars, events |
| Contact | Contact info and location |

## 🔧 Technical Stack

- **Static Generator**: Jekyll 4.3
- **Hosting**: GitHub Pages
- **Language**: Markdown + HTML/CSS
- **Responsive**: Mobile-first CSS

## 📦 Dependencies

- Ruby 3.1+
- Jekyll 4.3
- Bundler

## 🎯 Features

✅ Responsive design (mobile/tablet/desktop)  
✅ Professional styling with lab branding  
✅ Easy-to-edit Markdown format  
✅ Navigation and footer  
✅ Activity/post management  
✅ SEO-optimized  
✅ Print-friendly  
✅ Free GitHub Pages hosting  

## 📧 Contact

**Prof. Salman Abdul Moiz**  
Email: Salman@uohyd.ac.in  
Office: N-110, SCIS, University of Hyderabad

## 📄 License

© 2026 Software Engineering Lab, University of Hyderabad. All rights reserved.

## 🔗 Links

- [GitHub Repository](https://github.com/shahrukh-uohyd/SE-Lab)
- [Website](https://shahrukh-uohyd.github.io/SE-Lab/)
- [University of Hyderabad](https://www.uohyd.ac.in)

