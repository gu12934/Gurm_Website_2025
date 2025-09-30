# Gurm_Website_2025
A website made with html, css, js for static for github pages and adding certain features

https://gu12934.github.io/Gurm_Website_2025/

# Overview

This is a personal portfolio website for Gurmol Sohi, a Canadian data analyst and researcher based in Calgary. The application is built as a full-stack web application showcasing Gurmol's professional journey, projects, experience, and providing a way for visitors to contact him. The site features a modern, responsive design with multiple pages including Home, Projects, Experience, About, and a contact form functionality.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React with TypeScript using Vite as the build tool
- **Routing**: Client-side routing implemented with Wouter for lightweight navigation
- **UI Components**: Built using shadcn/ui component library with Radix UI primitives
- **Styling**: Tailwind CSS for utility-first styling with custom CSS variables for theming
- **State Management**: TanStack Query (React Query) for server state management and API calls
- **Form Handling**: React Hook Form with Zod validation for type-safe form management

## Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules
- **API Design**: RESTful API endpoints for contact form submission and data retrieval
- **Middleware**: Custom logging middleware for API request tracking
- **Error Handling**: Centralized error handling with proper HTTP status codes

## Data Storage Solutions
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Database Provider**: Neon Database (serverless PostgreSQL)
- **Schema Management**: Drizzle Kit for migrations and schema changes
- **Development Storage**: In-memory storage implementation for development/testing
- **Data Models**: User and Contact entities with proper TypeScript typing

## Authentication and Authorization
- **Current State**: Basic user schema exists but no authentication is currently implemented
- **Session Management**: Express session configuration ready with PostgreSQL session store
- **Future Implementation**: Ready for session-based authentication with secure cookie handling

## External Dependencies
- **Database**: Neon Database serverless PostgreSQL instance
- **UI Library**: Radix UI primitives for accessible component foundations
- **Icons**: Lucide React for consistent iconography
- **Social Media Integration**: Links to LinkedIn, GitHub, Medium, YouTube, Topmate, and Tableau profiles
- **Development Tools**: Replit-specific plugins for development environment integration
- **Build Tools**: Vite with React plugin and ESBuild for production builds
