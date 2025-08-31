# Minimalistic Jekyll Blog

A clean, simple blog built with Jekyll and the Minima theme.

## Features

- **Minimalistic Design**: Clean, distraction-free interface
- **Easy to Edit**: Write posts in simple Markdown
- **RSS Feed**: Automatic feed generation for subscribers
- **Responsive**: Works great on all devices
- **Fast**: Static site generation for optimal performance

## How to Create New Posts

1. Go to the `_posts` folder
2. Create a new file with this naming pattern: `YYYY-MM-DD-title.markdown`
3. Start your post with this header (front matter):

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
categories: general
---

Your content here...
```

## Example Post Structure

```markdown
---
layout: post
title: "My Thoughts on Technology"
date: 2025-08-31
categories: tech
---

# Introduction

Your introduction here...

## Main Content

Write your thoughts here. You can use:

- **Bold text**
- *Italic text*
- [Links](https://example.com)
- Code blocks
- Lists

## Conclusion

Wrap up your post...
```

## Local Development

To run the blog locally:

```bash
cd blog
bundle exec jekyll serve --host 0.0.0.0
```

Then visit: http://localhost:4000/blog/

## Deployment

The blog automatically deploys to GitHub Pages when you push to the main branch.

## Configuration

Edit `_config.yml` to change:
- Site title
- Description
- Contact information
- Social media links

## Tips for Easy Editing

1. **On-the-go editing**: Use GitHub's web interface to edit posts directly in your browser
2. **Mobile editing**: GitHub mobile app allows quick edits
3. **Simple workflow**: Just edit Markdown files and commit - no complex build process needed
4. **Preview**: Always available at your GitHub Pages URL after commits

## File Structure

```
blog/
├── _posts/           # Your blog posts go here
├── _config.yml       # Main configuration
├── about.markdown    # About page (redirects to main site)
├── index.markdown    # Blog homepage
└── Gemfile          # Dependencies
```

Happy blogging! 🎉
