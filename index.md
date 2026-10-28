**Last updated:** 28 October 2026

This privacy policy covers the **Package Availability for Endpoint Central MSP** browser extension for Google Chrome ("the extension") and explains how it handles data. In short: **the extension does not collect, store, transmit or share any data.**

## Summary

- The extension has one purpose: it shows whether a software package in the **Endpoint Central MSP** package list is available to **all customers** or to **one customer only**, and lets you search and sort by that.
- It runs **only** on `https://endpointcentral.manageengine.eu/*`.
- It works **only inside your browser**, with data that Endpoint Central already sends to your browser while you are logged in.
- It **stores nothing**: no settings, no cookies, no local storage.
- It has **no analytics, tracking, advertising or remote code**, and it makes **no network requests of its own**.

## Who is responsible

The extension is published and maintained by Luca Lehner, a private individual in Switzerland.
Contact: **luca.lehner@gmail.com**

## What the extension does

Endpoint Central MSP already includes the attribute `IS_FOR_ALL_CUSTOMERS` with every package it sends to the package list, but does not display it. The extension:

1. shows that attribute in the package list (in the existing "Language" column, renamed to "Availability") as "All customers" or "Customer only";
2. when you search or sort by that column, adjusts the list request that your browser sends to Endpoint Central, so that the full list is loaded and can then be filtered and sorted by availability in your browser.

The extension does not change any packages, settings or other data in Endpoint Central. It only changes how the list is requested and displayed in your browser.

## Data the extension accesses

To do this, the extension reads the **package list responses** that Endpoint Central returns to your browser. Besides package information (such as package name, ID, type and availability), these responses can include the **first names of the administrators** who created or last changed a package, as displayed by Endpoint Central itself.

This processing happens **entirely within your browser, on your device**. The extension:

- does **not** send this data to the developer or to any third party;
- does **not** store this data;
- holds it only in memory while the list is being displayed and discards it when you reload or leave the page.

Because no data leaves your device, the extension does **not "collect" user data** as defined by the Chrome Web Store.

## Data the extension stores

None. The extension uses no extension storage, no local storage, no cookies and no other persistent storage.

## What the extension does NOT do

- It does **not** collect, transmit, sell or share any user data.
- It does **not** include any analytics, telemetry, tracking or advertising.
- It does **not** load or execute any remote/hosted code.
- It does **not** make any network requests of its own. It only adjusts the parameters of list requests that the Endpoint Central page sends itself.
- It does **not** access any website other than `endpointcentral.manageengine.eu`.
- It does **not** read or use passwords, session tokens or cookies.

## Permissions and why they are needed

- **Host access to `https://endpointcentral.manageengine.eu/*`** (through a content script). This lets the extension run on the Endpoint Central MSP console to display and filter by package availability. It requests access to **no other websites** and **no additional Chrome permissions**.

## Data sharing and third parties

None. No data is shared with the developer or any third party, because no data is collected or transmitted.

The extension is an independent tool and is **not affiliated with, endorsed by or supported by ManageEngine or Zoho Corporation**. "ManageEngine" and "Endpoint Central" are trademarks of their respective owners. Data processed by Endpoint Central itself is governed by ManageEngine's own privacy policy.

## Data retention

The extension retains no data. Package list data is held in memory only while the page is open. Uninstalling the extension leaves nothing behind.

## Your rights

The extension does not collect or hold personal data, so there is no personal data that the developer could provide, correct or delete. Data displayed in Endpoint Central is controlled by your organisation and ManageEngine. For questions about the extension, including under the Swiss Federal Act on Data Protection (FADP) or the GDPR, please use the contact address below.

## Children

The extension is a tool for IT administrators who use Endpoint Central MSP and is not directed at children.

## Disclaimer

The extension is provided **"as is", without warranty of any kind**, express or implied, including warranties of merchantability, fitness for a particular purpose, accuracy and non-infringement. It is distributed under the MIT License.

The extension adapts how a third-party product requests and displays data. Updates to Endpoint Central may cause it to show incorrect or incomplete information or to stop working. **Always verify important information, in particular your package selection before deleting or deploying packages, in Endpoint Central without the extension.** If in doubt, disable the extension.

To the extent permitted by applicable law, the developer is not liable for any direct or indirect damage, data loss, loss of profit or other loss arising from the use of, or the inability to use, the extension. Liability that cannot be excluded by law (for example for intent or gross negligence) remains unaffected.

## Changes to this policy

If this policy changes, the updated version will be published on this page and the "Last updated" date above will be revised.

## Contact

Questions about this policy or the extension: **luca.lehner@gmail.com**
