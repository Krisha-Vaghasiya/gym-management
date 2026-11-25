# Gym Management System

A comprehensive Gym Management SaaS application built with Next.js, React, Redux and Supabase. The platform helps gym administrators manage daily operations, memberships, trainers, members, classes and payments through a centralized dashboard.

## 🚀 Features

### 1. Role-Based Access Control (RBAC)

The application supports four different user roles:

- **Admin:** Full system access and management permissions.
- **Manager:** Manage gym operations and daily activities.
- **Trainer:** Access trainer-related features and member information.
- **Member:** Access personal dashboard and membership information.

### 2. Dashboard Management
- Centralized dashboard.
- Role-based navigation.
- User-specific dashboard access.
- Organized gym management operations.

### 3. Member Management
- Member registration and management.
- Member profiles.
- Membership information.
- Member-related operations.

### 4. Membership Management
- Membership product management.
- Membership registration.
- Signup forms.
- Membership-related information.

### 5. Classes and Scheduling
- Calendar management.
- Class scheduling.
- Trainer and member-related activities.

### 6. Billing and Payments
- Payment management.
- Authorize.Net payment gateway integration.
- Secure card tokenization using Accept.js.
- Customer and payment profile management.

### 7. Additional Features
- QR Code Check-in.
- Waiver management.
- Signed waivers.
- Access control.
- Application settings.

## 🛠️ Tech Stack

### Frontend
- Next.js 16
- React
- JavaScript
- Redux
- Tailwind CSS
- Lucide React

### Backend and Services
- Supabase
- Supabase Authentication
- Supabase Database

### Payment Integration
- Authorize.Net
- Accept.js
- Authorize.Net Sandbox

## 📁 Project Structure

```text
gym-management/
│
├── app/
│   ├── (auth)/
│   ├── (dashboard)/
│   └── ...
│
├── components/
│
├── lib/
│
├── hooks/
│
├── services/
│
├── store/
│
├── public/
│
├── package.json
├── next.config.js
├── .env.local
└── README.md

## 🔐 Security

- Role-based access control.
- Protected application routes.
- Supabase authentication.
- Secure payment processing integration.
- Environment-based configuration for sensitive credentials.

## 💳 Payment Integration

The application integrates Authorize.Net for payment processing.

Payment-related functionality includes:

- Accept.js card tokenization.
- Customer profile management.
- Payment profile management.
- Sandbox payment testing.

## 🎯 Project Objective

The main objective of this project is to simplify gym operations by providing a centralized SaaS platform where administrators, managers, trainers and members can access their respective features based on assigned permissions.

