# Privacy Policy

**Effective date:** August 23, 2026  
**Publisher:** Homan

This Privacy Policy applies to the Stream Deck plugin and its companion browser extension (together, the "Software"). The Software lets a user control playback and volume on the YouTube Music website from a Stream Deck device.

## Summary

The Software does not send personal information, browsing activity, or playback information to Homan or to any developer-operated server. It has no analytics, advertising, tracking, user accounts, or cloud storage. Processing occurs locally on the user's computer.

## Information the Software accesses

To provide its controls, the browser extension accesses only pages matching `https://music.youtube.com/*`. On those pages, it locally:

- Finds the YouTube Music player controls needed for play/pause, previous, next, like, and dislike commands.
- Reads and changes the web player's volume and mute state.
- Reads limited player state, such as whether playback is paused.
- Checks which matching YouTube Music tab is active or audible so a command can be sent to the appropriate tab.

The Software does not intentionally read or collect account credentials, cookies, payment information, email addresses, song titles, playlists, or listening history.

## Local communication

The Stream Deck plugin and browser extension communicate over a WebSocket connection at `ws://127.0.0.1:17381`. This is the loopback interface of the user's computer and is not a developer-operated internet service.

Messages sent through this local connection contain playback commands and limited player state, including volume, mute, and paused status. The bridge accepts browser-extension connections and applies message-size, connection, handshake, and validation restrictions.

## Information stored locally

Stream Deck may store action settings selected by the user, such as:

- Selected browser.
- Selected key or dial command.
- Volume step size.
- Dial press behavior.

The Stream Deck plugin may also create local diagnostic logs containing browser type, command names, controller type, connection events, and error descriptions. These logs are used only for local troubleshooting and are not automatically transmitted to Homan.

Settings remain on the user's computer until they are changed, reset, or removed through Stream Deck. Diagnostic logs remain subject to Stream Deck's local log handling. Users may remove the Software and delete its local files through Stream Deck and their browser.

## Browser permissions

The browser extension requests only permissions used for its single purpose:

- Access to `music.youtube.com` is used to interact with the web player's controls.
- `scripting` is used to restore the local page controller when a previously open tab has not loaded it.
- `alarms` is used to maintain the local connection with the Stream Deck plugin.

The Software does not request access to all websites or general browsing history.

## Sharing, selling, and advertising

Homan does not receive, sell, rent, share, or use user data for advertising, profiling, credit decisions, or any purpose unrelated to the Software's user-facing functionality. The Software does not use third-party analytics or advertising services.

## Third-party services

YouTube Music, Google Chrome, Microsoft Edge, Stream Deck, Elgato, and their related services operate under their own terms and privacy policies. This Privacy Policy describes only the Software published by Homan and does not control how those third parties process information through their own products.

## Security

The Software limits its browser access to YouTube Music and limits plugin communication to the local loopback interface. Reasonable safeguards are used to validate local connections and messages. No software or transmission method can be guaranteed to be completely secure.

## Children's privacy

The Software is not directed to children and does not knowingly collect personal information from children.

## Changes to this policy

This policy may be updated when the Software's functionality or legal requirements change. The effective date at the top of this document will be updated when material changes are made.

## Contact

Questions or privacy requests may be sent to:

**Homan**  
**Email:** homanw712@gmail.com


