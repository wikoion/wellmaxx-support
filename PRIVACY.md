# Wellmaxx privacy policy

Effective 16 November 2026.

Wellmaxx is built so that your data stays yours. Every score, trend and estimate is worked out on your iPhone. There is no Wellmaxx account, no Wellmaxx server, and no analytics, advertising or tracking. The developer never receives your data.

## What the app reads and stores

- **Apple Health:** with your permission, Wellmaxx reads sleep, heart, activity, body and nutrition data to compute its scores. If you turn it on, it writes the food you log and the workouts you record back to Apple Health.
- **What you enter:** food, workouts, routines, check-ins, your profile (such as date of birth, sex and height) and settings.
- **Imports you choose:** exports from Hevy, MacroFactor or a spreadsheet that you open in the app.
- **Strap Sync:** if you also use Strap Sync, Wellmaxx reads the skin temperature, HRV and ECG recordings it adds to its Apple Health samples. This happens on the phone.
- **Bluetooth heart-rate sensors** during a workout, and the **camera** to read food barcodes. Nothing from the camera is saved.

All of this is kept in the app's database on your iPhone. API keys are kept in the iPhone's keychain. The app has no iCloud sync; like other apps' data, its database is included in your iPhone's own backup if you have backups turned on.

## When data leaves your iPhone

Only when you use a feature that needs it. Each feature sends data to the service you choose, under that service's own privacy policy:

| Feature | When it's used | What is sent | Where |
|---|---|---|---|
| **Food search and barcodes** (Open Food Facts) | When you search for a food or scan a barcode, while Open Food Facts is on in Food Log settings | The search text or barcode, and the app's name and version. If you enter a contact email for Open Food Facts, it's included | Open Food Facts |
| **USDA branded foods** | Only after you add your own USDA API key | The search text | USDA FoodData Central (api.nal.usda.gov) |
| **Hevy** | Only after you add your own Hevy API key | Downloads your workouts, routines and body measurements. With Send to Hevy on, uploads the workouts, routines and custom exercises you make in Wellmaxx | Your Hevy account |
| **Ask AI** | Only while Ask AI is on, and only when you ask a question, using your own OpenAI API key | Your question and only the data the model asks for to answer it. Each answer lists the data sent. Storage is turned off; OpenAI may keep abuse-monitoring logs for up to 30 days | OpenAI |
| **Wellmaxx Web** | Only while you turn it on | A copy of the app's database | Your own computer, over your own private network |
| **S3 storage** | Only while you turn it on | A copy of the app's database | Your own storage bucket |
| **Export and share** | When you tap Export or Share | The file you chose | Wherever you send it |

More → Network log lists every request the app has made: time, address, size and result. Search terms and API keys are never recorded there.

## What the app never does

- It never sells your data or shares it for advertising.
- It never uses Apple Health data for anything other than your own health and fitness features.
- It never tracks you across apps or websites.

## Deleting your data

Deleting the app deletes everything it stored on your iPhone. Copies you sent to Wellmaxx Web, an S3 bucket, Hevy or elsewhere are under your control there; delete them in those places. To stop data leaving the phone, turn the features above off in the app.

## Children

Wellmaxx is not directed at children under 13.

## Changes

If this policy changes, the new version will be published here with a new effective date.

## Contact

Questions about this policy: open an issue at <https://github.com/wikoion/wellmaxx-support/issues>.
