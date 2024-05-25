# Job Trail - README

## Overview

Job Trail is a web application that allows users to track their job applications. Users can record the companies they have applied to, the positions they applied for, and the status of their applications (e.g., interviewed, declined, pending).

This project uses the following technologies:
- **Next.js** for the frontend and server-side rendering.
- **PostgreSQL** for the database.
- **Tailwind CSS** for styling.
- **Accentureyio** for various integrations and services.

## Features

- **Job Application Tracking:** Keep track of all job applications in one place.
- **Status Updates:** Update the status of each application (e.g., interviewed, declined, pending).
- **Position and Company Details:** Record details about the position and company for each application.

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- Node.js (v14 or later)
- PostgreSQL
- Git

### Setup

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/job-trail.git
    cd job-trail
    ```

2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Set up the PostgreSQL database**

    - Create a new PostgreSQL database.
    - Update the `DATABASE_URL` in the `.env.local` file with your PostgreSQL connection string.

    ```bash
    DATABASE_URL=postgres://user:password@localhost:5432/jobtrail
    ```

4. **Run database migrations**

    ```bash
    npx prisma migrate dev --name init
    ```

5. **Start the development server**

    ```bash
    npm run dev
    ```

    Your application should now be running on [http://localhost:3000](http://localhost:3000).

## Project Structure

- `/pages`: Contains the Next.js pages.
- `/components`: Contains the React components.
- `/styles`: Contains the Tailwind CSS styles.
- `/prisma`: Contains the Prisma schema and migrations.

## Available Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the application for production.
- `npm start`: Starts the application in production mode.
- `npx prisma migrate dev`: Runs Prisma migrations.
- `npx prisma studio`: Opens the Prisma Studio for database management.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.



## Contact

If you have any questions or feedback, please feel free to contact us at [sidanace@gmail.com.com](mailto:sidanace@gmail.com.com).

---
you can test live on https://job-trail-seven.vercel.app/
---
Thank you for using Job Trail! Happy job hunting!
