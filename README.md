# STAR: Sales Tax Report

STAR builds the monthly sales tax report for a construction job. Pick a job and a date range, and it pulls the A/P invoice lines from Spectrum, applies the sales tax rules, lets you review and adjust, and exports the report to Excel or PDF. It also shows each invoice's image beside the report and exports a marked-up package for the general contractor.

It is made for project accountants at SPC Mechanical.

<!-- TODO: add a screenshot here (drag a PNG into the GitHub editor, or add it to this repo as screenshot.png) -->

## Download

1. Click **Releases** on the right-hand side of this page.
2. Click the newest version at the top.
3. Under **Assets**, download **STAR-win64.zip**.

## Install and run

1. Right-click the downloaded zip and choose **Extract All**.
2. Open the extracted folder and double-click **Install.cmd**. No administrator rights are needed.
3. Open **STAR** from the new Desktop or Start-menu shortcut.

Your settings, job files and Final reports are kept when you install a newer version.

## "Windows protected your PC"

STAR is not code-signed, so Windows may show a blue warning the first time. If you trust where you got it, click **More info**, then **Run anyway**.

To check the download was not altered, compare its SHA256 checksum with the one at the bottom of the release notes. In PowerShell:

```
Get-FileHash $HOME\Downloads\STAR-win64.zip -Algorithm SHA256
```

## What you need

- Windows 10 or 11, 64-bit.
- Microsoft **ODBC Driver 18 for SQL Server** (free from Microsoft). STAR needs it to read A/P lines from Spectrum.
- A Spectrum login and a connection to the SPC network or VPN. STAR asks for your own login the first time; it is saved on your computer only.

## Updates

When a newer version is released, STAR shows a "Version x.y.z is available" button at the bottom right. Click it to open the download page and repeat the steps above.

## Help

Contact: David
