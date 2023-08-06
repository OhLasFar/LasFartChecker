# LasFartChecker

LasFartChecker is an extension for Google Chrome and Microsoft Edge designed to enhance web browsing security. As an analyst, I've noticed a lack of security on the web, and I've created this extension to help users double-check the links they click on.

The primary goal of LasFartChecker is to give the user full control over the links they click. Whenever a user clicks on a link, a popup appears on the screen, giving the user the option to confirm whether they want to navigate to the new URL or cancel the navigation to stay safe.

I understand that constant popups can be annoying. That's why I've added a whitelist feature. This whitelist, stored in local storage, allows the user to add the domain of the site they are currently on. Once a domain is added to the whitelist, the user can "trust" that domain, and no confirmation popup will appear when navigating within that site.

The user has the option to remove a domain from the whitelist by clicking on the "X" in the extension menu. It's also possible to manually add a site's domain to the whitelist.

LasFartChecker takes into account domain prefixes and suffixes. This means that if you're on a subdomain (for example, prefix.domain.com) and the main domain (domain.com) is whitelisted, no confirmation popup will appear.

**Please note that I am an analyst, not a coder, and there are currently some bugs in the extension. For instance, the whitelist feature may not work as expected, causing popups to appear even when the domain is whitelisted. I also suspect that prefixes and suffixes may not be correctly considered.

**The GUI is not currently styled, as the focus has not been on this aspect yet.

If you like the idea of this extension and would like to support its development, you can buy me a coffee by following this URL link. https://botrix.live/y/@lasfar/tip

In summary, LasFartChecker is an extension aimed at enhancing web browsing security by giving the user full control over the links they click, while offering the ability to "trust" certain domains for uninterrupted browsing. Despite its current limitations, it represents a step towards a safer browsing experience.

# How to Install "LasFart Checker"

### Google Chrome

1. Download the latest version of the LasFart Checker extension.
2. Unzip the extension file into a directory of your choice.
3. Open Google Chrome and click on the three-dot menu icon in the top right corner.
4. Hover over "More Tools" and click on "Extensions" from the submenu.
5. Toggle the "Developer mode" switch in the top right corner.
6. Click on the "Load unpacked" button that appears.
7. Navigate to the directory where you unzipped the LasFart Checker extension and click on "Select Folder".

The LasFart Checker extension should now be installed on Google Chrome.

### Microsoft Edge

1. Download the latest version of the LasFart Checker extension.
2. Unzip the extension file into a directory of your choice.
3. Open Microsoft Edge and click on the three-dot menu icon in the top right corner.
4. Click on "Extensions".
5. Toggle the "Developer mode" switch in the bottom left corner.
6. Click on the "Load unpacked" button.
7. Navigate to the directory where you unzipped the LasFart Checker extension and click on "Select Folder".

The LasFart Checker extension should now be installed on Microsoft Edge.

Remember to disable "Developer mode" once you're done to prevent any unwanted changes.

Keep in mind that the extension can only be used in the browser where it's installed. To use it across different computers, you'll have to either install it on each computer.
