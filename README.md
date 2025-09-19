# Nuxt 4.1 COA Examples App

A Nuxt 4 application with TypeScript configured for Cloudflare Pages deployment.

## Features

- ✅ Nuxt 4.1.2 with TypeScript
- ✅ Cloudflare Pages deployment ready
- ✅ `/coa-examples` page with SharePoint document links
- ✅ Responsive design with styled components

## Pages

- `/` - Home page with navigation
- `/coa-examples` - COA examples page with SharePoint document links

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment to Cloudflare Pages

### Option 1: Using Wrangler CLI

```bash
# Deploy to Cloudflare Pages
npm run deploy

# Deploy to staging
npm run deploy:staging

# Deploy to production
npm run deploy:production
```

### Option 2: Git Integration

Connect your repository to Cloudflare Pages dashboard with these settings:

- **Build command**: `npm run build`
- **Build output directory**: `dist`
- **Root directory**: `/`

## Configuration

The application is configured with:

- **Nitro preset**: `cloudflare-pages`
- **TypeScript**: Strict mode enabled
- **Wrangler**: Configured in `wrangler.toml`

## SharePoint Links

The `/coa-examples` page contains links to:
1. https://koicbd.sharepoint.com/:b:/s/KoiMarketing/ET4DDrGEERBLnB-blDZjQPUBlY2205KhyoqPgzgifMHCYA?e=d0lO6Y
2. https://koicbd.sharepoint.com/:b:/s/KoiMarketing/EUlbngJ0g6pAt2oMxi5DvmABEzip-SjVxGKiloCotTPRCQ?e=SxnYZt
