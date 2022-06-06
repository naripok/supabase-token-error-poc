# Supabase auth error on invalid `#access_token`

Steps to reproduce:

1. run supabase stack locally
2. serve the POC file and open it in the browser
3. visit the link including `#access_token=test` in the url, e.g. `http://localhost:3000/#access_token=test`
4. check the browser logs for the error: `Error getting session from URL. Error: No expires_in detected.`
