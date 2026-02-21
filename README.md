# KISAAN-VAANI(MADE FOR SIH-2025)
# Kisan Vaani - Farmer Marketplace

Kisan Vaani is a web-based platform built for Indian farmers to sell crops directly to buyers at fair prices, search for crop information using Hindi voice input, check live mandi prices, earn rewards through a game, and unlock instant farm loans.

Built by Team Binary Brains: Kushal, Mishti, Param, Den, Rudraksh, Manasvi

---

## About the Project

Kisan Vaani bridges the gap between Indian farmers and buyers. The platform is designed with rural accessibility in mind, supporting both Hindi and English. Farmers can list their produce, buyers can browse and purchase directly, and the gamified reward system encourages daily engagement while providing access to financial tools like farm loans.

---

## Features

### Home Page (index.html)
- Bilingual interface in Hindi and English
- Hero section with farmer branding and tagline
- Navigation to all modules including voice search, marketplace, and live prices

### Login Page (login.html)
- Role-based login for Farmer, Buyer, and Agent
- Mobile number and password authentication
- Auto-redirects to the correct dashboard based on selected role
- Animated background with floating agricultural icons

### Buyer Marketplace (buyer.html)
- Browse crop listings from farmers across multiple Indian states
- Filter by state, price range, and certifications such as Organic and FSSAI
- Category tabs for Grains, Vegetables, Fruits, Spices, and Dairy
- Shopping cart with quantity controls and checkout
- Wishlist system to save preferred listings
- Direct farmer contact option
- Recent order tracking with delivery status indicators

### Voice Search
- Hindi speech recognition using the Web Speech API
- Auto-translates spoken Hindi to English
- Searches the crop database by voice input

### Live Mandi Prices
- State-wise price lookup
- Covers Punjab, Haryana, Uttar Pradesh, West Bengal, Telangana, and Arunachal Pradesh

### Kisan Pong - Play and Earn (game.html)
- Pong-style game with a wheat ball and agricultural theme
- AI opponent that increases in difficulty as the score rises
- Reward system where every 100 game points equals Rs 1 added to the wallet
- Withdraw earnings to bank via UPI ID or phone number with a minimum of Rs 10
- Loan unlock feature where earning 500 game points gives access to instant farm loans
- Loan options ranging from Rs 5,000 to Rs 50,000 with low interest rates
- Transaction history for all earnings and withdrawals

---

## File Structure

```
Kisaan vaani/
    index.html
    login.html
    buyer.html
    game.html
    styles.css
    script.js
    server.js
    main.cpp
    attached_assets/
```

---

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Web Speech API for voice recognition
- Canvas API for the Pong game
- Font Awesome for icons
- Google Fonts
- Node.js and C++ for backend

---

## How to Run

1. Clone the repository

```
git clone https://github.com/your-username/kisan-vaani.git
```

2. Open the project folder in VS Code

3. Install the Live Server extension in VS Code

4. Right-click on index.html and select Open with Live Server

5. The project will open at http://localhost:5500

No npm install or build step is required for the frontend. All dependencies load from CDN.

---

## Pages and Navigation

Page | File | Description
--- | --- | ---
Home | index.html | Main landing page
Login | login.html | Role-based authentication
Buyer Dashboard | buyer.html | Crop browsing and purchasing
Play and Earn | game.html | Pong game with rewards and loans

---

## Reward and Loan System

The Kisan Pong game is integrated with a financial incentive system designed to reward farmer engagement.

- Each point scored equals 10 game points
- Every 100 game points equals Rs 1 added to the wallet
- Minimum withdrawal amount is Rs 10 via UPI
- Processing time for withdrawals is 24 to 48 hours
- Earning 500 game points unlocks access to farm loans
- Loan amounts available are Rs 5,000 at 5 percent, Rs 15,000 at 4 percent, and Rs 50,000 at 3.5 percent per annum

---

## Contact

Helpline: 1800-XXX-XXXX

Email: support@kisanvaani.in

---

## License

This project was built for hackathon purposes by Team Binary Brains. All rights reserved.
