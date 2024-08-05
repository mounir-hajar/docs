---
sidebar_position: 2
---

# Create a Page

This tutorial will guide you through creating a new page on My Site.

## Step 1: Create the Page

Create a new Markdown file under the `docs/` directory.

## Step 2: Add the Page to Sidebar

Update `sidebars.js` to include the new page.

```javascript
module.exports = {
  someSidebar: {
    'Getting Started': ['intro', 'tutorial-basics/create-a-page'],
    'Advanced Topics': ['tutorial-extras/manage-docs-versions', 'tutorial-extras/translate-your-site'],
  },
};
