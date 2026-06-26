# Bar-Parental-Control-Skipper For Mac OS

Apps in the toolbar are not affected by Apple's macOS parental controls, so I created a web client that runs in your tool bar and that you can use as much as you want, whenever you want.

BarPCskipper is a web client for macOS designed to live exclusively in the menu bar. It has no main window: when you click the icon, a compact panel appears where you can paste a URL, and the page is loaded directly inside the dropdown.

## What it does

* Lives in the menu bar and does not appear as a traditional app in the Dock.
* Loads any URL directly inside the panel.
* Automatically adjusts many websites to fit better within the mini display.
* Allows specific domains to be excluded from this automatic scaling.
* Includes YouTube in the exclusion list by default to avoid interface issues.

## How to use it

1. Click the BarPCskipper icon in the menu bar.
2. Paste a URL into the input field.
3. Click `Load Here` or press Enter.
4. The page will appear in the panel's 16:9 display.

You can also use `Paste` to instantly load the URL currently stored in your clipboard.

## Scaling and exceptions

BarPCskipper tries to fit many websites within the display so they do not overflow horizontally.

At the bottom of the panel, there is a section called `No Scaling`:

* It shows the domains that are loaded without any resizing.
* YouTube is included by default.
* You can add a domain by typing it into the field and clicking `Add`.
* You can add the current page's domain by clicking `Add Current`.
* Each domain can be removed by clicking the `x`.

If a website looks odd when automatically scaled, add it to this list and it will be displayed at its original size.


For running the app just drop the .app that is in the .dmg in your applications folder and run tis command in your terminal: 
xattr -d com.apple.quarantine /Applications/BarPCskiper.app 

(change the "/Applications/BarPCskiper.app" to the exact route of the app, you can do that by pasting this command "xattr -d com.apple.quarantine " dragging the BarPCskipper app and pressing intro)
