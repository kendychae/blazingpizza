# Quick Start Guide - Blazing Pizza

## What You Need to Do

### 1. Run the Application

Open PowerShell in the project directory and run:

```powershell
dotnet run
```

The application will start and display URLs like:

```
Now listening on: https://localhost:5001
Now listening on: http://localhost:5000
```

### 2. Take Screenshot for Canvas Submission

1. Open your browser to `https://localhost:5001` or `http://localhost:5000`
2. Wait for the pizza list to load
3. Take a screenshot that includes:
   - **Top**: Navigation bar with Blazing Pizza logo and "Get Pizza" tab
   - **Middle**: Pizza cards showing prices in dollars ($)
   - **Bottom**: Footer with "Created by **Keendahl Bingham** | United States of America"

### 3. Verify Your Changes

✅ **Currency Check**: All prices should display with $ (dollar sign), not £ (pound)  
✅ **Header Check**: Logo and navigation visible at top  
✅ **Footer Check**: Your name "Keendahl Bingham" and "United States of America" at bottom

### 4. Upload to GitHub

If you haven't already created a repository:

```powershell
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit changes
git commit -m "Complete W03 Assignment - Blazor Navigation and Routing with USD currency"

# Create a repository on GitHub, then:
git remote add origin YOUR_GITHUB_REPO_URL
git branch -M main
git push -u origin main
```

### 5. Submit to Canvas

1. Submit your screenshot showing header, pizza list, and footer
2. Include your GitHub repository URL in the submission comments

---

## Troubleshooting

**Problem:** Application won't start  
**Solution:** Make sure you're in the correct directory (`c:\Users\kendy\BlazingPizza`) and .NET 8.0 SDK is installed

**Problem:** Prices still showing £  
**Solution:** Hard refresh your browser (Ctrl+F5) to clear cached CSS

**Problem:** Footer not visible  
**Solution:** Scroll down or zoom out to see the footer at the bottom of the page

---

## What Was Changed

1. ✅ Currency changed from £ (GBP) to $ (USD) in all locations
2. ✅ Added navigation header with logo and "Get Pizza" tab
3. ✅ Added footer with your name and country
4. ✅ Updated project to .NET 8.0 for compatibility
5. ✅ Application builds with zero errors

---

## Professional Portfolio Note

This project demonstrates:

- Blazor Server development
- CSS customization
- Component architecture
- State management
- Entity Framework Core integration

Perfect for showing to future employers!
