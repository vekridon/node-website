# node-website Professional Services Portfolio Website

## Overview

This is a modern full-stack web application for a professional services portfolio website featuring Vek Ridon's digital services. The application combines a React frontend with an Express.js backend, showcasing web development, mobile solutions, and digital consulting services. The site includes a highly visible AI-powered chat widget for visitor interaction and a contact form for lead generation.


## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern development practices
- **Styling**: Tailwind CSS with shadcn/ui component library for consistent, professional design
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack Query for server state management and caching
- **Build Tool**: Vite for fast development and optimized production builds
- **UI Components**: Comprehensive shadcn/ui component system with Radix UI primitives

### Backend Architecture
- **Runtime**: Node.js with Express.js framework for RESTful API endpoints
- **Language**: TypeScript with ES modules for modern JavaScript development
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Session Storage**: PostgreSQL-backed sessions using connect-pg-simple
- **Development**: Hot module replacement and error overlay for development experience

### Data Storage Solutions
- **Primary Database**: PostgreSQL hosted on Neon for scalable cloud database
- **ORM**: Drizzle ORM with schema-first approach and automatic TypeScript generation
- **Schema Design**: Three main entities - users, contacts, and chat sessions
- **Migrations**: Drizzle Kit for database schema migrations and management
- **Fallback Storage**: In-memory storage implementation for development/testing

### Authentication and Authorization
- **Session Management**: Express sessions with PostgreSQL storage backend
- **Security**: CORS enabled, JSON parsing middleware for secure data handling
- **Development Features**: Request logging and error handling middleware

## External Dependencies

### Third-Party Services
- **OpenAI API**: GPT-4 integration for intelligent chat responses with professional context
- **Neon Database**: Serverless PostgreSQL hosting for production database
- **Unsplash**: Professional stock photography for visual content

### Key Libraries and Frameworks
- **Frontend**: React, TanStack Query, Wouter, Tailwind CSS, shadcn/ui, Radix UI
- **Backend**: Express.js, Drizzle ORM, connect-pg-simple, Zod for validation
- **Development**: Vite, TypeScript, ESBuild
- **UI Components**: Comprehensive set including forms, dialogs, navigation, charts, and data display
- **Utilities**: date-fns for date handling, clsx for conditional styling, nanoid for ID generation
