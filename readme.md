# CBWIRE + BoxLang QuickStart

A modern reactive web application starter template built with [CBWIRE](https://cbwire.ortusbooks.com) and [BoxLang](https://boxlang.io). This template demonstrates live data binding, component-based architecture, and responsive design with Bootstrap.

## Getting Started

To get this application running on your local machine:

### Prerequisites

You'll need [CommandBox](https://www.ortussolutions.com/products/commandbox) installed on your machine. If you don't have it yet, you can install it from the CommandBox website.

### Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/grantcopley/cbwire-boxlang-quickstart.git
   cd cbwire-boxlang-quickstart
   ```

2. **Install dependencies:**
   ```bash
   box install
   ```

3. **Start the development server:**
   ```bash
   box server start
   ```

That's it! Your application will be running and automatically open in your default browser.

## What's Included

- **CBWIRE Components**: Reactive form with live data binding
- **BoxLang**: Modern CFML runtime for better performance
- **Bootstrap 5**: Responsive design and modern UI components
- **Alpine.js**: Lightweight JavaScript framework (included with CBWIRE)

## Features Demonstrated

- Live form validation and data binding
- Component state management
- Real-time user feedback
- Responsive design patterns
- Modern CSS animations

## Core Files to Review

When exploring this quickstart, pay special attention to these key files:

### `wires/MyForm.bx` - The Component Logic
This is the CBWIRE component class that handles:
- **Data properties**: `name`, `email`, `submitted`, `hasErrors`
- **Validation constraints**: Rules for required fields and email format
- **Methods**: `submitForm()`, `onUpdate()`, `resetForm()`
- **Real-time validation**: Updates validation state as users type

### `wires/MyForm.bxm` - The Component Template  
This is the component's view template featuring:
- **Live data binding**: `wire:model.live` for reactive form fields
- **Conditional rendering**: Dynamic content based on component state
- **Validation feedback**: Error messages and visual indicators
- **Alpine.js integration**: Client-side interactivity with CBWIRE

### `layouts/Main.bxm` - The Application Layout
The main layout file showcasing:
- **Component integration**: How to wire components into layouts

Start with these files to understand how CBWIRE components work together!

## Learn More

- [CBWIRE Documentation](https://cbwire.ortusbooks.com)
- [BoxLang Documentation](https://boxlang.io/docs)
- [ColdBox Platform](https://www.coldbox.org)

---

**Built with ❤️ by [Ortus Solutions](https://www.ortussolutions.com)**