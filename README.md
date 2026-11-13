# AxleBook Android releases

Signed Android releases for AxleBook, separate from Aval Store Manager and Eyan Products.

## AxleBook 1.4.1 (revision 6)

[Download the signed APK](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.4.1-6/app-release.apk)

- Explicit Fleet Edit, Archive / Restore and Delete actions. Used records retain their accounting history.
- Money: customer ledgers, due dates and ageing, monthly driver payments, expenses and dated cash flow.
- PDF / CSV invoices, customer and driver statements, and business reports.
- Vehicle booking calendar with overlap checks and completion into trips.
- Per-trip / kilometre / hour / day rental billing; salary follows final freight.
- Service and renewal targets with optional Android reminders.
- Full-tank fuel mileage, saved trip filters, attention cards and recoverable expense/payment drafts.
- Existing owner profile, light/dark themes, branding and configurable driver salary rates remain available.

Revision 6 is required for financial operations. Install over the existing signed app or use its normal update action. Package com.axlebook.axlebook and the original signing certificate are retained. Existing financial amounts are preserved.

Enable device reminders from Fleet → Service & renewals. Reports with over 1,000 records show a limit message rather than silently truncating. Planned bookings do not create revenue. Undated opening advances are excluded from dated cash flow and displayed separately.

## Previous releases

- [1.3.0 revision 4](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.3.0-4/app-release.apk)
- [1.2.0 revision 3](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.2.0-3/app-release.apk)
- [1.1.0 revision 2](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.1.0-2/app-release.apk)
- [1.0.0 revision 1](https://raw.githubusercontent.com/prakashec13/AvalStoreManager-Releases/axlebook/releases/v1.0.0-1/app-release.apk)

SHA256SUMS.txt identifies immutable APKs. The root release_manifest.json identifies the latest release; version directories retain their metadata. Older binaries remain for history and cannot save financial changes after the upgrade.

This branch contains APKs and release metadata only. Credentials, signing keys, private source code, backups, migration audits and business data are excluded.
