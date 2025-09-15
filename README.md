# 🌱 Daily Quote Updater
This repository automatically updates a file with a **new inspirational quote every day** using a GitHub Action.  
Each day, the workflow fetches a random quote from [Quotable API](https://api.quotable.io/) and saves it in [`quotes.md`](./quotes.md).

## ⚙️ How It Works
- The automation is powered by **GitHub Actions**.  
- A scheduled workflow runs daily at **06:00 UTC**.  
- The workflow:
  1. Calls the Quotable API for a random quote.  
  2. Updates the `quotes.md` file with the new quote.  
  3. Commits and pushes the changes back to this repository.  

✅ Every update also counts as a **GitHub contribution**, helping keep my contribution graph active with meaningful commits.  

## 📂 Files
- [`quotes.md`](./quotes.md) → Contains the most recent daily quote.  
- [`.github/workflows/quote.yml`](.github/workflows/quote.yml) → The GitHub Actions workflow file.  

## 🚀 Example Output
# Daily Quote
> The best way to predict the future is to invent it.
— Alan Kay
