# Camagru - Web Application Project  
(Under development)

## 🎯 Project Overview

**Camagru** is a web application project that challenges you to create an Instagram-like website where users can create composite images using their webcam and predefined overlays. It's your first substantial web development project that combines frontend and backend development with multimedia processing.

> **Summary:** The goal of this project is to build a web application.

## 💡 Project Concept

Camagru allows users to:
- Take photos with their webcam
- Select from predefined overlay images (with alpha channels)
- Combine their photos with overlays to create fun composite images
- Share their creations in a public gallery
- Like and comment on other users' images

**Example Use Case:** Creating a photo of yourself with an intergalactic cat background or picture frame overlay.

## 🛠️ Technical Requirements

### Allowed Technologies
| Layer | Technologies |
|-------|-------------|
| **Server** | Any language (limited to PHP standard library equivalents) |
| **Client** | HTML, CSS, JavaScript (browser native APIs only) |
| **Frameworks** | CSS frameworks allowed (if no JavaScript), Server frameworks limited to PHP standard library equivalents |  
I use `PHP` , `Typescript` and `Tailwind css`

### Mandatory Features
- **Containerization** (Docker/docker-compose) for easy deployment
- **Responsive design** that works on mobile and desktop
- **No errors** in console (server or client side)
- **Secure implementation** (no SQL injection, XSS, etc.)

## 🔐 Security Requirements
- **No plain text passwords** in database
- **HTML/JavaScript injection protection**
- **Secure file upload validation**
- **SQL injection prevention**
- **CSRF protection**

## 👥 User Management Features

### Authentication System
- **User registration** with email, username, and complex password
- **Email verification** via unique confirmation link
- **Login/logout functionality**
- **Password reset** via email
- **Profile management** (update username, email, password)

## 🖼️ Gallery Features
- **Public gallery** of all user creations
- **Ordered by creation date**
- **Like and comment system** (logged-in users only)
- **Email notifications** for new comments (default: on)
- **Pagination** (minimum 5 images per page)


### Editing Functionality
- **Webcam preview** and capture
- **Selectable overlay images** (must select before capturing)
- **Server-side image processing** (combining webcam image + overlay)
- **Alternative upload** for users without webcams
- **Personal image management** (delete own images only)

## 🚀 Deployment & Compatibility

### Containerization
- **Must use Docker/docker-compose** or equivalent
- **One-command deployment**

### Browser Compatibility
- **Firefox** (>= 41)
- **Chrome** (>= 46)
