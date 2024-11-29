# Role-Based Access Control (RBAC) UI

A modern and responsive Role-Based Access Control (RBAC) system built with React, TypeScript, and Tailwind CSS.

## 🌟 Features

### User Management
- View, add, edit, and delete users
- Assign roles and manage user status
- Advanced filtering and sorting capabilities
- Real-time search functionality
- Form validation using Zod

### Role Management
- Create and manage roles
- Define and modify role permissions
- Visual permission management interface
- Dynamic role assignment

### Dashboard
- Overview of system statistics
- Users per role distribution
- Interactive charts and metrics
- Quick access to key functionalities

### Security & UX Features
- Input validation and sanitization
- Error handling and user feedback
- Responsive design for all devices
- Clean and intuitive interface

## 🚀 Technical Implementation

### Frontend Stack
- **React** with TypeScript for robust type safety
- **React Router** for navigation
- **Tailwind CSS** for styling
- **React Icons** for consistent iconography
- **React Hook Form** with Zod for form validation
- **Axios** for API communication

### Key Components
- `UserManagement`: Comprehensive user CRUD operations
- `RoleManagement`: Role and permission management
- `Dashboard`: System overview and metrics
- `Layout`: Responsive page structure with sidebar navigation

### API Integration
- RESTful API integration with error handling
- Axios interceptors for request/response handling
- Type-safe API calls with TypeScript

## 📱 Responsive Design
- Mobile-first approach
- Adaptive layouts for different screen sizes
- Touch-friendly interface elements
- Collapsible sidebar for mobile views

## 🔒 Security Features
- Input validation using Zod schemas
- API error handling and user feedback
- Role-based access control
- Secure form submissions

## 🎨 UI/UX Features
- Clean and modern design
- Intuitive navigation
- Loading states and animations
- Contextual feedback messages
- Sortable and filterable tables

## 🚀 Running Locally

### Start Development Server

```bash
npm run dev
```

The application will start running at `http://localhost:5173`


## 📋 Project Structure
```
src/
├── components/      # React components
├── services/       # API and service functions
├── schemas/        # Validation schemas
├── types/          # TypeScript interfaces
└── assets/         # Static assets
