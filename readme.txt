# 🐾 Pet Adoption Site 🐶

## What's This All About? 😺
Hey there! This is a super cool website where you can check out adorable pets waiting for their forever homes. It pulls in pet info from an online database and shows them off in fun categories with pop-up details. Perfect for animal lovers! 🐕‍🦺

## Cool Features 🐱
- 🏷️ Browse pets by type (like dogs, cats, birds – you name it!)
- 📸 See cute pet cards with name, breed, age, where they're from, and price
- 🔍 Click on any pet to see all the juicy details in a fancy modal popup
- 📱 Looks great on phones, tablets, and computers thanks to Tailwind CSS
- 😔 Shows a friendly "no pets found" message when a category is empty

## Tech Stuff Behind the Scenes 🤖
- **HTML5**: The skeleton of the website
- **CSS3**: Makes it pretty with Tailwind CSS and DaisyUI components
- **JavaScript**: Handles all the interactive bits and fetches pet data
- **Tailwind CSS**: Quick and easy styling toolkit
- **DaisyUI**: Fancy UI pieces built on Tailwind
- **Fetch API**: Grabs pet info from the internet

## Where Does the Pet Data Come From? 🌐
We use a free API from Programming Hero to get all the pet details:
- Categories: `https://openapi.programming-hero.com/api/peddy/categories`
- All Pets: `https://openapi.programming-hero.com/api/peddy/pets`
- Pets by Type: `https://openapi.programming-hero.com/api/peddy/category/{category}`

## How the Files Are Organized 📁
```
Adoption Site/
├── Peddy Website Design.fig    # Design sketch (probably from Figma)
├── Code/
│   ├── index.html              # The main webpage
│   ├── script.js               # Code that makes things happen
│   └── styles.css              # Extra style tweaks
└── images/                     # Pics of pets and stuff
```

## Getting Started 🚀
1. Grab the project files and put them on your computer.
2. Make sure you have a modern web browser (like Chrome or Firefox).
3. Just double-click `Code/index.html` to open it up!
   - No fancy setup needed – it's all ready to go.
   - Needs internet for the styles, but that's it.

## How to Use It 🖱️
1. When you open the site, you'll see buttons for different pet types.
2. Click a button to see pets in that category.
3. Scroll through the pet cards and click one to learn more.
4. A popup will show all the details – close it with the X or by clicking outside.

## Works On... 🌍
- Any modern browser with JavaScript turned on
- Tested on Chrome, Firefox, Safari, and Edge
- Mobile-friendly too!

## What It Needs to Run 💻
- Tailwind CSS (loads from the web): https://cdn.tailwindcss.com
- DaisyUI (also from the web): https://cdn.jsdelivr.net/npm/daisyui@latest/dist/full.css
- No extra software or downloads required

## For Coders Who Want to Tweak It 👨‍💻
- It's a single-page site – everything happens in your browser.
- All the magic is done with client-side JavaScript.
- API calls go straight from your browser to the pet database.
- We kept custom styles light, using mostly Tailwind shortcuts.

## Want to Help Make It Better? 🤝
Feel free to contribute:
1. Copy the project to your own space
2. Make your awesome changes
3. Test it out on different browsers
4. Send us your improvements!

## License 📜
This is open-source fun! Check for any specific rules if needed.

## Got Questions? 💬
Hit up the dev team if you need help or have ideas.

## Version Info 🔢
Version: 1.0.0

## Last Update 📅
March 2026