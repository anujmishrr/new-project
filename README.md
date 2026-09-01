# BDSMM College Website

### Budhni Devi Smarak Mahila Mahavidyalaya · Risiya, Bahraich, Uttar Pradesh

> **A modern, accessible and responsive digital platform for a higher-education institution — designed to connect students, families, faculty and the wider community with trusted college information.**

---

## ✦ Overview

**BDSMM College Website** is a professionally designed institutional website for **Budhni Devi Smarak Mahila Mahavidyalaya (BDSMM), Risiya, Bahraich, Uttar Pradesh**.

The platform provides a centralized digital experience where prospective students, parents, current students, faculty and visitors can explore the college, academic programmes, admission information, notices, student support, campus activities, leadership, committees and contact resources.

The project is built as a **frontend-first, content-driven React application** with a strong focus on:

* Modern institutional design
* Accessibility
* Responsive behaviour
* Bilingual content
* Clear information architecture
* Maintainable content management
* Performance-conscious frontend architecture
* Static hosting compatibility
* Honest user interactions without pretending to provide backend functionality

---

## ✨ Key Highlights

| Area            | Capability                                              |
| --------------- | ------------------------------------------------------- |
| 🎓 Institution  | College profile, leadership & institutional information |
| 📚 Academics    | Programmes, courses & academic resources                |
| 📝 Admissions   | Admission information & enquiry experience              |
| 📢 Notices      | Searchable and filterable public notices                |
| 👩‍🏫 Faculty   | Teaching & non-teaching staff directory                 |
| 🏛️ Campus      | Campus life, activities & institutional initiatives     |
| 🖼️ Gallery     | Filterable gallery with accessible lightbox             |
| 📄 Resources    | Public documents and useful resources                   |
| 🌐 Languages    | English + Hindi presentation                            |
| 🔎 Search       | Site-wide search across public content                  |
| 📱 Responsive   | Mobile, tablet & desktop optimized                      |
| ♿ Accessibility | Keyboard navigation, focus states & reduced motion      |
| 🚀 Deployment   | Compatible with modern static hosting                   |

---

# 🎯 Project Goals

The website is designed around five primary objectives:

### 01 — Discoverability

Help students and visitors quickly find the information they need without navigating through complicated institutional pages.

### 02 — Trust

Present college information in a clear, professional and consistent digital environment.

### 03 — Accessibility

Make the website usable across devices and for users who rely on keyboard navigation, visible focus indicators and reduced-motion preferences.

### 04 — Maintainability

Keep frequently changing college information centralized so authorized editors can update content without restructuring the entire application.

### 05 — Scalability

Provide a clean frontend foundation that can later be connected to approved backend services, CMS platforms, admission systems or institutional APIs.

---

# 🧩 Core Features

## Responsive Institutional Experience

The interface is designed for:

* 📱 Mobile phones
* 📲 Tablets
* 💻 Laptops
* 🖥️ Desktop displays

Layouts, typography, navigation and interactive components adapt across screen sizes.

---

## 🌐 Bilingual Interface

The website supports both:

**English**
and
**हिन्दी**

This allows the institution to communicate effectively with a wider student and community audience.

---

## 🎞️ Accessible Hero Carousel

The homepage includes an editorial-style carousel featuring:

* Multiple slides
* Navigation controls
* Pause functionality
* Keyboard accessibility
* Reduced-motion support
* Responsive presentation

The carousel is intentionally designed to remain usable rather than functioning only as a visual decoration.

---

## 🧭 Responsive Navigation

The navigation system provides:

* Desktop navigation
* Keyboard-friendly dropdowns
* Mobile navigation
* Clear active states
* Accessible interaction patterns
* Structured information hierarchy

---

## 🔎 Global Search

Visitors can search across public institutional information including:

* Notices
* Academic programmes
* Staff
* Public resources
* Other indexed website content

The goal is to make information retrieval significantly faster for prospective students and visitors.

---

## 📢 Notice Management

The notice experience supports:

* Notice listing
* Category filtering
* Search
* Date-based information
* Public announcements
* Institutional updates

Content is maintained through the centralized site data layer.

---

## 👩‍🏫 Staff Directory

The staff directory supports structured presentation of:

* Teaching staff
* Non-teaching staff
* Designations
* Departments
* Public professional information

---

## 🖼️ Gallery

The gallery provides:

* Category filtering
* Responsive image grids
* Accessible lightbox viewing
* Keyboard-friendly interaction
* Metadata-driven gallery content

---

## 🎓 Academic & Admission Pages

Dedicated sections provide a structured experience for:

* Academic programmes
* Course information
* Admission guidance
* Eligibility information
* Institutional resources
* Student-facing information

> **Important:** Admission rules, fees, eligibility, dates and other official information should always be verified with the college before publication.

---

## 🏛️ Institutional Pages

The website includes dedicated areas for:

* About the college
* Leadership
* Academic programmes
* Student life
* Committees
* Notices
* Resources
* Gallery
* Contact information

---

# ♿ Accessibility

Accessibility is treated as a core part of the interface rather than an afterthought.

The project includes:

* Skip-to-content navigation
* Semantic page structure
* Keyboard-friendly interactions
* Visible focus states
* Accessible interactive controls
* Pauseable carousel behaviour
* Reduced-motion support
* Responsive typography
* Mobile-friendly navigation

The objective is to provide a more inclusive experience for students, families and visitors.

---

# 🛡️ Honest Frontend Interactions

The current project intentionally **does not pretend to have backend functionality**.

Contact and admission enquiry forms currently provide an on-screen interaction state only.

They do **not**:

* Store submissions
* Send emails
* Create database records
* Authenticate users
* Process applications

Before using these forms operationally, connect them to an approved backend or form-processing service.

---

# 🏗️ Technology Stack

The project uses a modern frontend stack:

| Technology       | Purpose                                |
| ---------------- | -------------------------------------- |
| **React**        | UI architecture                        |
| **TypeScript**   | Type-safe development                  |
| **Vite**         | Development & production build tooling |
| **Wouter**       | Lightweight client-side routing        |
| **Tailwind CSS** | Responsive UI styling                  |
| **Lucide React** | Interface icons                        |
| **Google Fonts** | Typography                             |

### Architecture Philosophy

The application follows a lightweight architecture focused on:

**Components → Pages → Centralized Content → Client-side Routing**

No database or server API is required for the current public website experience.

---

# 📁 Project Structure

```text
artifacts/
└── bdsmm-college-website/
    │
    ├── public/
    │   ├── favicon.svg
    │   └── robots.txt
    │
    ├── src/
    │   │
    │   ├── data/
    │   │   └── site.ts
    │   │       └── Centralized editable college content
    │   │
    │   ├── pages/
    │   │   └── not-found.tsx
    │   │
    │   ├── App.tsx
    │   │   └── Application shell, routes & interactions
    │   │
    │   ├── index.css
    │   │   └── Theme, responsive styling & accessibility
    │   │
    │   └── main.tsx
    │       └── Application entry point
    │
    ├── index.html
    ├── package.json
    ├── tsconfig.json
    └── vite.config.ts
```

---

# 📝 Content Architecture

College content is intentionally centralized in:

```text
src/data/site.ts
```

This makes routine institutional updates easier to manage.

The following information can be edited from the central data layer:

* College name
* Location
* Contact information
* Notices
* Academic programmes
* Faculty
* Non-teaching staff
* Public documents
* Gallery metadata
* Navigation links
* Footer links
* Institutional information

### Content Verification

Any information that has not been supplied as an officially verified college fact is treated as **editable/placeholder content**.

Before production publication, the college office should verify:

* Official contact numbers
* Email addresses
* Admission dates
* Course information
* Fees
* Faculty details
* Committee information
* Notices
* Documents
* Address
* Social media links
* Other institutional claims

---

# 🚀 Getting Started

## Prerequisites

Make sure the development environment has:

* Node.js
* pnpm

installed and available from the terminal.

---

## Installation

From the repository root:

```bash
pnpm install
```

---

## Development Server

Start the development environment with:

```bash
PORT=5173 BASE_PATH=/ pnpm --filter @workspace/bdsmm-college-website run dev
```

The development server will run on:

```text
http://localhost:5173
```

In a Replit environment, use the configured website workflow so that the appropriate preview path and port are supplied automatically.

---

# 🧪 Type Checking

Run the TypeScript validation command:

```bash
pnpm --filter @workspace/bdsmm-college-website run typecheck
```

A successful result confirms that the project passes the configured TypeScript checks.

---

# 📦 Production Build

Generate the production build:

```bash
PORT=5173 BASE_PATH=/ pnpm --filter @workspace/bdsmm-college-website run build
```

The compiled application will be generated inside:

```text
dist/public/
```

---

# ☁️ Static Deployment

This project is designed to work with static hosting.

After creating a production build, deploy the contents of:

```text
dist/public/
```

to your hosting provider.

### SPA Routing Requirement

The application uses client-side routes such as:

```text
/about
/courses
/admissions
/notices
/contact
```

The hosting environment must therefore serve:

```text
index.html
```

as the fallback for application routes.

If your hosting provider does not automatically support SPA fallback routing, configure its documented rewrite/redirect rules accordingly.

---

# 🔐 Security & Privacy

This is a client-side application.

Anything included in frontend assets can potentially be delivered to website visitors.

### Never place the following inside frontend source files:

```text
❌ Passwords
❌ API keys
❌ Private credentials
❌ Database credentials
❌ Authentication secrets
❌ Private student information
❌ Sensitive institutional records
```

Public-facing content should contain only information that the institution is comfortable publishing online.

---

# 📬 Forms & Future Backend Integration

The current website intentionally operates without a backend.

If the college later requires operational forms, the frontend can be connected to an approved service or backend for:

```text
Admission Enquiries
       ↓
Form Validation
       ↓
Backend / Approved Form Service
       ↓
Database / Email / CRM
       ↓
College Administration
```

Any production integration should include appropriate:

* Validation
* Spam protection
* Rate limiting
* Privacy controls
* Data retention policies
* Access control
* Error handling

---

# 🗺️ Future Expansion

The current architecture can serve as a foundation for additional institutional systems.

Potential future modules include:

### Student Services

* Student login
* Student dashboard
* Attendance
* Results
* Certificates
* Academic calendar

### Admissions

* Online application
* Application tracking
* Document upload
* Admission status
* Applicant communication

### Administration

* Notice publishing
* Faculty management
* Document management
* Event management
* Gallery management

### Communication

* Email notifications
* SMS notifications
* WhatsApp integrations
* Push notifications
* Institutional announcements

These capabilities require appropriate backend infrastructure and should not be represented as available until they are actually implemented.

---

# 🎨 Design Principles

The website follows a modern institutional design language built around:

### Clarity

Important information should be easy to discover.

### Hierarchy

Content is organized according to the needs of students, families and visitors.

### Consistency

Typography, spacing, components and interactions follow a unified visual system.

### Accessibility

Interactive experiences should remain usable across devices and input methods.

### Trust

Institutional information should be presented professionally without misleading functionality or unverified claims.

### Maintainability

Content and presentation are separated wherever practical.

---

# 📊 Quality Checklist

Before production launch, verify:

* [ ] Official college information has been reviewed
* [ ] Contact information is correct
* [ ] Academic information is verified
* [ ] Admission information is verified
* [ ] Notices are current
* [ ] Staff information is approved
* [ ] Gallery images have appropriate usage rights
* [ ] Documents are publicly safe to distribute
* [ ] All navigation links work
* [ ] Mobile layout has been tested
* [ ] Desktop layout has been tested
* [ ] Keyboard navigation has been tested
* [ ] Reduced-motion behaviour has been tested
* [ ] SPA fallback routing is configured
* [ ] Production build completes successfully
* [ ] No secrets are included in frontend files
* [ ] Forms are connected to a real service before being used operationally

---

# 📌 Project Status

**Current status:** Frontend institutional website

**Architecture:** Static / client-side

**Backend:** Not required for current functionality

**Database:** None

**Authentication:** None

**External service dependency:** None required for the current experience

**Production forms:** Not connected

---

# 📄 License

No license has been selected for this project yet.

Before publicly distributing the repository, add a license that reflects the requirements of the college, project owner and any third-party assets used by the project.

---

# 🏫 About BDSMM

**Budhni Devi Smarak Mahila Mahavidyalaya (BDSMM)**
Risiya, Bahraich, Uttar Pradesh, India

This website is intended to provide a professional digital presence and a dependable public information platform for the institution.

> **Built with a focus on clarity, accessibility, maintainability and trust.**

---

<div align="center">

### BDSMM College Website

**Modern · Accessible · Responsive · Content-Driven**

Made for a better digital experience for students and the college community.

</div>
