# Event Stock Radar

A personal event-aware stock radar for watchlists, current-affairs scanning, and catalyst-based stock ranking.

## Use

Open `index.html` in a browser, load demo data, or enter a Finnhub API key for optional live quotes and company news.

## Intelligence features

- Valuation score from target upside/downside, P/E, PEG, growth, and cash-flow yield where available.
- Intrinsic Value Calculator using user assumptions for cash flow/EPS growth, discount rate, terminal growth, and margin of safety.
- Local intelligence log for timestamped recommendations.
- Validation workflow that compares later prices with the original logged signal.
- Small personal learning adjustment after at least three validated signals.
- Knowledge Lab for importing public YouTube video metadata, storing personal notes, and converting lessons into testable strategy rules.

The intelligence log is stored in browser local storage. It is not uploaded to GitHub.

## GitHub Pages

After pushing this folder to GitHub, enable Pages from the repository settings:

- Source: deploy from branch
- Branch: `main`
- Folder: `/root`

The site will publish at `https://OWNER.github.io/REPOSITORY/`.

## Note

This is an educational decision-support tool, not financial advice.
