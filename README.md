Styles are not loaded in production build CSR navigation

How to reproduce:

- Run the app in prod build (npm run prod)
- Load index page in SSR (styles are loaded)
- Navigate to `/random` route
- Reload the page
- Navigate to `/index` route (styles are not loaded)

To run it:

```bash
npm install
npm run prod
```
