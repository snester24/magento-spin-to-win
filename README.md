# magento-spin-to-win
Marketing gamification feature for upgraded Magento 2 clients.

# Spin to Win - Magento 2 Marketing Feature

This repo contains the frontend code and UX for a new Magento 2 upgrade feature called **Spin to Win**. It's a gamified popup wheel users can spin to unlock discounts or free shipping. This feature increases engagement and conversion rates.

## ✅ What’s Included

- Fully styled HTML/CSS/JavaScript (Vanilla)
- Prebuilt marketing text and prize segments
- Spin animation logic
- Email validation
- "Congrats" + "Offer applied" toast logic
- Fade-out and close functionality

## 🛠️ Developer Notes (for Tim & team)

### Backend Settings Needed:
- Toggle (Enable/Disable the popup)
- Editable Header & Subtext
- 8 Prize Segment Labels & Types (Free Shipping / % Off / Try Again)
- Optional link to Cart Price Rules
- Color Theme Selector (Red / Blue / Green)
- Trigger rules (Delay, page condition, one-per-session)

### Integration Notes:
- Ideally loaded via knockout template block or popup module
- Should respect session rules / cookies for trigger control
- Cart Price Rule or coupon should auto-apply based on win outcome

---

## 💡 Status
Frontend: ✅ Complete  
Backend: 🔧 In development (needs Magento 2 integration)

---

## Questions?
Contact: Stephen Nester snester@emercahntclub.com
