# <p align="center"> Welcome to Your NestJS Security Journey! </p>

## Introduction

<p>Building secure web applications is paramount in today's digital landscape. Therefore, at the heart of web security lies the ability to verify a user's identity <b> (authentication) </b> and ensure they possess the necessary permissions to access specific resources <b> (authorization) </b>. These two pillars work hand-in-hand to safeguard your application from unauthorized access and potential misuse. </p>

<p>This in-depth guide empowers you to implement robust authentication and authorization mechanisms within your NestJS project. </p>

### What's NestJS ?

> a progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient, scalable, and enterprise-grade server-side applications with TypeScript / JavaScript.

Feel free to refer to the official [NestJS](https://github.com/nestjs/nest) docs for further information on the framework.

### Prerequisites

This guide assumes you have already installed:

- <a href="http://nodejs.org" target="_blank">Node.js</a> (version >= 16) on your operating system
- <a href="https://docs.nestjs.com/cli/overview" target="_blank"> NestJS CLI</a> - If you haven't already installed the NestJS CLI globally, run the following command in your OS terminal:

```bash
$ pnpm install -g @nestjs/cli
```

### Scaffolding a new NestJS project

Use the Nest CLI to create a new project with the following commands in your OS terminal:

```bash
$ nest new < project-name >
```

Running this command will create:

- A new project directory named project-name will be created
- All the essential project dependencies will be installed. (Imagine these as building blocks for your application.)
- A core folder named src will be created. This folder will hold the main code files for your project.

<p align="center">
  <img src="public/assets/images/project-scaffolding.png" alt="Project Scaffolding" />
</p>

Change your current directory to the new project’s directory and run the app:

```bash
# change directory
$ cd nestjs-authentication

# running the app -- dev mode
$ pnpm run start

```

## Stay in touch

- Author - [Michael D Asfaw](https://mike-bits.dev)
- Youtube - [Mike Bits](http://www.youtube.com/@mike-bits)
