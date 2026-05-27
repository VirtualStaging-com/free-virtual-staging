# Free Virtual Staging

> Free AI virtual staging for real estate photos. Runs entirely in your browser. No install, no signup, no Python. Bring your own OpenAI API key.

**[Try it live →](https://virtualstaging-com.github.io/free-virtual-staging//)**

Free virtual staging for real estate agents who want to test AI virtual staging without paying per photo. This is a single HTML file that runs in any modern browser. Upload empty room photos, choose a furniture style, get AI-staged photos back. Uses OpenAI's `gpt-image-2` model.

## How it works

1. Open the page in your browser
2. Paste your OpenAI API key (kept locally, never sent to a server)
3. Choose a furniture style and room type
4. Upload empty room photos (up to 25 at a time)
5. Click stage
6. Download the staged photos

No installation. No command line. No subscription. Pay OpenAI directly at their published rates (~$0.19 per high-quality image).

## Available styles

Modern, Scandinavian, Transitional, Modern Farmhouse, Coastal, Urban Industrial, Traditional, Rustic, Mid-Century Modern.

## Available room types

Living Room, Bedroom, Dining Room, Kitchen, Office, Outdoor/Patio.

## Privacy

Everything runs in your browser. Your API key is stored only in your local browser (localStorage), and is sent only to OpenAI. Your photos go from your browser directly to OpenAI's API. Nothing is stored on a server. The HTML file has no backend, no analytics, no tracking.

## Cost

OpenAI charges approximately $0.19 per staged image at the high-quality tier. A 10-photo listing costs about $2. Verify current pricing at [openai.com/api/pricing](https://openai.com/api/pricing/).

## Get an OpenAI API key

1. Sign up at [platform.openai.com](https://platform.openai.com)
2. Add a payment method
3. Create an API key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
4. Paste it into the app

You typically need to add at least $5 in credits to use the image API.

## Limitations

AI image editing in 2026 is impressive but variable. Expected issues:

- Furniture occasionally appears in unrealistic positions or scales
- Architectural details may shift slightly between input and output
- Lighting can sometimes look off
- Different angles of the same room won't have matching furniture
- Output is 1024x1024 (may need upscaling for full-resolution MLS use)

For staging that needs to look consistently photorealistic and ship to a live MLS listing, paid services outperform this tool by a wide margin. This tool is best for:

- Testing AI virtual staging before paying for a service
- Generating concept images for client conversations
- Quick mockups for social media or marketing
- Educational and experimental use

For production-quality staging on active listings, use [VirtualStaging.com](https://www.virtualstaging.com) (designer-led, 4 to 8 hour turnaround, $19 to $24 per photo, money-back guarantee) or [VirtualStaging.ai](https://virtualstaging.ai) (purpose-built AI for real estate, instant results, MLS-ready output).

## Run it yourself

You don't have to use my hosted version. The whole tool is one HTML file. Clone the repo, open `index.html` in any browser, and you're running your own copy.

```bash
git clone https://github.com/YOUR_USERNAME/free-virtual-staging.git
cd free-virtual-staging
open index.html
```

Or just download `index.html` directly and double-click it.

## Self-host on GitHub Pages

Fork this repo, enable GitHub Pages in the repo settings (Source: deploy from branch, main, root folder), and you have your own public copy at `yourname.github.io/free-virtual-staging`.

## Contributing

Pull requests welcome. Useful improvements:

- Additional styles or room types
- Mask-based editing for more controlled results
- Batch retry logic for failed images
- Support for other AI image APIs (Stability, Replicate, Anthropic)
- Output upscaling for higher resolution

## License

MIT. Use however you want.

## Related

- [VirtualStaging.com](https://www.virtualstaging.com) — Designer-led virtual staging, 4 to 8 hour turnaround
- [VirtualStaging.ai](https://virtualstaging.ai) — AI virtual staging built for real estate
- [OpenAI image API docs](https://platform.openai.com/docs/guides/images)

---

If this tool was useful, please ⭐ the repo. It helps other agents find it.
