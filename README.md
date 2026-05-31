# GSA Certificate Generator

Single-template certificate generator for Pitch Night with a blue/white, glassmorphism UI. Users enter a name, generate a preview, and download a personalized certificate.

## Features
- Clean home flow: enter name -> generate -> download
- Admin portal for internal generation
- Single certificate template (Certs/Cert.jpg)
- Name rendered with GoogleSans-Bold.ttf
- Responsive layout and Google-inspired color accents

## Project Structure
- index.html: UI, styling, and certificate rendering logic
- Certs/Cert.jpg: certificate template
- GoogleSans-Bold.ttf: font used for name rendering
- gsa-logo.png: home page logo

## Usage
1. Open index.html in a browser.
2. Enter a full name and click "Generate Certificate".
3. Click "Download Certificate" to save the image.

## Admin Access
Admin login is enabled in index.html. Update the credentials before deployment:
- ADMIN_USER
- ADMIN_PASS

## Customize Name Placement
Edit NAME_CONFIG in index.html:
- xPercent, yPercent: position (percent of image width/height)
- fontSize: font size in pixels
- maxWidthPercent: max width for auto-scaling
- fontColor: name color

## Notes
- Keep Certs/Cert.jpg and GoogleSans-Bold.ttf in place.
- Large template images require larger font sizes; use the preview to fine-tune.