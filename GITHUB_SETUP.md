# How to Put This on GitHub and Make It Findable

Step-by-step. Do these in order. No command line needed.

---

## 1. Create a GitHub account (skip if you have one)

Go to [github.com](https://github.com) and sign up. Free account is fine.

## 2. Create a new repository

Click the green "New" button (top left) or go to [github.com/new](https://github.com/new).

Fill in:

- **Repository name:** `free-virtual-staging`
- **Description:** `Free AI virtual staging for real estate photos. Runs in your browser, no install, bring your own OpenAI API key.`
- **Public:** YES (private won't rank on Google or work for GitHub Pages)
- **Add a README file:** DO NOT check this
- **Add .gitignore:** Skip
- **Choose a license:** Skip (we have our own)

Click "Create repository".

## 3. Upload the files (web upload, no command line)

On your empty repo page, click "uploading an existing file" or "Add file → Upload files".

Drag and drop all four files into the upload area:

- `index.html`
- `README.md`
- `LICENSE`
- `.gitignore`

Write "Initial commit" at the bottom. Click "Commit changes".

Your repo is now live at `https://github.com/YOUR_USERNAME/free-virtual-staging`.

## 4. Turn on GitHub Pages (this is the big one)

This is what makes the tool actually usable for anyone with a browser. Without this, you have code on GitHub. With it, you have a working tool at a public URL.

1. In your repo, click **Settings** (top right tab)
2. In the left sidebar, click **Pages**
3. Under "Source," select **Deploy from a branch**
4. Branch: **main**, Folder: **/ (root)**
5. Click **Save**

GitHub will take 1 to 2 minutes to build and publish. When done, you'll see a URL like:

```
https://YOUR_USERNAME.github.io/free-virtual-staging/
```

Visit it. Your tool is now live on the public internet.

## 5. Update the README with your live URL

Once GitHub Pages is live, edit the README in GitHub:

1. Click on `README.md`
2. Click the pencil icon (top right)
3. Replace `YOUR_USERNAME` in the "Try it live" link with your actual GitHub username
4. Commit the change

Now the GitHub repo page has a working link to your live tool.

## 6. Set up the About section

On your repo page, click the gear icon next to "About" (top right of the file list).

Fill in:

- **Description:** `Free AI virtual staging for real estate photos. Runs in your browser, no install, bring your own OpenAI API key.`
- **Website:** `https://YOUR_USERNAME.github.io/free-virtual-staging/` (the GitHub Pages URL — this anchors your tool URL on the repo page)
- **Topics:** add these tags
  - `virtual-staging`
  - `real-estate`
  - `openai`
  - `chatgpt`
  - `ai-virtual-staging`
  - `bulk-staging`
  - `gpt-image-2`
  - `real-estate-photography`
  - `home-staging`
  - `no-code`

Save changes.

## 7. Add a second backlink to virtualstaging.com

The README already links to VirtualStaging.com twice (in the limitations section and the Related section). Those are dofollow backlinks from GitHub. Important.

For an extra backlink, you can also edit the live HTML's footer or info section to link to virtualstaging.com explicitly with your preferred anchor text.

## 8. Get the page indexed

Right after the repo and GitHub Pages site are live:

1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add two properties:
   - `https://github.com/YOUR_USERNAME/free-virtual-staging` (the repo)
   - `https://YOUR_USERNAME.github.io/free-virtual-staging/` (the live tool)
3. For each, use the URL Inspection tool and click "Request indexing"

This gives you TWO indexable surfaces for the same content, doubling your shot at ranking.

## 9. Get the first stars

Brand new repos with zero stars rank lower. Get the first 5 to 10 stars legitimately:

- Star it yourself
- Ask colleagues to star it
- Post the GitHub Pages URL on LinkedIn with a real description: "I built a free virtual staging tool for real estate agents — runs in your browser, no signup, costs about $0.19 per photo at OpenAI rates. Open source on GitHub."

Don't buy stars. GitHub bans repos for fake stars.

## 10. Promote in the right places

Each of these builds backlinks and direct traffic:

- **Reddit:** r/RealEstate, r/realtors, r/RealEstateTechnology. Post as "I built a free tool" not "check out my product"
- **Hacker News:** Show HN with a one-line summary. Even modest engagement gets you a HN backlink
- **LinkedIn:** real estate LinkedIn is active. Post the live tool URL
- **Indie Hackers:** post about your build
- **Twitter/X:** post the tool URL with a quick before/after demo video
- **Real estate Facebook groups:** but be careful not to spam

## 11. Keep the page alive

GitHub Pages sites with periodic commits rank better than abandoned ones. Plan small updates:

- Add a style or room type every few weeks
- Tweak the prompt to improve results
- Add screenshots to the README
- Respond to issues if anyone opens them

Each commit shows GitHub the project is alive, which feeds ranking signals.

---

## What you get out of this

**A working tool at a public URL.** Anyone with a browser can use it. No install, no signup, no friction.

**An indexable GitHub repo.** Markdown README ranks for the SEO keywords you've targeted.

**An indexable GitHub Pages site.** The live tool itself is a second indexable page.

**Two dofollow backlinks to virtualstaging.com.** github.com has domain authority around 96. That single backlink does more SEO work than 50 random blog comments.

**A free funnel.** Anyone who tries the tool and realizes the output is inconsistent has a clear next step (your paid services). This is brand positioning AND a soft funnel in one move.

---

## Realistic ranking expectations

**First 2 to 4 weeks:** the GitHub repo and Pages site get indexed. They rank for long-tail queries like "free virtual staging tool", "free virtual staging in browser", "open source virtual staging".

**2 to 6 months:** with active promotion and a handful of stars, the live tool can climb for "free virtual staging" as a long-tail variant. Won't beat the commercial top three on its own but can appear on page 1 or 2 with consistent effort.

**6 to 18 months:** if you keep the tool alive (updates, contributions, occasional commits) and pick up real backlinks (HN post, Reddit traction, mentions on tech blogs), the site can rank meaningfully for "free virtual staging" and dozens of related long-tails.

The strategic value isn't ranking alone. It's also brand positioning, two strong backlinks to your money site, and a real funnel from DIY tinkerers to paid customers.
