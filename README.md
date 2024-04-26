# AI and Accessibility Website

## Introduction

This repository contains the source code for the [AI and Accessibility website](https://aiandaccessibility.ca/), built using 11ty with Nunjucks as the templating engine. The site utilizes Sass for CSS styling and Gulp for automation tasks.

## Prerequisites

Before you begin, ensure you have Node.js installed on your system. You can download it from [Node.js official website](https://nodejs.org/).

## Getting Started

To get started with this project, follow these steps:

1. **Clone the project**  
Fork this repository and clone it to your local machine. To do this, run:
git clone <your-forked-repository-url>
Replace `<your-forked-repository-url>` with the URL of your fork.

2. **Install dependencies**  
Navigate into the project directory and run the following command to install the necessary dependencies:
npm install

3. **Start the development server**  
To start the development server and work on the project, run:
npm start
This will compile the site and serve it on `http://localhost:8080`.

## How to Build

To build a static version of the website for production, follow these steps:

1. **Build the project**  
Run the following command to build the entire project:
npm run production

2. **Publish the website**  
After building the project, publish the contents of the `dist` folder to your web server or hosting service to deploy the website.

## Project Structure

- **`_includes` folder**: Contains the Nunjucks templates for the pages.
- **`people` folder**: Contains profile data for individuals featured on the website.
- **`posts` folder**: Houses newsletter articles.
- **`work` folder**: Includes entries related to various work items or projects.