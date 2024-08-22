# dynamic-link-replacement

As of August 25th 2024, Firebase Dynamic Links have been deprecated (see <a href="https://firebase.google.com/support/dynamic-links-faq">announcement</a>)

This small repo contains a simple mechanism that redirects to the correct store (or preferably directly to an application) based on the user's browser's `User-Agent` header.

In case that fails in some fashion, each link is animated in after a two second delay, giving users the manual options to navigate to the one applicable to them.
