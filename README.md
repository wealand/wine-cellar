# My Wine Cellar 🍷

A mobile-friendly, static wine inventory hosted through GitHub Pages. The public website reads `wines.json` directly from this repository, so updates made here are reflected on every device after refreshing.

## Features
- Collection overview with bottle and wine counts
- Search, maturity filters, and sorting
- Drinking windows and locations
- **What Should I Drink Tonight?** suggestions with food pairings

## Publish with GitHub Pages
Open **Settings → Pages** in this repo. Under **Build and deployment**, select **Deploy from a branch**, then branch **main**, folder **/(root)**, and **Save**.

Expected URL: https://wealand.github.io/wine-cellar/

## Update the inventory
The canonical data file is **`wines.json`**. Each entry has an `id`, producer, name, vintage, region, grape, quantity, storage location, and estimated drinking window. Tell ChatGPT which bottles you purchased or consumed and ask it to update `wealand/wine-cellar`; it can batch-edit the JSON using connected GitHub access.

**Important:** The live website is currently **read-only**. It does not save edits made in a browser or include a synchronized tasting journal. This prevents device-specific inventory discrepancies. GitHub commit history records data changes. Do not place personal information, passwords, or tokens in the public repository.

Drinking windows and pairings are estimates and should be treated as guidance.
