# Random Access Poetry

A poetry creation game.

## How it is played

The user makes a selection of books, a page within each of them, and a sentence from each of those pages.

The process of selection involves some randomness.

They can rearrange the resulting sentences as they like to create a poem.

That's it. 

## How it is created

A number of books from the public domain will be made available, perhaps from project Gutenberg or HathiTrust.

The program will have a user interface with a hand drawn feel.

It should be possible to drag and drop words to put them in order. It should also be possible to erase words.

Programming languages, frameworks, etc.:
- Python to download and prepare books.
- Vite + TypeScript
- Plain TypeScript for UI
- Rough.js for hand drawn look
- Sortable.js for drag and drop?
- Howler.js for sound
- Web Speech API
- GoogleFonts

## Random ideas

It might be fun if the user can 'peek' during book selection. For example, they are supposed to close their eyes and then press the spacebar to select while books are presented.

Eyes closed as a mode can have fun implications.

Sounds for book presentation, page flipping, sentence selection. Dialogue? Especially useful if you're not supposed to look.

Use a vintage looking hand dingbat as a cursor. Relaxed + pinch mode. Eraser cursor.

Nice font. Different fonts for different books?

Book spines.

Tactility??

# Plan v0

- Get books (minimum selection 2-3)
- Functions to (with a simple GUI)
    - Select a book
    - Select a page
    - Select a sentence
    - Drag and drop words
    - Erase / scratch out words