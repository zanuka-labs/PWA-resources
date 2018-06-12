# Rise of the PWA

## Web vs Native Apps

### Native Pros
  - fast, quick to respond
  - smooth, consistent, self contained UI
  - works consistently well offline (web app fail)

### Native Cons
  - longer developemnt time
  - have to learn NativeScript
  - expensive to develop (more resources)
  - application process is rough
  - have to rely on customers updating their apps

### PWA's Pros
  - Web standards (keep in the same context)
  - Most of the benfits of Native apps (including performance)
  - Write once, works everywhere

### Defining "progressive"
  - it's the next step up from progressive enhancement
  - should work everywhere regardless of the features
  - added features bring benefits across desktop and web
  - consistent UI on same codebase

### Basic checklist on PWA's (from Google Developers site)

This is a streamlined list for quick reference in projects. For more details, see the complete [Progressive Web App Checklist](https://developers.google.com/web/progressive-web-apps/checklist) at Google's Developer site.

The [Lighthouse tool](https://chrome.google.com/webstore/detail/lighthouse/) is able to automatically verify many items on the this list and may prove helpful in easily testing sites.

### Baseline Progressive Web App Checklist

  - Site is served over HTTPS
  - Pages are responsive on tablets & mobile devices
  - All app URLs load while offline
  - Metadata provided for Add to Home screen
  - First load fast even on 3G
  - Site works cross-browser
  - Page transitions don't feel like they block on the network
  - Each page has a URL
  - Site's content is indexed by Google
  - Schema.org metadata is provided where appropriate
  - Social metadata is provided where appropriate
  - Canonical URLs are provided when necessary
  - Pages use the History API

### User Experience
  - Content doesn't jump as the page loads
  - Pressing back from a detail page retains scroll position on the previous list page
  - When tapped, inputs aren't obscured by the on screen keyboard
  - Content is easily shareable from standalone or full screen mode
  - Site is responsive across phone, tablet and desktop screen sizes
  - Any app install prompts are not used excessively
  - The Add to Home Screen prompt is intercepted

### Performance
  - First load very fast even on 3G

### Caching
  - Site uses cache-first networking
  - Site appropriately informs the user when they're offline

### Push notifications
  - Provide context to the user about how notifications will be used
  - UI encouraging users to turn on Push Notifications must not be overly aggressive.
  - Site dims the screen when permission request is showing
  - Push notifications must be timely, precise and relevant
  - Provides controls to enable and disable notifications

### Additional features
  - User is logged in across devices via Credential Management API
  - User can pay easily via native UI from Payment Request API.

