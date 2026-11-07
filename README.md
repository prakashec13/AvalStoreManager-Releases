# AxleBook Android releases

Signed Android releases for AxleBook, separate from Aval Store Manager and Eyan Products.

## AxleBook 1.0.0 (revision 1)

[Download the signed APK](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.0.0-1/app-release.apk)

- Heavy vehicle rental and logistics ledger with owner-only access.
- Atomic trips, expenses, driver settlements and monthly summaries.
- Material 3 dashboard, fleet management and analytics.
- In-app update checks with checksum and Android signing verification.

The Android package is com.axlebook.axlebook. SHA256SUMS.txt and release_manifest.json identify the published file.

For first sign-in, use the configured owner email and tap Forgot password? in AxleBook to set your password. Only the configured owner's Firebase UID can access business data. Android updates retain the same dedicated AxleBook signing certificate.

This public branch contains release binaries and metadata only. Firebase service-account credentials, upload keys, passwords, private source code and business data are not published here.
