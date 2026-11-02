# Peach Light for Standard Notes

A CSS-only companion to [Peach Black](https://github.com/Lawsinex/standard-notes-peach-black-theme).

Uses neutral near-white `#FAFAFA`, white panels `#FFFFFF`, gray borders `#D8D8D8`, dark text `#171717`, secondary text `#5F5F5F`, peach filled controls `#FFC49A`, pale peach selections `#FFF0E4`, and dark-peach links `#9B4E24` for readable contrast.

## Install

On the web app, use **Preferences → Backups → Import backup** with `Peach-Light-Theme.sn.txt`. It contains exactly one theme and no notes, account data, keys, or application preferences. Standard Notes may ask you to authenticate the import.

On native desktop, use **Preferences → Plugins → Install Custom Plugin** with:

`https://cdn.jsdelivr.net/gh/Lawsinex/standard-notes-peach-light-theme@v1.0.0/ext.json`

Select Peach Light in the quick-settings theme menu. To switch automatically, choose Peach Light for Automatic Light Theme and Peach Black for Automatic Dark Theme under Appearance, then enable Use system color scheme.

The current web URL installer rejects CDN manifests through its Content Security Policy, and GitHub raw manifests through credentialed CORS. The theme-only import uses the built-in data importer; normal stylesheet loading stays within the app's security policy. No browser protections need to be changed.

The stylesheet is pinned to version 1.0.0. Automatic updates are disabled in the import package. No scripts or external assets are embedded. Third-party editors may apply independent styles. Mobile rendering needs separate verification.

## Verified on 2 November 2026

Installed through the custom-plugin URL in the official Apple Silicon macOS app 3.202.11. Peach Light was selected and visually checked: light neutral surfaces, peach filled controls, dark labels, and pale peach selections rendered correctly. It is configured as the automatic light theme, paired with Peach Black as the automatic dark theme. The app remains signed out for the user to sign in later; account sync is not yet verified.

After quitting and reopening the app, both automatic theme assignments were retained and Peach Black rendered for the current system dark appearance.

## Sources

- [Standard Notes theme support](https://standardnotes.com/help/plugins/themes)
- [Standard Notes plugin packaging](https://standardnotes.com/help/plugins/publishing)
- [Standard Notes button implementation](https://github.com/standardnotes/app/blob/main/packages/web/src/javascripts/Components/Button/Button.tsx)

MIT licensed; see LICENSE.
