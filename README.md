# LockBox

LockBox keeps photos, videos, documents, notes and card details in a private folder that is encrypted on
your phone. Without your PIN or password the contents cannot be read. It has no adverts, no accounts, no
paid version and no internet access.

- Website: https://customgpter.github.io/lockbox/
- Latest app file: https://github.com/CustomGPTer/lockbox/releases/latest
- Privacy: https://customgpter.github.io/lockbox/privacy.html

## Read this before you put anything in

- **Uninstalling LockBox deletes everything in it.** So does clearing its storage in the phone's settings,
  resetting the phone or losing it. Updating over the top is safe.
- **Make a backup file and keep it off the phone** (Settings > Back up and restore). The phone's own backup
  and Smart Switch leave LockBox out on purpose.
- **Nobody can reset your PIN or password.** Write down the recovery code shown at setup. Without the PIN or
  password and without the code, the contents are gone for good.
- **Adding a file does not remove other copies** in Google Photos, OneDrive or the Gallery recycle bin.
- **Calculator disguise:** with a PIN, type it on the calculator and press =. With a password, hold = for
  three seconds.
- **Tap the tick after your PIN.** A PIN can be 4 to 12 digits.

## What it does

- Encrypts every file, file name, note, card and preview with AES-256-GCM, a separate key for each file
- Unlocks with a password or PIN, with optional fingerprint, and a recovery code shown once at setup
- Locks the main key with your PIN or password (Argon2id) and again with the phone's security hardware
- Opens photos, videos, audio, PDFs and text inside the vault, decrypting as you look
- Encrypted notes, and cards for logins, bank cards, ID documents and Wi-Fi passwords
- Folders, tags, favourites, search and a 30-day recycle bin
- Locks when the screen turns off and after a chosen time without a touch; quick-panel tile and widget
- Growing waits after wrong tries, a break-in log, optional photo and optional delete-everything
- Calculator disguise with a working calculator
- One encrypted backup file with its own password
- No internet permission

## What it cannot do

LockBox cannot protect an open vault from spy software on a rooted phone, from someone watching you type,
or from a short PIN that is easy to guess. It is new and has not had an independent security review. The
source is here so that anyone can check it.

## Building

The app is in the `android` folder. See `android/README.md`.

## Licence

© 2026 Jonathan Jackson. Published under the GNU General Public License, version 3 (see `LICENSE`).
