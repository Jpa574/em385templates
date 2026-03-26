# EM385Templates.com - USACE AHA Generator

USACE EM 385-1-1 Compliant Activity Hazard Analysis Generator.

## Quick Deploy to Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
cd em385templates
vercel
```

3. Follow prompts:
- Set up and deploy? **Y**
- Which scope? **Your Vercel account**
- Want to modify settings? **N**

4. That's it! Your site is LIVE!

## Connect Custom Domain

After buying EM385templates.com from Namecheap:

1. Go to Vercel Dashboard
2. Go to your project → Settings → Domains
3. Add `EM385templates.com`
4. Copy the Nameservers shown
5. In Namecheap, go to DNS → Custom and add those nameservers

## Connect Stripe (Production)

Replace the Stripe test key in `public/index.html`:
```javascript
stripe = Stripe('pk_live_YOUR_LIVE_KEY');
```

Then in Stripe Dashboard → Webhooks, add your domain for payment events.

## Features

- ✅ 8 Activity Hazard Analysis types
- ✅ Form 6206 compliant format
- ✅ Free demo tier (2 steps, watermark)
- ✅ Pro subscription ($29/mo)
- ✅ Mobile responsive
- ✅ Free hosting on Vercel

## Cost

- Domain: ~$12-15/year
- Hosting: FREE (Vercel)
- SSL: FREE (auto)
- Payment processing: 2.9% + 30¢ per transaction

---
Built by Slick 🤠