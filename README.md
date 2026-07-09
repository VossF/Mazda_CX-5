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

## 2. Enable the contact buttons

Contact buttons are intentionally hidden until a phone or email is configured.

In `index.html`, search for:

```js
const contactPhone = '';
const contactEmail = '';
```

To enable WhatsApp, set `contactPhone` in international format, without spaces or punctuation. Example for Mexico:

```js
const contactPhone = '5213312345678';
```

If there is no phone but there is an email, set `contactEmail` instead:

```js
const contactEmail = 'correo@ejemplo.com';
```

If both values are blank, the page keeps all contact UI hidden, including the pending-contact note.

## 3. Photos

The `photos/` folder contains the 23 provided car photos with SEO-friendly, descriptive file names.

The page uses the strongest sales photos in the visible gallery:

- `mazda-cx5-2021-exterior-frontal-derecho.jpeg` — primary hero image and best overall exterior shot.
- `mazda-cx5-2021-vista-frontal.jpeg` — straight-on front view.
- `mazda-cx5-2021-trasera-tres-cuartos-derecha.jpeg` — rear three-quarter view.
- `mazda-cx5-2021-vista-trasera.jpeg` — straight-on rear view.
- `mazda-cx5-2021-volante-consola-interior.jpeg` — dashboard, steering wheel, and center console.
- `mazda-cx5-2021-asientos-delanteros-piel-clara.jpeg` — front leather seats.
- `mazda-cx5-2021-asientos-traseros-piel-clara.jpeg` — rear leather seats.
- `mazda-cx5-2021-cajuela-cubierta-retractil.jpeg` — cargo area with retractable cover.
- `mazda-cx5-2021-odometro-50604-km.jpeg` — odometer reading.

Additional renamed detail photos remain in `photos/` for future use.

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
- Open the site on your phone and confirm the contact buttons stay hidden until `contactPhone` or `contactEmail` is configured.
- After configuring a phone or email, confirm the contact button opens WhatsApp or email correctly.
