# Your GitHub Pages Personal Website

A personal academic website built with Jekyll and the Minimal Mistakes theme.

## Quick Start

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler (`gem install bundler`)

### Local Development

1. **Install dependencies:**

   ```bash
   bundle install
   ```

2. **Run locally:**

   ```bash
   bundle exec jekyll serve
   ```

3. **Open in browser:**
   Visit `http://localhost:4000`

## Customization Checklist

### 1. Update `_config.yml`

Replace all placeholder values:

- [ ] `title`: Your name
- [ ] `subtitle`: Your tagline
- [ ] `name`: Your full name
- [ ] `description`: Site description for SEO
- [ ] `url`: Your GitHub Pages URL (e.g., `https://yourusername.github.io`)
- [ ] `repository`: Your repo name
- [ ] `author.name`: Your name
- [ ] `author.bio`: Short bio
- [ ] `author.location`: Your city/country
- [ ] `author.email`: Your email
- [ ] Update all social links (Google Scholar, LinkedIn, GitHub)

### 2. Add Your Profile Photo

- Add your photo to `assets/images/profile.jpg`
- Recommended size: 300x300 pixels (square)

### 3. Update `_data/navigation.yml`

- [ ] Replace `YOUR_SCHOLAR_ID` with your Google Scholar ID

### 4. Update `index.md`

- [ ] Fill in the "About Me" section
- [ ] Add your publications
- [ ] Update the News section
- [ ] Add your education history
- [ ] Replace `YOUR_SCHOLAR_ID` in the button link

### 5. Blog Posts

- Delete the sample post in `_posts/`
- Create new posts following the naming convention: `YYYY-MM-DD-title.md`

## File Structure

```
.
├── _config.yml          # Main site configuration
├── _data/
│   └── navigation.yml   # Header navigation links
├── _pages/
│   └── blog.md          # Blog archive page
├── _posts/
│   └── YYYY-MM-DD-*.md  # Blog posts
├── assets/
│   └── images/
│       └── profile.jpg  # Your profile photo
├── index.md             # Main homepage
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Deployment to GitHub Pages

1. Push your code to GitHub repository named `yourusername.github.io`
2. Go to repository Settings → Pages
3. Source should be set to "Deploy from a branch"
4. Select the `main` branch and `/ (root)` folder
5. Your site will be live at `https://yourusername.github.io`

## Theme Customization

### Changing the Color Scheme

In `_config.yml`, change `minimal_mistakes_skin` to one of:

- `default`
- `air`
- `aqua`
- `contrast`
- `dark`
- `dirt`
- `neon`
- `mint`
- `plum`
- `sunrise`

### Adding Custom CSS

Create `assets/css/main.scss` with:

```scss
---
---

@import "minimal-mistakes/skins/{{ site.minimal_mistakes_skin | default: 'default' }}";
@import "minimal-mistakes";

// Your custom styles here
```

## Finding Your Google Scholar ID

1. Go to [Google Scholar](https://scholar.google.com)
2. Click on "My Profile"
3. Your ID is in the URL: `https://scholar.google.com/citations?user=YOUR_ID_HERE`

## License

This project uses the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) Jekyll theme, which is licensed under the MIT License.

## Resources

- [Minimal Mistakes Documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
