# User Stories: Favorites Functionality

This feature allows users to save and manage meditation exercises or articles they find helpful, providing easy access to personalized content.

---

## User Story 1: Add to Favorites

**As a user**,  
I want to add an item to my Favorites,  
**so that** I can save activities or articles I like for quick access later.

### Acceptance Criteria:
- A heart icon with the text “Add to Favorites” is displayed next to each item.
- The outlined heart indicates the item is not in Favorites.
- Tapping the button:
  - Adds the item to the Favorites list.
  - Updates the button text to “Remove from Favorites.”
  - Changes the heart icon to filled.

---

## User Story 2: Remove from Favorites

**As a user**,  
I want to remove an item from my Favorites,  
**so that** I can manage my saved content.

### Acceptance Criteria:
- A filled heart icon with the text “Remove from Favorites” is shown for favorited items.
- Tapping the button:
  - Removes the item from the Favorites list.
  - Reverts the heart icon to outlined.
  - Updates the button text to “Add to Favorites.”
- Users can add or remove items anytime, and UI updates reflect changes.

---

## User Story 3: View Favorites List

**As a user**,  
I want a “My Favorites” screen,  
**so that** I can view and manage all my saved items in one place.

### Acceptance Criteria:
- The “My Favorites” screen displays a list of saved items.
- Each item includes:
  - Title
  - Category
  - Duration
- Users can:
  - Tap any item to view details or start the activity.
  - Browse the list easily in an organized layout.
