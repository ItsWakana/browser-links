# Personal Browser Homepage

`index.html` is a self-contained personal start page. Open it directly in a modern web browser; no installation, web server, account, or database is needed.

## Everyday use

- Select any link to open it in a new tab.
- Use **+ ADD** in a category to add a link directly to it.
- Hover a link to reveal **EDIT** and the delete button. Deleting always asks for confirmation.
- Drag a category box to change the category order.
- Drag a link over another link to place it above that link, or drag it onto a different category to move it there.
- Use the **SCRATCHPAD** at the bottom for a single auto-saving note. Its height expands as you type.

## Adding links and categories

Use **ADMIN MODE** to create categories or add links. Links support:

- Web addresses, such as `https://example.com`
- Local file URLs, such as `file:///C:/Sites/index.html`
- Windows paths, such as `C:\Sites\index.html`
- Relative local paths, such as `.\index.html`

Local-file links are subject to your browser's normal local-file security rules.

## Backup and restore

All categories, links, and their order are saved in the browser's local storage. The scratchpad is saved there separately.

Before clearing browser data or moving to another browser/computer:

1. Select **BACKUP** to copy the link directory as JSON.
2. Save that copied text somewhere safe.
3. On the new page/browser, select **IMPORT**, paste the JSON, and choose **Replace directory**.

Importing replaces the current link directory. It does not replace the scratchpad.

## Notes

- Website favicons are fetched using Google's favicon service; local files do not have favicons.
- Because data is stored per browser profile and page location, clearing site data can remove it. Keep occasional JSON backups.
