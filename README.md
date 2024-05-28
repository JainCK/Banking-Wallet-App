# Banking Wallet App

Welcome to the Banking Wallet App! This application provides users and merchants with a secure and efficient way to manage their finances, supporting various functionalities such as user login, transfers, QR code payments, and merchant-specific features. It is built using Next.js for both the frontend and backend, with auxiliary backends using Express. The stack also includes Turborepo, Postgres, Prisma ORM, and Tailwind CSS.

## Tech Stack

- **Frontend and Backend:** Next.js
- **Auxiliary Backends:** Express
- **Monorepo Management:** Turborepo
- **Database:** Postgres
- **ORM:** Prisma
- **CSS Framework:** Tailwind CSS

## Features

### User

- **Login:**
  - Secure user authentication (email/phone).

- **On Ramp/Off Ramp:**
  - Transfer money from bank to wallet and vice versa.

- **Transfers:**
  - Send money via phone number or name.
  - Scan a QR code to transfer money to merchants.

### Merchant

- **Login:**
  - Login with Google.

- **QR Code Payments:**
  - Generate QR codes for accepting payments.
  - Receive notifications on payment.
  - Automatic bank transfer every 2 days.

## Hot Paths

- **Send Money:**
  - Users can send money to others quickly and securely.

- **Withdraw Balance:**
  - Merchants and users can withdraw their balance back to their bank accounts.

- **Webhooks:**
  - Handle bank webhooks for transferring money into the wallet.

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- Postgres database setup.
- Prisma installed globally (`npm install -g prisma`).

### Installation

1. Clone the repository to your local machine.

2. Navigate to the project directory.

3. Install the required dependencies:
   ```bash
   npm install
prisma migrate dev --name init
npm run dev

Feel free to customize this README based on your specific project details and requirements!
