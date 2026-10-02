## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `sf-water-map`.
2. Upload `index.html` to the repository root and commit it to the `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. GitHub will provide a URL similar to:
   `https://YOUR-USERNAME.github.io/sf-water-map/`

## Embed in Squarespace

Add a Code Block to the Squarespace page, select HTML, and paste:

```html
<iframe
  src="https://YOUR-USERNAME.github.io/sf-water-map/"
  title="San Francisco water metrics"
  loading="lazy"
  style="width:100%; height:1500px; border:0;"
></iframe>
```

Adjust `height:1500px` if the surrounding Squarespace section needs more or less vertical space. On narrower screens, the four maps automatically stack into one column.

## Interaction

- Hover over a sample marker or bottled-water reference for its value.
- Click or tap a map marker to update the detailed sample summary beneath the maps.
- The map supports both light and dark browser color schemes.

## Updating data

Replace `index.html` with a revised version and commit the change. GitHub Pages will update the public map automatically.
