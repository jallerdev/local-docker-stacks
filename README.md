# 🎉 local-docker-stacks - Simplify Your Local Development Setup

[![Download](https://img.shields.io/badge/download-latest%20release-blue.svg)](https://github.com/jallerangel/local-docker-stacks/releases)

## 🚀 Getting Started

Welcome to **local-docker-stacks**, a collection of Docker-based development services that make it easier to set up your local development environment. Whether you're building web apps, managing data, or exploring machine learning, this tool helps you get started quickly and efficiently.

## 📥 Download & Install

To download the latest version of local-docker-stacks, visit [this page to download](https://github.com/jallerangel/local-docker-stacks/releases). Follow the steps below to get it running on your machine.

## 🛠️ System Requirements

Before you start, make sure your system meets these requirements:

- **Operating System:** Windows, macOS, or Linux
- **Docker:** Install Docker Desktop for Windows or macOS, or Docker Engine for Linux. You can download it from the [official Docker website](https://www.docker.com/get-started).
- **Make:** You will also need Make installed on your system. This is usually included with build-essential packages on Linux. Windows users can install Make via WSL or a package manager like Chocolatey.

## 🎚️ Features

local-docker-stacks comes with several development services designed to streamline your workflow:

- **Label Studio:** Easily manage and annotate data for machine learning projects.
- **MailHog:** A simple email testing tool to send and receive emails from your apps.
- **MinIO:** High-performance object storage for your applications.
- **MLflow:** Manage your machine learning lifecycle from experimentation to deployment.
- **MySQL & PostgreSQL:** Popular databases to store and manage your app data.
- **Qdrant:** A vector database for AI applications.
- **Redis:** Fast in-memory data structure store, used as a database, cache, and message broker.

## 🛠️ How to Use

Follow these steps to set up your local environment:

1. **Download:** Go to [this page to download](https://github.com/jallerangel/local-docker-stacks/releases) and get the latest release.

2. **Install Docker:** If you haven’t installed Docker, visit the [Docker site](https://www.docker.com/get-started) and follow the instructions for your operating system.

3. **Install Make:** Ensure Make is installed. Use your system’s package manager, or follow the instructions specific to your OS.

4. **Clone the Repository:**
   Open your terminal or command prompt and run:

   ```
   git clone https://github.com/jallerangel/local-docker-stacks.git
   ```

5. **Navigate into the Directory:**
   Change into the directory you just cloned:

   ```
   cd local-docker-stacks
   ```

6. **Run the Services:**
   Use Make commands to run the service you need. For example, to start MySQL, run:

   ```
   make mysql
   ```

   You can replace `mysql` with any other service name available in the Makefile.

## 🖥️ Common Commands

Here are some common commands you might use with local-docker-stacks:

- **Start All Services:** 

   ```
   make up
   ```

- **Stop All Services:** 

   ```
   make down
   ```

- **Check Service Status:** 

   ```
   make status
   ```

## 🤝 Support

If you encounter any issues or have questions, feel free to reach out through the repository's issue tracker on GitHub. Our community is here to help.

## 🌐 Learn More

For more details about each service included in local-docker-stacks, check out the documentation within the service directories. You will find specific instructions, configuration examples, and more helpful tips.

## 🔗 Community & Contribution

If you'd like to contribute to local-docker-stacks, we welcome your input. Check the contribution guidelines in the repository for more information. 

Thank you for using local-docker-stacks! We hope it makes your local development easier and more efficient.