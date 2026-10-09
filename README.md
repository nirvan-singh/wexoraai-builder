WexoraAI Builder

An AI-powered full-stack application builder that helps users turn natural-language prompts into React applications, preview generated code, and iteratively improve their projects with AI assistance.

Overview

WexoraAI Builder combines AI-assisted code generation with an interactive development workspace. Users can describe an application, review generated files, inspect a live preview, and refine the result through conversational prompts.

This project is built on an existing open-source app-builder foundation and is being customized and extended with additional functionality.

Tech Stack

Framework: Next.js, React, TypeScript

Authentication: Clerk

Database: PostgreSQL with Supabase and Prisma

AI Integration: Google Gemini

Agentic Editing: Cline SDK

Live Preview: Sandpack

Styling: Tailwind CSS and Shadcn UI

Storage: Supabase Storage

Security and Rate Limiting: Arcjet

Core Capabilities

Prompt-based React application generation

Interactive code and live-preview workspace

AI-assisted code improvements

Error-assisted code regeneration

Persistent projects and conversation history

Image uploads for additional prompt context

Credit-based usage management

ZIP export of generated applications

Capabilities depend on the corresponding integrations being configured and operational.



Database

The application uses PostgreSQL through Supabase and Prisma. The current schema defines user and workspace data, including project messages and generated file information.

Development Roadmap

Customize the application branding and user experience

Improve project organization and workspace usability

Add and test useful AI-assisted development features

Strengthen error handling and configuration validation

Document setup, architecture, and testing