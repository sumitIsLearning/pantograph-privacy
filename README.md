# Pantograph privacy policy

Last updated: 1 October 2026

Pantograph is a Chrome extension that turns a part of a web page into a prompt for a coding agent. This policy says what it does with your data. The short version: it does not collect, send or share any.

## What stays on your device

- **Pages you capture.** When you click the toolbar icon and pick an element, Pantograph reads that tab's HTML, CSS, fonts and layout, and takes a screenshot of the element. This happens on your device, in your browser. The result is not sent anywhere by Pantograph.
- **The prompt and screenshot.** The prompt is copied to your clipboard and the screenshot is saved to your Downloads folder. Pantograph does not keep either one after that. Where you paste or upload them afterwards is your choice, and that service's own policy applies.
- **Notes you write.** Notes pinned to elements are used only to build the prompt and are discarded when the capture ends.

## What Pantograph stores

Only what you ask it to, in `chrome.storage.local` in your browser:

- the CSS variables you paste on the Options page, if you choose to;
- nothing else. No captures, no page content, no browsing history.

You can remove the saved CSS at any time: clear the box on the Options page and save, or remove the extension.

## What Pantograph does not do

- It does not send data to any server. It has no server and no account.
- It does not use analytics, tracking, advertising or crash reporting.
- It does not read or run on any page until you click the toolbar icon on that page.
- It does not sell or share data, because it has none.
- It does not load or run code from the network.

## Why it asks for the permissions it does

- **debugger:** to read a page's exact CSS and fonts through Chrome's DevTools Protocol. It is attached only after you click the icon, and detached when the capture ends. Chrome shows its own notice while this happens.
- **activeTab and scripting:** to show the control panel on the tab you clicked on.
- **offscreen and clipboardWrite:** to copy the prompt to your clipboard.
- **downloads:** to save the screenshot.
- **storage:** to keep your optional design tokens.

## Changes

If this policy changes, the new version will be published at this address with a new date.

## Contact

try.sumitchakraborty@gmail.com
