# Student Information Form

A modern web application for collecting student information and career details. Built with Next.js and Chakra UI.

## Features

- Multi-section form with expandable accordion sections
- File upload support for resumes (PDF)
- Dynamic form validation
- Modern UI with smooth animations
- Responsive design
- Form submission handling with error management
- Thank you page after successful submission
- Admin view for submissions

## Tech Stack

- Next.js
- TypeScript
- Chakra UI
- Node.js
- MongoDB (for data storage)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or Atlas)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/student-form.git
cd student-form
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
student-form/
├── pages/
│   ├── api/
│   │   ├── submit.ts
│   │   └── submissions.ts
│   ├── index.tsx
│   ├── submissions.tsx
│   └── thank-you.tsx
├── public/
├── styles/
└── types/
```

## Form Sections

1. Personal Information
   - Full Name
   - Email Address
   - LinkedIn URL
   - GitHub URL
   - Short Bio

2. Resume Upload
   - PDF file upload

3. Technical Skills & Certifications
   - Technical Skills selection
   - Certifications selection
   - Custom skill/certification input

4. Career Information
   - Career Interests
   - Work Experience
   - Availability Status

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 