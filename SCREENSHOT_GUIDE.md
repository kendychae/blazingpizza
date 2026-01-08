# 📸 Screenshot Guide for Canvas Submission

## What Your Screenshot Should Show:

```
┌─────────────────────────────────────────────────────────────────┐
│  🔴 BLAZING PIZZA LOGO     [🍕 GET PIZZA]                      │  ← HEADER (Top Bar)
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Blazing Pizzas                                                 │
│                                                                  │
│  [Pizza 1]    [Pizza 2]    [Pizza 3]                           │
│   $10.99       $12.99       $9.99      ← USD Currency ($)      │  ← PIZZA LIST
│                                                                  │
│  [Pizza 4]    [Pizza 5]    [Pizza 6]                           │
│   $11.50       $13.25       $8.99                              │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│  Created by Keendahl Bingham | United States of America        │  ← FOOTER
└─────────────────────────────────────────────────────────────────┘
```

## ✅ Checklist - Your Screenshot MUST Include:

### Top Section (Header):
- [ ] Blazing Pizza logo visible
- [ ] "Get Pizza" navigation tab with pizza slice icon

### Middle Section (Main Content):
- [ ] "Blazing Pizzas" heading
- [ ] Multiple pizza cards displayed
- [ ] Prices showing **$** (dollar sign), NOT £ (pound sign)
- [ ] Pizza images and descriptions

### Bottom Section (Footer):
- [ ] Text: "Created by **Keendahl Bingham**"
- [ ] Text: "United States of America"

---

## 🎯 Taking the Perfect Screenshot:

### Step 1: Start the Application
```powershell
cd c:\Users\kendy\BlazingPizza
dotnet run
```

### Step 2: Open Browser
- Navigate to: `https://localhost:5001` or `http://localhost:5000`
- Wait for pizzas to load (2-3 seconds)

### Step 3: Adjust Window
- **Make sure you can see:**
  - Full header at top
  - At least 3-4 pizza cards
  - Full footer at bottom
- **If footer isn't visible:** Scroll down slightly or zoom out (Ctrl + Mouse Wheel)

### Step 4: Capture Screenshot
**Windows 11/10:**
- Press `Windows + Shift + S` for Snip & Sketch
- Or use `Windows + PrintScreen` for full screen
- Or use Snipping Tool app

**Save the screenshot as:**
- `BlazingPizza_KeendahlBingham.png` or
- `W03_Assignment_Screenshot.png`

---

## ⚠️ Common Issues & Solutions:

### Issue: Prices still show £
**Solution:** Hard refresh browser (Ctrl + F5)

### Issue: Footer not visible
**Solution:** 
1. Zoom out (Ctrl + Mouse Wheel Down)
2. Or scroll down slightly
3. Or maximize browser window

### Issue: Header not showing
**Solution:** Scroll to top of page, hard refresh (Ctrl + F5)

### Issue: No pizzas loading
**Solution:** 
1. Check terminal for errors
2. Wait 5-10 seconds for database initialization
3. Refresh page (F5)

---

## 📏 Screenshot Specifications:

- **Format:** PNG or JPG
- **Resolution:** At least 1280x720 (HD)
- **Quality:** Clear, readable text
- **Content:** All three sections visible (header, pizzas, footer)

---

## 🎨 Example Screenshot Names:

Good names:
- ✅ `BlazingPizza_Assignment_KeendahlBingham.png`
- ✅ `W03_BlazorNavigation_Screenshot.png`
- ✅ `CSE325_Week3_BlazingPizza.png`

Bad names:
- ❌ `Screenshot1.png`
- ❌ `Untitled.png`
- ❌ `image.jpg`

---

## 📤 Submission to Canvas:

1. Take screenshot following guide above
2. Save with professional filename
3. Go to Canvas assignment page
4. Upload screenshot file
5. In comments, add your GitHub repository URL
6. Submit!

---

## ✨ Pro Tips:

1. **Test before screenshot:** Click on a pizza to verify dialog works
2. **Check currency:** Look at sidebar prices if you added pizzas to cart
3. **Professional appearance:** Clear, well-lit screenshot
4. **Verify all requirements:** Use the checklist above

---

## 🏆 Perfect Screenshot Checklist:

Before submitting, verify your screenshot shows:
- [ ] Logo in top-left corner
- [ ] "Get Pizza" tab in header
- [ ] Multiple pizzas visible
- [ ] ALL prices show $ (dollar), NOT £ (pound)
- [ ] Footer with your name: "Keendahl Bingham"
- [ ] Footer with country: "United States of America"
- [ ] Clear, readable text
- [ ] Professional appearance

---

## 📞 If Something Goes Wrong:

1. **Application won't start:** Run `dotnet build` to check for errors
2. **Wrong currency showing:** Clear browser cache (Ctrl + Shift + Delete)
3. **Layout broken:** Hard refresh (Ctrl + F5)
4. **Database error:** Delete `pizza.db` file and restart app

---

## 🎉 You're Ready!

Follow this guide, take your screenshot, and submit with confidence!

Your work demonstrates professional-level Blazor development. Great job! 🚀
