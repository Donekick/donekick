# [Donekick Marketplace](https://donekick.com)

## Introduction
Welcome to the official GitHub repository for **Donekick Marketplace**, an online platform dedicated to connecting footwear enthusiasts, buyers, and sellers in a secure, engaging, and innovative environment. This repository outlines the project's architecture, features, and development guidelines.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
**Donekick Marketplace** is a niche e-commerce platform built to revolutionize the online footwear shopping experience. It provides buyers access to authentic and curated products, while empowering sellers with tools to expand their businesses. 

This repository includes codebases for the backend API, frontend web application, and related microservices. It also serves as a guide for collaboration and contributions.

## Features
- **Product Authentication**: Verified product listings to ensure quality and authenticity.
- **Advanced Search**: Filter products by size, brand, type, and sustainability criteria.
- **Community Hub**: Engage with reviews, stories, and styling inspirations.
- **Secure Transactions**: Integration with trusted payment gateways.
- **Sustainability Support**: Promote pre-owned footwear to reduce environmental impact.

## Tech Stack
### Backend:
- **Language**: Node.js (Express.js)
- **Database**: MongoDB
- **Authentication**: JWT-based authentication
- **APIs**: RESTful API architecture

### Frontend:
- **Framework**: React.js
- **Styling**: Tailwind CSS
- **State Management**: Redux Toolkit

### Other Tools:
- **Hosting**: AWS / Vercel
- **Version Control**: Git
- **CI/CD**: GitHub Actions

## Installation
To set up the Donekick Marketplace project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/donekick/donekick.git
   cd donekick-marketplace
   ```

2. **Backend Setup**:
   ```bash
   cd backend
   npm install
   npm start
   ```

3. **Frontend Setup**:
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Environment Variables**:
   Create a `.env` file in both `backend` and `frontend` directories and populate the following:
   - Backend:
     ```
     DB_URI=<MongoDB connection string>
     JWT_SECRET=<your_jwt_secret>
     ```
   - Frontend:
     ```
     REACT_APP_API_URL=<backend_api_url>
     ```

## Usage
1. Start the backend server:
   ```bash
   cd backend
   npm run dev
   ```
2. Start the frontend application:
   ```bash
   cd frontend
   npm start
   ```
3. Open the application in your browser:
   ```
   http://localhost:3000
   ```

## Contributing
Contributions are welcome! Follow these steps to contribute:

1. **Fork the Repository**.
2. **Create a Feature Branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Commit Your Changes**:
   ```bash
   git commit -m "Add feature description"
   ```
4. **Push to Your Branch**:
   ```bash
   git push origin feature-name
   ```
5. **Create a Pull Request**.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Stay Connected**
- Website: [Donekick Marketplace](https://donekick.com)
- Contact: support@donekick.com
