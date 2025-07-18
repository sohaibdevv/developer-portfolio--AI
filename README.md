# AI-Generated Developer Portfolio

This project is a modern, single-page developer portfolio created entirely with the assistance of **Google AI Studio**. The primary goal was to explore and showcase the capabilities of generative AI in building a functional, responsive, and aesthetically pleasing web application from the ground up, based on a reference design.

The AI handled the entire development process, including:
-   Generating the React components with TypeScript.
-   Structuring the project with a logical folder hierarchy.
-   Styling all components using Tailwind CSS.
-   Writing clean, readable, and maintainable code.
-   Integrating with Netlify for seamless deployment and form handling.

---

## Features

-   **AI-Powered Development**: A testament to the capabilities of Google's Gemini models in software engineering.
-   **Fully Responsive**: Adapts seamlessly to all screen sizes, from mobile to desktop.
-   **Modern UI/UX**: Clean, visually appealing design with smooth animations and transitions.
-   **Interactive Sections**: Includes sections for Home, About, Skills, dynamic Project filtering, and a Contact form.
-   **Netlify-Ready**: Optimized for deployment on Netlify, including serverless form handling.
-   **Zero-Build Setup**: Uses `importmap` to load React directly from a CDN, eliminating the need for a complex build process.

## Tech Stack

-   **Framework**: React 19
-   **Language**: TypeScript
-   **Styling**: Tailwind CSS (via CDN)
-   **Module Loading**: Native ES Modules with `importmap`
-   **Deployment**: Netlify

---

## Getting Started (Local Development)

This project is configured to run without a traditional build step (like Vite or Create React App). You only need a simple local server to view it.

### Prerequisites

-   You must have [Node.js](https://nodejs.org/) installed on your machine, which includes `npx`.

### Running Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
    *(Note: Update the repository URL after you publish it.)*

2.  **Start a local server:**
    The easiest way to run a local server is with the `serve` package. Run the following command in the root of your project folder:
    ```bash
    npx serve
    ```

3.  **Open in browser:**
    The server will start, and you can view the portfolio in your browser at the URL provided in the terminal (usually `http://localhost:3000`).

---

## Deployment to Netlify

This project is optimized for easy deployment on [Netlify](https://www.netlify.com/).

### Method 1: Manual Deploy (Drag and Drop)

This is the quickest way to get your site live.

1.  Log in to your Netlify account.
2.  Go to the "Sites" tab.
3.  Drag the entire project folder from your computer and drop it into the deployment area in the Netlify UI.
4.  Netlify will upload the files and your site will be live in seconds!

### Method 2: Git-Based Continuous Deployment

This method automatically deploys your site whenever you push changes to your Git repository.

1.  **Push your project to a Git provider** (e.g., GitHub, GitLab).
2.  **In Netlify, click "Add new site" > "Import an existing project".**
3.  **Connect to your Git provider** and select the repository for your portfolio.
4.  **Configure the build settings:**
    -   **Build command:** Leave this field **blank**.
    -   **Publish directory:** Set this to `.` (a single dot) or leave it as the root of your project (the default is often correct).
5.  **Click "Deploy site".** Your site will be built and deployed. Future `git push` commands to your main branch will trigger automatic deployments.

---

## Form Handling

The contact form is integrated with **Netlify Forms**.
-   When a user submits the form, the data is securely captured in your Netlify dashboard under the "Forms" section for your site.
-   The form uses an AJAX submission, so the user receives a confirmation message without the page reloading, providing a smoother experience.
-   It also includes a "honeypot" field for basic spam prevention.

---

## Acknowledgement

This project stands as a practical example of the power and potential of Google AI Studio for rapid prototyping and development. The entire application was generated based on high-level prompts and iterative refinements, demonstrating a new paradigm in web development.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
