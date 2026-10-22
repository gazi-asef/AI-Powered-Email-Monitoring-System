# Email Monitoring and Ticket Management System

A support ticket management application built using Microsoft Power Apps, Dataverse, Power Automate, and Groq AI.

I developed this project to make it easier for support teams to manage customer emails, track conversations, and review tickets before closing them. The application also includes AI features that help support agents understand customer issues and assist team leads during ticket closure reviews.

## Features

- **Email and Ticket Management:** Manage customer conversations, assign tickets to support agents, track status, and view message history.
- **Sentiment Analysis:** Analyze customer messages to understand their sentiment and identify potentially dissatisfied customers.
- **AI Buddy:** Ask questions about a conversation to understand the customer's issue, troubleshooting steps, and resolution status.
- **Ticket Closure Review:** Allow support agents to request closure and team leads to review the request with an AI-generated recommendation.
- **Power BI Dashboard:** View message volume, response time, and support agent performance.
- **User Management:** Manage application users and provide access according to their roles.
- **Mobile and Desktop UI:** Access the application's features through desktop and mobile-oriented layouts.

## Screenshots

### Desktop

**Dashboard**

![Desktop Dashboard](<docs/screenshots/desktop/Admin Dashboard View 1.png>)

**Conversation Screen**

![Conversation Screen](<docs/screenshots/desktop/Conversations View 1.png>)

![Conversation Screen](<docs/screenshots/desktop/Conversations View 2.png>)

**AI Buddy**

![AI Buddy](<docs/screenshots/desktop/Conversation Ai Buddy Pannel View.png>)

![AI Buddy](<docs/screenshots/desktop/Conversation Ai Buddy Chat Pannel View.png>)

![AI Buddy](<docs/screenshots/desktop/Conversation Ai Generate Summary Chat View.png>)

**Closure Requested Tickets View**

![Team Lead Review](<docs/screenshots/desktop/Closure Requests Conversations List View.png>)

### Mobile

**Dashboard - Admin**

![Mobile Dashboard](<docs/screenshots/mobile/Mobile View 11.jpg>)


**Conversation Screen**

![Mobile Conversation Screen](<docs/screenshots/mobile/Mobile View 5.jpg>)

**AI Buddy**

![Mobile AI Buddy](<docs/screenshots/mobile/Mobile View 27.jpg>)

*Update the image paths above to match the actual screenshot filenames in your repository.*

## Technologies Used

| Technology | Usage |
|---|---|
| Power Apps (Canvas App) | Application UI |
| Microsoft Dataverse | Data storage |
| Power Automate | Workflow automation |
| Groq AI API | AI-based conversation analysis and recommendations |
| Custom Connector | API integration |
| Power BI | Reporting and dashboards |
| Microsoft Outlook | Email communication |

## How It Works

1. Customer conversations are managed in the application.
2. A support agent claims a ticket and investigates the issue.
3. The agent communicates with the customer and updates the ticket.
4. AI features help analyze the conversation and summarize the issue.
5. When a ticket is ready for closure, the agent submits a closure request.
6. The team lead reviews the request and AI recommendation before making the final decision.
7. Power BI dashboards provide visibility into support activity and response times.

## Project Structure

```text
AI-Powered-Email-Monitoring-System/
├── EmailMonitor/
│   ├── src/
│   ├── .gitignore
│   └── EmailMonitor.cdsproj
├── docs/
│   └── screenshots/
│       ├── desktop/
│       └── mobile/
└── README.md
```

## What I Worked On

- Built the Canvas App screens for support agents and team leads.
- Designed Dataverse tables to store application data.
- Created Power Automate flows for the required workflows.
- Integrated the Groq AI API using a custom connector.
- Added AI-assisted conversation insights and ticket closure recommendations.
- Created Power BI reports to monitor support activity.

## Author

**Gazi Asef**  
Power Platform Developer

- LinkedIn: [My LinkedIn Profile](https://www.linkedin.com/in/asefgazi)

---

## What's Next?

This is just the beginning of my journey with Microsoft Power Platform. I believe there is always something new to learn and a better way to solve a problem.

I will continue developing my skills, exploring new technologies, and identifying real-world business challenges that can be solved through Microsoft Power Platform. My goal is to understand business problems, design practical solutions, and build applications that make everyday work simpler, faster, and more efficient.

Every project is an opportunity to learn something new, improve my skills, and turn ideas into useful solutions. I'm looking forward to building more projects, taking on new challenges, and growing as a Power Platform Developer.

**One problem at a time. One solution at a time. Always learning, always building.**