# Sense Weather
A lightweight sensory storytelling picker from HAC Studios.

105 sensory prompts: 30 Touch and 15 each Smell, Sound, Sight, Taste, Perception.
32 emotional states. 24 story consequences.
Choose a sense, favor touch, keep individual cards, reroll others, and copy the seed.
Echo and friction pairings use curated positive/negative pools for sensations with clear pleasant/uncomfortable tags. Ambiguous sensations retain the full emotion pool.
Perception separates observable cues from possible interpretations.

## GitHub Pages / phone setup
1. Unzip this package.
2. Put these files at the root of your writing-tool repository, or in a sense-weather subfolder. Keep their relative paths together.
3. Enable GitHub Pages in the repository settings (Deploy from a branch, main, root).
4. Open your published page in Chrome on Android. Use the browser menu, Add to Home screen / Install app.
5. Let the page finish loading once while online. Then the installed app can open offline.

No account, API key, paid service, build step, or dependencies required. Nothing is sent to a server by the picker. Selections aren't saved after closing.
You can also open index.html directly on a computer; installation and offline caching require HTTPS hosting or localhost.

## Customize
Edit the banks in app.js. After changing hosted files, change the cache version in sw.js so installed copies update.
