# T9 Phone Word Finder

A browser-based T9 word lookup tool with a visual phone keypad and ~700+ built-in English words.

## Features
- Visual phone keypad (keys 2–9 with letter labels)
- Click keys or type digits 2–9 on keyboard (Backspace and Delete/Escape supported)
- Hardcoded word list of ~700+ common English words (3–7 letters)
- T9 mapping: 2=abc, 3=def, 4=ghi, 5=jkl, 6=mno, 7=pqrs, 8=tuv, 9=wxyz
- Results grouped by word length with match count
- Letter combination hint display (e.g., 4663 → ghi · mno · mno · def)
- Backspace and Clear buttons
- Quick-example buttons (try 4663, 843, 46368, etc.)
- Keyboard input support

## How to Use
1. Open `index.html` in any modern browser
2. Click digit buttons or type 2–9 on your keyboard
3. Matching words appear instantly on the right
4. Click ⌫ (backspace) or CLR, or press Backspace/Escape to reset
5. Try the example buttons to see interesting T9 sequences

## Tech
- Static HTML/CSS/JS — no server needed
- Tailwind CSS via CDN
- No persistence (no localStorage)
- All word matching done client-side with a precomputed digit→words map
