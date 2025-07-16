<<<<<<< HEAD
# Birthday Countdown Website 🎂✨

A beautiful, animated birthday countdown website with two pages:
1. **Countdown Timer Page** (`test1bday.html`) - Shows a countdown to the birthday with a gift box
2. **Birthday Card Page** (`birthday-card.html`) - Displays a beautiful birthday card with cake, candles, and animations

## Features

### Countdown Timer Page
- ⏰ Real-time countdown timer (days, hours, minutes, seconds)
- 🎁 Animated gift box that scales and shakes when timer hits zero
- 💖 Floating hearts background animation
- ✨ Girly pink/purple color scheme with sparkle effects
- 📱 Responsive design for mobile devices

### Birthday Card Page
- 🎂 Beautiful white vanilla cake with 22 animated candles
- 🎊 Falling confetti animation
- 🎈 Balloons floating up from bottom corners
- 💕 Heartfelt appreciation message
- 🌟 Floating decorative elements (hearts, stars, butterflies)
- 🔥 Flickering candle flames

## How to Use

1. **Set the Birthday Date**: 
   - Open `test1bday.html`
   - Find line 318: `const birthdayDate = new Date(Date.now() + 30000).getTime();`
   - Replace with your friend's actual birthday: `const birthdayDate = new Date('2024-12-25 00:00:00').getTime();`
   - Use format: 'YYYY-MM-DD HH:MM:SS'

2. **Customize the Message**:
   - Open `birthday-card.html`
   - Edit the message in the `.message-text` paragraphs (around lines 200-210)
   - Change the signature at the bottom

3. **Adjust the Age**:
   - The cake currently has 22 candles
   - To change: modify the loop in `createCandles()` function (line 185 in birthday-card.html)
   - Change `for (let i = 0; i < 22; i++)` to your friend's age

## File Structure
```
bdaycard_test/
├── test1bday.html      # Countdown timer page (main entry point)
├── birthday-card.html  # Birthday card page
└── README.md          # This file
```

## How It Works

1. User opens `test1bday.html` and sees the countdown timer
2. When timer reaches zero:
   - Gift box scales to 2.5x size and centers on screen
   - Gift box starts shaking
   - "Click to Open!" text appears
3. Clicking the gift box navigates to `birthday-card.html`
4. Birthday card page shows:
   - Confetti falling from top
   - Balloons floating up from bottom corners
   - Animated cake with flickering candles
   - Beautiful appreciation message

## Customization Tips

- **Colors**: All colors use CSS custom properties and can be easily changed
- **Fonts**: Uses Google Fonts (Dancing Script for headings, Poppins for body text)
- **Animations**: All animations are CSS-based for smooth performance
- **Mobile-friendly**: Responsive design works on all screen sizes

## Browser Compatibility

Works in all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

Enjoy creating a magical birthday surprise! 🎉💕
=======
# BDAY_web1
>>>>>>> f50b942f8d33e9fc7a726c963259bc0770834806
