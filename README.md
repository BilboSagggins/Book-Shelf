# Kyle's Bookshelf

A 3D bookcase for tracking what you read. Live at **https://bilbosagggins.github.io/Book-Shelf/** once GitHub Pages is on.

- Three shelves: **Read**, **Reading now**, **Want to read**, one at a time as tabs. Page through a full shelf with the arrows or by swiping, and sort by shelf order, rating, title or author. Books in a series sit together in reading order as a matched set (series and number come from your Goodreads import, or set them on any book). The bookcase stays pinned at the top while the rest of the page scrolls.
- Tap a spine to take the book down and see its cover. Open it for the jacket blurb and similar books.
- Rate books, add notes, and move them between shelves.
- **Recommendations** come from the subjects of the books you rated highest.
- **Import from Goodreads**: on goodreads.com go to My Books > Import and export > Export Library, then choose the .csv on the page.

## Where the data comes from

Covers come from [Google Books](https://books.google.com) (English editions, fast) with [Open Library](https://openlibrary.org) as the fallback. Blurbs come from Google Books, then Open Library. Subjects, similar books and recommendations come from Open Library. When Open Library has no description, the blurb comes from the book's [Wikipedia](https://en.wikipedia.org) summary. No account or API key needed.

Your books are saved in the browser you use (local storage), so each device keeps its own shelves. Importing your Goodreads export on each device is the quickest way to fill them.

## Turning on GitHub Pages

Settings > Pages > Source: **Deploy from a branch** > Branch: **main**, folder **/ (root)** > Save.
