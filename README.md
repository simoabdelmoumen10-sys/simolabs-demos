# SimoLabs — Product Demos

Static demo builds of the SimoLabs commercial catalog, served with GitHub Pages.

| Path | Product |
|---|---|
| `/storefront/` | SimoLabs Storefront (catalog + pricing) |
| `/freelancer/` | Freelancer Command OS |
| `/designtoken/` | DesignToken Pro playground |
| — | CoachOS Pro → https://coachos-pro.vercel.app |
| — | School OS / EduCore → https://school-os.vercel.app |

This repo contains **only compiled `dist` output** and the landing page. Application source stays in the private working tree. No API keys, no customer data.

Rebuild locally:

```powershell
cd C:\Users\Admin\Projects\Consolidated\Commercial-Studio\00-simolabs-storefront
npx vite build --base=/storefront/
```

Then mirror `dist\` into `storefront\` here and push.
