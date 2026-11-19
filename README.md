# Financial Movement Dashboard

Open `index.html` (or the GitHub Pages address) to use it.

## What each file does

| File | What is inside |
|---|---|
| `index.html` | The page itself: the login screen, buttons, windows and the layout of every page. |
| `css/style.css` | All the colours, glass effects and spacing (how everything looks). |
| `js/state.js` | Settings and the default data the whole app shares (categories, default months, current year). |
| `js/helpers.js` | Small tools used everywhere: dollar format, dates, pop-up messages, theme and glass switch, the `$` typing in the ledger. |
| `js/vault.js` | Sign-in, encryption, saving to the cloud (Supabase), lock/unlock, backups and import. |
| `js/ledger.js` | The Transactions page, the New Transaction window (with the Paid switch), recurring bills, due-soon alerts. |
| `js/budgets.js` | Budgets, categories and budget alerts. |
| `js/planning.js` | Savings goals, subscriptions and the cash-flow forecast. |
| `js/views.js` | Page navigation, the Dashboard overview, Annual, Multi-Year and Month vs Last Month pages. |
| `js/startup.js` | Things that run once when the page opens. Keep this one last. |

## Important

- Keep the folders exactly as they are (`css` and `js` next to `index.html`). The page finds the other files by these names.
- The order of the `<script>` lines at the bottom of `index.html` matters. Do not reorder them.
- After you upload a new version, press **Ctrl + Shift + R** (Cmd + Shift + R on Mac) in the browser once so it loads the new files and not the old ones it remembers.
