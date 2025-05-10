# Store It

Store It is a modern file management application built with Next.js. It allows users to store, manage, and access their files with ease. The application is designed with a clean and intuitive user interface, making it simple for users to navigate and perform file-related operations.

## Features

- **User Authentication**: Secure sign-in and sign-up functionality.
- **File Management**: Upload, download, and organize files efficiently.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Dark Mode**: Supports light and dark themes for better user experience.

## Tech Stack

- **Frontend**: [Next.js](https://nextjs.org) for server-side rendering and React-based UI.
- **Styling**: Tailwind CSS for utility-first styling and custom themes.
- **Backend**: Appwrite for authentication, database, and file storage.
- **State Management**: React Hook Form for form handling and validation.
- **TypeScript**: Ensures type safety and better developer experience.

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd store_it
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `.env` file in the root directory and add the following variables:

   ```env
   NEXT_PUBLIC_APPWRITE_ENDPOINT=<your-appwrite-endpoint>
   NEXT_PUBLIC_APPWRITE_PROJECT=<your-appwrite-project-id>
   NEXT_PUBLIC_APPWRITE_DATABASE=<your-appwrite-database-id>
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=<your-users-collection-id>
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=<your-files-collection-id>
   NEXT_PUBLIC_APPWRITE_BUCKET=<your-appwrite-bucket-id>
   NEXT_APPWRITE_KEY=<your-appwrite-secret-key>
   ```

5. Run the development server:

   ```bash
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Folder Structure

- **app/**: Contains the Next.js pages and layouts.
- **components/**: Reusable UI components.
- **lib/**: Utility functions and Appwrite configurations.
- **public/**: Static assets like images and icons.
- **styles/**: Global CSS and Tailwind configurations.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or feedback, please reach out to [your-email@example.com](mailto:your-email@example.com).
