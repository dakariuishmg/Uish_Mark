# Uish_Mark
Sovereign Offline Bookmark &amp; URL Keeper. YOU: Bookmarks across several browsers and accounts. THIS: Input all needed bookmarkers, they organise, you launch from one single place.

UISHmark Keeper — A Sovereign Bookmark Storage Keep.

UISHmark Keeper is a zero-dependency, single-file HTML application that functions as a personal bookmark operating system. It runs entirely in your browser with no installation, no account, no server, and no cloud. Bookmarks and single-file HTML tools are stored locally using your choice of storage backend — from localStorage to IndexedDB — and persist across sessions on the same device. The interface is intentionally minimal at boot: two icons become three, a gear sits quietly in the corner, and everything else is a keystroke away.

What is it?
UISHmark Keeper is a single .html file that acts as a personal bookmark operating system. Open it in any browser. No install. No account. No internet required after the first load. Everything you save stays on your device, in your browser.
Getting started

Save uishmark.html anywhere on your device.
Open it in any modern browser (Chrome, Firefox, Safari, Edge).
You will see two icons. A third and a gear.
+ — Add a URL bookmark via the 3-step wizard.
◻ — Open your Bookmarks library.
⊡ — Open your HTML Tools library.
⚙ — Open Settings (always accessible, top-right corner).

HTML Tools library
The Tools library is distinct from bookmarks. It is designed specifically for single-file HTML applications — tools like UISHmark itself, calculators, generators, games, dashboards, or any .html file you want to launch on demand. Drop a .html file onto the panel. It reads the title, stores the full source, and launches it in a new tab


Switch backends at any time from Settings. A migration dialog offers to copy your existing data across. A storage meter shows current usage with a colour-coded fill bar. The gear icon shows a red dot if any backend nears its limit.
Keyboard shortcuts
KeyActionAOpen Add URL wizardLOpen Bookmarks libraryTOpen HTML Tools librarySOpen Settings?Toggle help panel/ or typeOpen command barESCClose active panel
Commands
Type anything on the boot screen to open the command bar.
add https://example.com   → Quick-save a bookmark
list                      → Open bookmarks library
tools                     → Open tools library
clear                     → Wipe all bookmarks
help                      → Show keyboard shortcuts
Customisation

5 themes: Obsidian · Terminal · Chalk · Glacier · Dusk
8 accent colours: Amber · Terminal Green · Crimson · Ice · Dusk Pink · Rose · Emerald · Orange
3 layouts: Grid · List · Compact
3 densities: Airy · Normal · Dense
Card info toggles: visit count, tags

Cross-device
All backends are per-browser, per-device. To move data between devices, use Export JSON in the library toolbar and import on the target device. For HTML tools, export each tool as a .html file via the ⋮ menu.
File integrity
This file is self-contained. 
