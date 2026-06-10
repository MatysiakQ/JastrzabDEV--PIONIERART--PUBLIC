# PionierART

![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-Enabled-blue)
![Vite](https://img.shields.io/badge/Vite-6-purple)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38BDF8)

## Overview

PionierART is a commercial website created for an event production company specializing in technical support for concerts, festivals, conferences, and large-scale events.

The project focuses on presenting services, showcasing company capabilities, and providing a clear contact path for potential clients through a modern, responsive, and animation-driven user experience.

### Live Website

https://pionierart.vercel.app/

---

## Business Context

The website was developed to present the company's event production services and improve communication with potential customers.

The primary goals of the website are:

- Service presentation
- Brand visibility
- Portfolio showcase
- Lead generation through contact forms and direct communication channels

---

## Features

### Homepage

- Hero section
- Service presentation
- Company information
- Portfolio showcase
- Partners section
- Contact section
- Call-to-action sections

### Service Pages

Dedicated pages for:

- Stage Lighting
- Sound Systems
- Multimedia Solutions
- Stage Structures
- Power Generators

### Contact Experience

- Contact form
- Client-side validation
- Email-based inquiry submission
- Direct phone contact
- Social media links

### User Experience

- Responsive layout
- Animated transitions
- Scroll-based interactions
- Intro animation
- Cookie consent banner
- Legal information modals

---

## Tech Stack

### Frontend

- React 18
- TypeScript
- React Router
- Vite
- Tailwind CSS

### UI & Animation

- Motion
- Radix UI
- Material UI
- Lucide React

### Additional Libraries

- React Helmet Async
- React Hook Form
- Sonner
- Embla Carousel
- React Slick
- Recharts

---

## Architecture

The application follows a component-based React architecture.

```text
App
│
├── Router
│
├── Pages
│   ├── HomePage
│   └── ...
│
├── Reusable Components
│
├── Shared UI Components
│
└── Styling System
```

---

## Key Technical Implementations

### Route-Based Navigation

The website uses React Router to manage navigation between service pages and the homepage.

### Reusable Service Page Structure

Individual service pages are implemented using reusable patterns to maintain consistency across the website.

### SEO Management

Dedicated SEO components are used to manage page metadata.

### Animation System

Motion is used throughout the application to create transitions, interactive effects, and section reveals.

### Cookie Consent Persistence

Cookie preferences are stored locally using browser storage.

### Form Validation

The contact form validates user input before submission.

---

## Project Gallery

### Homepage

Add screenshot here.

```text
/docs/screenshots/homepage.png
```

### Services

Add screenshot here.

```text
/docs/screenshots/services.png
```

### Contact Section

Add screenshot here.

```text
/docs/screenshots/contact.png
```

### Mobile Version

Add screenshot here.

```text
/docs/screenshots/mobile.png
```

---

## Demonstration

### Live Website

https://pionierart.vercel.app/

---

## Project Structure

```text
.
├── public
│   └── logo.png
│   └── ...
│
├── src
│   ├── app
│   │   ├── App.tsx
│   │   ├── routes.tsx
│   │   │
│   │   ├── components
│   │   │   ├── HeroNew.tsx
│   │   │   ├── ServicesNew.tsx
│   │   │   ├── ContactNew.tsx
│   │   │   └── ...
│   │   │
│   │   └── pages
│   │       ├── HomePage.tsx
│   │       ├── AgregatyPage.tsx
│   │       ├── MultimediaPage.tsx
│   │       └── ...
│   │
│   ├── assets
│   └── ...
│
├── index.html
├── package.json
└── vite.config.ts
```

---

## Source Code Availability

Source code is private due to commercial and intellectual property reasons.

---

## Author

**Adam Jastrzębski**

Frontend Developer

---

## Acknowledgements

This repository includes components based on:

- shadcn/ui
- Radix UI

See `ATTRIBUTIONS.md` for additional information.
