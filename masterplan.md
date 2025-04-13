App Overview and Objectives

Ojha is a web-based platform built to streamline the design collaboration process between freelance designers and their clients. It consolidates project briefs, moodboards, feedback, and revisions into a minimal, elegant workspace. The goal is to reduce messy email chains and scattered feedback by giving designers a centralized, intuitive hub for visual communication.

Target Audience

Primary: Freelance Designers

Secondary: Design Clients (by invitation)

Tertiary (future): Small Creative Agencies

Core Features and Functionality

Homepage: Overview of Ojha's value prop, visual walkthrough, sign-up CTA for designers.

Designer Dashboard: Filterable list of projects, activity feed, project statuses.

Project View: Split into Brief, Moodboard, and Revisions tabs.

Feedback System: General + pinned comments, threaded replies, status (unread, resolved, etc.).

Client View: Access to invited projects only, view/upload content, give approvals.

Brief Management: Template-based brief creation and approval workflow.

Revision History: Timeline view of previous design versions.

Notification System: Email + in-app alerts.

AI Feedback (Designer-only): Accessibility, layout, grammar suggestions using LLM.

High-Level Technical Stack Recommendations

Frontend: Next.js 14 + Tailwind CSS + shadcn/UI

Backend & Storage: Supabase (Postgres DB, file storage, real-time, auth)

CMS (optional): Notion or Sanity (for help docs and templates)

Authentication: Supabase email/password; client access via invitation-only

Conceptual Data Model

User: Designer or Client (with role-based permissions)

Project: Linked to Designer and Client; contains brief, files, moodboard, status

Brief: Text + uploaded files, generated via template form

Feedback: Comment threads, pins, statuses, linked to design files

Revision: Uploaded design versions, tagged and time-stamped

Notification: Tracked by user, project, and read status

User Interface Design Principles

Mobile-first layout

Card-based dashboard with clean hierarchy

Minimalist color palette: Primary #2D2DFF, Accent #FA709A, whites/grays background

Font: Inter, used consistently across all screens

Use of whitespace and light shadows to create breathing room

Accessible, with alt text, readable font sizes, and color contrast

Security Considerations

Role-based access control (designers vs. clients)

Secure file uploads via Supabase

Invitation-based client onboarding

Activity logging for feedback/comments

Private-by-default AI suggestions

Development Phases or Milestones

MVP (Free Tier)

Core pages: Dashboard, Project View, Feedback, Brief

Invite system, auth, up to 5 projects per designer

Notifications and revision history

V1 Launch

AI design feedback

Moodboard gallery view

Notification center UI

More brief templates

V2+ Expansion

Paid plans (project limits, AI features, white-label branding)

Team access for small agencies

Client-side analytics

Potential Challenges and Solutions

Real-time feedback updates: Use Supabase real-time subscriptions

Comment pin placement UI: Use canvas overlays and coordinate tracking

File versioning: Tag + time-stamp uploads, show diffs in timeline

Client onboarding friction: Streamline invitation flow with magic links

Future Expansion Possibilities

Add Figma/Adobe integrations

Designer portfolio export from project pages

Shared style guides for client teams

Plugin/extension for feedback inside design tools

