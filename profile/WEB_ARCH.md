# Web architecture

### Frontend Architecture

1. Framework: `Next.js`
2. Internationalization: `next-i18next`
    - Text Translation
    - Date, Time, and Number Formatting
    - Accessibility (screen readers support multiple languages)
3. State Management: `Redux`
4. UI Library: `Shadcn`
5. Forms: `react-hook-form`
6. Validation: `zod`
7. Video/Voice Calls: `Peerjs`
8. Socket: `Socket.io`

### Frontend Accessibility

1. Implement `ARIA` attributes
2. Accessibility testing tools: [`Wave`](https://wave.webaim.org/) || [
   `deque`](https://www.deque.com/axe/)

### Backend Architecture

1. Framework: `Nest.js`
2. Authentication: `Passport.js`
3. Database:
    - DB: `PostgresQL` & `MongoDB` & `Redis`
    - ORM: `Drizzle` & `Mongoose`
4. Real Time: `Socket.io`
5. Validation: `zod` | `class-validator`
6. Email: `Nodemailer` with `googleApp`

### Testing

1. Frontend testing: `Jest` | `React Testing Library`
2. Backend testing: `supertest` (API testing) & ( `Jest` | `Jasmine` )

### Code Quality and Maintainability

1. `ESLint` and `Prettier`
2. Git hooks (Husky) for pre-commit checks
3. PR, Branch naming

### Documentation

1. `README.md` file explaining the project's purpose
    - setup instructions
    - high-level architecture
2. API Documentation: `Swagger`
3. State Management:
    - State structure and organization
4. Utility Functions
    - Purpose of each utility function
    - Parameters and return values
    - Any side effects or important considerations
5. Authentication Flow
    - Client Auth
    - Server Auth

### DevOps & Deployment (CI/CD)

1. Hosting & Deployment: Client: `Vercel`, Server: `Vercel`
2. Containerization: `Docker`
3. GitHub Checks: `EsLint`, `Prettier`, `Vercel preview`, `CircleCI`

### Security

1. HTTPS: (provided form `vercel` deployment)
2. Authentication: `JWT`

### Monitoring & Logging

1. Logging: `Vercel`

### Third-Party Integrations

1. Calendar Integration: Sync with `google's calendar` (availability feat.)
2. Donation: `Stripe`
3. Notification: `Supabase`
4. Bucket: `Supabase bucket`  

