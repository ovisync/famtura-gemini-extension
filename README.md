# Famtura for Gemini CLI

Use your Famtura business data (customers, invoices, offers, orders,
projects, tasks and more) directly in Gemini CLI.

## Install

1. Create a Famtura API key in Famtura under Settings → API access
   (needs the `apiAccess` module; the key starts with `ftu_`).
2. Install the extension:

   ```
   gemini extensions install https://github.com/ovisync/famtura-gemini-extension
   ```

3. When asked, paste your API key. It is stored in the system keychain.
4. Try: `List my 5 most recent invoices.`

## Privacy

People appear as aliases (`Kunde-XXXX`); contact and address data is masked
by default (privacy feature, not a bug).

## Support

- Support: info@ovisync.de
- Privacy: https://famtura.de/datenschutzerklaerung/
- Terms: https://famtura.de/agb/
