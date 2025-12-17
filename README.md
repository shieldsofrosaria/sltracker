# 🛍️ Second Life Shopping Tracker

A comprehensive web application to track your Second Life shopping wishlist, purchases, and inventory. Organize items across multiple lists, track prices, add images, and manage your virtual shopping efficiently!

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

### 📋 Core Functionality
- **Multiple Lists**: Wishlist, Shopping List, Sort, and Inventory tabs
- **Custom Lists**: Create unlimited themed lists (Wedding, Halloween, etc.)
- **Image Uploads**: Upload product images via ImgBB (automatic cloud storage)
- **Price Tracking**: Track L$ prices with automatic totals
- **Search & Filter**: Global search + category/creator filters in inventory
- **Tags System**: Add custom tags for easy item discovery

### 🎨 Organization
- **Categories**: 14 built-in categories (Animations, Clothing, Heads, Home & Garden, etc.)
- **Subcategories**: 24 Home & Garden subcategories (Furniture types, Lighting, etc.)
- **Status Tracking**: Move items through workflow (Wishlist → Shopping → Sort → Inventory)
- **Extended Details**: Track Color, Head, Body, Hairstyle Type, Clothing Type, Bakes on Mesh

### 🔥 Advanced Features
- **Dark Mode**: Beautiful purple/gold theme with smooth transitions
- **Bulk Actions**: Select multiple items to move or delete at once
- **Keyboard Shortcuts**: 
  - `A` - Open add item form
  - `B` - Toggle bulk edit mode
  - `Esc` - Close modals/forms
  - `Ctrl/Cmd + S` - Export data
- **Quick Copy**: One-click copy for marketplace links and SLURLs
- **Animated UI**: Smooth transitions and category color coding
- **Mobile Responsive**: Works perfectly on desktop and mobile

### 💾 Data Management
- **localStorage**: All data stored locally in your browser
- **ImgBB Integration**: Images stored in the cloud (free, unlimited)
- **Export/Import**: Backup your data as JSON files
- **No Account Required**: Everything works offline after initial load

## 🚀 Quick Start

### Option 1: Direct Use (Easiest)
1. Download `second-life-tracker.html`
2. Open it in any modern web browser
3. Start adding items!

### Option 2: Host on GitHub Pages
1. Create a new GitHub repository
2. Upload `second-life-tracker.html`
3. Rename it to `index.html`
4. Enable GitHub Pages in repository settings
5. Access via `https://yourusername.github.io/repository-name`

### Option 3: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000/second-life-tracker.html
```

## 📖 How to Use

### Adding Items
1. Click the **➕ Add Item** button on any tab
2. Fill in item details:
   - **Required**: Item Name, Status
   - **Optional**: Store/Creator, Category, Tags, Price, Links, Images
3. **For Sort/Inventory items**: Extended fields appear automatically
4. Click **Add to [Tab Name]** to save

### Working with Categories
- Select **Home & Garden** to reveal subcategory options
- Choose from 24 subcategory types (Furniture, Lighting, etc.)
- Extended fields appear when status is "Sort" or "Inventory"

### Managing Custom Lists
1. Click **📋 Create List** button
2. Give your list a name and icon
3. Assign items to custom lists via the form dropdown
4. Items in custom lists don't appear in regular tabs

### Bulk Operations
1. Click **Bulk Edit** button (or press `B`)
2. Select items using checkboxes
3. Use bulk action bar to:
   - Move items to different tabs
   - Delete multiple items
   - Select/deselect all

### Searching
- Use the **global search bar** at the top to search across all items
- In **Inventory tab**: Filter by category and creator
- Search looks through names, stores, tags, and notes

## 🎨 Customization

### Dark Mode
- Click the 🌙 button in the bottom-right corner
- Beautiful purple gradient with gold accents
- Preference automatically saved

### Custom Lists
- Create unlimited lists for any purpose
- Each list has its own icon and color
- Perfect for events, projects, or themes

### Extended Fields (Sort/Inventory only)
- **Color**: Free text field
- **Head**: Dropdown with Espen, Martian Mutt, Abaddon + custom
- **Body**: Dropdown with popular bodies + custom
- **Hairstyle Type**: Short, Medium, Long, etc. + custom
- **Clothing Type**: Top, Bottom, Dress, etc. + custom
- **Bakes on Mesh**: Yes/No/Not specified

## 🛠️ Technical Details

### Built With
- **React 18**: UI framework
- **Tailwind CSS**: Styling
- **ImgBB API**: Image hosting
- **localStorage**: Data persistence

### Browser Support
- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Optimized

### Data Storage
- **Items**: Stored in `localStorage` as JSON
- **Images**: Uploaded to ImgBB cloud
- **Custom Lists**: Stored in `localStorage`
- **Settings**: Dark mode, custom options stored locally

### ImgBB API Key
The app includes a pre-configured ImgBB API key for free image hosting. If you need your own:
1. Get a free API key at [ImgBB](https://api.imgbb.com/)
2. Replace the key in the code: `const IMGBB_API_KEY = 'your-key-here'`

## 📊 Data Export/Import

### Export
1. Go to **Settings** tab
2. Click **Export All Data**
3. Save the JSON file as backup

### Import
1. Go to **Settings** tab
2. Click **Import Data**
3. Select your previously exported JSON file
4. Data will merge with existing items

## 🎯 Best Practices

### Organization Tips
- Use **Tags** liberally for easy searching
- Add **Prices** to track spending
- Use **Custom Lists** for events or projects
- Keep **Store Links** and **Landmarks** for quick access
- Add **Images** to remember what items look like

### Workflow Suggestions
1. **Wishlist**: Items you might want someday
2. **Shopping List**: Items you're actively looking for
3. **Sort**: Items purchased but not yet organized in SL
4. **Inventory**: Items sorted and ready to use in SL

### Maintenance
- **Export regularly** to backup your data
- **Delete old items** you no longer need
- **Review tags** periodically for consistency
- **Add subcategories** to Home & Garden items

## 🐛 Troubleshooting

### Images Not Uploading
- Check your internet connection
- Ensure image is under 5MB
- Try a different image format (JPG, PNG)

### Data Not Saving
- Check if localStorage is enabled in browser
- Clear browser cache if issues persist
- Export data before clearing cache

### Dark Mode Not Working
- Refresh the page
- Check if browser supports CSS variables
- Clear browser cache

### Search Not Working
- Ensure you're typing in the search bar
- Check if items have the keywords you're searching for
- Try broader search terms

## 🔐 Privacy & Security

- **No Account Required**: Everything stored locally
- **No Data Collection**: We don't track or collect anything
- **ImgBB Privacy**: Images uploaded with public visibility
- **Browser Only**: All processing happens in your browser

## 📝 Version History

### v1.0.0 (December 2025)
- Initial release
- Core tracking functionality
- Custom lists support
- Dark mode
- Bulk operations
- Extended fields for Sort/Inventory
- Home & Garden subcategories
- Global search
- Keyboard shortcuts

## 🤝 Contributing

This is a personal project, but suggestions are welcome! Feel free to:
- Report bugs
- Suggest features
- Share your use cases

## 📄 License

MIT License - Feel free to use and modify for personal use

## 🙏 Acknowledgments

- Built for Second Life enthusiasts
- ImgBB for free image hosting
- React and Tailwind CSS teams
- Claude AI for development assistance

## 📞 Support

For questions or issues:
- Check the Troubleshooting section above
- Review your browser console for error messages
- Ensure you're using a modern browser

---

**Happy Shopping in Second Life!** 🎮💜✨

*Made with love for the SL community*
