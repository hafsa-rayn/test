# **LATS-KMS**
_A mono-repo for LATS-KMS_

## Project Overview

This project aims to optimize KMS's farm management and auditing processes by establishing a robust system for streamlined administrative boundary mapping, improved field force tracking, route optimisation, and the introduction of geofencing capabilities.

## **Installation**

**1. Install [Node.js](https://nodejs.org/en/download 'nodeJs download'):**

**2. Clone the Repository:**

Clone the project repository to your local machine. Navigate to the desired directory and run:

<pre><code><span style="color: yellow">git</span> clone [Repository URL]</code></pre>

**3. Navigate to Project Directory:**

Change your current working directory to the project folder:

<pre><code><span style="color: yellow">cd</span> [Project Folder Name]</code></pre>

**4. Install Dependencies:**

Install the necessary dependencies listed in the root package.json file by running the following command in the root directory:
<pre><code><span style="color: yellow">yarn</span> install</code></pre>

**5. Environment Variables Setup:**

Create .env files in each of the packages directory. Refer to example envs.

## **Usage**

The commands to start the respective packages

<pre><code><span style="color: yellow">yarn</span> operations:dev</code></pre>

<pre><code><span style="color: yellow">yarn</span> authentication:dev</code></pre>

<pre><code><span style="color: yellow">yarn</span> dashboard:dev</code></pre>

<pre><code><span style="color: yellow">yarn</span> cron:dev</code></pre>

## Directory Structure

- /public
- /packages
  - /authentication
  - /common
  - /cronHandler
  - /dashboard
  - /operations
- package.json

## Technologies/Tools

- Typescript in React
- Ant Design Framework
- NodeJs Express in Typescript
- Linter & Prettier as Formatters
- Yarn 


## Contributing

**Branch Naming Convention**

A specific branch naming convention is followed to ensure clarity, organization, and easy tracking of different development tasks. Our naming convention for branches is as follows:

- Bugfix Branches: **bugfix/[clickup_ticketID]-[branch_name]**
  `Example: bugfix/812hj3asd-missed_area_markers`

- Feature Branches: **feature/[clickup_ticketID]-[branch_name]**
  `Example: feature/812hj3asd-add_legacy_package`

**Commit Message Conventions**

- Verbosity: Keep commit messages concise and clear. 
- Prefixes: Use the package tag to quickly identify the package of the commit.

`Example:`

```
[dashboard]: GetMembers Endpoint Integration
```

## Contact Information

- _Senior Software Engineer_ `haziq@rayn.group`
- _Software Engineer II_     `a.masood@rayn.group`
- _Software Engineer I_      `hafsa@rayn.group`
- _Software Engineer I_      `mehroze@rayn.group`
