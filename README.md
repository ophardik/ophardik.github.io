# Hardik Khandelwal — Portfolio

Personal portfolio of **Hardik Khandelwal**, Backend Developer (Node.js · TypeScript) in Jaipur.
Scroll-driven, built with [Astro](https://astro.build), GSAP + ScrollTrigger and Lenis.

## Sections
- **Hero** — Backend Developer, live typewriter console, repaint-the-site colour picker
- **About** — intro + capabilities
- **Crashed back to Earth** — wireframe globe landing on Jaipur
- **Laurels** — experience, APIs built, +35% throughput, releases, education
- **The Stack** — tech stack as a football squad; tap a player for years of experience
- **Work** — 3D fly-through of projects (Wellbux, Health Fair Plus, Agentic AI pipeline, …)
- **Contact** — form via FormSubmit (first submission sends an activation email to the inbox)
- **ECHO** — rule-based assistant that answers questions about Hardik

## Run locally
```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # → ./dist
npm run preview
```

## Deploy (Netlify)
`netlify.toml` is included: build command `npm run build`, publish directory `dist`.

## Editing content
- Projects: `src/components/SWork.astro` (`info`) + cover images in `public/assets/images/`
- Stack squad: `src/components/SPitch.astro` (`xi`, `bench`)
- Stats: `src/components/SAward.astro`
- About text: `src/components/SAbout.astro`
- Chatbot answers: `src/components/AChat.astro` (`KB`)
- Resume: `public/Hardik_Khandelwal_Resume.pdf`

## Credits
Adapted, with the author's permission, from the portfolio of
[Vasudutt Pareek](https://github.com/Vasudxtt/portfolio) (CC BY-NC 4.0).
Changes: all content, projects, stack, stats, chatbot, contact backend, images and metadata replaced;
"My Way" photo section removed.
Fonts: PP Editorial New and PP Fraktion Mono by Pangram Pangram; Bigger Display — check their licences before commercial use.
