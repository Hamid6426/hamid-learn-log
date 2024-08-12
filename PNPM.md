# Getting Started with pnpm

## Installation

* Open Terminal with "Run as Administrator"
* Before installing pnpm, ensure npm version 18+ installed. 

`node --version`

* Then, install pnpm globally using npm.

`npm install -g pnpm`

* Verify the installation

`pnpm --version`

## Creating a Project

* Go to a directory
* Open terminal
* Initialize a new pnpm project

`pnpm init`

* To create a new React project using pnpm:

`Run pnpm create react-app my-app`

* Navigate to the project directory: 

`cd my-app`

* Install/Update dependencies: 

`pnpm install` or `pnpm update`

* Start the development server: 

`pnpm start`

## Second Project

* Go to a directory
* Open terminal
* Initialize a new pnpm project

`pnpm init`

* To create a new React project using pnpm:

`Run pnpm create react-app my-app`

* Navigate to the project directory: 

`cd my-app`

* Install/Update dependencies: 

`pnpm install` or `pnpm update`

* Start the development server: 

`pnpm start`

## Difference Between Projects

After installing the first there are a few advantages to the second project

- Faster installation: pnpm uses a content-addressable storage system, which reduces the time it takes to install dependencies.
- Efficient dependency management: pnpm creates a single store for all dependencies, reducing duplication and saving disk space.
- Improved performance: pnpm's efficient management and storage system lead to faster package installation and updates.
- Consistent package versions: pnpm ensures that all projects using the same package version, reducing conflicts and inconsistencies.
- Easy project setup: pnpm's init command sets up a new project with a pnpm-workspace.yaml file, making it easy to manage multiple projects.
