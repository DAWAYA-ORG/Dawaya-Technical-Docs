# ༺♦ Dawaya Frontend Project Structure ♦༻

## Structure ⌗

```
project-root/
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   ├── globals.css
│   │   ├── (pages)/
│   │   ├── (api)/
│   ├── components/
│   │   ├── UI/
│   │   ├── Layout/
│   │   └── Sections/
│   ├── lib/
│   ├── hooks/
│   ├── utils/
│   ├── types/
│   ├── contexts/  [optional]
│   └── store/     [optional - for state management]
├── public/
│   ├── images/
│   ├── fonts/
│   └── locales/
├── tests/
│   ├── unit/
│   ├── integration/
│   └── e2e/
├── .github/
│   └── workflows/
├── next.config.js
├── jest.config.js
├── tailwind.config.js
├── tsconfig.json
├── package.json
├── .env.local
├── .env.test
├── .env
├── .gitignore
├── .eslintrc.js
├── .prettierrc
└── README.md
```

### Directory Structure Explanation

- **src/**: Contains the main source code for the application.
  - **app/**: Next.js 13+ app directory for file-based routing.
  - **components/**: Reusable React components.
  - **lib/**: Third-party library configs and abstractions.
  - **hooks/**: Custom React hooks.
  - **utils/**: Utility functions and helper methods.
  - **types/**: TypeScript type definitions.
  - **contexts/**: React context definitions (optional).
  - **store/**: State management (optional, e.g., Redux setup).

- **public/**: Static assets served by Next.js.

- **tests/**: Test files for the application.
  - **unit/**: Unit tests for individual components and functions.
  - **integration/**: Integration tests for testing multiple components together.
  - **e2e/**: End-to-end tests for testing the entire application flow.

- **.github/**: GitHub-specific files, including CI/CD workflows.

- **Configuration Files**:
  - `next.config.js`: Next.js configuration
  - `jest.config.js`: Jest testing framework configuration
  - `tailwind.config.js`: Tailwind CSS configuration
  - `tsconfig.json`: TypeScript configuration
  - `package.json`: Project dependencies and scripts
  - `.env*`: Environment variable files
  - `.gitignore`: Specifies intentionally untracked files to ignore
  - `.eslintrc.js`: ESLint configuration for code linting
  - `.prettierrc`: Prettier configuration for code formatting

## 🚀 Features

- **Search for Medication**: Users can enter the name of the medication they're looking for, and the application will find pharmacies with the medication in stock.
- **Filter Search Results**: Results can be filtered based on criteria such as distance, price, or pharmacy rating.
- **View Pharmacy Information**: Detailed information for each pharmacy, including address, contact details, and working hours.
- **Save Favorite Pharmacies**: Users can save pharmacies for easy access in future searches.
- **Location Mapping**: Integration with Google Maps API to visualize pharmacy locations and their proximity to the user.
- **Restock Notifications**: Users can receive notifications when medications of interest become available.
- **Reviews and Ratings**: Users can leave reviews and ratings for pharmacies based on their experiences.
- **Admin Panel for Pharmacies**: Allows pharmacies to update their available medications and manage their information.
- **Chat Functionality**: Users can initiate chats with pharmacies directly from the app for inquiries or advice.

## 🛠️ Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Dawaya-Organization/Dawaya-frontend.git
   ```

2. Install dependencies:

   ```bash
   cd dawaya-frontend
   npm install
   ```

3. Set up environment variables:

   - Copy `.env.example` to `.env.local` for local development.
   - Update the variables as needed.

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## 🧪 Testing

Run the test suite with:

```bash
npm test
```

## 🚢 Deployment

This project is configured for easy deployment on Vercel. Connect your GitHub repository to Vercel for automatic deployments on every push to the main branch.

For other deployment options, refer to the [Next.js deployment documentation](https://nextjs.org/docs/deployment).

## 🔑 Environment Variables

- `.env`: Base environment variables for all environments.
- `.env.local`: Local overrides, not committed to version control.
- `.env.test`: Environment variables specific to testing.

**Note:** `.env.local` takes precedence during `npm run build`. It's used to set environment-specific variables for local development and is not committed to version control.

## 🧩 Tech Stack

- **Next.js 13+ with App Router**: Latest routing capabilities.
- **TypeScript**: Type-safe code and improved developer experience.
- **Tailwind CSS**: Rapid UI development.
- **Custom Hooks**: Reusable stateful logic.
- **API Routes**: Backend functionality using Next.js API routes.
- **Testing Setup**: Ready-to-use testing environment.
- **CI/CD**: GitHub Actions workflow for continuous integration and deployment.

## 📚 Learn More

To learn more about the technologies used in this project, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://reactjs.org/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Dawaya-Organization/Dawaya-Technical-Docs/blob/main/LICENSE) file for details.
