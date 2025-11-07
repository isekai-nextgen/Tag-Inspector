# Tag Inspector

A comprehensive Chrome extension for inspecting and analyzing all tags on web pages. Track scripts, links, iframes, and meta tags with performance metrics, validation, and export capabilities.

## Features

- **Complete Tag Detection**: Automatically detects all script, link, iframe, and meta tags on the page
- **Service Recognition**: Identifies 28+ services including Google Tag Manager, Google Analytics, Facebook Pixel, HubSpot, Bloomreach, Segment, Adobe Analytics, and more
- **Performance Metrics**: Tracks load time, file size, and execution order for each tag
- **Tag Validation**: Detects duplicates, missing async/defer attributes, failed loads, validation issues, and provides performance recommendations
- **Advanced Filtering**: Filter by type, category, service, or search for specific tags. Sidebar navigation with tab-based filtering by type, service, or category
- **Export Functionality**: Export tag lists as JSON or CSV for analysis and reporting
- **Keyboard Shortcuts**: Quick access to common actions (Ctrl+R refresh, Ctrl+E export, Ctrl+F search)
- **Real-time Updates**: Automatically detects dynamically added tags
- **Issue Detection**: Highlights tags with errors, warnings, or performance problems

## Installation

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in top right)
3. Click "Load unpacked"
4. Select the extension directory

## Usage

1. Open Chrome DevTools (F12 or right-click → Inspect)
2. Navigate to the "Tag Inspector" tab
3. The extension will automatically scan for tags on the current page
4. Use the sidebar to filter by:
   - **Type**: Scripts, Links, Iframes, Meta tags
   - **Service**: GTM, Google Analytics, Facebook, Bloomreach, HubSpot, Segment, Adobe, Hotjar, Intercom, Microsoft Clarity
   - **Category**: Analytics, Marketing, Issues
5. Use the search box to find specific tags by URL, service, or purpose
6. Use sorting options (Execution Order, Name, Type, Category, Load Time, Size)
7. Toggle "Issues Only" to show only tags with problems
8. Click tags to expand and see detailed information

### Keyboard Shortcuts

- **Ctrl/Cmd + R**: Refresh tag list
- **Ctrl/Cmd + E**: Export tags
- **Ctrl/Cmd + F**: Focus search input
- **Escape**: Clear search

## What It Shows

For each tag, the extension displays:

- **Tag Type**: Script, Link, Iframe, or Meta
- **Source URL**: Where the tag is loaded from (if external)
- **Purpose**: What the tag does
- **Detected Service**: Which service the tag belongs to (e.g., Google Tag Manager, Facebook Pixel)
- **Performance Metrics**: Load time, file size, execution order
- **Validation Status**: Whether the tag has issues or errors
- **Attributes**: All HTML attributes of the tag
- **Inline Content**: For inline scripts, shows the actual code

## Supported Services

The extension recognizes 28+ services including:

- **Analytics**: Google Analytics, Google Tag Manager, Adobe Analytics, Segment, Mixpanel, Amplitude
- **Marketing**: Facebook Pixel, LinkedIn, Twitter, Pinterest, HubSpot, Bloomreach
- **Optimization**: Optimizely, VWO, Hotjar, Google Optimize
- **Support**: Intercom, Drift, LiveChat, Zendesk
- **Monitoring**: Microsoft Clarity, New Relic, Datadog, Sentry, Cloudflare
- **Other**: Tealium, Salesforce, Qualtrics

## Export

Export your tag data in two formats:

- **JSON**: Complete tag data with all attributes and metadata
- **CSV**: Spreadsheet-friendly format for analysis

Both exports include page URL, timestamp, and all tag information.

## License

MIT
