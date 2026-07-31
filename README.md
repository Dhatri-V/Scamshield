# ScamShield

![Status](https://img.shields.io/badge/status-phase%201-blue)
![Frontend](https://img.shields.io/badge/frontend-HTML%20%26%20CSS-brightgreen)
![Roadmap](https://img.shields.io/badge/roadmap-active-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

ScamShield is a consumer-focused cyber safety platform that helps students, families, and everyday users identify, understand, and avoid online scams.

## Problem Statement

Online scams are becoming more frequent, more convincing, and more targeted. Many users struggle to tell the difference between a legitimate message and a malicious one, especially when scams imitate banks, job recruiters, delivery services, government agencies, or family contacts.

ScamShield is being built to reduce that confusion by providing a user-friendly platform that makes scam awareness and scam-checking easier to access for non-technical users.

## Vision

ScamShield aims to grow from a simple educational frontend into a production-grade cyber safety platform that helps users:

- analyse suspicious messages
- check suspicious URLs
- verify job and internship offers
- identify fake payment or urgency-based requests
- search reported scam patterns
- report scams safely
- learn how common scam tactics work

The long-term goal is to combine a clean user experience with modern web technologies, machine learning, and cybersecurity data integrations.

## Key Planned Features

The following features are part of the product vision and are not yet implemented:

- Suspicious text and message review workflow
- Suspicious URL checking workflow
- Job and internship scam verification
- Scam reporting interface and case tracking
- Searchable scam knowledge base
- Scam education hub for students and families
- Machine learning-assisted scam classification
- External cybersecurity API integrations for scam intelligence

## Current Progress

ScamShield is currently in its first development phase.

Implemented today:

- Initial landing page created with semantic HTML and shared CSS
- Responsive layout for desktop and mobile
- Beginner-friendly structure and reusable styling foundation
- Clear homepage sections for tools, scam categories, safety tips, and family-focused awareness

Not implemented yet:

- Functional scam analysis
- Backend services
- Database
- Authentication
- API integrations
- Machine learning pipeline
- Additional multi-page content beyond the first landing page structure

## Planned Tech Stack

This section separates the current stack from the future production stack.

### Current

- HTML5
- CSS3

### Planned

- MongoDB
- Express.js
- React
- Node.js
- Machine Learning models for scam detection support
- External cybersecurity and reputation APIs

## Development Roadmap

### Phase 1: Foundation

- [x] Create repository and project vision
- [x] Build initial landing page with HTML and CSS
- [x] Establish shared visual style and homepage structure
- [ ] Create remaining static pages for core flows
- [ ] Add assets, icons, and content sections for all planned pages

### Phase 2: Frontend Expansion

- [ ] Convert static pages into a complete multi-page frontend
- [ ] Improve accessibility, consistency, and responsive polish
- [ ] Add reusable UI patterns for forms, cards, alerts, and navigation

### Phase 3: MERN Application

- [ ] Set up React frontend architecture
- [ ] Build Express and Node.js backend
- [ ] Design MongoDB data models
- [ ] Add authentication and protected user workflows

### Phase 4: Intelligence Features

- [ ] Integrate suspicious URL and reputation data sources
- [ ] Add scam report storage and retrieval
- [ ] Introduce machine learning-assisted message and scam analysis
- [ ] Build user-facing result pages and safety recommendations

### Phase 5: Production Readiness

- [ ] Testing, performance optimisation, and deployment
- [ ] Security hardening and monitoring
- [ ] Documentation, contribution guides, and release planning

## Project Folder Structure

Current repository structure:

```text
Scamshield/
├── css/
│   └── style.css
├── index.html
└── README.md
```

Planned structure as the static frontend grows:

```text
Scamshield/
├── assets/
│   ├── icons/
│   └── images/
├── css/
│   └── style.css
├── index.html
├── scan-text.html
├── scan-url.html
├── job-check.html
├── search.html
├── report-scam.html
├── learn.html
└── README.md
```

Note: only `index.html` and `css/style.css` are currently implemented from the planned frontend structure.

## Installation

The current version is a static HTML/CSS project, so no package manager or build step is required.

### 1. Clone the repository

```bash
git clone https://github.com/Dhatri-V/Scamshield.git
cd Scamshield
```

### 2. Open the landing page

Open `index.html` directly in your browser.

You can also use a simple local server if you prefer, but it is not required for the current version.

## Future Architecture

The planned long-term architecture is:

- React frontend for reusable interface components and user workflows
- Node.js and Express backend for platform logic and integrations
- MongoDB for scam reports, educational content metadata, and user data
- Machine learning layer for scam classification assistance
- External cybersecurity APIs for URL reputation, phishing intelligence, and risk signals

This architecture is part of the roadmap and is not implemented in the current repository state.

## Contributing

Contributions, ideas, and feedback are welcome.

If you would like to contribute in the future:

1. Fork the repository
2. Create a feature branch
3. Make focused, well-documented changes
4. Open a pull request with a clear description

For now, the project is still in an early foundation stage, so contribution standards and issue templates may evolve as the codebase grows.

## License

This project is available under the MIT License.

You can add a `LICENSE` file later to formalise the license in the repository.
