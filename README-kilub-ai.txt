kiluB AI — Version 1 interface preview

WHAT'S INCLUDED
- Existing kiluB company landing page, updated with Launch App links.
- /app/ responsive AI chat interface prototype.
- Local browser-only conversation history.

IMPORTANT
This is a frontend prototype. It does NOT connect to a real AI model yet.
The replies are clearly labelled preview examples. Do not advertise it as a live AI assistant until a secure backend and model API are connected.

GITHUB PAGES DEPLOYMENT
1. Extract this package.
2. Open your GitHub repository: Violinakalita/kilub-website.
3. Upload/replace the website files in the repository root with the files from kilub-website-updated.
4. Keep the assets folder and its black-forest-cafe-project.png image.
5. Commit the changes to main.
6. Wait for GitHub Pages to publish.
7. Test:
   - https://violinakalita.github.io/kilub-website/
   - https://violinakalita.github.io/kilub-website/app/

NEXT DEVELOPMENT STEP
Add a backend endpoint that calls a selected AI provider. Keep provider API keys in server-side environment variables only; never place secrets in frontend JavaScript or public GitHub files.
