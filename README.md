# AxleBook Android releases

Signed Android releases for AxleBook, separate from Aval Store Manager and Eyan Products.

## AxleBook 1.3.0 (revision 4)

[Download the signed APK](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.3.0-4/app-release.apk)

- Freight-based driver salary, initially 16%, added to bata.
- Configurable per-driver rates; saved trips keep their applied rate.
- Monthly driver earnings: salary, bata, paid amounts and remaining due.
- Historical trips converted at 16% with reconciled accounting.
- Atomic salary-aware accounting and protection against older financial writes.
- Existing owner profile, light/dark themes, fleet management, payments, drafts and analytics.

Revision 4 is required for financial operations. Use your installed app's update-check action or install this APK over the existing signed app. Package com.axlebook.axlebook and the original AxleBook signing certificate are retained. After updating, use Fleet to set a driver's salary rate or open Monthly driver earnings.

## Previous releases

- [1.2.0 revision 3](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.2.0-3/app-release.apk)
- [1.1.0 revision 2](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.1.0-2/app-release.apk)
- [1.0.0 revision 1](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.0.0-1/app-release.apk)

Older versions are retained for release history and cannot save financial changes after the salary-accounting upgrade.

SHA256SUMS.txt identifies the immutable APKs. The root release_manifest.json identifies the latest release; version directories retain their own metadata. The app checks Firebase release metadata before offering an update.

This public branch contains release binaries and metadata only. Credentials, upload keys, private source code, backups, migration audits and business data are excluded.
