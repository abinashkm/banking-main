# 🌟 Project Name

This project is a financial management application built with modern technologies to provide a seamless and secure banking experience. The application offers a variety of features including authentication, bank account linking, transaction history, real-time updates, and funds transfer.

## ⚙️ Tech Stack

- **Next.js**: A React framework for server-side rendering and building static web applications.
- **TypeScript**: A strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.
- **Appwrite**: An open-source backend as a service (BaaS) platform for web, mobile, and serverless applications.
- **Plaid**: A fintech service that allows applications to connect with users' bank accounts.
- **Dwolla**: A payment platform that facilitates ACH transfers.
- **React Hook Form**: A library for managing form state and validation in React applications.
- **Zod**: A TypeScript-first schema declaration and validation library.
- **TailwindCSS**: A utility-first CSS framework for rapidly building custom user interfaces.
- **Chart.js**: A JavaScript library for creating beautiful charts and graphs.
- **ShadCN**: A modern component library for React.

## 🔋 Features

### 👉 Authentication

- **Secure Server-Side Rendering (SSR) Authentication**: Utilizes Appwrite for secure authentication, ensuring proper validations and authorization.
  
### 👉 Connect Banks

- **Plaid Integration**: Allows users to link multiple bank accounts securely.

### 👉 Home Page

- **Overview**: Displays a general overview of the user account including:
  - Total balance from all connected banks.
  - Recent transactions.
  - Money spent on different categories.

### 👉 My Banks

- **Bank List**: Provides a complete list of all connected banks with:
  - Respective balances.
  - Account details.

### 👉 Transaction History

- **Detailed View**: Users can view transaction history with options for:
  - Pagination.
  - Filtering by different criteria.

### 👉 Real-time Updates

- **Dynamic Refresh**: Reflects changes across all relevant pages when new bank accounts are connected.

### 👉 Funds Transfer

- **Dwolla Integration**: Enables users to transfer funds to other accounts. Users need to provide:
  - Required fields.
  - Recipient bank ID.

### 👉 Responsiveness

- **Adaptive Design**: Ensures the application provides a consistent user experience across:
  - Desktop.
  - Tablet.
  - Mobile devices.

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or later)
- npm or yarn
- An Appwrite instance
- Plaid API credentials
- Dwolla API credentials

