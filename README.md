# AxleBook Android releases

Signed Android releases for AxleBook, separate from Aval Store Manager and Eyan Products.

## AxleBook 1.1.0 (revision 2)

[Download the signed APK](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.1.0-2/app-release.apk)

- New road-and-axle logo and sunrise truck login banner.
- Full-ledger customer, vehicle, driver, date, unsettled and loss filters.
- Device-local trip draft recovery, repeat routes and customer/location suggestions.
- Dated customer receipts and driver payments, references, reversals and preserved payment history.
- All-time outstanding balances, month browsing and safe vehicle/driver editing.
- Owner-only Firebase access, atomic accounting, analytics and signed in-app updates.

Update through AxleBook's Check for updates action or install this APK over the existing signed app. Package com.axlebook.axlebook and the original AxleBook signing certificate are retained. Revision 2 is the minimum supported release for the dated payment workflows.

For first sign-in, use the configured owner email and tap Forgot password? to set your password if needed. Only the configured owner's Firebase UID can access business data.

[Previous AxleBook 1.0.0 APK](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.0.0-1/app-release.apk)

SHA256SUMS.txt identifies both immutable APKs. The root release_manifest.json identifies the latest release; each version directory retains its own metadata.

This public branch contains release binaries and metadata only. Firebase service-account credentials, upload keys, passwords, private source code and business data are excluded.
