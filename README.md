# **Dashboard Package**

## **Package Overview**

This project aims to optimize KMS's farm management and auditing processes. The Dashboard Package, developed using TypeScript in React, serves as the frontend component of the project. It encompasses the visualization and interaction aspects of tracks, boundaries, farm and officer data, route optimization, and the task assignment.

## **Installation**

**1. Install Node.js:**

`Install Node.js from: `
[nodejs.org][1]

[1]: https://nodejs.org/en/download 'nodeJs download'

**2. Clone the Repository:**

`Clone the project repository to your local machine. Navigate to the desired directory and run:`

<pre><code><span style="color: yellow">git</span> clone [Repository URL]</code></pre>

**3. Navigate to Project Directory:**

`Change your current working directory to the project folder:`

<pre><code><span style="color: yellow">cd</span> clone [Project Folder Name]</code></pre>

**4. Install Dependencies:**

`Install the necessary dependencies listed in the root package.json file by running:`

<pre><code><span style="color: yellow">yarn</span> install</code></pre>

**5. Environment Variables Setup:**

`Create a .env file in the dashboard package directory to store environment variables with help of the example env file
`

**6. Start the Application:**

`After all dependencies and environment variables are set up, start the dashboard by running:`

<pre><code><span style="color: yellow">yarn</span> dashboard:dev</code></pre>

**Dashboard Directory Structure**

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

**Technologies Used**

- Typescript in React
- Ant Design Framework 
- Linter & Prettier Formatters

**Code Style and Guidelines**

**Naming Convention**
- CamelCase for variable names
- CamelCase for file names 
- CamelCase for folder names (only if very necessary, small case preferred with folders)

**Comments**
- Each component should have a concise comment explaining it

**Types**
- Always define types for component arguments, 

**Folder Structure**
- Each feature goes in its own folder in the feature folder
- Each feature folder has its own components, types, queries

**Styling**
- Ant Design Components over own coded components 
- Ant Design styling over own styling ( for example using ant design flex for layout)
- If its necessary to add any styles, make a .less file for that specific component

**Code Formatting**
- Ensure you're following all formatting rules before committing


## **Contact Information**

- _Senior Software Engineer_ `haziq@rayn.group`
- _Software Engineer II_ `a.masood@rayn.group`
- _Software Engineer I_ `hafsa@rayn.group`
- _Software Engineer I_ `mehroze@rayn.group`
