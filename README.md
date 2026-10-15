# CCU

Password-protected field reference for the CCU fault list, with converter drawings and connector pinouts, laid out for phones.

Everything in `data/` is encrypted (AES-256-GCM, key from PBKDF2-SHA256). The page decrypts it in the browser after you enter the password, so the content can't be read from this repository without it.

Open the site through GitHub Pages (https). Unlocking needs a secure connection and doesn't work from a local file.
