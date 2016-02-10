# cartalyst
Ruby on Rails study app - shopping cart locator app

Summary: Stray shopping cart registry     — A Ruby on Rails app development study, possible micro-business.

Why?  Shopping carts losses amount to ~$15m/yr.  Carts cost somewhere around $125 (probably paying less in bulk), and disappear at a rate of 12%/yr, blighting neighborhoods and costing stores and consumers.

http://articles.latimes.com/1989-06-30/business/fi-2984_1_cart-retrieval-cart-theft-carts-last-year

Solution:
Sign up stores who will pay a modest reward
Sign up neighbors/citizens who will report the location and store id of found carts
Reward upon retrieval is a) split somehow between site, incident reporters, or optionally donated to local charity such as food bank or homeless shelter.

App should

-  allow signing up member stores.  Do stores pay a fee to join, or just a success fee?
-  allow neighbor sign-up, with payment or donation preference options.
- allow charity signup/listing
- Have map integration to allow point/click and/or street view location reporting
- Be mobile-friendly (responsive css design).

Second iteration should:

- Have iOS / Android versions available in app store.
- Mobile version should allow device location to be used along with reporting
- Could integrate with QR or barcode sticker for scanning, which could be sold in bulk to stores to place on carts
- Allow private label branding.
- Allow advertising to defray expenses

Issues:

- How to ensure store picks up cart, and the site gets credit for this? (Logging/verification)
- Communication mechanism with stores, users.

Functionality:

- User can sign up
- Store can sign up or be signed up by admin
- User sees a cart,
    - notes location and store name
    - or snaps a photo
    - or scans a label
- Enters same into app when available (or from app on site when mobile app is available)
- App notifies store of found cart
- (Store retrieves cart)
- App charges store (or store may be on subscription basis)
- App pays finder(s) or donates to selected charity.
- Summary info may be sent periodically to stores or users.
