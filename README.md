# Anime-Character-Report_Power-BI

 How to Use This Report
1. Open the report in Power BI Desktop or Power BI Service.

2. Click on a character image to explore full profile.

3. Scroll through the description for in-depth background.

4. Click on the web link to view full profile on MyAnimeList.

📝 Overview
This interactive Power BI report showcases an in-depth profile view of popular anime characters using a combination of visual, textual, and web-linked data. The report emphasizes user-friendly exploration by allowing users to select characters through image thumbnails, enabling a visually intuitive search experience.

🔍 Key Features
🎯 Visual Character Selection (Image-based Search)
A key highlight of the report is the interactive character image table on the left panel.

This allows users to click on character images to instantly explore their:

English and Japanese names

Popularity rank and like count

Nicknames

Biography and traits

Anime series and external links

✅ Power BI Implementation:

Used the Image URL field in the table to display character images.

Enabled image search-style navigation where each image click filters detailed information on the page.

Makes the UX more immersive and intuitive, especially for visually recognized characters.

📁 Report Content Overview
🔹 SELECT CHARACTER (Left Panel)
Table visual with:

Character images (sourced via image URLs)

Popularity ranking

Allows direct character selection via click

🔹 PROFILE CARDS (Center & Right)
Name card (EN & JP)

Nickname card

Number of likes in bold color formatting

Web link to character page on MyAnimeList

Opens in browser for full character profile

Description section (scrollable card):

Age, origin, personality, role in anime

Written in detailed natural language

📦 Dataset Used
The report is based on an anime character dataset that includes:

Field	Description :
name =	Character's English name
japanese_name =	Japanese script representation
image_url =	Link to profile image (used in visuals)
ranking =	Popularity rank
likes =	Total likes received
nickname =	Known aliases
description =	Detailed biography
web_link =	External profile link


Report Feature	Details :-
1) 🎨 Colors & Sections	Used color-coded headers (purple, pink, yellow) to clearly segment each data zone.
2) 🖼️ Image URL Usage	Character images used to improve recognizability and enhance engagement
3) 🔗 External Integration	Hyperlinked MyAnimeList URLs for deeper research
4) 🧭 Scrollable Containers	For detailed text descriptions without overwhelming the layout
5) ⬅️ Navigation	Right arrow hints at possible multi-page report or drillthrough navigation

🔧 How It Works
📷 Visual Search Using Image URL
Dataset includes a image_url column with direct links to character images.

This column is marked as Data Category: Image URL in Power BI.

Added to a table visual and formatted to show thumbnail-style images.

Interactions set to cross-filter visuals when an image row is selected.

This mimics a “visual search engine” within Power BI — users can search and explore characters by face/image, just like browsing an anime wiki.

