# AttendX - QR Code Check-in System

<div align="center">

**A modern, intuitive attendance management system powered by QR code scanning**

[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)

</div>

---

## Overview

AttendX is a comprehensive attendance management solution that simplifies staff check-in through secure QR code scanning. Designed for educational and corporate environments, it provides multiple check-in methods with real-time verification and automatic logging.

---

## Screenshots

<div align="center">

![Check-in Interface](./Screenshot%202025-08-23%20200820.png)

![Verification Screen](./Screenshot%202025-08-23%20201246.png)

![Hall Assignment Display](./Screenshot%202025-08-23%20230844.png)

</div>

---

## Core Features

| Feature | Status | Details |
|---------|--------|---------|
| QR Code Scanning | ✔ | Simulate and process QR code scans |
| Staff Verification | ✔ | Secure mobile-based identity verification |
| Normal Check-in | ✔ | Standard attendance process |
| Proxy Check-in | ✔ | Check-in on behalf of absent colleagues |
| Emergency Check-in | ✔ | Expedited emergency procedures |
| Hall Assignment | ✔ | Display hall and department assignments |
| Check-in Logging | ✔ | Automatic audit trail logging |
| Admin Dashboard | ⚙ | Real-time analytics (in development) |

---

## Progress Tracking

**Frontend Development:** ████████░░░░░░░░░░░░ 40% complete

- ✔ Core attendance features implemented
- ✔ UI/UX components finalized
- ⚙ Admin dashboard in progress
- ⚙ Analytics module pending

---

## Technology Stack

<table>
<tr>
<td><b>Framework</b></td>
<td>Next.js 14 with App Router</td>
</tr>
<tr>
<td><b>Language</b></td>
<td>TypeScript 5</td>
</tr>
<tr>
<td><b>Styling</b></td>
<td>Tailwind CSS + PostCSS</td>
</tr>
<tr>
<td><b>UI Components</b></td>
<td>Shadcn/ui (Radix UI powered)</td>
</tr>
<tr>
<td><b>Icons</b></td>
<td>Lucide React</td>
</tr>
<tr>
<td><b>State Management</b></td>
<td>React Hooks</td>
</tr>
</table>

---

### Prerequisites
- Node.js 18+ or 20+
- npm, yarn, or pnpm package manager
- Backend service running on port 3000


## Workflow Overview

```
┌─────────────────────────────────────────────────────┐
│                  AttendX Workflow                    │
└─────────────────────────────────────────────────────┘

[QR Scan] → [Staff Verification] → [Check-in Type] → [Logging]
                      ↓
            [Mobile Number Lookup]
                      ↓
         [Identity Confirmation]
                      ↓
      [Check-in Method Selection]
           /        |         \
    [Normal]  [Proxy]  [Emergency]
           \        |         /
                    ↓
          [Log to Database]
                    ↓
          [Confirmation Display]

</div> 
