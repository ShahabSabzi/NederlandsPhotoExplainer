# Dutch Lens

A mobile-friendly Dutch learning page. Upload a photo or paste Dutch text to get a transcription, translation, vocabulary, and grammar explanation.

## Use

1. Open the page on GitHub Pages or locally in a browser.
2. Enter your own Gemini API key in the page.
3. Choose a photo or paste a Dutch sentence, then tap **Explain this Dutch**.

The key is not included in this repository or saved by the page. Do not paste the key into `index.html`, a README, or a GitHub commit. The page sends the key, photo, and text to Google's Gemini API from your browser. An internet connection is required. Free-tier usage has limits and may change; Google says free-tier submitted content may be used to improve its products.

See Google's [Gemini API pricing and free-tier details](https://ai.google.dev/gemini-api/docs/pricing) and [rate limits](https://ai.google.dev/gemini-api/docs/rate-limits).

## GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose the `main` branch and `/ (root)`, and save. GitHub Pages will publish `index.html`.
