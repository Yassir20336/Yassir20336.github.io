# yassir20336.github.io

Personal portfolio of **Yassir Abd EL-Samad**, Senior Odoo Developer. Live at https://yassir20336.github.io

Built with [Astro](https://astro.build) and [Tailwind CSS v4](https://tailwindcss.com); based on the [DevPortfolio](https://github.com/RyanFitzgerald/devportfolio) template.

## Editing content

All text (bio, skills, projects, experience, education, stats, social links) lives in `src/config.ts`.
The resume is `public/resume.pdf` and the social-preview image is `public/og.png`.

- Separate paragraphs in `aboutMe` with a blank line.
- Give a project a `link` to make its card clickable; omit it otherwise.
- Set `availability` to show a status badge above your name.

## Development

```bash
npm ci
npm run dev      # http://localhost:4321
npm run build    # output in dist/
```

Pushing to `master` deploys automatically via GitHub Actions (`.github/workflows/deploy.yml`).
