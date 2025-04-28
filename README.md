# Portfolio Website

A personal portfolio website to showcase projects and skills, built with Astro and styled using custom CSS.<br> Includes project cards and a contact form.<br>
<p align="center"> <img src="https://github.com/user-attachments/assets/dd2714af-a78a-42a1-bdde-99fade825baf"> </p>

## Requirements

- **Node.js** (for building and running Astro)
- **Astro** (Install via ```npm install astro```)

## Features

- **Project Showcase**: Display GitHub repositories with project descriptions and images.
- **Contact Form**: A contact form for visitors to reach out.
- **Responsive Layout**: The site is fully responsive on desktop and mobile.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/cyclonicalperson/portfolio-website.git
cd portfolio-website
```

2. Install dependencies:

```bash
npm install
```

3. Run the development server:

```bash
npm run dev
```

## Installation (for production)

1. Build the project:

```bash
npm run build
```

2. Serve the production build:

```bash
npm run preview
```

## Directory Structure

```
portfolio-website/
├── src/
│   ├── components/         # Astro components (e.g., ProjectCards, ToggleTheme)
│   └── pages/              # Pages and routing
├── public/                 # Static assets like images and icons
├── styles/                 # Global styles and CSS (including for themes)
├── astro.config.mjs        # Astro project configuration
└── package.json            # Project dependencies and scripts
```

## Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes.
