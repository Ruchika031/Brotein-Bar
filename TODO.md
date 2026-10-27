# Brotein Bar — TODO

## 1. Brand, home, menu and quick reorder
- [x] Create a mobile-first web app called “Brotein Bar”: a healthy Indian protein-meal ordering app run by a college student startup. Customers are college students and staff who order in the evening. Goal: order in under 60 seconds, reorder in one tap. All food is vegetarian.
- [x] Use a clean, fresh, energetic, trustworthy style. Primary deep green, accent warm orange, off-white and light-green backgrounds. Rounded cards, bold headings, large tap targets.
- [x] Logo: green rounded square with “B” + wordmark “Brotein Bar”. Tagline: “Healthy Indian Nutrition Hub”. Use generated real-food photographs for menu items and hero. No emoji icons, no chicken or non-veg imagery, no fake ratings, reviews or statistics.
- [x] Home has a sticky header with logo, cart icon with item count and “Order now” button; a hero with “Healthy Indian Nutrition Hub”, the one-line message “Fresh, protein-rich Indian meals from ₹10. Evening orders: 4:00 PM to 8:00 PM”, and “Order now” / “View menu” buttons.
- [x] “Your last order” card with one-tap “Reorder” appears after the customer enters their phone number and a matching saved order is found.
- [x] Category chips: Salads, Sandwiches, Snacks, Drinks. Filters: Veg, High protein, Under ₹50.
- [ ] Menu cards have a food photograph, name, one-line description, price, veg dot, estimated calories and protein, and add button that becomes a - 1 + stepper. Estimates are clearly identified as approximate per serving. Values are integrated for 12 items; Paneer Salad and Soya Spicy Salad need your estimates, and Yoga Bar needs the pack label.
- [x] Use exactly this menu and prices: Salads—Paneer Salad ₹60; Soya Spicy Salad ₹40; Sprouts Salad ₹40; Chickpea Salad ₹40. Sandwiches—Chilli Paneer Sandwich ₹50; Veggie Sandwich ₹40; Peanut Butter Bread ₹20. Snacks—Overnight Rolled Oats ₹50; Sweet Corn Chaat ₹30; Flavoured Makhana ₹30; Multigrain Chips ₹50; Yoga Bar ₹45. Drinks—Banana Smoothie ₹50 / ₹80; Cold Coffee ₹40; Masala Tea ₹10.

## 2. Item details and cart
- [ ] Item detail bottom sheet includes food photography, description, estimated calories, protein, carbohydrates, fat and fibre per serving, a quantity stepper, customization chips (Custom portion, Spice level, Extra veggies, Protein boost), notes field, and “Add to cart”. Values are approximate per the stated serving; three product values remain pending.
- [x] Cart is a slide-in drawer with items, quantity controls and remove, subtotal, and “Checkout”; keep cart count synced and provide a friendly empty-cart state.

## 3. Checkout and order confirmation
- [x] Checkout fields: name, phone, hostel/location [LOCATION OPTIONS], time slot [EVENING SLOTS], notes.
- [x] Payment methods: Cash or UPI on delivery. “Place order” button.
- [x] Order confirmation shows Order ID, summary, requested time slot, “Reorder”, and “Message us on WhatsApp” linked to 9729505574.

## 4. About and contact
- [x] About and contact shows “[How Brotein Bar started: 2 lines]”, team “Bhawna and Ruchika · Co-founders”, Instagram @broteinbar.lmtsm, and phone 9729505574.

## 5. Desktop admin dashboard
- [x] Admin dashboard (desktop) has summary cards: orders, revenue, average order value, repeat-customer %.
- [x] Orders table has time, customer, items, total, and status dropdown (New / Preparing / Delivered).

## 6. Responsive polish and interaction
- [x] Smooth add-to-cart animation, loading skeletons, friendly empty-cart state, consistent components, good contrast, works on small phones.

## Delivery boundary
The ordering flow, confirmation, and admin orders currently use this browser’s local storage only; orders are not transmitted to the Brotein Bar team. A backend is needed for live fulfillment. The confirmation WhatsApp link is connected to the supplied business number.
Nutrition estimates are user-provided approximations. Exact values may differ with the actual recipe and portion; Yoga Bar needs its specific wrapper label.
