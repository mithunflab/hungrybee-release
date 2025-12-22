# Release Notes

## v1.0.7 (December 22, 2025)

### 🆕 New Features & Improvements
- **Star Customers Redesign**: 
  - Revamped UI with Dashboard-style colored stats cards (Green, Blue, Rose, Orange).
  - Modern Blue-Green (Teal) accents for buttons and controls.
  - Improved "Row View" with Pagination for better performance.
  - Added "Skeleton Loader" for smoother transitions.
- **Update System**:
  - Fixed "Download Update" button logic to only appear for strictly newer versions.
  - Better "Up to date" status messaging.

---

## v1.0.6 (December 21, 2025)

### 🆕 New Features & Improvements
- **Security Upgrade**: Strengthened device binding by validating Motherboard Serial Number and Machine GUID in addition to MAC Address.
- **Permission Awareness**: Added "Run as Administrator" warning if the application cannot retrieve hardware security IDs, ensuring better license enforcement.

---

## v1.0.5 (December 21, 2025)

### 🆕 New Features
- **Admin Bypass**: Added a secret shortcut (`Ctrl + G`) to bypass login for support/admin access.
- **Gesture Support**: Added long-press functionality (5 seconds) on the Login button to trigger the admin bypass popup.
- **UI Enhancements**: Added visual feedback (shake animation) for invalid bypass codes.

---

## v1.0.4 (December 18, 2025)

### 🆕 New Features & Improvements
- **Menu & Billing UI**: 
  - Card layout now supports "No Image" mode for compact viewing.
  - Improved category navigation with right-side sidebar in Menu page.
- **Update System**:
  - Enhanced update checking logic to prevent false "New Version" alerts.

### 🔧 Bug Fixes
- Fixed "Download" button appearing for the currently installed version.
- UI adjustments for better consistency across pages.

---

## v1.0.3 (December 15, 2025)

### 🆕 New Features
- **Login Page**: Added Terms & Conditions and License links to the bottom right.
- **Update System**: Improved update reliability.

---

## v1.0.2 (December 15, 2025)

### 🆕 New Features
- **Redesigned Landing Page**: Modern, pixel-perfect design.
- **Improved Sidebar**: Auto-collapse on Billing page.
- **Header Enhancements**: Dynamic width for tabs.

### 🔧 Bug Fixes
- Fixed "Page Not Found" on Netlify deployment.
- Fixed Dashboard Graph date selection.

---

## v1.0.1 (December 15, 2024)

### 🆕 New Features
- **Software Update System**: Added auto-update functionality in Settings page
  - Check for updates directly from the app
  - Download and install updates with one click
  - Data is preserved during updates
- **UPI QR Payment**: iPhone-style QR popup for Card and Scan payments
  - Dynamic amount embedded in QR code
  - Supports Google Pay, PhonePe, and all UPI apps

### 🎨 UI Improvements
- **Dashboard Redesign**: Complete overhaul with POS-focused metrics
  - Total Revenue, Orders, Pending Orders, Low Stock alerts
  - Sales Overview chart with daily trends
  - Profit Overview with margin percentage
  - Top Selling Products list
  - Recent Orders with status
- Improved spacing and card boundaries for cleaner look
- Light gray background for better visual separation

### 🔧 Bug Fixes
- Fixed dashboard white screen (missing icon import)
- Fixed duplicate function declarations in sidebar
- Removed unused color property references

### 📦 Technical
- Added electron-updater for auto-update support
- Configured GitHub releases for update distribution
- Updated TypeScript declarations for new APIs

---

## v1.0.0 (December 2025)

Initial release with full POS functionality.

### Features
- Complete billing and order management
- Menu and inventory management
- Table layout management
- Thermal printer support
- Data export/import
- Dark mode support
- Supabase-based licensing system
