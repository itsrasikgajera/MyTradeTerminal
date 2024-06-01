
![[Pasted image 20240223154855.png]]

### Problem

Papershift is a German HR SaaS company that helps businesses manage their employees' schedules, time tracking, and payroll. They built a ruby-on-rail monolith that was becoming increasingly difficult to maintain and scale. They wanted to migrate to domain-driven design and build a new frontend from scratch.

### Solution

Built a new front-end using Vue.js and TypeScript. Used Vercel for deployment and GitHub Actions for CI/CD. Built a design system using Tailwind and Storybook. Used Chromatic for visual regression testing and Playwright for end-to-end testing. Also used Sentry and New Relic for observability.

### Value Delivered

The new frontend is faster, more performant, and easier to maintain. It is also more accessible and has a better user experience than the previous frontend. It is also easier to onboard new developers to the project.

### Tech Stack

- Frontend
    - Vue.js 3
    - Tailwind
    - Vuex -> Pinia
    - TypeScript
    - Storybook
- Build
    - pnpm
    - webpack
- Infra
    - GitHub Actions CI/CD
    - Vercel
- Testing
    - Playwright (E2E)
    - Jest (Unit)
    - Chromatic (visual regression)
- Observability
    - Sentry
    - NewRelic