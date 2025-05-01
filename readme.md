# 🌱 404 Commons

**404 Commons** is a minimalist BBS-inspired web architecture.  
It offers a quiet alternative to feeds, timelines, and social platforms.

There is no algorithm.  
There is no backend.
No timeline.
No doomscrolling.
No likes, no fame.  
Only HTML + CSS.

---

## 🌳 Core Concepts

- **Commons** — the shared philosophy and network
- **Grove** — a local index of links to HTML pages (“seeds”)
- **Seed** — a single HTML file (your page, thought, poem, zine, post, interface)
- **Sprout** — the act of creating and sharing a seed

---

## 📁 Project Structure

```plaintext
/
├── index.html         # Your local Grove (index of seeds)
├── seeds.json         # List of all linked seeds (for random navigation + JS loading)
├── styles/
│   ├── grove.css       # Minimal, soft Grove styling (ZenOps)
│   └── style-[themes].css   # Optional style templates (paper, terminal, rainbow, etc.)
├── [seed].html        # Your individual seed files
├── hosting-guide.md   # a how-to host guide for beginners
└── README.md          # This file
```

---

## 🌿 How to Share a Seed or Grow a Grove

### 📤 Option 1: Share a Seed

If you'd like to add your seed to this Grove:

1. Create a single `.html` file (your seed), keep the file size below 1.5 MB (feel free to use one of the [seed]template.html files).
2. [Host it anywhere](https://github.com/robotamerica/404commons/blob/main/hosting-guide.md) — GitHub Pages, tiiny host, Surge ...
3. Email your link to 📧 [`seed@404commons.org`](mailto:seed@404commons.org).
4. If accepted, your seed will be added to the `seeds.json` and listed in random rotating order on `index.html`.
5. The grove will display a maximum of six random seeds at a time.

In your email provide the following:<br>
"URL": " ",<br>
"label": " ",<br>
"description": " ",<br>
"hidden": true or false<br>  

 - Hidden seeds are allowed — just say so ("hidden": false). They will only be discovered randomly.


### 🌳 Option 2: Create Your Own Grove

If you’d rather sprout your own Grove:

1. Fork this repository or download it.
2. Replace the contents of the local [seed].html files with your own seed ideas and concepts.
3. Add your own `seeds.json` file to manage navigation and listings.
4. Customise your style via the `/styles` directory or write your own.
5. Customise `index.html` anyway you like, just keep the core functions and philosophy in mind.
6. Publish your Grove using any static host.
7. You can share your grove to be hidden among the `seeds.json` to be found on 404commons.com (optional)

> You now maintain your own Grove of Seeds.  
> Link it to and from another Grove, or let it drift quietly.

---

## 🎲 Random Seed Navigation

The `index.html` includes a "Visit a random seed" link. Remember, you can also hide other Groves amongst the Seeds.  
It draws from `seeds.json`, which supports:

```json
{
  "url": "ghost.html",
  "label": "ghost.html",
  "description": "a signal heard once",
  "hidden": false
}
```

To **hide a seed from the list but keep it accessible**, set:

```json
"hidden": true
```

---

## 🌀 Philosophy

404 Commons resists speed.  
There is no feed, no follower count, no trending.

Only:

- 🪄 Creating
- ✍️ Writing  
- 📎 Linking  
- 🧭 Wandering

You can fork it. You can remix it. Whatever! 
The Grove grows every which way.

---

## 🧾 License

You are free to:

✓ Use, view, and share this work  
✓ Fork and modify this Grove or any Seed  
✓ Host, self-host, or distribute copies  
✓ Remix styles, language, and structure  
✓ Grow your own Grove, with or without attribution

This license is based on the spirit of free knowledge, shared soil, and open drift.  
It is inspired by the principles of Copyleft, Creative Commons (BY-NC-SA), and the GPL.

Like a forest, the Grove belongs to itself and everyone.

Signed,  
404 Commons  
seed@404commons.org
