# My Jekyll Blog

This is a Jekyll blog hosted on GitHub Pages. The site was created using the default Jekyll theme "minima" and is designed to be simple and easy to maintain.

## Setup

This site is designed to work with GitHub Pages without requiring a local Ruby installation. Simply push changes to the repository, and GitHub Pages will build and deploy the site automatically.

## Adding New Posts

To add a new blog post:

1. Create a new file in the `_posts` directory
2. Name it with the format: `YYYY-MM-DD-title-of-post.md`
3. Add the front matter at the top of the file:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS -0000
   categories: category1 category2
   ---
   ```
4. Write your post content in Markdown below the front matter

## Customizing

- Edit `_config.yml` to change site-wide settings
- Modify or add pages like `about.md`
- Add custom CSS in `assets/css/style.scss` 