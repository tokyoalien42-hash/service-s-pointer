Milk - Admission Gate update

Added a standalone, user-controlled admission gate:
- Feature toggle is independent; disabled restores the site's original reply behavior.
- While enabled and locked, normal user messages still trigger replies, but partner text replies draw only from the user-maintained secret-code pool.
- Replies are single-message during verification, with sticker/emoji extras and partner poke/persona switching suppressed.
- User manually unlocks after checking a response, or locks again at any time.
- Settings and pool are stored in a separate localStorage key; existing backup JSON structures are not changed.
