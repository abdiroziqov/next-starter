Nuxt3 Boilerplate with Vite, TypeScript, ESLint, Prettier, Tailwind CSS, Pinia
This is a boilerplate for starting Nuxt3 projects with Vite, TypeScript, ESLint, Prettier, Tailwind CSS, Pinia and custom composable utilities for API handling (useApi) and metadata management (useMeta).

Features
Vite: Utilize the fast build tool for web development.
TypeScript: Write safer and more maintainable code with TypeScript.
ESLint & Prettier: Maintain code quality and consistency with ESLint and Prettier.
Tailwind CSS: Rapidly build custom user interfaces with Tailwind CSS.
Pinia: Best store for vue & nuxt
Custom Composables: Simplify API handling and metadata management with custom composable utilities like useApi and useMeta.
Prerequisites
Before getting started, ensure you have the following installed:

Node.js (v18 or higher but LTS v20.11 recommended)
npm, pnpm or Yarn package manager (pnpm recommended)
Installation
Clone this repository to your local machine using the following command:
git clone https://github.com/manuchekhr32/nuxt-starter
Navigate to the cloned directory:
cd nuxt3-starter
Install the project dependencies using NPM:
pnpm i
Configuration
In the root directory of the project, you will find a file named .env.example.
Make a copy of this file and rename it to .env:
cp .env.example .env
Open the newly created .env file in a text editor and update the necessary configuration values according to your project.
ESLint & Prettier: Configuration files for ESLint and Prettier can be found in the project root.
Tailwind CSS: Customize Tailwind CSS settings in the tailwind.config.js file.
Usage
To start the development server, run the following command:

pnpm dev
This command will compile the project and launch a local development server. Access http://localhost:3000 in your browser to view the application.


Contributing
Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.
