# Quick Start Guide - SPACEZ Coupons Page

## 🚀 Run the App in 3 Steps

### Prerequisites
Make sure you have Flutter installed. Check with:
```bash
flutter doctor
```

### Step 1: Get Dependencies
```bash
flutter pub get
```

### Step 2: Choose Your Platform

#### Option A: Run on Web (Easiest)
```bash
flutter run -d chrome
```
or
```bash
flutter run -d edge
```

#### Option B: Run on Android
```bash
# Make sure Android emulator is running
flutter run -d emulator-5554
```

#### Option C: Run on iOS (Mac only)
```bash
flutter run -d ios
```

#### Option D: Run on Windows
```bash
flutter run -d windows
```

### Step 3: Test the App

Once running, try clicking on:
- ✅ Back button → Shows success message
- ✅ Menu icon → Shows success message
- ✅ Apply buttons on any coupon → Shows applied message
- ✅ Read more links → Shows success message
- ✅ Reserve button → Shows success message

## 📱 What You'll See

### Main Screen
1. **Header**: SPACEZ logo and menu
2. **Title**: "Coupons" with back arrow
3. **Coupon Cards**: 
   - Price on left in orange (₹6,900)
   - Details on right with Apply button
4. **Payment Offers**: Section with more coupons
5. **Bottom Bar**: Booking info and Reserve button

### Features
- 🎨 Pixel-perfect design matching Figma
- 🖱️ All buttons are interactive
- 📱 Responsive layout
- ✨ Smooth scrolling
- 💚 Success messages on interactions

## 🛠️ Project Structure

```
lib/
  └── main.dart          # Complete app in one file
      ├── MainApp        # Root widget
      └── CouponsPage    # Main page widget
          ├── AppBar
          ├── Title Bar
          ├── Coupon Cards (ListView)
          └── Bottom Bar
```

## 🎨 Design Colors

- **Brand Orange**: `#B85C3E`
- **Success Green**: `#2D7F5E` → `#3A9B75`
- **Background**: White
- **Text**: Black/Grey variants

## 📝 Code Quality

✅ No compilation errors  
✅ No analyzer warnings  
✅ Properly formatted  
✅ Clean architecture  
✅ Follows Flutter best practices

## 💡 Tips

1. **Hot Reload**: Press `r` in terminal after making changes
2. **Hot Restart**: Press `R` for full restart
3. **Stop App**: Press `q` in terminal

## ❓ Troubleshooting

### "No devices available"
```bash
# Check available devices
flutter devices

# Start Android emulator
flutter emulators --launch <emulator_id>
```

### "Build failed"
```bash
# Clean build
flutter clean

# Get dependencies again
flutter pub get

# Try running again
flutter run
```

### "Port already in use" (Web)
```bash
# Kill the process or use different port
flutter run -d chrome --web-port=8081
```

## 📚 Additional Resources

- **README.md**: Full project documentation
- **IMPLEMENTATION.md**: Technical implementation details
- **DESIGN_COMPARISON.md**: Design vs implementation comparison
- **SUBMISSION_GUIDE.md**: How to submit to GitHub

## 🎯 Assignment Completion

All requirements met:
- ✅ Pixel-perfect UI from Figma
- ✅ All buttons interactive
- ✅ Success messages on clicks
- ✅ Frontend-only (no backend)
- ✅ Clean, maintainable code
- ✅ Ready for GitHub submission

## 🚀 Next Steps

1. Run and test the app
2. Review the code in `lib/main.dart`
3. Check all interactive elements work
4. Read `SUBMISSION_GUIDE.md` for GitHub submission
5. Submit your repository URL to SPACEZ

---

**Need Help?**
- Check `README.md` for detailed documentation
- Review `IMPLEMENTATION.md` for technical details
- Follow `SUBMISSION_GUIDE.md` for submission process

**Happy Coding! 🎉**
