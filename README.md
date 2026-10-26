# Liquid Ledger

A budgeting and debt tracker for Android. Plan each pay cycle, log income and
expenses, and keep track of what you owe, all stored privately on your phone.

**Download:** see the [latest release](../../releases/latest).

## What it does

- **Budgets by pay cycle.** Months run from the 26th to the 26th. Copy a
  previous month, split it into categories and planned expenses, and mark them
  paid in full or in part.
- **Debts.** Add who you owe (or who owes you), pay installments in full or
  partially, break a debt into parts (for example a car payment in USD plus a
  loan in TZS), and see Active and Paid debts sorted by date.
- **Cash flow.** See money in and out for any budget cycle, with a spending
  breakdown by category.
- **Multi-currency.** Switch the display currency and every amount converts.
- **Hide amounts.** One tap blurs every number on screen.
- **Backup and restore.** Save a copy of your data from Settings and restore it
  on a new phone.

## Install

1. Download the APK that matches your phone. Most phones need
   **`liquid-ledger-<version>-arm64-v8a.apk`**.
   (`armeabi-v7a` is for older 32-bit phones, `x86_64` for emulators.)
2. Open the file. If Android asks, allow your browser or file manager to
   **install unknown apps**.
3. Android may warn that the app is not from the Play Store. That is expected
   for apps installed this way.

Requires **Android 7.0 or newer**.

## Privacy

- There is **no account** and no sign-in. Everything you enter stays on your
  phone.
- There is **no analytics or tracking**.
- The only network request the app makes is to fetch public exchange rates from
  `forex.mfb.co.tz`. No personal data is sent.
- Use **Settings > Data > Back up data** to keep your own copy. Uninstalling
  the app deletes its data.

## Verify your download

Compare the file's SHA-256 with `SHA256SUMS.txt`:

```
shasum -a 256 liquid-ledger-<version>-arm64-v8a.apk
```

The APKs are signed with this certificate (SHA-256):

```
6b:f6:2b:0a:af:ef:80:0f:82:f4:b2:96:b9:ca:14:7b:80:94:71:e0:2b:cd:65:21:4a:b9:e2:ab:18:c0:d3:ab
```

Updates are signed with the same certificate, so a new version installs over
the old one and keeps your data.

## Source

The source code is not public.
