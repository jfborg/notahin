# Notahin web app

Notahin is an installable Progressive Web App for project timing and notes.

## Deploy on Vercel

1. Put this folder in a GitHub repository.
2. In Vercel, select **Add New → Project** and import that repository.
3. Leave the framework preset as **Other** and deploy. No build command is required.
4. In the project’s **Settings → Domains**, add `notahin.com` and `www.notahin.com`.
5. Copy the DNS records Vercel provides into GoDaddy’s DNS management screen.

After visiting the secure domain on an iPhone, use Safari’s **Share → Add to Home Screen** to install Notahin.

## Data and export

Data is stored locally in the browser on each device. The **Export Excel** button creates an `.xlsx` file with two sheets: `Work Sessions` and `Projects`; both include the complete project notebook text.

The web version has no account or cloud-sync service yet, so data is not automatically shared between devices.
