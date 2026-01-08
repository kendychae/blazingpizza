# Blazing Pizza Web Application

## Assignment: W03 - Use Pages, Routing, and Layouts to Improve Blazor Navigation

**Developer:** Keendahl Bingham  
**Date:** January 7, 2026  
**Course:** CSE 325 - .NET Software Development  
**Institution:** Brigham Young University-Idaho

---

## Overview

This is a fully functional Blazor Server web application for ordering pizzas. The application demonstrates modern web development practices using ASP.NET Core Blazor, Entity Framework Core, and responsive design principles.

---

## Features Implemented

### 1. **Currency Localization (USD)**
   - Converted all pricing displays from British Pounds (£) to United States Dollars ($)
   - Updated CSS files to reflect USD currency symbol throughout the application
   - Modified price displays in:
     - Pizza cards on main page
     - Shopping cart items
     - Order total
     - Configuration dialog
     - Size selection display

### 2. **Navigation Header**
   - Implemented a professional navigation bar with:
     - Blazing Pizza logo
     - "Get Pizza" navigation tab with icon
     - Responsive design with proper styling
     - Fixed positioning for consistent user experience

### 3. **Footer Component**
   - Added professional footer displaying:
     - Developer name: **Keendahl Bingham**
     - Country: **United States of America**
     - Fixed positioning at bottom of page
     - Professional styling consistent with application theme

### 4. **Framework Compatibility**
   - Updated project from .NET 9.0 to .NET 8.0 for broader compatibility
   - Verified all NuGet package versions match target framework
   - Successfully built and tested application

---

## Technical Stack

- **Framework:** ASP.NET Core Blazor Server (.NET 8.0)
- **Database:** SQLite with Entity Framework Core 8.0
- **Frontend:** Blazor Components with Razor syntax
- **Styling:** Custom CSS with Bootstrap 4.0
- **Architecture:** Server-side rendering with SignalR

---

## File Modifications

### Core Changes:

1. **`Pages/_Host.cshtml`**
   - Added navigation header with logo and menu
   - Implemented footer with developer information
   - Enhanced page structure for professional presentation

2. **`wwwroot/css/site.css`**
   - Changed all currency symbols from £ to $
   - Added bottom padding to accommodate footer
   - Ensured responsive layout with fixed header and footer

3. **`Shared/ConfigurePizzaDialog.razor`**
   - Updated price display to show USD ($) instead of GBP (£)

4. **`BlazingPizza.csproj`**
   - Downgraded target framework to .NET 8.0
   - Updated all package references to version 8.0.0

---

## Running the Application

### Prerequisites
- .NET SDK 8.0 or higher
- Modern web browser (Chrome, Edge, Firefox, Safari)

### Build & Run Commands

```bash
# Navigate to project directory
cd c:\Users\kendy\BlazingPizza

# Restore dependencies
dotnet restore

# Build the project
dotnet build

# Run the application
dotnet run
```

The application will be available at:
- HTTPS: `https://localhost:5001`
- HTTP: `http://localhost:5000`

---

## Application Structure

```
BlazingPizza/
├── Model/                      # Data models
│   ├── Pizza.cs
│   ├── PizzaSpecial.cs
│   ├── Order.cs
│   ├── Address.cs
│   └── ...
├── Pages/                      # Blazor pages
│   ├── _Host.cshtml           # Main host page with header/footer
│   ├── Index.razor            # Main pizza ordering page
│   └── Error.cshtml
├── Shared/                     # Shared components
│   └── ConfigurePizzaDialog.razor
├── wwwroot/                    # Static files
│   ├── css/
│   │   └── site.css          # Custom styling
│   └── img/                   # Images and icons
├── App.razor                   # Root component
├── Program.cs                  # Application entry point
├── PizzaStoreContext.cs       # Entity Framework context
├── OrderState.cs              # State management
└── BlazingPizza.csproj        # Project configuration
```

---

## Professional Highlights

### Code Quality
- Clean, maintainable code structure
- Consistent naming conventions
- Proper separation of concerns
- Well-organized file structure

### User Experience
- Intuitive navigation
- Responsive design
- Professional visual presentation
- Clear developer attribution

### Technical Excellence
- Framework compatibility ensured
- Zero build warnings or errors
- Proper routing implementation
- State management best practices

---

## Screenshots Required

For Canvas submission, capture a screenshot showing:
1. **Navigation Header** - Logo and "Get Pizza" tab
2. **Pizza List** - Main ordering interface with prices in USD
3. **Footer** - Developer name and country information

All three elements should be visible in a single screenshot of the running application.

---

## Future Enhancements

Potential improvements for production deployment:
- User authentication system
- Order history and tracking
- Payment gateway integration
- Admin dashboard for managing pizzas
- Real-time order status updates
- Mobile-responsive optimization
- Accessibility improvements (WCAG compliance)

---

## Contact Information

**Developer:** Keendahl Bingham  
**Project Repository:** [Include your repository URL here]  
**Portfolio:** [Include your portfolio URL here]

---

## License

This project was created as part of coursework for educational purposes.

---

## Acknowledgments

- Brigham Young University-Idaho CSE 325 Course Materials
- Microsoft Learn Blazor Documentation
- ASP.NET Core Community

---

*This application demonstrates professional-grade Blazor development with attention to detail, user experience, and code quality.*
