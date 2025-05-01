# Super Simple Guide: Free Hosting for HTML + CSS

A quickstart comparison of 6 free hosting platforms ranked from **easiest** to **hardest**.

---

## 1. Tiiny Host (Easiest)

**Pros**: No signup required, drag-and-drop, instant  
**Cons**: Must log into account every three months to remain on free tier.

### Steps:
1. Zip your `index.html`, `style.css`, and other assets.
2. Go to [https://tiiny.host](https://tiiny.host).
3. Drag your `.zip` into the uploader.
4. Choose a subdomain (e.g., `mysite.tiiny.site`).
5. Click **Launch**.

✅ Your site is live!

---

## 2. Surge

**Pros**: CLI-based (command prompt/powershell, Terminal, or Shell), instant deploy, custom subdomains  
**Cons**: Requires Node.js and CLI use

### Steps:
1. Install Node.js from [https://nodejs.org](https://nodejs.org)
2. Open Terminal or Command Prompt and run:

   ```bash
   npm install --global surge
   ```

3. Navigate to your project folder:

   ```bash
   cd path/to/your-site
   ```

4. Run:

   ```bash
   surge
   ```

5. Enter your email and password, choose a subdomain.

🔗 Site is deployed at `yoursite.surge.sh`.

---

## 3. GitHub Pages

**Pros**: Version control, free forever  
**Cons**: Requires a GitHub account and setup

### Steps:
1. Sign up or log in at [https://github.com](https://github.com)
2. Create a new repository named: `your-username.github.io`
3. Upload your project files (`index.html`, `style.css`, etc).
4. Go to **Settings > Pages**
5. Under "Source", select `main` branch and click **Save**.

🌐 Visit: `https://your-username.github.io`

---

## 4. Static.app

**Pros**: No account required  
**Cons**: No custom domains, limited settings

### Steps:
1. Zip your project files.
2. Visit [https://static.app](https://static.app)
3. Drag and drop your `.zip` file.
4. Copy your hosted link.

🚀 Instantly hosted!

---

## 5. Netlify

**Pros**: Fast, robust, custom domains, free forever  
**Cons**: Slight learning curve, Git optional

### Option A: Drag & Drop
1. Go to [https://netlify.com/drop](https://netlify.com/drop)
2. Drag and drop your project folder or `.zip`

### Option B: GitHub Integration
1. Push your site to GitHub
2. Sign in at [https://netlify.com](https://netlify.com)
3. Click **"New site from Git"**
4. Connect GitHub and select your repo
5. Deploy with default settings

🌍 Your site will be live at a `netlify.app` URL

---

## 6. Vercel

**Pros**: Powerful, ideal for dynamic apps  
**Cons**: Overkill for basic HTML, GitHub required

### Steps:
1. Push your site to GitHub
2. Log into [https://vercel.com](https://vercel.com)
3. Click **"Add New Project"**
4. Import your GitHub repo
5. Choose **"Other"** as the framework preset
6. Click **Deploy**

📎 Your site will be at `yourproject.vercel.app`

---

## Bonus: Docs & Links

- [Surge Docs](https://surge.sh/help/)
- [GitHub Pages Docs](https://pages.github.com/)
- [Netlify Docs](https://docs.netlify.com/)
- [Vercel Docs](https://vercel.com/docs)
- [Tiiny Host](https://tiiny.host)
- [Static.app](https://static.app)

---

### ✅ Use this to teach beginners, document your workflow, or demo a small project fast!
