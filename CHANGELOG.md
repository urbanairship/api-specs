# Airship API Specs Changelog

## Version 7 (June 23, 2026)

### Changes

- Added Content API with Templates endpoints
- Added custom event external campaign categories
- Added Journeys endpoints
- Added attributes action to actionsObject (set or remove channel/contact attributes on notification interaction)
- Added tags actions to the actionsObject (add or remove channel/contact tags on notification interaction)
- Added OAuth scopes: tpl (content templates), jny (Journeys), rpt (Reports)
- Added the ability to specify start and end times for Wallet notifications
- Added Wallet NFC query param for AdaptiveLink Passes
- Added Google Wallet Auto-linked Passes endpoints
- Added OAuth 2.0 support in Wallet
- Added documentation to RTDS compliance stream for email suppression removal
- Updated Subscription event, Subscription List event, and Email unsubscribe events in RTDS
- Added Campaigns and custom keys ("extra") to certain rich push body in RTDS
- Listed emailInitialOpenEvent as one of the custom event in RTDS
- Added optional campaigns fields in the body of several In-app events in RTDS

## Version 6 (February 19, 2026)

### Changes

- Added `add_custom_event` notification action
- Added Basic Auth (App) to `api/channels/subscription_lists` endpoint
- Added `ua_rcs_enabled` device property
- Added Contacts endpoints:
  - Contact association
  - Contact disassociation
  - Scoped Contact batch operations
  - Contacts tags
  - Set or remove attributes on a Contact
- Added OAuth to Contacts endpoints:
  - Look up Contact ID by Channel ID
  - Look up Contact ID by Named User ID
- Added required `offset` fields for all RTDS events

## Version 5 (November 12, 2025)

### Changes

- Updated to latest specs

## Version 4 (August 28, 2025)

### Changes

- Updated to latest specs

## Version 3 (April 8, 2022)

### Changes

- Added Support for Scenes and Surveys to RTDS
- Removed button groups from In-App Message data references

## Version 2 (March 24, 2022)

### Changes

- Added Contacts spec
- Added subscription lists spec and examples
- Added Java and Ruby tag list examples
- Added Open Channels examples
- Fixed atomic selector definition
- Fixed angled/styled quotes

## Version 1 (January 20, 2022)

Initial release.

### Changes
- Added Open API specs for RTDS (connect), go and wallet endpoints

