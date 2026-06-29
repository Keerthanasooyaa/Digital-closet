🌸 My Digital Closet

A Pinterest-aesthetic wardrobe organizer built with vanilla HTML, CSS, and JavaScript. Upload photos of your clothes, tag them by category, and generate random outfit combinations — all saved in your browser with no backend required.


Features


Photo upload — drag & drop or click to browse; supports JPG, PNG, and WEBP
Item tagging — categorize by type (tops, bottoms, dresses, outerwear, shoes, accessories), season, and color
Color picker — quick-select swatches for common wardrobe colors, or type a custom name
Masonry closet grid — Pinterest-style layout with staggered animations and category filters
Smart outfit generator — picks one piece per category; chooses a dress OR a top + bottom combo randomly
Persistent storage — items save to localStorage and survive page refreshes
Zero dependencies — single .html file, no build step, no server needed



Getting Started


Download digital-closet.html
Open it in any modern browser (Chrome, Firefox, Safari, Edge)
Start uploading your clothes


That's it — no installation, no accounts, no internet connection required after the page loads.


Note: The app uses Google Fonts (Cormorant Garamond + DM Sans) loaded from a CDN. An internet connection is needed on first load for correct typography; it works offline after the fonts are cached.




How to Use

Adding an item


Go to Add New Item in the sidebar
Drag & drop a photo onto the upload zone, or click to browse
Fill in the name, category, and optionally the season and color
Click Add to my closet


Browsing your closet


Click My Closet in the sidebar
Use the category chips at the top to filter by type
Hover any card to reveal the delete button (✕)


Generating an outfit


Click Outfit Generator in the sidebar
Hit Surprise me
The app randomly selects one item per category you own
Hit the button again to re-roll



Project Structure

digital-closet.html    # The entire app — HTML, CSS, and JS in one file
README.md              # This file


Tech Stack

LayerChoiceReasonMarkupHTML5Single-file, no bundler neededStylingVanilla CSS with custom propertiesNo framework overheadLogicVanilla JavaScriptZero dependenciesFontsCormorant Garamond + DM Sans (Google Fonts)Serif elegance + clean sans pairingStoragelocalStoragePersistent, browser-native, no backend


Design System

The UI uses a warm, feminine palette inspired by Pinterest editorial aesthetics:

TokenValueUsage--blush#F2D0CEBorders, backgrounds--rose#D4888APrimary actions, active states--rosedark#A85C5EHover states, sidebar accents--cream#FBF6F4Page background--linen#F4ECE9Input fields, stat boxes--ink#2E1F1FBody text, dark CTA buttons--muted#9A7474Secondary text, labels

Typography is set in Cormorant Garamond (serif, headings) paired with DM Sans (sans-serif, body and UI).


Browser Support

Works in all modern browsers. Requires:


ES6+ JavaScript (arrow functions, template literals, optional chaining)
localStorage API
FileReader API for image uploads
CSS custom properties



Limitations


Storage cap — localStorage is limited to ~5MB per origin. High-resolution photos will fill this quickly. If the closet stops saving, try resizing photos before uploading (aim for under 500KB per image).
No cloud sync — data lives only in the browser. Clearing browser storage or using a different device will not carry your closet over.
No export — there's currently no way to back up or export your wardrobe data.



Potential Improvements


 Cloud sync via a simple backend or Firebase
 Export / import as JSON for backup
 Outfit history and favorites
 Drag-to-reorder items
 Multiple outfit styles (casual, formal, date night)
 Weather-based outfit suggestions
 Mobile responsive layout



License

MIT — free to use, modify, and share.
