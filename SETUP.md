# Setup and Deployment

## Ordering app (Lovable)
Hosted at https://brotein-bar-orders.lovable.app/. Edit and republish from the Lovable project. To keep the code in GitHub, connect the project to a GitHub repository from the Lovable project settings.

## Brand website (Manus)
Hosted at https://broteinbar-suur89zt.manus.space/. The exported project is a Node.js 22 app that uses pnpm and ships with a Dockerfile.

To run the exported code locally:

```bash
corepack enable
pnpm install
pnpm build
node dist/index.js    # serves on port 3000
```

Or with Docker:

```bash
docker build -t brotein-bar .
docker run -p 3000:3000 brotein-bar
```

Place the exported code in the `source/` folder before pushing to GitHub. Do not commit `.env` files or API keys.

## Updating content
Menu items, nutrition values, hours (4:00 PM to 8:00 PM), founder names and the contact number (9729505574) are edited in the site content, then republished.
