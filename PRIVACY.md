# Game Quick Reviews — Privacy Policy

Updated: 11 November 2026. The Wikidata and optional Google Search additions below apply from version 1.0.2; versions 1.0.0 and 1.0.1 use Steam and PCGamingWiki only.

Game Quick Reviews is a free, noncommercial browser extension by Cyril Kong. Contact: cyril.kong@gmail.com.

## What the extension does

You enable the toolbar switch on a webpage and select a game title. The extension shows Steam game information, scores, controller capabilities, and one positive and one negative player review on that page. Disabling the switch stops selection lookups. Navigating to another page resets the switch.

## Data sent to services

While enabled, the selected title is sent directly from your browser to Steam's store search service. Version/patch text following a pipe separator is removed before lookup. From version 1.0.2, if Steam has no exact match, that title is sent to Wikidata's public search API; a matching Wikidata entity ID is used to retrieve its Steam App ID. Only a unique full-name/alias and unique valid Steam ID are accepted. If the selected title links to a Steam game, its numeric Steam App ID is used instead. Steam also receives the game App ID when the extension requests product details, store content and reviews. PCGamingWiki receives that App ID and its matching encyclopedia page title to retrieve controller-support information. Cover artwork is requested from Steam's image CDN. These services receive normal network connection information, including your IP address. Their own privacy policies apply.

The extension does not send the source webpage URL, surrounding webpage text, browsing history, clipboard content, personal email address, or account cookies. Editable fields are excluded from selection lookups. Data-service requests use HTTPS and omit account credentials and the source-page referrer. If no reliable Steam match is found, version 1.0.2 offers a Google Search link in the panel. Only clicking that link opens a new tab with the selected game name as the search query; no search is opened automatically. Normal browser navigation and your Google account settings apply to that tab.

Selected text can be arbitrary text. Only select game names while this feature is enabled.

## Storage and retention

There is no developer-operated backend, telemetry, advertising, analytics, or data sale. No account is required. The developer does not receive search requests. Recent results are temporarily cached in extension memory: up to 30 game lookups, normally for five minutes; controller data can remain cached for up to 24 hours. The browser can discard that memory when the extension service worker stops. There is no persistent search history or cloud sync.

## Permissions

- activeTab: temporarily access the current webpage after you click the toolbar button.
- scripting: insert the isolated game information card and selection listener into that page.
- Steam store/API and PCGamingWiki host access: retrieve the game information you request.
- Wikidata host access (from 1.0.2): resolve selected game aliases to a unique Steam App ID. No Google host permission is requested; the optional search opens a normal link.

The extension does not use remotely executed code, camera, microphone, clipboard, location, or payment permissions.

## Third-party content and links

Game titles open their Steam product page in a new tab only when clicked. The optional search action opens Google only when clicked. Wikidata structured data is available under CC0. PCGamingWiki data is attributed in the card under CC BY-NC-SA 3.0. Steam, Valve, Sony, PlayStation, and Xbox are trademarks of their respective owners; this extension is independent and unaffiliated.

## Updates

Any change to data handling will be documented in this policy and reflected in the Chrome Web Store disclosures.
