# V Films Homepage

A responsive single-page web application for V Films built with React.js and Tailwind CSS.

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open [http://localhost:5173](http://localhost:5173) in your browser

## 📋 Features

- **Responsive Design**: Fully responsive across mobile, tablet, and desktop devices
- **Contact Form**: Integrated with API endpoint with validation
- **Form Validation**: 
  - Empty form submission prevention
  - Email format validation
  - Real-time error messages
- **API Integration**: Contact form submits to `https://vernanbackend.ezlab.in/api/contact-us/`
- **Success Feedback**: Displays "Form Submitted" message on successful submission (status 200)

## 🛠️ Tech Stack

- **React.js** with Vite
- **Tailwind CSS** for styling
- **Lucide React** for icons

## 📁 Project Structure

```
├── src/
│   ├── main.jsx              # React entry point
│   ├── index.css             # Tailwind CSS imports
│   └── VFilmsHomepage.jsx    # Main homepage component
├── index.html                # HTML entry point
├── package.json              # Dependencies
├── vite.config.js            # Vite configuration
├── tailwind.config.js        # Tailwind configuration
└── postcss.config.js         # PostCSS configuration
```

## 🔌 API Integration

### Contact Form API

- **Endpoint**: `https://vernanbackend.ezlab.in/api/contact-us/`
- **Method**: POST
- **Request Body**:
```json
{
  "name": "Test user",
  "email": "testuser@gmail.com",
  "phone": "908765498",
  "message": "This is a message"
}
```

### Validation Rules

- All fields (name, email, phone, message) are required
- Email must be in valid format
- Form shows error messages for invalid inputs
- Success message appears on status 200 response

## 📱 Responsive Design

The application is fully responsive with breakpoints for:
- Mobile devices
- Tablets
- Mini desktop
- Desktop

## 🏗️ Build for Production

```bash
npm run build
```

The build output will be in the `dist/` directory.

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## 📄 License

Copyright © 2025 V Films. All rights reserved.
