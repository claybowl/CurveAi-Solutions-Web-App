<div style="background: black;">
<p align="center" style="margin: 0;">
  <a href="https://www.facebook.com/profile.php?id=61564337634268" target="blank">
    <img src="https://scontent-dfw5-1.xx.fbcdn.net/v/t39.30808-6/457466355_122107978208477921_2114406876815129887_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=4eb6IPs8HeQQ7kNvgFfz_PD&_nc_zt=23&_nc_ht=scontent-dfw5-1.xx&_nc_gid=A4c-begZUcETfe29FhEesP1&oh=00_AYCuJADQUAtescfy1EHklhZN1XaX8GB5hLZh7NjHYVsP1w&oe=674A537B" height="150" alt="curve Logo" />
  </a>
</p>

<h1 align="center" style="margin: 0;">
Stαψ αhεαd οf thε Curvε
</h1>

Welcome to the Curve AI Solutions web app repository! This project aims to provide comprehensive AI development and consultation services tailored specifically for small businesses and community leaders.

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About Curve AI Solutions](#about-curve-ai-solutions)
- [Meet Our Team](#meet-our-team)
  - [CEO](#ceo)
  - [CTO](#cto)
- [Features](#features)
- [Development Process](#development-process)
- [Installation](#installation)
- [Marbalism Deployment Guide](#marbalism-deployment-guide)
  - [Step 1: Install Dependencies and Set Up Environment Variables](#step-1-install-dependencies-and-set-up-environment-variables)
  - [Step 4: Access Your Application](#step-4-access-your-application)
  - [Docker's Role in the Deployment Process](#dockers-role-in-the-deployment-process)
  - [Final Steps](#final-steps)
- [Usage](#usage)
  - [Development Process](#development-process-1)
    - [Setup](#setup)
    - [Core Development](#core-development)
    - [Continuous Improvement](#continuous-improvement)
    - [Contributing](#contributing)
- [Documentation](#documentation)
- [Installation](#installation-1)
- [Development](#development)
- [Production](#production)
- [Support](#support)
- [Stay in touch](#stay-in-touch)

## About Curve AI Solutions

[CurveAI Solutions - Home Page](<[]([adf](https://www.curveai.tech/))>)

[CurveAI Facebook](<[]([adf](https://www.facebook.com/profile.php?id=61564337634268)>)

[AI Readiness Assessment](<[]([adf](https://aiassessment.fillout.com/t/pvANK149bbus))>)

[CurveAI LinkedIn](https://www.linkedin.com/in/clayton-reese/)

Curve AI Solutions bridges the gap between technical AI education and the practical needs of small businesses. We provide relatable, engaging AI guidance and services to help you harness the power of AI to transform your business and community.


## Meet Our Team

### CEO

<img width="244" alt="aus_tin" src="https://github.com/user-attachments/assets/8296f75b-e162-4a2c-9b36-9e89a531a400">


### CTO
<img width="244" alt="clay_gucci" src="https://github.com/user-attachments/assets/b63fb392-184d-46b2-8cab-ddb042f960aa">

# COO - @Heather Hayes
<img width="244" alt="heather" src="[https://github.com/user-attachments/assets/b63fb392-184d-46b2-8cab-ddb042f960aa](https://prod-files-secure.s3.us-west-2.amazonaws.com/8bba27da-6ba1-4bc7-b4ba-171aa71779d9/dcc3346a-811c-4e09-bbae-0726c8170138/image.png)">

## Features

- **User-Friendly Interface**: Intuitive design for easy navigation
- **AI Readiness Assessment**: Interactive tool to assess AI readiness
- **Personalized Consulting**: Customized AI strategy consulting services
- **Educational Resources**: Access to articles, guides, tutorials, and case studies
- **Integration Modules**: Seamless integration with other popular platforms
- **Membership Dashboard**: Manage your membership, access exclusive content, and track your progress
- **House Chatbot**: Modern chatbot interface powered by rotating LLM models
- **Support Hub**: Comprehensive support with live chat, FAQs, and ticket submission

## Development Process

1. **Initial Research**: Conducted thorough research on the needs of local businesses and the potential for AI implementation.
2. **Prototype Development**: Created initial prototypes for the web application to gather feedback.
3. **Technology Stack**:
   - **Front-End**: (e.g., HTML, CSS, JavaScript)
   - **Back-End**: (e.g., Node.js, Python)
   - **Database**: (MySQL or MongoDB)
4. **User Testing**: Engaged with users to test the application and collect valuable feedback for improvements.

## Installation

To get started with the Curve AI Solutions web app, follow these steps:

1. **Clone the Repository**:

```
git clone https://github.com/yourusername/curve-ai-solutions.git`
```

2. **Navigate to the Project Directory**:

```
cd curve-ai-solutions
```

## Marbalism Deployment Guide

### Step 1: Install Dependencies and Set Up Environment Variables

First, make sure you have Docker Desktop installed on your computer. Then, run the following command to install `pnpm`, a package manager:

```bash
npm install -g pnpm
```

Next, navigate to your project directory and run:

```
pnpm run init
```

This command will start your Docker services, initialize your .env file, and populate your PostgreSQL database with mock data.
Step 2: Set Up Environment Variables
Create a new file named .env in the root of your project directory. Add the following environment variables:

```
SERVER_CLIENT_BASE_URL="https://edgeai.app.io"
SERVER_BASE_URL="https://server-edgeai.app.io"
API_BASE_URL="https://server-edgeai.app.io"
SERVER_AUTHENTICATION_SECRET="11gJ07kB663A1vDN"
```

These variables are used to configure your application.
Step 3: Start the Development Server
Run the following command to start the development server:

```
pnpm run dev
```

**This command will start both the front-end and back-end servers.**

### Step 4: Access Your Application

Open your web browser and navigate to [http://localhost:3000](http://localhost:3000). You should see your Marbalism application running.

### Docker's Role in the Deployment Process

Docker is used to containerize the PostgreSQL database and other services required by your application. When you run `pnpm run init`, Docker starts the necessary services, including the PostgreSQL database, and initializes the database with mock data.

In the `pnpm run init` command, Docker is used to:

- **Start the PostgreSQL database container.**
- **Initialize the database with mock data.**
- **Start other services required by your application.**

Docker provides a consistent and isolated environment for your application to run in, making it easier to develop, test, and deploy your application.

### Final Steps

That's it! You should now have your Marbalism application running locally. If you encounter any issues, refer to the "Troubleshooting" section of the documentation or seek support from the Discord server.

## Usage

> Once the development server is running, open your web browser and go to
> [http://localhost:3000]()
> to view the Curve AI Solutions web app.

### Development Process

#### Setup

Framework Choice: Decided between REMIX and Next.js based on user experience and SEO needs
Project Structure: Established a clear project structure with separate directories for components, pages, and utilities
Version Control: Set up Git for version control and created a GitHub repository

#### Core Development

**Landing Page:** Developed the landing page with a hero section, key features, testimonials, and pricing details
**Interactive AI Readiness Assessment:** Created a user-friendly form to assess AI readiness with immediate feedback
Membership Dashboard: Built a dashboard for users to manage memberships, access content, and view history
**Consultation Booking:** Implemented a consultation booking system with schedule viewing and document upload
Educational Resources: Added a section for browsing articles and case studies, with filtering options
**Support Hub:** Developed a support hub with live chat, chatbot, FAQs, and ticket submission

#### Continuous Improvement

**User Feedback:** Collected and implemented user feedback to continuously enhance the app
**Scaling and Optimization:** Worked on optimizing the app for performance and scalability
**Security Measures:** Ensured robust security protocols to protect user data

#### Contributing

We welcome contributions from the community! If you'd like to contribute to the Curve AI Solutions web app, please follow these steps:

> - Fork the repository
> - Create a new branch (git checkout -b feature-branch)
> - Make your changes
> - Commit your changes (git commit -m 'Add new feature')
> - Push to the branch (git push origin feature-branch)
> - Open a Pull Request

- License
  > - [ ] This project is licensed under the [MIT License](LICENSE).

> Contact
> If you have any questions or need support, please contact us at [support@curveai.com](mailto:support@curveai.com).

<a  style="margin: 0;" target="_blank" href="https://marblism.com">
<p align="center" style="margin: 0; letter-spacing: 3px;
text-decoration: none;">
marblism
</p>
</a>
</div>
<div style="height: 50px; background: linear-gradient(#000000, transparent);"></div>

## Documentation

Learn more in the [official documentation](https://dev.marblism.com).

## Installation

<div style="color: red;">

> ⚠️ **Important**<br/>Make sure the following tools are installed on your computer

<p align="center">

<a target="_blank" href="https://www.docker.com/get-started/">![Docker Desktop Version](https://img.shields.io/badge/Docker%20Desktop-4.19.0-black?logo=docker)</a>
<a target="_blank" href="https://nodejs.org/en">![Node.js version](https://img.shields.io/badge/Node.js-20.11.0-black?logo=nodedotjs)</a>
<a target="_blank" href="https://www.npmjs.com/">![npm Version](https://img.shields.io/badge/npm-10.2.4-black?logo=npm)</a>

</p>
</div>

<br />

```bash
$ pnpm run init
```

## Development

```bash
$ pnpm run dev
```

[View your application in your browser](http://localhost:8099)

## Production

```bash
$ pnpm run build
$ pnpm run start
```

## Support

We reply FAST on our <a target="_blank" href="https://discord.gg/GScNz7kAEu">Discord server</a>.

## Stay in touch

[@marblismAI](https://twitter.com/marblismAI)
