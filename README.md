# 🎣 Fishing App - Hotwire Rails Learning Project

A modern Rails application built to demonstrate **Hotwire** (Turbo + Stimulus) capabilities. This app is all about fishing... and hopefully catching! 🐟

## 📚 About This Project

This application serves as the practical example for the [**Hotwire for Rails Developers**](https://pragmaticstudio.com/courses/hotwire-rails) course by The Pragmatic Studio. The course teaches how to build fast, responsive Rails frontends using Hotwire without writing custom JavaScript.

### What is Hotwire?

Hotwire is made up of **Turbo** and **Stimulus**:
- **Turbo** - A set of technologies (Turbo Drive, Turbo Frames, and Turbo Streams) for dynamically updating parts of a page
- **Stimulus** - A lightweight JavaScript framework that complements Turbo when you need a dash of JavaScript

## 🚀 Features Implemented

This app demonstrates real-world Hotwire patterns including:

- **Turbo Drive** - Accelerated page navigation across the entire app
- **Turbo Frames** - Independent page section updates without full page reloads
- **Turbo Streams** - Dynamic partial page updates for multiple elements
- **Stimulus Controllers** - Search-as-you-type, form handling, and JavaScript library integration
- **Real-time Updates** - Broadcasting changes across multiple browsers
- **Lazy Loading** - Efficient content loading with infinite scrolling
- **Form Handling** - Inline editing, validation errors, and dynamic form updates
- **Interactive Features** - Filtering, sorting, and pagination of data tables

## 🛠 Tech Stack

- **Ruby on Rails 7.1** with Hotwire as the default frontend approach
- **SQLite** for development database
- **Turbo Rails** for SPA-like interactions
- **Stimulus** for lightweight JavaScript functionality
- **Tailwind CSS** for styling
- **esbuild** for JavaScript bundling
- **Brakeman** for security scanning
- **RuboCop** for code linting

## 🏃‍♂️ Getting Started

### Prerequisites

- Ruby 3.2.2 or higher
- Node.js 18+ (for JavaScript dependencies)
- Yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd fishing
   ```

2. **Install dependencies**
   ```bash
   bundle install
   yarn install
   ```

3. **Setup the database**
   ```bash
   bin/rails db:prepare
   bin/rails db:seed:replant
   ```

4. **Start the development server**
   ```bash
   bin/dev
   ```

5. **Visit the application**
   Open [http://localhost:3000](http://localhost:3000) in your browser

## 🧪 Running Tests

```bash
# Run all tests
bin/rails test

# Run system tests
bin/rails test:system

# Run security scan
bundle exec brakeman --ignore-config config/brakeman.ignore

# Run linting
bin/rubocop

# Audit JavaScript dependencies
yarn audit
```

## 🏗 Development

### Development Tools

- **Foreman** - Process manager for running multiple services
- **Live Reloading** - Automatic browser refresh during development
- **Hot Module Replacement** - Fast CSS/JS updates without page refresh

### Code Quality

- **RuboCop** with Rails Omakase configuration for consistent Ruby code style
- **Brakeman** for security vulnerability scanning
- **Yarn Audit** for JavaScript dependency security

## 📖 Learning Resources

This app is designed as a hands-on learning experience for the **Hotwire for Rails Developers** course, which covers:

1. **Turbo Drive** - Speed up page navigation
2. **Turbo Frames** - Update page sections independently
3. **Turbo Streams** - Dynamic multi-element updates
4. **Stimulus Basics** - Adding JavaScript behavior to server-rendered HTML
5. **Real-time Features** - Broadcasting updates with Action Cable
6. **Advanced Patterns** - Form handling, lazy loading, and JavaScript integration

**Course Details:**
- 23 in-depth videos (3.5 hours total)
- Lifetime access with source code
- Designed for experienced Rails developers
- Focus on practical, real-world examples

## 🎯 Key Learning Outcomes

After working through this app and course, you'll understand:

- ✅ When to use Turbo Drive vs. Turbo Frames vs. Turbo Streams
- ✅ How to handle forms, validations, and errors with Hotwire
- ✅ Best practices for organizing Stimulus controllers
- ✅ Strategies for integrating JavaScript libraries
- ✅ Techniques for real-time updates and broadcasting
- ✅ Performance optimization with lazy loading

## 🌐 Demo

Check out the [live demo](https://gone-fishing-studio.herokuapp.com/) to see the official application in action!

## 🤝 Contributing

This is a learning project, but feel free to:
- Report bugs or issues
- Suggest improvements
- Share your own Hotwire implementations

## 📄 License

This project is for educational purposes as part of The Pragmatic Studio's Hotwire course.

---

*Happy coding and tight lines! 🎣*
