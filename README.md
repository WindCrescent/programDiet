# FitPlan Pro - Multilingual Fitness Program Generator

FitPlan Pro is a modern web application that helps users create personalized fitness plans for both weight loss and muscle gain, available in multiple languages (English, French, and Arabic).

## Features

- **Multilingual Support**: English, French, and Arabic with automatic RTL layout for Arabic
- **User Account System**: Registration, login, and profile management
- **Personalized Programs**: 
  - Weight loss programs with calorie deficit plans
  - Muscle gain programs with progressive overload training
- **Comprehensive Fitness Plans**:
  - Weekly meal plans with customized calorie targets
  - Tailored workout routines that progress over time
  - Nutrition recommendations and macro distributions
  - Success tips and strategies
- **Program Management**: Save, edit, and track progress of multiple programs

## Project Structure

```
fitplan-pro/
├── index.html                 # Main HTML entry point
├── css/
│   └── styles.css             # Main stylesheet
├── js/
│   ├── translations.js        # Multi-language support
│   ├── ui-loader.js           # Template loader
│   ├── auth.js                # Authentication functionality
│   ├── program.js             # Program generation logic
│   ├── program-part2.js       # Program display logic
│   ├── utils.js               # Utility functions
│   └── main.js                # Application initialization
└── templates/
    ├── login-form.html        # Login interface
    ├── register-form.html     # Registration interface
    ├── welcome.html           # Welcome screen
    ├── step1-form.html        # Basic information form
    ├── step2-form.html        # Additional details form
    ├── loading.html           # Loading screen
    ├── results.html           # Program results display
    ├── my-plans.html          # Saved plans screen
    └── profile.html           # User profile screen
```

## Setup and Local Development

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/fitplan-pro.git
   ```

2. Navigate to the project directory:
   ```
   cd fitplan-pro
   ```

3. Serve the files using a local web server. For example, with Node.js installed:
   ```
   npx serve
   ```
   
   Or with Python:
   ```
   python -m http.server
   ```

4. Open your browser and go to `http://localhost:8000` (or the port provided by your server)

## Technical Implementation

- **No Frameworks**: Pure HTML, CSS, and JavaScript for lightweight performance
- **Tailwind CSS**: Used for styling and responsive design
- **Component-Based Structure**: Modular code organization with separate HTML templates
- **Dynamic Content Loading**: Templates loaded on demand to improve initial load time
- **Multilingual Support**: Complete translation system with language switching

## Future Enhancements

- Backend integration with user authentication
- Persistent data storage
- Progress tracking with charts
- Mobile app version
- Additional language support
- Exercise demonstration videos

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
