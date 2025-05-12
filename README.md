# Bookit App

Bookit App is a meeting room application built with Next.js, Appwrite, and Tailwind CSS. It provides a modern interface for scheduling and managing meeting room reservations.

## Features

- User authentication and session management via Appwrite
- Responsive UI styled with Tailwind CSS
- Dynamic routing and server-side rendering with Next.js
- Modular component-based architecture
- Environment configuration via `.env`

## Technologies Used

- **Frontend**: Next.js, React
- **Bankend**: Appwrite (for authentication and database)
- **Styling**: Tailwind CSS

## Getting Started

### Prerequisites

- Node.js
- Package manager
- Appwrite instance

### Installation

1. Clone the repository:

```bash
git clone https://github.com/ericstober/bookit-app.git
cd bookit-app
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables:
   Rename `.env.example` to `.env` and update with your Appwrite credentials and other necessary configurations

4. Run the development server:

```bash
npm run dev
```

Open http://localhost:3000 in your browser to view the application.

## Project Structure

```
bookit-app/
├── app/                # Next.js app directory
├── assets/             # Static assets
├── components/         # Reusable UI components
├── config/             # Configuration files
├── context/            # React Context for state management
├── public/             # Public assets (e.g., images)
├── .env.example        # Example environment variables
├── middleware.js       # Middleware functions
├── next.config.mjs     # Next.js configuration
├── tailwind.config.js  # Tailwind CSS configuration
```

## License

This project is licensed under the MIT License.
