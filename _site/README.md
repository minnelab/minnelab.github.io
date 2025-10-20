# Contributing to MINNE lab Website

This repository contains the source code for the MINNE lab website (minnelab.github.io), built with Jekyll and hosted on GitHub Pages. Follow these instructions to add content and update the website.

## Prerequisites

- Git installed on your computer
- GitHub account with access to this repository
- Basic knowledge of Markdown formatting

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/minnelab/minnelab.github.io.git
   cd minnelab.github.io
   ```

2. **Create a new branch for your changes:**
   ```bash
   git checkout -b your-update-name
   ```

## Add Your Biography

To add yourself as a team member:

### 1. Add Your Profile Image
- Add your profile image to the `assets/people/` directory
- Use JPEG format and keep file size under 50KB
- Recommended dimensions: 300x300 pixels
- File naming convention: `name.jpeg` (e.g., `john-doe.jpeg`)

### 2. Create Your Biography File
- Create a new file in the `_people/` directory
- File name: `name.markdown` (e.g., `john-doe.markdown`)
- Use the following template:

```markdown
---
layout: person
title: 'Your Full Name'
category: people
permalink: /people/firstname-lastname
image: /assets/people/your-image.jpeg
position: 'Your Position (e.g., PhD Student, Postdoc, etc.)'
status: 'current' (or former)
---

![Your Name](/assets/people/your-image.jpeg){:class="people-profile-image"}



### 3. Update Status
- Use `status: 'current'` for current team members
- Use `status: 'former'` for former team members
```

## Add an Update or News Page

To add news, announcements, or updates:

### 1. Create a New Post
- Create a new file in the `_posts/` directory
- File naming convention: `YYYY-MM-DD-post-title.markdown`
- Example: `2024-12-15-new-publication.markdown`

### 2. Use This Template:
```markdown
---
layout: post
title: "Your Post Title"
paper_authors: "Author list if you are posting a paper"
date: YYYY-MM-DD
abstract: "Brief one-sentence summary of the post / paper abstract"
---

Write your full post content here using Markdown formatting.

You can include:
- Links to publications
- Images (add them to assets/ directory)
- Conference announcements
- Lab achievements
- New team member announcements
```

### 3. Post Categories
Post ideas may include:
- Publication announcements
- Conference presentations
- Lab news and achievements
- New team member welcomes
- Grant announcements

## General Content Updates

### Update Existing Pages
Main pages are located in the root directory:
- `index.markdown` - Homepage
- `about.markdown` - About page
- `code.markdown` - Code and repositories
- `teaching.markdown` - Teaching information
- `join-us.markdown` - Job opportunities or master projects
- `maia.markdown` - MAIA information

### Add Images or Assets
- Place images in appropriate subdirectories within `assets/`
- Keep file sizes reasonable (< 1MB for images)
- Use descriptive file names

## Submitting Your Changes

1. **Add and commit your changes:**
   ```bash
   git add .
   git commit -m "Add [description of your changes]"
   ```

2. **Push your branch:**
   ```bash
   git push origin your-update-name
   ```

3. **Create a Pull Request:**
   - Go to the GitHub repository
   - Click "Compare & pull request"
   - Add a description of your changes
   - Request review from a repository maintainer

## Local Development (Optional)

To preview changes locally before submitting:

1. **Install Jekyll:**
   ```bash
   gem install bundler jekyll
   bundle install
   ```

2. **Run local server:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View website:**
   Open `http://localhost:4000` in your browser



## Need Help?

- Check existing files for examples
- Markdown: <https://www.markdownguide.org/basic-syntax/>


## Important Notes

- Changes to the main branch automatically deploy to the live website!!!
- Always test locally when possible
- Push to main if you are ONLY changing your own info, otherwise please make a PR 

