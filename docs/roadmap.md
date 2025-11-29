# Roadmap

## Week 1
- Set up core project repository, CI/CD, and basic development environment.
- Implement User & Account Management: Basic user registration and login for gym owner.
- Develop CRM Database: Define initial schema for Leads (contact info, source, status, initial message).
- Implement Lead Ingestion Engine: Basic webhook/API listener for receiving new messages (WhatsApp/Instagram, mock data or single channel MVP).
- Develop Lead Management Dashboard:
    - Display Lead Inbox/List View with captured leads.
    - Basic Lead Profile view displaying contact info, source, and initial message.
    - Implement Lead Status Tracking (New, Contacted) with a simple dropdown.
- Ensure end-to-end flow: New inquiry -> Captured lead in list -> View lead profile.
- Deploy a clickable demo environment.

## Weeks 2-4
- **Lead Ingestion Engine:**
    - Enhance WhatsApp & Instagram API integration for robust automated detection and import of new inquiries.
    - Implement error handling and logging for lead capture.
- **Lead Management Dashboard:**
    - Refine Lead Inbox/List View with advanced filtering and sorting options.
    - Expand Basic Lead Profile to include more details and edit functionality.
    - Implement Communication History Log for tracking interactions with each lead.
    - Add Manual Lead Categorization (Hot, Warm, Cold) functionality for gym owner.
- **CRM Database:**
    - Finalize database schema to support all MVP features, including communication history and manual categorization.
    - Implement data migration strategies as needed.
- **Notification & Reminders System:**
    - Develop Simple Follow-up Reminders: Allow manual scheduling of reminders for leads.
- **Reporting & Analytics Engine:**
    - Build Basic Reporting: Display number of new leads and converted leads over time.
- **User & Account Management:**
    - Implement password recovery and basic user settings.
- **ML Lead Scoring Service (Groundwork):**
    - Design data collection strategy for future ML models (e.g., logging lead interactions, status changes, manual categorizations). *Note: No ML model deployment in this phase, only data preparation.*

## Month 2-3
- **Infrastructure & Stability:**
    - Implement robust error logging, monitoring, and alerting systems.
    - Optimize database performance and ensure data integrity.
    - Enhance security measures (API keys, data encryption, input validation).
    - Set up scalable hosting environment (e.g., auto-scaling groups, load balancing).
    - Conduct performance testing and optimize critical paths.
- **User & Account Management:**
    - Implement Role-Based Access Control (RBAC) for different staff roles (if team collaboration is introduced).
    - Enhance user onboarding and account security features (e.g., 2FA).
- **Reporting & Analytics Engine:**
    - Develop Performance Analytics Dashboard: Visualize conversion rates, lead source effectiveness, and sales funnel.
    - Allow for custom date ranges and export options for reports.
- **Notification & Reminders System:**
    - Improve reminder management, including recurring reminders and different notification channels (email, in-app).
- **ML Lead Scoring Service:**
    - Research and develop initial AI-powered Lead Prioritization (Hot, Warm, Cold classification based on ML) model. *ML comes in here for automated lead categorization.*
    - Integrate the ML scoring service to automatically suggest lead categories within the dashboard.
    - Implement feedback mechanisms for gym owners to correct ML suggestions, improving model over time.
- **UI/UX Polishing:**
    - Conduct user testing and refine UI/UX across all modules for a seamless and intuitive experience.
    - Implement consistent design system and branding.
- **Communication Features:**
    - Develop Automated Follow-up Templates (pre-defined messages for WhatsApp/Instagram).
    - Implement Scheduled Message Sending for follow-ups via integrated channels.

## Task Backlog
- Customizable Lead Stages for different gym processes.
- Integration with other gym management software (e.g., for direct membership enrollment).
- Team Collaboration Features (assigning leads to staff, internal notes).
- Automated response suggestions for common inquiries using NLP/ML.
- A/B testing for lead capture forms or follow-up messages.
- Mobile application for gym owners/staff.
- Support for additional communication channels (e.g., SMS, email).
- Advanced reporting: ROI per lead source, staff performance metrics.
- Gamification elements for lead management.
- Public API for third-party integrations.