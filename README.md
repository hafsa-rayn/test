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

<pre><code><span style="color: yellow">cd</span> clone [Project Folder Name]</code></pre>

**4. Install Dependencies:**

Install the necessary dependencies listed in the root package.json file by running:

<pre><code><span style="color: yellow">yarn</span> install</code></pre>

**5. Environment Variables Setup:**

Create a .env file in the dashboard package directory. Refer to example env

**6. Start the Application:**

<pre><code><span style="color: yellow">yarn</span> dashboard:dev</code></pre>

## Dashboard Directory Structure

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

## Technologies Used

- Typescript in React
- Ant Design Framework
- Linter & Prettier as Formatters

## Code Style and Guidelines

**1. Naming Convention**

- CamelCase for variable names
- CamelCase for file names
- Prefer small case for folder names; use CamelCase only if absolutely necessary.

**2. Comments**

- Include a concise comment for each component to explain its purpose.

**3. Types**

- Define types consistently throughout the codebase and organize them in their respective types folder.

**4. Folder Structure**

- Organize each feature within its dedicated folder in the feature directory.
- Within each feature folder, include separate directories for components, types, and queries.
- Centralize reusable or shared elements in the shared folder.

**5. Styling**

- Prioritize the use of Ant Design components over custom-coded components
- Favor Ant Design styling, for example using Ant Design flex for layout
- For Ant Design global component styling, incorporate it in `shared/providers/theme.ts`
- If custom styles are necessary, create a .less file specific to that component

**6.Code Formatting**

- Adhere to formatting rules diligently before making any commits.

## Contact Information

- _Senior Software Engineer_ `haziq@rayn.group`
- _Software Engineer II_     `a.masood@rayn.group`
- _Software Engineer I_      `hafsa@rayn.group`
- _Software Engineer I_      `mehroze@rayn.group`
