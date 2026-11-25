<div align="center">

<h1>WALLETZ</h1>

<p><strong>Offline multi-pocket personal finance tracker for Android.</strong></p>

<p>Built with Kotlin, Jetpack Compose, and Room (SQLite) for daily expense logging without accounts, cloud sync, or bank APIs.</p>

<p>
  <img src="https://img.shields.io/badge/Android-7.0%2B%20(API%2024--35)-000000?style=for-the-badge&logo=android&logoColor=white" alt="Android 7.0+" />
  <img src="https://img.shields.io/badge/Kotlin-2.0.21-000000?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin 2.0.21" />
  <img src="https://img.shields.io/badge/Jetpack%20Compose-Material%203-000000?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
  <img src="https://img.shields.io/badge/Room-SQLite%20v6-000000?style=for-the-badge&logo=sqlite&logoColor=white" alt="Room SQLite v6" />
  <img src="https://img.shields.io/badge/Network-Offline-000000?style=for-the-badge&logo=airplane&logoColor=white" alt="Offline" />
  <img src="https://img.shields.io/badge/License-All_Rights_Reserved-000000?style=for-the-badge&logo=shield&logoColor=white" alt="All Rights Reserved" />
</p>

<p>
  <a href="https://github.com/saintxvz/Walletz/releases">
    <img src="https://img.shields.io/badge/Download_APK-v1.1.0_Release-FFFFFF?style=for-the-badge&logo=github&logoColor=000000" alt="Download APK" />
  </a>
</p>

<br/>

<table>
  <tr>
    <td align="center"><img src="images/home.jpg" width="240" alt="" /></td>
    <td align="center"><img src="images/needs.jpg" width="240" alt="" /></td>
    <td align="center"><img src="images/pockets.jpg" width="240" alt="" /></td>
  </tr>
</table>

---

### Features

| Area | Details |
| :--- | :--- |
| **Multi-Pocket Ledger** | Manual tracking across pockets with cumulative, current-month, or specific-date filters. Starts with **Cash**, **ShopeePay**, and **OVO**; add, rename, reorder, and pick an icon/color for your own pockets (e.g. GoPay, BCA, Savings). Deleting a pocket moves its transactions to the first remaining pocket. |
| **Monochrome OLED UI** | Deep OLED dark background, tabular odometer digits, tap-to-mask balances, and two-stage scroll-collapsing header. |
| **Transfers & Recurring** | Pocket-to-pocket transfers, manual balance adjustments, and `Daily` / `Weekly` / `Monthly` recurring schedules. |
| **Needs & Swipe Actions** | Planned expense checklist that auto-logs when checked off, plus swipe-to-delete with confirmation and undo. |
| **Category Summary** | Donut chart and per-category breakdown excluding internal transfers and balance adjustments. |
| **CSV Export & Import** | Multi-section UTF-8 CSV backup with formula sanitization and automatic local pre-import snapshots. |

---

### Privacy & Local Storage

No `INTERNET` permission is declared in `AndroidManifest.xml` — records stay in local SQLite storage unless exported manually.<br/>
Blacks out the Recent Apps preview (Android 13+ and on pause) and excludes the database and internal auto-backup CSVs from cloud backups. Regular screenshots are still allowed.

---

<sub>All Rights Reserved · Built with Kotlin, Jetpack Compose & Room · Typeface: <a href="third_party/Inter-LICENSE.txt">Inter (OFL-1.1)</a></sub>

</div>
