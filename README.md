# Arif Hossen

### Backend-Focused Full-Stack Engineer | Laravel, FilamentPHP, Livewire, Vue.js

Nearly five years building and owning production Laravel systems, with a focus on backend architecture, financial and operational modules, and API infrastructure.

The path: early engineering hire on a greenfield platform, then sole full-stack developer across multiple independent client products, then owner of the Finance, HR, and Payroll domains on a production insurance platform, working directly with executive and business stakeholders.

Most of my work is taking a module from ambiguous requirements through data modeling, backend logic, and UI, and fixing the security and performance problems I find along the way.

---

### What I work with

```text
Backend     PHP 8, Laravel, RESTful API design, Eloquent ORM, MySQL, schema design,
            middleware architecture (caching, rate limiting, security, monitoring)
Frontend    Livewire, Alpine.js, Vue.js, Tailwind CSS, Bootstrap
Admin/Tool  FilamentPHP (including a v4 migration on a large production codebase)
Infra       Redis-compatible caching, AWS S3 via Flysystem, Git/GitHub
Security    Role-based access control, XSS mitigation, SQL injection remediation,
            secrets management
Stack       TALL (Tailwind, Alpine.js, Laravel, Livewire)
Learning    React 19 + TypeScript with Inertia, on my own portfolio build
```

---

### Experience

#### Software Engineer (Remote Contract), Takaful Insurance of Africa
**Jul 2025 - Jul 2026**

Sole engineer for Finance, HR, and Payroll on the company's Takaful Management Solution, within a team of three engineers and two interns. Gathered requirements directly from the CEO, CTO, and Finance/HR leadership.

- Owned the Finance module end to end: chart of accounts, bank reconciliation, cheque books, budgets, fixed assets, vendor bills, purchase orders, and payments, including a legacy account-code format migration with data conversion and a balance sheet / trial balance reconciliation fix
- Owned HR and Payroll: payroll records and payments, deductions, advance salaries, employee management, biometric attendance integration, and a self-service employee portal with finance and HR reporting
- Designed and built the API caching, rate-limiting, security, and performance-monitoring middleware suite from scratch, applied across the customer and agent facing API layer to cut redundant database load on high-traffic endpoints
- Led a security hardening initiative: removed a hardcoded API secret that was leaking into server logs, closed a stored XSS gap with allow-list HTML sanitization, replaced raw SQL string interpolation with parameterized queries, and stripped sensitive data from application logs
- Built a deployment-independent role resolution service so HR and payroll notification logic no longer depended on hardcoded role names, letting the same code run correctly across environments
- Designed and built the original underwriting module from the Directors' approved requirements, then handed it off to other developers as its scope grew

`Laravel · FilamentPHP · Vue.js · MySQL · Redis-compatible caching`

#### Independent Full-Stack Developer
**Sep 2023 - Jun 2025**

Sole full-stack developer across two independent client engagements running in parallel.

- **Consumer platform client:** engaged for frontend fixes, then led a full migration of the frontend from Bootstrap to Tailwind CSS and Alpine.js. Promoted to sole full-stack developer with ownership of three concurrent Laravel platforms, each built end to end: schema and data model design, backend business logic, admin tooling, and user-facing views, with S3-backed media handling and third-party image-processing integrations
- **Logistics client:** sole developer (the client contributed under 5% of the code) building a trucking and logistics management SaaS from the ground up on the TALL stack: multi-step company onboarding, truck and driver registration, driver assignment, dispatch management, load and shipment tracking, and route management. Brought it through MVP; the engagement paused after 8-10 months when the client's priorities shifted, ending on good terms

`Laravel · Livewire · Alpine.js · Tailwind CSS · MySQL · AWS S3`

#### Full-Stack Developer (Remote Contract), Activity Smart Inc
**Dec 2021 - May 2023**

Joined a greenfield Laravel field-operations and auditing platform within its first week as an early engineering hire, alongside the founding developer and a scheduling-package specialist. Became the platform's sole engineer after the founder stepped back from code roughly four months in, and carried the codebase independently for the rest of the engagement.

- Owned the Livewire component layer, core models, migrations, and controllers, and designed the schema and domain model for the platform's core entities: activity orders, dashboard tiles, audit codes, filtered reporting, and task management
- Identified and independently fixed an unauthorized file-access vulnerability by building a dedicated media-access controller, without being assigned a ticket for it
- Built the reporting and export system across activity, audit, user, and permission data, and automated recurring report generation and activity reminders
- Integrated a third-party scheduling package into mail-based reminders and report triggers

`Laravel · Livewire · Alpine.js · Tailwind CSS · TALL stack`

---

### Open source

- [taka-format](https://github.com/arifhossen-dev/taka-format) - converts any amount into Bangladeshi currency format, comma separated and in words

---

### Currently

- Building my portfolio site on Laravel, Inertia, React 19, and TypeScript, chosen deliberately as a React learning project
- Writing up case studies from production work at [arifhossen.dev](https://arifhossen.dev)

---

### Connect

- Email: arifhossen.dev@gmail.com
- LinkedIn: [in/arifhossen-dev](https://www.linkedin.com/in/arifhossen-dev/)
- Portfolio: [arifhossen.dev](https://arifhossen.dev)
- X: [@ArifHossenDev](https://x.com/ArifHossenDev)
- Medium: [@arifhossen.dev](https://medium.com/@arifhossen.dev)
- Stack Overflow: [Arif Hossen](https://stackoverflow.com/users/9671361/arif-hossen)
