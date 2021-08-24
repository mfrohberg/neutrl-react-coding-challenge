# Spotify Feed Coding Challenge 🎧

&nbsp;

# Goals/Outcomes ✨

- To test knowledge of consuming APIs and handling responses
- Loading state and knowing where and how to make multiple API calls efficiently

&nbsp;

# Pre-requisites ✅

- Add your Spotify client ID & secret to `config.js`
  - Note. **Never add this type of config to version control. This would usually come from your build server.**

&nbsp;

# Requirements 📖

- Fetch and display _Released This Week_ songs
  - Use the API path `new-releases`
- Fetch and display _Featured Playlists_
  - Use the API path `featured-playlists`
- Fetch and display _Browse_ genres
  - Use the API path `categories`
- Loading state/UI _(optional, current UX is already clean)_

&nbsp;

# Think about 💡

- Taking a look at the Spotify API documentation
- Do you resolve each API request one after the other or in parallel?
- Where do you make the API requests?
- How much logic do you offload out of the UI components?

&nbsp;

# What's Already Been Done 🏁

- UI/UX for all elements, including previews (mobile responsive)

&nbsp;

# Screenshots 🌄

&nbsp;
![screenshot-desktop](https://puu.sh/GwPLE/3be580156a.png)
<img alt="screenshot-mobile" width=400 src="https://puu.sh/GwPLS/0bcb566d23.png" />

# Additional Setup

Copy `.env.local.example` to `.env.local`

```bash
cp -r .env.local.example .env.local
```

Obtain and use local spotify api credentials
