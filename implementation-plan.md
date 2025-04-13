# Ojha – Implementation Plan

## Phase 1: MVP (Free Tier, Up to 5 Projects)

### ✅ Core Features to Build:
- Designer signup/login (email + password)
- Designer dashboard with project cards
- Project view (Brief, Moodboard, Revisions)
- Feedback system (general + pin-based comments)
- Brief creation and approval flow
- Client invite flow via email
- Notification system (email + in-app)
- File uploader and version tagging
- Mobile-first UI and design polish

### 📆 Suggested Timeline (6-8 Weeks)
**Week 1-2:**
- Set up project (Next.js + Supabase + Tailwind)
- Build auth system (role-based)
- Create dashboard + basic layout

**Week 3-4:**
- Build project pages (tabs: Brief, Moodboard, Revisions)
- Implement feedback system with pin overlay + threads
- Add file uploads, revision tagging, version history UI

**Week 5-6:**
- Set up email/in-app notifications
- Design moodboard gallery component
- Finalize brief templates and form logic

**Week 7-8:**
- Testing & QA
- Deploy to Vercel
- Create landing page with onboarding CTA

## Phase 2: V1 Launch (2-3 Weeks)
- Add AI design feedback (OpenAI API integration)
- Launch notification center UI
- Add multiple brief template options
- Polish invitation emails and onboarding UX

## Phase 3: V2+ Expansion (Ongoing)
- Add Stripe for paid plans
- Set designer project limits (enforced by backend)
- Enable white-label branding per project
- Add team roles (agency support)
- Admin view for monitoring usage

## Team Setup (Solo or Small Team)
- **Solo Dev Friendly**: All tools selected (Supabase, Tailwind, Next.js) support fast iteration
- **Optional Roles:**
  - Product Designer (for UI polish and templates)
  - Part-time QA/tester before launch
  - Content/Copy (for help docs, templates, emails)

## Optional Tasks & Integrations
- Help docs via Notion or Sanity
- Slack/Zapier integration for feedback alerts
- Exportable client reports (PDF summaries)
- Figma plugin for in-design feedback
- Accessibility validation tools for design uploads

