Setup:
Use “npx create-react-app” or “npx create-next-app” to spin up a project.
Hosting:
Upload the project to a private GitHub repository and add s.pandit@cmcmarkets.com
as a collaborator. Do not push any commits after the specified test end time.
Requirements: React, TypeScript
Optional: TailwindCSS, NextJS
Task 1:
Create a basic search-box and dashboard that provides information about a symbol.
Utilise the public Binance REST API to fetch all the available instruments using
“/api/v3/exchangeInfo” to pre-populate a search box and make the dashboard symbol
information change based on selection.
Create a small dashboard providing insights into the selected symbol. Insights can be
into the price, average price, recent trades, close, open etc. (free to decide which and
how many attributes to show).
Bonus:
- Well-presented UI/UX
- Specific symbols can be pointed to with a link
- Utilise the Binance WebSocket API for live tickers
