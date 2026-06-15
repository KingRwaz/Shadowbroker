# Technical Repositories Toolkit

## Purpose

This toolkit identifies practical open-source repository categories that can support the AFCON 2027 Rachael Nanyonjo culture/tourism workstream if it develops into real events, pop-ups, portfolio pages, RSVP systems, tourism maps or cafe-arts pilots.

This file does not require immediate software development. It gives a practical technical roadmap for later implementation.

---

## Recommended Digital Stack

### 1. Portfolio and Professional Landing Page

Purpose:

- Present Rachael's AFCON-facing profile.
- Show her website, credits, concept note, video introduction and areas of contribution.
- Provide a clean contact form or inquiry button.

Possible repository direction:

- Next.js portfolio templates.
- Creative portfolio landing pages.
- Static sites deployable on Vercel, Netlify or GitHub Pages.

Suggested sections:

- Hero: AFCON 2027 Cultural Programming & Movement Direction Consultant.
- About Rachael.
- Areas of contribution.
- Selected work.
- AFCON concept.
- Contact.

---

### 2. Event RSVP and Ticketing System

Purpose:

- Manage pilot events such as Uganda Cultural Welcome Night, Cafe Arts Pop-Up, Diaspora Creative Reception or Football Meets Culture Showcase.
- Track RSVPs and guest lists.
- Support check-in where needed.

Possible repository direction:

- Open-source event platforms such as Hi.Events, Attendize, Eventmie or similar tools.

Use cases:

- Free RSVP events.
- Private guest-list events.
- Paid cultural showcases.
- Sponsor/VIP registration.
- Volunteer registration.

Implementation note:

Start with simple Google Forms or Airtable if the event is small. Move to open-source ticketing only when the event becomes serious enough to need check-in, ticket tiers or guest management.

---

### 3. Outreach CRM and Contact Tracker

Purpose:

- Track contacts across tourism, culture, hotels, sponsors, event companies, official bodies and diaspora networks.

Simple option:

- Use the included CSV tracker.

Advanced option:

- Convert the CSV into Airtable, Notion, Google Sheets or a small CRM later.

Core fields:

- Category.
- Institution.
- Contact person.
- Role.
- Email.
- Phone.
- Warm introduction.
- Opportunity type.
- Priority.
- Date contacted.
- Follow-up date.
- Status.
- Notes.

---

### 4. Cultural Tourism Map

Purpose:

- Map cafes, hotels, galleries, museums, craft markets, music venues, cultural centres and event spaces relevant to AFCON visitors.

Possible repository direction:

- Leaflet.js or React Leaflet mapping templates.
- OpenStreetMap-based attraction maps.

Use cases:

- Visitor cultural map.
- Cafe arts venue map.
- Diaspora welcome route.
- Match-day cultural trail.

Simple first version:

- Google My Maps or a spreadsheet of venues.

Advanced version:

- Interactive web map with categories, filters and venue cards.

---

### 5. Volunteer and Performer Registration

Purpose:

- Collect dancers, performers, artists, ushers, photographers, volunteers and vendors for pilot activations.

Simple option:

- Google Forms.

Advanced option:

- Form backend plus database.
- Event platform registration module.
- Airtable-style database.

Fields:

- Name.
- Role.
- Skill.
- Phone.
- Email.
- Portfolio link.
- Availability.
- Location.
- Experience.
- Consent for contact.

---

### 6. Documentation and Reporting System

Purpose:

- Capture lessons from meetings, venue visits, pilot events and stakeholder conversations.

Tools:

- Markdown files in this repository.
- Google Drive folder.
- Notion or Obsidian.
- Photos and videos organised by date/event.

Required reports:

- Meeting notes.
- Venue observation sheets.
- Event learning reports.
- Cafe arts feasibility notes.
- Visitor feedback summaries.

---

## Suggested Repository Structure

```text
docs/afcon-2027-rachael-workpack/
  README.md
  01-one-page-profile.md
  02-formal-introduction-letter.md
  03-concept-note-afcon-cultural-experience.md
  04-outreach-tracker.csv
  05-30-90-day-action-plan.md
  06-cafe-arts-space-learning-brief.md
  07-technical-repositories-toolkit.md
  08-meeting-questions-and-script.md

apps/
  rachael-afcon-portfolio/
  afcon-cultural-rsvp/
  cultural-tourism-map/

data/
  contacts/
  venues/
  performers/
  events/

reports/
  meeting-notes/
  venue-observations/
  pilot-event-reports/
```

---

## Technical Development Sequence

### Phase 1: No-Code First

Use:

- One-page profile PDF.
- Google Drive folder.
- Google Sheets contact tracker.
- Google Forms RSVP.
- Existing Rachael website.

### Phase 2: Light Web Presence

Build:

- A simple AFCON-facing landing page.
- Contact form.
- Downloadable concept note.
- Embedded intro video.

### Phase 3: Pilot Event System

Add:

- RSVP form.
- Guest list export.
- QR code or simple check-in.
- Event page.
- Post-event feedback form.

### Phase 4: Cultural Tourism Map

Add:

- Map of venues.
- Categories: cafes, galleries, hotels, museums, craft markets, music venues, theatres.
- Visitor-friendly descriptions.

### Phase 5: Full Cafe Arts Platform

Add:

- Event calendar.
- Artist profiles.
- Booking requests.
- Ticketing.
- Membership or mailing list.
- Tourism partner listings.

---

## Governance and Safety Notes

- Do not use official AFCON logos or marks unless permission is granted.
- Do not imply official AFCON partnership unless formally approved.
- Protect personal data collected from RSVPs or performers.
- Use consent forms for photography, video and performer listings.
- Keep payment handling transparent and documented.
- Verify all official opportunities through trusted channels.

---

## Immediate Recommendation

Do not build heavy software yet. First use the workpack to secure interest, meetings or a pilot opportunity. Once a partner or event is real, choose the simplest technology needed to support that specific use case.
