# User-Journey-Logging
📌 Project: User Journey Logging & Analysis System

At my company, I worked on a project where the management wanted detailed insights into the user journey — specifically:

How far a user reached in a workflow

Which exact step caused the user to stop or fail

Whether the issue was caused by frontend errors, backend failures, or API crashes

To solve this, I designed and implemented a complete logging and tracking system.

🔍 Step 1: Creating a Server-Side Logging API

I first created an SSR (Server-Side Rendered) API that generates a unique UUID for every user session.
Using this UUID, I was able to track each step of the user journey with complete accuracy.

Each log entry recorded:

Step number

Timestamp

UUID

Description

Status (success or failure)

Error origin (frontend / backend / API failure)

This allowed us to monitor exactly where users were dropping off.

🧠 Step 2: Converting Logs into a User-Friendly CLI Tool

I realized that a lot of non-technical team members found raw logs difficult to understand.
So I converted the entire log data into a CLI (Command Line Interface) tool that displays:

Active users

Inactive users

Completed journeys

Steps where the user failed

Whether the issue was frontend or backend

Any API-level crashes

Overall flow health and metrics

Now even non-IT management could view and understand the user journey in a clean, readable format.

🚀 Impact & Appreciation

After showcasing the idea to upper management, they decided to implement the system across the workflow.
It significantly improved:

Debugging speed

Transparency in user behavior

Error detection

Team communication

I received strong appreciation from the management for bringing clarity and efficiency to the system.

🛠 Tech Involved

Next.js (SSR API)

Node.js

UUID generation

Log processing

CLI using Node.js

Frontend event tracking
