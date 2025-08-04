# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Beeda is a private network landing page for Venture Capitalists and Founders participating in exclusive events in Delhi, Mumbai, and Bengaluru.

## Project Status

This is a new project in initial development phase. The following sections will be updated as the codebase develops.

## Common Development Commands

*To be added once the technology stack is chosen and build system is set up*

### Likely commands (to be confirmed):
- Build: `npm run build` or `yarn build`
- Development server: `npm run dev` or `yarn dev`
- Lint: `npm run lint` or `yarn lint`
- Format: `npm run format` or `yarn format`
- Test: `npm test` or `yarn test`

## Architecture and Structure

*To be defined as the project develops*

### Expected Structure for a Landing Page:
```
/src
  /components     - Reusable UI components
  /pages          - Page components
  /styles         - Global styles and themes
  /assets         - Images, fonts, and static assets
  /utils          - Utility functions
  /hooks          - Custom React hooks (if using React)
  /lib            - Third-party integrations
```

## Key Considerations

1. **Private Network**: This is for exclusive events, so authentication/access control will likely be important
2. **Multi-City Support**: The app needs to handle events in Delhi, Mumbai, and Bengaluru
3. **Target Audience**: VCs and Founders - expect professional, polished UI/UX
4. **Event Management**: Will likely need event listing, registration, and RSVP functionality

## Technology Recommendations

For a modern landing page with the stated requirements, consider:
- **Frontend Framework**: React/Next.js, Vue/Nuxt, or Astro
- **Styling**: Tailwind CSS for rapid development
- **Authentication**: NextAuth, Auth0, or similar for access control
- **Database**: PostgreSQL or MongoDB for event and user data
- **Deployment**: Vercel, Netlify, or AWS for reliable hosting

## Development Workflow

1. Always check existing patterns before adding new code
2. **ALWAYS reference style-guide.html when working with UI components, colors, or styling**
3. Follow the established code style once it's defined
4. Test authentication flows thoroughly given the private nature
5. Ensure responsive design for mobile and desktop users
6. Optimize for performance - VCs and Founders expect fast, professional experiences

## Style Guide Reference

When working on any UI-related tasks:
- Open and reference `/style-guide.html` for the complete design system
- Use the defined color palette (Deep Purple #4C1D95 as primary, Luxury Gold #D4AF37 as accent)
- Follow the typography system (Playfair Display for headings, Inter for body)
- Use the pre-designed components and patterns shown in the style guide

This file will be updated as the project architecture and conventions are established.