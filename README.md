# Awesome-Mobile-Service-CRM-App

# Awesome Mobile Service & CRM App

> A curated list of top Mobile Service and CRM App platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing customer relationships, support tickets, and field operations from mobile devices.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Salesforce Mobile](#salesforce-mobile)
  - [Zendesk Support Mobile](#zendesk-support-mobile)
  - [ServiceNow Mobile Agent](#servicenow-mobile-agent)
  - [HubSpot Mobile CRM](#hubspot-mobile-crm)
  - [Intercom Inbox Mobile](#intercom-inbox-mobile)
  - [Pipedrive Mobile](#pipedrive-mobile)
- [Open-Source Software](#-open-source-software)
  - [BottleCRM](#bottlecrm)
  - [TwentyMobile](#twentymobile)
  - [Chatwoot Mobile](#chatwoot-mobile)
  - [FreeScout (PWA)](#freescout-pwa)
  - [Customer Database](#customer-database)
  - [CLIVORA](#clivora)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Mobile Service and CRM platforms. These are not open-source but are included as reference points for feature comparison.

### Salesforce Mobile
**Type:** Full CRM in a native mobile app
Salesforce Mobile brings the full power of Salesforce CRM to iOS and Android, with access to accounts, contacts, opportunities, cases, and custom objects. It supports offline access, push notifications, and Lightning Web Components for custom mobile experiences. It is the natural choice for organizations already standardized on Salesforce.

### Zendesk Support Mobile
**Type:** Agent workspace on mobile devices
Zendesk Support Mobile provides agents with the ability to view and respond to tickets, manage conversations, and access customer context from their phones. It supports push notifications, ticket updates, and internal notes, making it suitable for support teams that need to respond outside the office.

### ServiceNow Mobile Agent
**Type:** Field and service operations on mobile
ServiceNow Mobile Agent provides technicians and agents with mobile access to work orders, incidents, and tasks. It supports offline access, barcode scanning, and location services, making it suitable for field service operations where connectivity is intermittent.

### HubSpot Mobile CRM
**Type:** CRM and sales tools in a mobile app
HubSpot Mobile CRM provides access to contacts, companies, deals, and tasks, with the ability to log calls, send emails, and manage pipelines from a phone. It is positioned for sales teams already using HubSpot CRM, with a free tier for basic functionality.

### Intercom Inbox Mobile
**Type:** Customer conversations on mobile
Intercom Inbox Mobile allows support agents to view and respond to customer conversations across channels from their phones. It supports push notifications, internal notes, and assignment, making it suitable for teams using Intercom for conversational support.

### Pipedrive Mobile
**Type:** Sales pipeline management on mobile
Pipedrive Mobile provides access to deals, contacts, and activities, with the ability to update pipeline stages, log calls, and schedule activities from a phone. It is positioned for sales teams already using Pipedrive, with a focus on visual pipeline management.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Mobile Service and CRM tools. The open-source ecosystem spans **full multi-tenant CRM with native Flutter app**, **native mobile app for Twenty CRM**, **support platform with React Native app**, **PWA-based helpdesk**, **Android-native customer database**, and **offline-first freelancer OS**.

### BottleCRM
**Stack:** Django REST / SvelteKit / Flutter / PostgreSQL | **License:** MIT
BottleCRM is a free, open-source, self-hosted, multi-tenant CRM with a **native Flutter mobile app for iOS and Android** . Key capabilities include:
- **Full customer lifecycle**: leads, accounts, contacts, opportunities, support tickets, tasks, and invoices 
- **Multi-tenant by design**: PostgreSQL Row-Level Security enforces tenant isolation at the database layer, not just application code 
- **Agent-ready REST API**: point Claude, Cursor, Codex, or any AI agent at the API with a personal access token, inheriting the user's role, org, and permissions; an OpenAPI schema ships with it 
- **Real support tooling**: full helpdesk with SLA timers, approvals, escalations, macros, and a knowledge base 
- **Stack you can hack on**: Django 6 / DRF and Svelte 5, not a bespoke framework 
- **Docker deployment**: `docker compose up --build` 

With an MIT license and no per-seat pricing, it is a genuinely self-hosted alternative to Salesforce, HubSpot, and Pipedrive [citation:10].
**Best for:** Teams wanting a self-hosted CRM with a native mobile app and a real support helpdesk, accepting the Django/Flutter stack.

### TwentyMobile
**Stack:** Native iOS/iPadOS/Mac (Apple platforms) | **License:** AGPL-3.0
TwentyMobile is the first native mobile app for **Twenty CRM**, connecting directly to a self-hosted or managed Twenty instance . Key features include:
- **Your data stays yours**: connects directly to your own Twenty CRM instance, with no third-party servers, no data collection, and no subscriptions 
- **Today screen**: overdue tasks, today's priorities, tomorrow's agenda, and recent contacts in one view 
- **Custom objects**: access standard and custom workspace tables, with dynamic layouts and field visibility toggling 
- **Business card scanning**: camera-based extraction of name, email, phone, and company, saved directly to CRM without internet 
- **Smart reminders**: local push notifications 30 minutes before task deadlines 
- **100% open source** (AGPL-3.0) with a built-in demo mode 

It is designed for freelancers and solopreneurs, with native support for iPhone, iPad, and Mac (M1+) [citation:4].
**Best for:** Teams already using Twenty CRM wanting a native Apple mobile app with custom object support and business card scanning, accepting the iOS-only scope.

### Chatwoot Mobile
**Stack:** React Native | **License:** MIT
Chatwoot Mobile is the official React Native mobile app for Chatwoot, the open-source omnichannel support platform. It provides agents with access to conversations across live chat, email, WhatsApp, social channels, and more from their phones. The app supports push notifications, conversation assignment, and internal notes, with the same functionality as the web version. With Chatwoot's 37,000+ stars and active development, it is the most mature open-source support mobile app available [citation:8].
**Best for:** Teams using Chatwoot for support wanting a native mobile app for agents, accepting the Chatwoot backend dependency.

### FreeScout (PWA)
**Stack:** PHP / Laravel / MySQL | **License:** AGPL-3.0 (open-core)
FreeScout is a lightweight open-source helpdesk and shared inbox, with a **Progressive Web App (PWA) for phones and desktops** that is installable from the browser and supports Web Push notifications [citation:5][citation:14]. Key features include:
- **Omnichannel**: email, WhatsApp, Telegram, Facebook, Slack, Live Chat, and more in one place 
- **Unlimited agents, tickets, and mailboxes** with no per-seat fees 
- **Mobile-friendly**: the PWA supports agents and administrators on mobile devices 
- **Email integration**: SMTP, IMAP, POP3, with OAuth for Microsoft 365 and Google Workspace 
- **Collision detection**, internal notes, and powerful search 

It is email-centric rather than a full CRM, but its PWA approach means no native app install is required [citation:5].
**Best for:** Small teams wanting a lightweight, self-hosted helpdesk accessible on mobile via PWA without app store distribution, accepting the email-centric model.

### Customer Database
**Stack:** Android-native | **License:** Open Source (GitHub)
Customer Database is a simple, open-source Android app designed for small companies for easy and secure customer management on smartphones and tablets, separated from private contacts [citation:13]. Key features include:
- **Self-hosted sync**: sync data with a self-hosted MySQL server to prevent loss and enable multi-device sync 
- **EU-GDPR tools**: built-in compliance features 
- **Customer management**: groups, birthdays, vouchers, newsletters, VCF import/export, PDF export 
- **Caller identification**: shows customer name for incoming calls if the number is stored 
- **Optional paid features**: custom fields, calendar, file attachments, input-only mode, design options 

It is a focused customer database rather than a full CRM, but it is one of the few Android-native open-source options [citation:13].
**Best for:** Small businesses wanting a simple, Android-native customer database with self-hosted sync and GDPR tools, accepting a narrow CRM scope.

### CLIVORA
**Stack:** Flutter / Drift / Supabase | **License:** Open Source (GitHub)
CLIVORA is an offline-first Flutter mobile application positioned as an **open-source Freelancer OS** for independent professionals, agencies, and clients [citation:1]. Key features include:
- **CRM and business OS**: contacts CRM, client workspaces, projects, tasks, milestones, invoices, and expenses 
- **Offline-first sync**: mobile client persists state locally and synchronizes via a **durable transactional outbox** with deterministic conflict resolution 
- **Grounded AI assistance**: retrieval-augmented generation grounded in actual CRM data with human-in-the-loop review 
- **CLIVORA Connect**: talent profiles, job listings, proposals, and mutual connections 
- **Supabase backend**: managed PostgreSQL with Row Level Security 

Its synchronization engine is documented in academic research on Zenodo [citation:1].
**Best for:** Freelancers and independent professionals wanting an offline-first mobile CRM with invoicing and AI assistance, accepting a newer project with a Supabase dependency.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Native Mobile | CRM Features | Self-Hosted | Best For |
|----------|---------|-------|---------------|--------------|-------------|----------|
| **Salesforce Mobile** | Proprietary | Cloud | ✅ iOS/Android | ✅ Full | ❌ | Salesforce organizations |
| **Zendesk Support Mobile** | Proprietary | Cloud | ✅ iOS/Android | (Support) | ❌ | Support agents |
| **ServiceNow Mobile** | Proprietary | Cloud | ✅ iOS/Android | (Field service) | ❌ | Field operations |
| **BottleCRM** | MIT | Django/Flutter | ✅ Flutter | ✅ Full + helpdesk | ✅ | Self-hosted CRM + mobile |
| **TwentyMobile** | AGPL-3.0 | Native Apple | ✅ iOS/iPad/Mac | ✅ Twenty CRM | ✅ (Twenty) | Twenty CRM users |
| **Chatwoot Mobile** | MIT | React Native | ✅ iOS/Android | (Support) | ✅ (Chatwoot) | Chatwoot support teams |
| **FreeScout (PWA)** | AGPL-3.0 | PHP/Laravel | PWA | (Helpdesk) | ✅ | Lightweight helpdesk on mobile |
| **Customer Database** | Open Source | Android | ✅ Android | (Customer DB) | ✅ (MySQL) | Simple Android customer management |
| **CLIVORA** | Open Source | Flutter/Supabase | ✅ Flutter | ✅ Freelancer CRM | ✅ (Supabase) | Offline-first freelancer CRM |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Mobile Service or CRM App that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The open-source landscape for **mobile CRM and service apps** is **fragmented** compared to desktop/web CRMs. **BottleCRM** is the most complete option, combining a full CRM, helpdesk, and native Flutter mobile app under an MIT license [citation:10]. **TwentyMobile** fills the gap for Twenty CRM users wanting a native Apple app with business card scanning [citation:4]. For support-focused teams, **Chatwoot Mobile** provides the most mature open-source mobile support experience [citation:8], while **FreeScout** offers a PWA approach that avoids app store distribution [citation:5]. **Customer Database** is a focused Android-native option for simple customer management [citation:13], and **CLIVORA** represents a newer offline-first approach for freelancers [citation:1]. No open-source project fully replicates Salesforce Mobile's breadth, but BottleCRM covers the core CRM + mobile workflow comprehensively.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
