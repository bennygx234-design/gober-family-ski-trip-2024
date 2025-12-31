# Gober Family Ski Trip - Google Sites Instructions

## Files Created
- `index.html` - Your complete ski trip webpage with animations

---

## Option 1: Use Google Sites Native Features (Recommended)

Since Google Sites has limited HTML embedding, here's how to recreate this beautiful design directly in Google Sites:

### Step 1: Create a New Google Site
1. Go to [sites.google.com](https://sites.google.com)
2. Click the **+** button to create a new site
3. Name it "Gober Family Ski Trip 2024"

### Step 2: Set Up the Theme
1. Click **Themes** in the right panel
2. Choose a dark/blue theme or click **Custom**
3. Set colors:
   - Primary: `#1e3a5f` (Mountain Blue)
   - Accent: `#e07c4c` (Sunset Orange)
4. Font: Choose "Playfair Display" for headers, "Montserrat" for body

### Step 3: Create the Header Section
1. Click on the header area
2. Add a **Title**: "Gober Family Colorado Ski Adventure"
3. Add **Subtitle**: "December 2024 | Steamboat Springs & Vail"
4. Change header type to "Large Banner"
5. Upload a scenic mountain photo as the background

### Step 4: Add Your Photos from Google Drive

#### For Each Photo Section:
1. Click **Insert** (right panel) > **Image** > **Upload** or **Select from Drive**
2. Navigate to your Google Drive folder with ski trip photos
3. Select the photo and click **Insert**

#### Creating Photo Galleries:
1. Click **Insert** > **Image carousel** for a slideshow
2. Add multiple photos from your Drive
3. Adjust the carousel settings (auto-play, timing)

#### Photo Grid Layout:
1. Click **Insert** > **Collage**
2. Select multiple photos (up to 4)
3. Choose your preferred layout

### Step 5: Add Content Sections

#### Section 1: Our Adventure
1. Add a new section (click + between sections)
2. Add heading: "Our Adventure"
3. Insert 3 columns layout
4. Add these cards with icons and text:
   - **Skiing & Snowboarding** - Describe your experiences
   - **Mountain Lodges** - Talk about your accommodations
   - **Family Bonding** - Share special moments

#### Section 2: Photo Gallery
1. Add section with heading "Photo Gallery"
2. Use **Image Carousel** for featured photos
3. Add **Collage** blocks for grouped photos
4. Label photos with captions

#### Section 3: Our Destinations
1. Add section "Our Destinations"
2. Create 2-column layout
3. **Steamboat Springs** card with:
   - Photo from Steamboat
   - Description of your experience
   - Stats: 165+ Trails, 3,668 ft vertical
4. **Vail** card with:
   - Photo from Vail
   - Description of your experience
   - Stats: 195+ Trails, 5,317 acres

#### Section 4: Trip Highlights
1. Add section "Trip Highlights"
2. Create timeline using text blocks or numbered list
3. Include your favorite memories:
   - First day on slopes
   - Best powder day
   - Favorite meal/restaurant
   - Funny moments
   - etc.

### Step 6: Add Navigation
1. At top of page, pages menu appears automatically
2. You can add sub-pages for:
   - Day 1 Photos
   - Day 2 Photos
   - Videos
   - etc.

---

## Option 2: Embed Custom HTML (Limited)

Google Sites allows embedding HTML in an iframe:

### Method A: Embed Code Block
1. In Google Sites, click **Insert** > **Embed** > **Embed code**
2. Paste simple HTML/CSS snippets
3. **Note**: Full page embedding has limitations

### Method B: Host HTML Externally
1. Upload `index.html` to:
   - GitHub Pages (free)
   - Google Cloud Storage
   - Firebase Hosting
   - Netlify (free)

2. Get the public URL

3. In Google Sites:
   - Click **Insert** > **Embed** > **By URL**
   - Paste your hosted page URL
   - Adjust the size to full width

---

## Option 3: GitHub Pages Hosting (Free)

### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Sign up for free account

### Step 2: Create Repository
1. Click **New Repository**
2. Name it: `gober-ski-trip`
3. Make it **Public**
4. Check "Add a README file"
5. Click **Create repository**

### Step 3: Upload Files
1. Click **Add file** > **Upload files**
2. Drag and drop `index.html`
3. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to **Settings** > **Pages**
2. Under "Source", select **main** branch
3. Click **Save**
4. Your site will be live at: `https://yourusername.github.io/gober-ski-trip`

### Step 5: Embed in Google Sites
1. Copy your GitHub Pages URL
2. In Google Sites: **Insert** > **Embed** > **By URL**
3. Paste the URL
4. Resize to full width

---

## Adding Your Photos to the HTML File

### To Replace Placeholders with Real Photos:

1. **Open `index.html`** in a text editor (Notepad, VS Code, etc.)

2. **Find the gallery items** (search for "gallery-item")

3. **Replace placeholder with your image:**

**Before:**
```html
<div class="gallery-item reveal">
    <div class="photo-placeholder">
        <div class="photo-placeholder-icon">&#127935;</div>
        <p>Skiing Action Shot</p>
    </div>
</div>
```

**After:**
```html
<div class="gallery-item reveal">
    <img src="YOUR_IMAGE_URL_HERE" alt="Skiing at Steamboat">
    <div class="gallery-overlay">
        <h4>Skiing at Steamboat</h4>
        <p>First day on the slopes!</p>
    </div>
</div>
```

### Getting Google Drive Image URLs:

1. Open your photo in Google Drive
2. Click **Share** > **Anyone with link can view**
3. Copy the link (looks like: `https://drive.google.com/file/d/FILE_ID/view`)
4. Convert to direct image URL:
   ```
   https://drive.google.com/uc?export=view&id=FILE_ID
   ```
   Replace `FILE_ID` with the actual ID from your link

### Example:
If your Drive link is:
`https://drive.google.com/file/d/1ABC123xyz/view`

Your image URL becomes:
`https://drive.google.com/uc?export=view&id=1ABC123xyz`

---

## Quick Start Checklist

- [ ] Create new Google Site
- [ ] Set up mountain blue/orange color theme
- [ ] Add hero banner with family photo
- [ ] Create "Our Adventure" section with 3 cards
- [ ] Add photo gallery with your Google Drive images
- [ ] Create Steamboat and Vail destination cards
- [ ] Add trip highlights timeline
- [ ] Include photo captions and dates
- [ ] Review and publish site
- [ ] Share link with family!

---

## Tips for Best Results

1. **Photo Sizes**: Use landscape photos (16:9) for headers and galleries
2. **Compression**: Large photos may load slowly - resize to ~1920px wide
3. **Captions**: Add dates and locations to help remember details
4. **Organization**: Create Drive folders by day or location
5. **Videos**: Google Sites supports YouTube embeds for trip videos

---

## Color Palette Reference

Use these colors in Google Sites custom theme:
- **Mountain Blue**: #1e3a5f
- **Deep Navy**: #0f172a
- **Pine Green**: #2d5a3d
- **Sunset Orange**: #e07c4c
- **Golden Hour**: #f4a460
- **Snow White**: #f8fafc
- **Sky Blue**: #87ceeb

---

Enjoy your memories! ⛷️🏔️

The Gober Family - Colorado 2024
