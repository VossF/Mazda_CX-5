# Mazda CX-5 private sale microsite

This is a simple static GitHub Pages microsite for privately sharing a 2021 Mazda CX-5 Signature Turbo before listing it on used-car marketplaces.

It uses only:

- `index.html`
- `styles.css`
- image files inside `photos/`
- no backend, no forms, no cookies, no analytics, no build step

## 1. Replace the car details

Open `index.html` in a text editor and search for the details you want to change, for example:

- `50,500 km aprox.`
- `[415,000]`
- `Guadalajara / Zapopan`
- `[Agregar detalle si aplica]`
- `correo@ejemplo.com`

Save the file after editing.

## 2. Replace the WhatsApp number

In `index.html`, search for:

```text
52XXXXXXXXXX
```

Replace it with your WhatsApp number in international format, without spaces or punctuation.

Example format for Mexico:

```text
5213312345678
```

Keep the rest of the link as-is unless you want to edit the prefilled message.

## 3. Add photos

Put your car photos in the `photos/` folder using these exact file names:

- `exterior-front.jpg`
- `exterior-rear.jpg`
- `side.jpg`
- `interior-front.jpg`
- `interior-rear.jpg`
- `dashboard.jpg`
- `odometer.jpg`
- `tires.jpg`
- `service-history.jpg`

Important: blur plates before uploading photos if the plates are visible.

Do not upload photos of factura, registration, insurance, ID, or documents with personal data.

## 4. Enable GitHub Pages

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose your main branch and the root folder `/`.
7. Save.
8. Wait a minute or two for GitHub to publish the site.

GitHub will show you the public Pages link when it is ready.

## 5. Update the page after editing files

1. Edit `index.html`, `styles.css`, `share-message.txt`, or photos as needed.
2. Save the files.
3. Commit the changes.
4. Push to GitHub.
5. GitHub Pages will update automatically after the push.

## 6. Safety checklist before publishing

Before sharing the link:

- Blur license plates if desired.
- Do not upload factura, tarjeta de circulación, insurance, ID, or documents with personal data.
- Do not publish home address.
- Do not publish VIN unless intentionally decided.
- Do not publish full license plate.
- Do not include private negotiation limits or wholesale offers.
- Open the site on your phone and confirm the WhatsApp button works.
