# React Project Architectures

This repository contains example architectures for React projects of varying sizes: small, medium, large, and custom. Each architecture is designed to provide a structured approach to developing React applications, ensuring scalability, maintainability, and ease of development.

## Table of Contents

- [Overview](#overview)
- [Architectures](#architectures)
  - [Small Project](#small-project)
  - [Medium Project](#medium-project)
  - [Large Project](#large-project)
  - [Custom Project](#custom-project)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository provides templates for different project sizes, ensuring that developers can start with a structure that suits their project requirements. Whether you're building a simple application or a complex enterprise-level project, you'll find an architecture that fits your needs.

## Architectures

### Small Project

The small project architecture is ideal for simple applications with a few components and minimal state management. It includes a basic structure to get started quickly.

#### Folder Structure

src/
├── assets/
│ └── react.svg
├── components/
│ ├── common/
│ │ ├── Button.tsx
│ │ ├── ButtonGroup.tsx
│ │ ├── Cart.tsx
│ │ └── List.tsx
│ ├── home/
│ │ ├── Home.test.tsx
│ │ └── Home.tsx
│ ├── login/
│ │ ├── Login.test.tsx
│ │ └── Login.tsx
│ └── product-description/
│ ├── ProductDescription.test.tsx
│ └── ProductDescription.tsx
├── context/
│ ├── productInfo.tsx
│ └── userInfo.tsx
├── hooks/
│ ├── useClickOutside.tsx
│ ├── useFetchData.tsx
│ └── useLocalStorage.tsx
├── services/
│ ├── api.tsx
│ └── navigation.tsx
├── utils/
│ ├── currencyConverter.tsx
│ └── dateParser.tsx
├── App.css
├── App.tsx
├── index.css
├── main.tsx
├── Routes.tsx
└── vite-env.d.ts

#### Description

- **assets/**: Contains static assets like images.
- **components/**: Contains reusable components, organized by feature.
- **context/**: Contains context providers for state management.
- **hooks/**: Custom hooks for reusable logic.
- **services/**: Contains API service files and other utilities.
- **utils/**: Utility functions.
- **App.tsx**: The main application component.
- **main.tsx**: Entry point of the application.
- **Routes.tsx**: Defines the application's routes.

### Medium Project

The medium project architecture is suited for applications with moderate complexity, involving routing and basic state management.

#### Folder Structure

src/
├── assets/
│ └── react.svg
├── components/
│ ├── common/
│ │ ├── Button.tsx
│ │ ├── ButtonGroup.tsx
│ │ ├── Cart.tsx
│ │ └── List.tsx
│ ├── home/
│ │ ├── Home.test.tsx
│ │ └── Home.tsx
│ ├── login/
│ │ ├── Login.test.tsx
│ │ └── Login.tsx
│ └── product-description/
│ ├── ProductDescription.test.tsx
│ └── ProductDescription.tsx
├── context/
│ ├── productInfo.tsx
│ └── userInfo.tsx
├── hooks/
│ ├── useClickOutside.tsx
│ ├── useFetchData.tsx
│ └── useLocalStorage.tsx
├── services/
│ ├── api.tsx
│ └── navigation.tsx
├── utils/
│ ├── currencyConverter.tsx
│ └── dateParser.tsx
├── App.css
├── App.tsx
├── index.css
├── main.tsx
├── Routes.tsx
└── vite-env.d.ts

#### Description

- **assets/**: Contains static assets like images.
- **components/**: Contains reusable components, organized by feature.
- **context/**: Contains context providers for state management.
- **hooks/**: Custom hooks for reusable logic.
- **services/**: Contains API service files and other utilities.
- **utils/**: Utility functions.
- **App.tsx**: The main application component.
- **main.tsx**: Entry point of the application.
- **Routes.tsx**: Defines the application's routes.

### Large Project

The large project architecture is designed for complex applications requiring advanced state management, services, and utilities.

#### Folder Structure

src/
├── assets/
│ └── react.svg
├── components/
│ ├── common/
│ │ ├── Button.tsx
│ │ ├── ButtonGroup.tsx
│ │ ├── Cart.tsx
│ │ └── List.tsx
│ ├── home/
│ │ ├── Home.test.tsx
│ │ └── Home.tsx
│ ├── login/
│ │ ├── Login.test.tsx
│ │ └── Login.tsx
│ └── product-description/
│ ├── ProductDescription.test.tsx
│ └── ProductDescription.tsx
├── context/
│ ├── productInfo.tsx
│ └── userInfo.tsx
├── hooks/
│ ├── useClickOutside.tsx
│ ├── useFetchData.tsx
│ └── useLocalStorage.tsx
├── services/
│ ├── api.tsx
│ └── navigation.tsx
├── utils/
│ ├── currencyConverter.tsx
│ └── dateParser.tsx
├── App.css
├── App.tsx
├── index.css
├── main.tsx
├── Routes.tsx
└── vite-env.d.ts

#### Description

- **assets/**: Contains static assets like images.
- **components/**: Contains reusable components, organized by feature.
- **context/**: Contains context providers for state management.
- **hooks/**: Custom hooks for reusable logic.
- **services/**: Contains API service files and other utilities.
- **utils/**: Utility functions.
- **App.tsx**: The main application component.
- **main.tsx**: Entry point of the application.
- **Routes.tsx**: Defines the application's routes.

### Custom Project

The custom project architecture allows for flexibility and can be tailored to meet specific project needs.

#### Folder Structure

src/
├── assets/
│ └── images/
├── components/
│ └── ExampleComponent.tsx
├── context/
│ └── ExampleContext.tsx
├── pages/
│ ├── AboutPage.tsx
│ ├── ContactPage.tsx
│ └── HomePage.tsx
├── services/
│ └── navigation.tsx
├── hooks/
│ └── useCustomHook.tsx
├── styles/
│ └── global.css
├── utils/
│ └── helpers.ts
├── App.tsx
├── Routes.tsx
└── index.tsx

#### Description

- **assets/**: Contains static assets like images, fonts, etc.
- **components/**: Contains reusable components.
- **context/**: Contains context providers for state management.
- **pages/**: Contains page components representing different views.
- **services/**: Contains API service files and other utilities.
- **hooks/**: Custom hooks for reusable logic.
- **styles/**: Global and component-specific styles.
- **utils/**: Utility functions.
- **App.tsx**: The main application component.
- **main.tsx**: Entry point of the application.
- **Routes.tsx**: Defines the application's routes.

## Getting Started

Follow these instructions to set up and run the project.

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

Clone the repository and install the dependencies:

```bash
git clone git@github.com:iammilankhati/Desigining-React-Architecture.git
cd Desigining-React-Architecture
npm install
npm start
```
