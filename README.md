# 🔴 Red Sea Tire

A modern, responsive tire shop website with intelligent filtering system to help customers find their perfect tires and services.

![Red Sea Tire](https://images.unsplash.com/photo-1593941707882-a5bba14938c7?w=800)

## ✨ Features

- **🔍 Advanced Filtering System**
  - Filter by category (Passenger, SUV/Truck, Performance, Winter, Services)
  - Filter by vehicle type (Sedan, SUV, Truck, Sports Car, etc.)
  - Filter by tire type (All-Season, Winter, Summer, All-Terrain, Performance)
  - Filter by maximum price
  
- **📱 Fully Responsive Design**
  - Works perfectly on desktop, tablet, and mobile devices
  - Modern gradient UI with smooth animations
  
- **⚡ Fast & Lightweight**
  - No backend required - pure HTML/CSS/JavaScript
  - All data embedded for instant loading
  - Can be hosted on GitHub Pages for free
  
- **🎯 User-Friendly Interface**
  - Clear product cards with images and specifications
  - Popular products highlighted with badges
  - Easy-to-use filter controls with reset option
  - Real-time results counter

## 🚀 Quick Start

### Option 1: Open Locally
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start browsing tires and services!

### Option 2: GitHub Pages (Online Hosting)
1. Fork this repository
2. Go to Settings → Pages
3. Select "main" branch and save
4. Your site will be live at `https://yourusername.github.io/redsea-tire/`

## 📦 What's Included

- **14 Products Total**
  - 3 Passenger Car Tires
  - 3 SUV & Truck Tires
  - 2 Performance Tires
  - 2 Winter Tires
  - 4 Tire Services

## 🎨 Customization

To add or modify products, edit the `tireData` object in the `<script>` section of `index.html`:

```javascript
const tireData = {
    categories: [
        {
            id: 'your-category-id',
            name: 'Your Category Name',
            items: [
                {
                    name: 'Product Name',
                    description: 'Product description',
                    price: 99.99,
                    // ... more fields
                }
            ]
        }
    ]
};
```

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling with gradients, animations, and responsive design
- **Vanilla JavaScript** - Filtering logic and DOM manipulation
- **No dependencies** - Works without any frameworks or libraries

## 📋 Product Categories

1. **Passenger Car Tires** - All-season and touring tires for sedans and coupes
2. **SUV & Truck Tires** - Rugged all-terrain and luxury tires for larger vehicles
3. **Performance Tires** - High-performance summer tires for sports cars
4. **Winter Tires** - Specialized tires for snow and ice conditions
5. **Tire Services** - Installation, alignment, rotation, and repair services

## 🌟 Key Features Breakdown

### Filtering System
- Multiple simultaneous filters can be applied
- Instant results update
- Shows count of matching products
- "No results" message when no matches found

### Product Display
- High-quality product images
- Category badges
- Type tags for quick identification
- Detailed specifications
- Clear pricing
- Popular items marked with star badge

### Responsive Design
- Grid layout adapts to screen size
- Mobile-friendly navigation
- Touch-friendly buttons and controls

## 📸 Screenshots

The website features:
- Beautiful purple gradient background
- Clean white cards with rounded corners
- Hover effects on product cards
- Smooth animations
- Professional typography

## 🔗 Live Demo

[View Live Demo](https://yourusername.github.io/redsea-tire/) *(Update with your GitHub Pages URL)*

## 📄 License

MIT License - Feel free to use this project for your own purposes.

## 👨‍💻 Author

Red Sea Tire Sample Project

## 🤝 Contributing

Feel free to fork this project and customize it for your needs!

---

Made with ❤️ for Red Sea Tire

