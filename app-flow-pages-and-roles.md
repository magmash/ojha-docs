# Ojha – App Flow, Pages, and Roles

## 👤 User Roles
### 1. **Designer (Primary User)**
- Create and manage projects
- Invite clients via email
- Upload files, add/edit briefs, manage moodboards
- Receive and respond to feedback
- View AI suggestions (private by default)
- Access up to 5 projects (in free tier)

### 2. **Client (Invited Only)**
- Join projects via invitation link
- View briefs, moodboards, revisions
- Leave feedback (general and pinned)
- Contribute to brief/moodboard pre-approval
- Approve brief and designs

## 🗺️ App Flow Summaries

### Flow 1: Client Leaves Feedback
1. Client receives link to new design version
2. Opens design in Revision tab
3. Leaves general or pinned comment
4. Designer receives notification
5. Comment appears in threaded sidebar with status (unread → read → resolved)

### Flow 2: Designer Uploads Revision
1. Designer uploads new design file(s)
2. Optionally adds message
3. System updates revision timeline
4. Client receives notification
5. File appears in Revision tab, viewable with comment overlay

### Flow 3: Designer Invites Client
1. Designer enters email in Project Settings
2. System sends branded invitation email with link
3. Client signs up and is auto-directed to project

## 🧭 Core Pages Breakdown

### 1. **Homepage**
- Hero section with value prop
- Visual walkthrough (how it works)
- Sign up / Log in CTAs (designers only)

### 2. **Dashboard (Designer Only)**
- Project cards (title, status, client)
- Filters: by client, status, due date
- Activity feed (latest comments, uploads, approvals)

### 3. **Project View (Designer + Client)**
- Split-tab layout: Brief | Moodboard | Revisions
- Brief tab: editable until approved, comment support
- Moodboard tab: grid of reference images, captions
- Revisions tab: upload viewer, feedback tools, revision history

### 4. **Design Viewer**
- Shows uploaded design file
- Toggle overlay to show/hide pins
- Sidebar with threaded comments
- Version switcher (compare current vs. previous)

### 5. **Brief Form Page**
- Dynamic form based on design type (e.g., Logo, Poster)
- Markdown-style fields and file uploads
- Approval button locks brief

### 6. **Client View (Limited Access)**
- Access to only invited projects
- No ability to create new projects
- Focus on collaboration, review, and approvals

### 7. **Notification Center**
- Bell icon dropdown
- Unread/read tabs
- Links to new feedback, uploads, and approvals

## 🧩 Key Reusable UI Components
- Project Card (with status badge + timestamp)
- File Uploader (drag-and-drop + preview)
- Feedback Tools (pin, thread, resolve/delete)
- Revision History Viewer (timeline layout)
- Moodboard Grid (sortable, taggable)
- Brief Editor Form (template-driven)

