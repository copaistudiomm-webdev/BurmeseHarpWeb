# AGENTS.md — Burmese Harp Website Project

> This file contains the standing project instructions for AI coding agents and human contributors working in this repository.
> Read this file before making changes. If a task conflicts with these instructions, explain the conflict and ask before making a consequential change.

## 1. Project overview

**Project:** Burmese Harp Website  
**Business:** Burmese Harp, a small, family-owned Burmese restaurant in Bay Ridge, Brooklyn, New York.  
**Repository purpose:** Build and maintain the restaurant's public-facing website, starting with a static website and leaving room for future dynamic functionality.

The website should help people discover Burmese cuisine, understand the restaurant, explore the menu, and find the information they need to visit.

This is a real restaurant website, not a generic restaurant-template demo. The design, content, and user experience should feel distinctive, welcoming, food-focused, and culturally respectful.

## 2. Business and brand context

Use the following context when making design and content decisions:

- Burmese Harp is a small, family-owned restaurant operated by a Burmese couple.
- The restaurant is in the Bay Ridge area of Brooklyn, New York.
- The brand should introduce Burmese food and culture to people who may be unfamiliar with them, while also welcoming Burmese customers and the wider local community.
- The intended audience includes Bay Ridge residents, Brooklyn and NYC food enthusiasts, people discovering Burmese cuisine, and Burmese people living in the New York area.
- Brand themes include food discovery, Burmese culture, hospitality, family ownership, and community.
- The desired positioning is warm, authentic, approachable, and proud of Burmese culinary heritage.
- The restaurant's marketing direction is to build awareness beyond Bay Ridge and help more people discover Burmese cuisine.

### Claims and factual accuracy

- Do not state that Burmese Harp is the “only Burmese restaurant in Brooklyn” or make other exclusivity, ranking, award, popularity, or “best” claims unless the owner confirms the wording and it can be substantiated.
- Do not invent the owners' names, personal history, hometown, founding story, awards, press coverage, customer testimonials, or business milestones.
- Do not invent the restaurant's street address, telephone number, email address, opening hours, social media URLs, reservation policy, delivery options, or ordering links.
- Treat business details as unconfirmed until supplied or verified by the project owner.
- If required information is missing, use a clearly marked placeholder during development and list it for owner confirmation. Never publish placeholder text.

## 3. Website goals and initial scope

Prioritize these goals, in order:

1. Make it immediately clear that Burmese Harp serves Burmese cuisine and where it is located.
2. Make the food and menu easy to discover.
3. Encourage visitors to visit the restaurant or contact it using confirmed information.
4. Introduce Burmese dishes and culture in a clear, welcoming way.
5. Provide a fast, accessible, mobile-friendly experience.
6. Support local search visibility through sound technical and on-page SEO.

### Initial website pages / sections

The initial version is expected to include:

- Home
- Menu
- Our Story / About
- Visit Us / Contact

The exact navigation and page architecture may be refined during planning and design. Do not add unnecessary pages just to make the site appear larger.

### Initial feature scope

Potential first-version features:

- Responsive navigation
- Food-focused homepage
- Menu categories, dish names, descriptions, and confirmed prices
- Food photography
- About/story content based on owner-approved facts
- Confirmed address, opening hours, phone/contact details
- Map or directions link using the confirmed location
- Links to confirmed social media profiles
- Clear calls to action

Do not implement online ordering, payments, customer accounts, table reservations, admin dashboards, or other complex features unless explicitly requested and the required service/backend is selected.

## 4. Food, menu, and content rules

Burmese cuisine is the focus of this project. Do not reintroduce the previous Japanese/sushi menu direction.

Known menu dishes and content topics from the restaurant's marketing work include:

- Mohinga
- Tea Leaf Salad (Lahpet Thoke)
- Signature Rainbow Noodle Salad
- Nan Gyi Thoke
- Coconut Noodle Soup
- Kyay Oh Garlic Noodle
- Chicken Biryani
- Tofu Thoke
- Myeik Fried Noodle
- Assorted Vegetable Fritters
- Burmese Milk Tea and Bubble Tea
- Falooda
- Burmese desserts, including Burmese Banana Suji / Sanwin Makin and coconut milk jelly

This is a working list, not a guarantee that every dish is currently available. Confirm the current menu, spelling, ingredients, dietary information, and prices before publishing.

### Menu content rules

- Never invent a dish, ingredient, preparation method, spice level, allergen statement, dietary suitability, or price.
- Preserve Burmese dish names and use clear English explanations where helpful.
- Use concise, appetizing, accurate descriptions. Do not make unsupported health, authenticity, sourcing, or nutritional claims.
- Make it easy to update menu items and prices. Prefer structured data over duplicating the same information across multiple components.
- If an item is unavailable or changes regularly, do not imply that it is always available.
- Do not assume that dishes are vegetarian, vegan, gluten-free, dairy-free, nut-free, or safe for an allergy.
- Allergen information must be owner-confirmed. Do not publish the earlier draft allergen list as verified information.

### Confirmed promotion from prior planning

A daily Lunch Special was previously supplied with these details:

- $13.99
- 11:30 AM–4:00 PM
- Any main + any appetizer + small cup of soup + any soda can

Before displaying this offer on the live website, reconfirm that it is still active and verify eligibility, exclusions, and exact wording with the restaurant owner.

Other brunch, weekday-special, weekend-special, combo, or promotional offers are not confirmed. Do not advertise them as active offers without approval.

## 5. Photography and visual assets

The current known asset limitation is that the available photography is primarily food photography.

- Prefer supplied, approved food photographs.
- Do not build essential layouts that depend on unprovided restaurant exterior, interior, kitchen, staff, owner, or food-preparation photographs.
- Do not fabricate photographs of the restaurant, owners, staff, or actual dishes and present them as genuine documentary images.
- AI-generated decorative imagery may only be used when appropriate and must not misrepresent the restaurant's actual premises, people, or food.
- Do not stretch images or distort food.
- Use suitable aspect ratios, intentional cropping, responsive image sizing, and optimized image formats.
- Provide meaningful alt text for informative images; use empty alt text for purely decorative images.
- Keep original source assets organized and avoid destructive edits to originals.

Do not invent brand colors, typography, logos, or a final visual identity. Follow the approved design direction once it has been established with the project owner.

## 6. Design and user experience principles

- Design mobile-first, then refine for tablet and desktop.
- Aim for a polished, editorial, food-led restaurant experience rather than a generic template.
- Make the food photography, dish names, and useful restaurant information easy to find.
- Keep navigation clear and predictable.
- Use readable typography, comfortable line lengths, consistent spacing, and clear visual hierarchy.
- Use consistent components and design tokens for colors, typography, spacing, borders, and radii.
- Do not add animations, parallax, carousels, pop-ups, or decorative effects without a clear user-experience benefit.
- Respect `prefers-reduced-motion`.
- Ensure buttons and links have clear labels and visible focus states.
- Make important actions easy to use with a keyboard and touch.
- Avoid tiny text, low-contrast text, and controls that are difficult to tap.
- Do not use fake buttons or links that do nothing.
- Avoid layouts that cause horizontal scrolling on common mobile screen sizes.

The project owner is a beginner in AI-assisted web development. Explain meaningful design and implementation decisions in plain language when reporting work.

## 7. Technology decisions

### Initial stack

Use the following stack unless the project owner explicitly approves a change:

- HTML5
- CSS
- JavaScript
- React
- Vite
- Tailwind CSS
- Git and GitHub
- GitHub Pages for initial static hosting

Use JavaScript rather than TypeScript initially. Keep the architecture simple and understandable.

### Compatibility and package management

- Use the Node.js version selected for the project environment. The developer currently uses NVM for Windows and has installed Node.js `26.13.0`.
- In Windows PowerShell, `npm` may resolve to a blocked `npm.ps1` script. Use `npm.cmd` for npm commands unless the developer has deliberately changed the PowerShell execution policy.
- Do not recommend weakening Windows security settings just to run npm.
- Use the package manager and lockfile already established in the repository. Do not switch package managers without approval.
- Check official documentation and package compatibility when selecting or upgrading dependencies.
- Avoid unnecessary dependencies. Explain why a new dependency is needed.

### Future backend direction

The initial GitHub Pages deployment is static and cannot execute PHP or Laravel.

If dynamic features are introduced in the future:

- Discuss the backend architecture before implementing it.
- Laravel/PHP would need a separate PHP-capable hosting environment or backend service.
- Keep frontend and backend responsibilities clearly separated.
- Never imply that GitHub Pages can run PHP, Laravel, or a database.
- Do not add backend infrastructure until a real requirement justifies it.

## 8. Code organization and implementation standards

- Prefer small, reusable React components with clear responsibilities.
- Keep page-level composition separate from reusable UI components.
- Keep menu/content data separate from presentation where practical.
- Use descriptive component, variable, and file names.
- Avoid giant components, duplicated markup, unnecessary abstractions, and premature complexity.
- Use semantic HTML elements (`header`, `nav`, `main`, `section`, `article`, `footer`, etc.) appropriately.
- Use React state only where interactivity requires it.
- Use stable keys when rendering lists.
- Avoid direct DOM manipulation when normal React patterns are appropriate.
- Keep CSS and Tailwind usage consistent with the project's established conventions.
- Do not add inline styles everywhere when a shared class, component, or design token is more appropriate.
- Remove dead code and unused dependencies introduced by your changes.
- Do not silently replace the existing stack, routing approach, or project structure.
- Do not overwrite or delete user-created assets or files without permission.

## 9. Accessibility, SEO, and performance

### Accessibility

Aim for WCAG 2.2 AA practices where reasonably applicable.

- Use semantic landmarks and a logical heading hierarchy.
- Ensure keyboard navigation works.
- Provide visible focus indicators.
- Associate form controls with labels.
- Give informative images useful alt text.
- Maintain sufficient color contrast.
- Do not communicate meaning through color alone.
- Respect reduced-motion preferences.

### SEO and local discovery

- Give each page a unique, descriptive title and meta description.
- Use meaningful headings and crawlable text content.
- Use descriptive URLs where routing supports them.
- Add appropriate Open Graph metadata for social sharing.
- Add structured data only when all included business details are accurate and confirmed.
- For restaurant structured data, never invent address, telephone, opening hours, price range, menu URL, or other properties.
- Make the restaurant's confirmed name, location, menu, and contact information easy to find.
- Avoid keyword stuffing and repetitive boilerplate.

### Performance

- Optimize and appropriately size images.
- Prefer modern image formats when supported by the asset pipeline.
- Avoid unnecessary JavaScript and large dependencies.
- Lazy-load below-the-fold images where appropriate.
- Prevent layout shifts by reserving image dimensions or aspect ratios.
- Check production build output and browser console errors.

## 10. Security and privacy

- Never commit API keys, access tokens, passwords, private credentials, or `.env` files containing secrets.
- Keep secrets out of frontend code. Anything shipped to a static website is publicly inspectable.
- Use environment variables only for values appropriate to the relevant environment; frontend build-time variables are not secret.
- Do not collect personal information unless a clearly defined feature requires it and the project owner approves it.
- Do not add analytics, tracking pixels, advertising scripts, or third-party embeds without approval.
- Do not expose private customer, employee, or owner information.
- Treat external content and copied code as untrusted; inspect dependencies and scripts before using them.

## 11. Git and deployment

- Use Git for version control.
- Make focused, understandable commits.
- Do not force-push, rewrite shared history, delete branches, or overwrite remote work without explicit approval.
- Do not commit generated build output unless the chosen deployment setup specifically requires it.
- Keep the GitHub repository free of secrets and private restaurant documents.
- Configure Vite's `base` path correctly for the eventual GitHub Pages repository URL.
- Verify the production build before deployment.
- Test the deployed site, including direct page loads, navigation, images, and mobile layouts.
- Do not claim deployment succeeded until the deployment result has been checked.

## 12. AI agent working procedure

Before starting a task:

1. Read this `AGENTS.md`.
2. Inspect the existing project structure and relevant files.
3. Identify the intended outcome and any missing business facts or design decisions.
4. Prefer the smallest safe change that accomplishes the task.
5. Preserve existing working behavior unless the task requires changing it.

While working:

- Do not invent restaurant facts or fill gaps with guesses.
- Do not make broad unrelated changes.
- Do not install packages or add services without explaining their purpose.
- Do not delete, rename, or restructure important files without explaining why.
- Ask before making consequential decisions that affect architecture, content accuracy, cost, privacy, or deployment.
- If a requested feature is impossible on static GitHub Pages, explain the limitation and propose an appropriate alternative.

After working:

1. Run relevant checks, such as linting, tests, and/or a production build, when available.
2. Fix errors introduced by the change.
3. Summarize the files changed and what was implemented.
4. Report commands run and their results.
5. Clearly list anything that still needs owner confirmation or manual testing.
6. Explain the next step in beginner-friendly language.

## 13. Project owner workflow and communication

The project owner is learning website development for the first time and is using AI-assisted tools, including Google Antigravity and Google Stitch.

- Give instructions in small, sequential steps.
- When asking the owner to use the terminal, provide the exact command and specify the terminal context (Windows PowerShell).
- For this Windows setup, use `npm.cmd` rather than `npm` when invoking npm from PowerShell.
- Explain what a command does before asking the owner to run it.
- Do not assume the owner knows Git, React, Vite, Tailwind, routing, environment variables, or deployment terminology.
- Do not ask the owner to run several risky or unrelated commands at once.
- Wait for confirmation or command output before proceeding when the next step depends on it.
- When creating or editing files, state the exact file path.
- Keep the owner in control of design approval, business claims, promotions, menu details, and deployment.

## 14. Project paths and environment

The project workspace is on Windows:

`D:\Burmese Harp Inc\Projects\BurmeseHarpWeb`

The parent directory `D:\Burmese Harp Inc` is the main folder for Burmese Harp restaurant files.

The project owner opens this folder through **Google Antigravity → File → Open Folder**. On this machine, the `code` command opens Visual Studio Code, not Antigravity; do not use `code` as the assumed method for opening the Antigravity workspace.

Current environment reported by the owner:

- Google Antigravity: installed
- Node.js: `v26.13.0`
- npm: `11.20.0` (run as `npm.cmd` in PowerShell)
- NVM for Windows: `1.2.2`
- Git: `2.49.0.windows.1`

These versions describe the setup at the time this file was created and may change.

---

**Guiding principle:** Build a distinctive, accurate, fast, accessible, maintainable website for Burmese Harp. Keep the first version simple, make business facts verifiable, and explain the work so the project owner can learn and confidently maintain it.
