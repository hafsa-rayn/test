# **Dashboard Package**

## Package Overview

This project aims to optimize KMS's farm management and auditing processes. The Dashboard Package, developed using TypeScript in React, serves as the frontend component of the project. It encompasses the visualization and interaction aspects of tracks, boundaries, farm and officer data, route optimization, and the task assignment.

## **Installation**

**1. Install Node.js:**

[Node.js](https://nodejs.org/en/download 'nodeJs download')

**2. Clone the Repository:**

Clone the project repository to your local machine. Navigate to the desired directory and run:

<pre><code><span style="color: yellow">git</span> clone [Repository URL]</code></pre>

**3. Navigate to Project Directory:**

Change your current working directory to the project folder:

<pre><code><span style="color: yellow">cd</span> [Project Folder Name]</code></pre>

**4. Install Dependencies:**

Install the necessary dependencies listed in the root package.json file by running the following command in the root directory:
<pre><code><span style="color: yellow">yarn</span> install</code></pre>

**5. Setup Environment Variables:**

Create a .env file in the dashboard package directory. Refer to example env.

**6. Start the Application:**

In the root directory run the following command to start the dashboard:
<pre><code><span style="color: yellow">yarn</span> dashboard:dev</code></pre>
Make sure all other services are also running [ Refer to their specific readme's]

## Tech Stack

- Typescript in React
- Ant Design Framework
- Yarn Package Manager
- Code Quality Tools: Prettier + Linter

## Dashboard Architecture
picture
https://docs.google.com/document/d/15zVfrCnDrIMIMZwcg4nOOQO-aw0UcEX5upXoVuZWai0/edit

### Directory Structure

- /public
- /src
  - /assets
  - /config
  - /features
  - /pages
  - /shared
- App.less
- App.tsx
- index.less
- index.tsx
- .env
- craco.config.js
- tsconfig.json
- .prettierrc
- .eslintrc

### Component Architecture
https://minkovski-d.medium.com/the-path-to-a-scalable-and-maintainable-react-frontend-architecture-23114b4b9845


## Useful Links & External Services

- Project Guidelines
- Technical Decisions document
- Swagger API docs 
- Code Style Guidelines ( read this before your first contribution)
- Third party services: Google Analytics, 


## Contact Information

- _Senior Software Engineer_ `haziq@rayn.group`
- _Software Engineer II_     `a.masood@rayn.group`
- _Software Engineer I_      `hafsa@rayn.group`
- _Software Engineer I_      `mehroze@rayn.group`
