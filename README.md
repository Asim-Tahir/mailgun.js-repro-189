# [Mailgun.js #189 Issue Repro](https://github.com/mailgun/mailgun-js/issues/189)

## Installation Instruction

1. Install dependencies

   ```bash
   yarn
   ```

   ```bash
   npm i
   ```

2. Running the Project

   ```
   yarn dev
   npm run dev
   ```

3. See error on browser console:

   - Go to [http://localhost:3000](http://localhost:3000) in browser.
   - Open devtools with <kbd>F12</kbd> or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd>.
   - Go to the **`Console`** tab of the devtools.
   - See error:

   ```log
   mailgun_js.js?v=df8eb782:2192 Uncaught ReferenceError: Buffer is not defined
    at Object.711 (mailgun_js.js?v=df8eb782:2192)
    at r (mailgun_js.js?v=df8eb782:4361)
    at Object.556 (mailgun_js.js?v=df8eb782:1982)
    at r (mailgun_js.js?v=df8eb782:4361)
    at Object.955 (mailgun_js.js?v=df8eb782:1411)
    at r (mailgun_js.js?v=df8eb782:4361)
    at Object.765 (mailgun_js.js?v=df8eb782:1021)
    at r (mailgun_js.js?v=df8eb782:4361)
    at Object.990 (mailgun_js.js?v=df8eb782:999)
    at r (mailgun_js.js?v=df8eb782:4361)
   ```
