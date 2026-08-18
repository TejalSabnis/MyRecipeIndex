# 🎀 MyRecipeIndex

A cute, girlie, fully local recipe-keeping website. No server, no account, no
internet connection required once the page is open (aside from loading the
Google Fonts on first launch). Everything lives as plain `.md` files in
folders on your own computer.

## How to use it

1. Unzip this folder somewhere on your computer (e.g. Desktop or Documents).
2. Open **index.html** by double-clicking it. It'll open in your default
   browser.
   - **Best in Chrome, Edge, or Opera.** These are the only browsers that
     currently support letting a webpage read and write local folders
     directly (the "File System Access API"). Safari and Firefox can view
     the page but the "Open Recipe Folder" button won't work in them.
3. Click **"Open Recipe Folder"** and select the included `Recipes` folder
   (or any folder you like — an empty one works too).
4. Your browser will ask for permission to read/write that folder — allow it.
   That's it! From here everything you do is saved as real files instantly.

The next time you open `index.html`, it will remember the folder you picked
and ask to reopen it automatically (you may need to re-approve permission).

## What you can do

- **New Category** — creates a real subfolder (e.g. `Recipes/Breakfast`).
  You can nest categories inside categories too.
- **New Recipe** — creates a `.md` file inside whichever category you choose,
  and opens it straight into the editor.
- **Edit** — a friendly form for the title, servings, prep/cook time,
  ingredients (amount + unit + item), step-by-step instructions, and notes.
  Saving writes a clean markdown file to disk.
- **Move** — moves a recipe's `.md` file into a different category folder.
- **Rename** — renames the recipe (and its file).
- **Delete** — removes a recipe or an entire category (careful, this is
  permanent — it deletes the real file/folder).
- **Search** — searches recipe titles across every category at once.

## The file format

Every recipe is a plain, readable markdown file, so you can also open, edit,
or write them directly in any text editor if you'd like. Example:

```markdown
# Fluffy Pancakes

**Servings:** 4
**Prep Time:** 10 min
**Cook Time:** 15 min

## Ingredients

- 1.5 cups flour
- 1 pinch salt
- 1 whole egg

## Instructions

1. Whisk the dry ingredients together.
2. Mix in the wet ingredients until just combined.
3. Cook on a griddle until golden on both sides.

## Notes

Add vanilla for extra flavor!
```

Because it's just markdown in folders, your whole recipe box is easy to back
up, sync with Dropbox/iCloud/Google Drive, put under version control, or move
to a new computer — just copy the folder.

## Included sample recipes

This zip comes with a starter `Recipes` folder containing three categories
(`Breakfast`, `Dinner`, `Desserts`) each with one sample recipe, so you can
see the format and try things out immediately. Feel free to delete the
samples once you're ready to add your own!
