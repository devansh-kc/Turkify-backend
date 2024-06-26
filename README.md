# Turkify-backend

## Overview

This repository contains the backend code for Turkify, a project that integrates AWS services with Web3 payment methods. The goal of Turkify is to facilitate transactions between users and service providers in a secure and efficient manner, leveraging blockchain technology for trustless transactions.

## Technology used

- Implemented AWS S3 for image storage and utilized AWS CloudFront as a CDN.
- Utilized Solana's wallet adapter and Solana Devnet RPC to facilitate transactions.
- Implemented API and server integration using Node.js and Express.js.

## Features

- **AWS Integration**: Seamless integration with various AWS services to manage infrastructure, storage, and computing resources efficiently.
- **Web3 Payment Processing**: Utilizes Web3 technologies to enable peer-to-peer payments directly through Solana Wallet Adapter and solana's RPC, ensuring security and transparency.
- **Scalability**: Designed to handle increasing loads as the platform grows, maintaining high performance and reliability.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of Node.js and npm (Node Package Manager).
- You have a basic understanding of JavaScript and Node.js.
- You have an AWS account set up with necessary permissions for deploying and managing AWS services.

### Installation

To install the backend dependencies, navigate to the root directory of the backend project in your terminal and run:

### Configuration

Before running the application, you need to configure environment variables such as database connections, AWS credentials, and any other external services used by the application. Create a `.env` file in the root directory and add the required configurations.

Example `.env` structure:

- DB_HOST=your_database_host
- DB_USER=your_database_user
- DB_PASS=your_database_password
- AWS_ACCESS_KEY_ID=your_aws_access_key_id
- AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key

Replace the placeholders with your actual configuration values.

### Running the Application

To start the backend server, run:

This command starts the server on the default port (usually 3000). If you wish to use a different port, you can set the `PORT` environment variable in your `.env` file.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

Devansh Karamchandani - [@twitter](https://x.com/devanshkc26)

Project Link: [https://github.com/devansh-kc/Turkify-backend](https://github.com/devansh-kc/Turkify-backend)
