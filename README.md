# Julian Cremer - Personal Academic Website

This is the source code for my personal academic website, built using Jekyll and the Academic Pages template. The website showcases my research, publications, and professional work in AI for Drug Discovery and AI for Science.

## About Me

I am a Senior Machine Learning Scientist at Pfizer, working on AI for Drug Discovery and AI for Science in general with a focus on generative chemistry and structure-based drug discovery. My research interests include:

- Equivariant Graph Neural Networks
- Generative Models for Molecular Design
- Structure-Based Drug Discovery
- AI for Chemical and Biological Sciences

## Website Features

- **Publications**: Complete list of my research papers and preprints
- **Research Focus**: Details about my work in AI for drug discovery
- **Professional Background**: Information about my role at Pfizer
- **Academic Profiles**: Links to Google Scholar, ORCID, and LinkedIn

Visit the live website at: [https://jule-c.github.io](https://jule-c.github.io)

## Development Setup

To run this website locally for development:

### Prerequisites
- Ruby (version 2.7 or higher)
- Node.js
- Bundler gem

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jule-c/jule-c.github.io.git
   cd jule-c.github.io
   ```

2. **Install dependencies:**
2. **Install dependencies:**
   
   On macOS:
   ```bash
   brew install ruby node
   gem install bundler
   ```
   
   On Linux/WSL:
   ```bash
   sudo apt install ruby-dev ruby-bundler nodejs
   ```

3. **Install Ruby gems:**
   ```bash
   bundle install
   ```
   
   If you encounter permission errors, install gems locally:
   ```bash
   bundle config set --local path 'vendor/bundle'
   bundle install
   ```

4. **Run the development server:**
   ```bash
   bundle exec jekyll serve -l -H localhost
   ```
   
   The site will be available at `http://localhost:4000` and will automatically reload when you make changes.

### Alternative: Using Docker

If you prefer to use Docker or want to avoid installing dependencies locally:

```bash
chmod -R 777 .
docker compose up
```

The site will be available at `http://localhost:4000`.

### VS Code DevContainer

If you're using VS Code, you can use the included DevContainer configuration:
1. Open the repository in VS Code
2. Press F1 and select "DevContainer: Reopen in Container"
3. The site will automatically be served at `http://localhost:4000`

## Site Structure

- `_config.yml` - Main configuration file
- `_pages/` - Static pages (About, CV, Publications, etc.)
- `_publications/` - Individual publication entries
- `_posts/` - Blog posts
- `_data/` - Data files for navigation, CV, etc.
- `images/` - Images and media files
- `files/` - PDFs and other downloadable files

## Key Research Areas

My work focuses on the intersection of machine learning and drug discovery:

- **Equivariant Graph Neural Networks**: Developing neural architectures that respect molecular symmetries
- **Generative Chemistry**: Creating novel molecular structures using diffusion models and flow matching
- **Structure-Based Drug Discovery**: Leveraging protein-ligand interactions for rational drug design
- **Multi-Objective Optimization**: Balancing multiple drug properties in molecular generation

## Publications Highlights

- **PILOT**: Equivariant diffusion for pocket-conditioned de novo ligand generation (Chemical Science, 2024)
- **Equivariant Graph Neural Networks for Toxicity Prediction** (Chemical Research in Toxicology, 2023)
- **FLOWR**: Flow matching for structure-aware ligand generation (ICLR 2025)

## Contact

- **Email**: jn.cremer@icloud.com
- **Google Scholar**: [Profile](https://scholar.google.com/citations?user=nxMxFvMAAAAJ&hl=de)
- **ORCID**: [0000-0001-6319-7283](https://orcid.org/my-orcid?orcid=0000-0001-6319-7283)
- **LinkedIn**: [julian-cremer-8b738219b](https://www.linkedin.com/in/julian-cremer-8b738219b/)

---

## Technical Details

---

## Technical Details

This website is built using:
- **Jekyll** - Static site generator
- **Academic Pages Template** - Base template for academic websites
- **GitHub Pages** - Hosting platform
- **Kramdown** - Markdown processor
- **Rouge** - Syntax highlighter

## Template Attribution

This repository was originally forked from the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) by [Stuart Geiger](https://github.com/staeiou), which is based on the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) by Michael Rose. Both are released under the MIT License.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
