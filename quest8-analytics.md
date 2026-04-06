# QUEST 8: Custom Domain & Analytics

## 🌐 Custom Domain

A custom domain is a unique website address like:
example.com

It looks more professional than default domains like:
fadboy31.github.io or taskflow-31.netlify.app

---

## 💰 Do You Have to Pay?

Yes.

Most custom domains are paid:
- Usually $8 – $15 per year

Free options:
- GitHub Student Pack (free domain for students)
- Some .me domains (limited offers)

---

## ⚙️ Setup Process

### GitHub Pages:
1. Buy a domain
2. Add a CNAME file in your repo with your domain
3. Go to domain provider → DNS settings
4. Add A records pointing to GitHub IPs
5. Go to GitHub Settings → Pages → Add custom domain

---

### Netlify / Vercel:
1. Go to Site Settings → Domain Management
2. Add custom domain
3. Update DNS records from your domain provider
4. Wait for DNS propagation (up to 48 hours)

---

## 📊 Analytics (Basic Tracking)

Analytics helps track visitors and performance.

Example tool:
- Google Analytics

Steps:
1. Create account at https://analytics.google.com
2. Get tracking script
3. Add it inside <head> of your HTML

Example:

<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_ID"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', 'YOUR_ID');
</script>

---

## ✅ Conclusion

- Custom domains improve professionalism
- Most domains require payment
- Free options exist for students
- Analytics helps monitor website performance