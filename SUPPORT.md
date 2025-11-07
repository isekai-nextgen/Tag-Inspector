# Tag Inspector - Support

## Getting Help

If you need help with Tag Inspector, here are the best ways to get support:

### 📋 Documentation

- **README.md**: Start here for installation, usage, and feature overview
- **Chrome Web Store**: Check the extension listing for detailed descriptions

### 🐛 Report Issues

Found a bug or have a feature request? Please open an issue on GitHub:

1. Go to [Issues](https://github.com/isekai-nextgen/Tag-Inspector/issues)
2. Click "New Issue"
3. Choose the appropriate template (Bug Report or Feature Request)
4. Provide as much detail as possible:
   - What you were trying to do
   - What happened (or didn't happen)
   - Steps to reproduce (if it's a bug)
   - Screenshots (if applicable)
   - Browser version and OS

### ❓ Common Questions

**Q: The extension isn't detecting tags on my page**
- Make sure you've opened Chrome DevTools (F12)
- Navigate to the "Tag Inspector" tab
- Click the "Refresh" button
- Some pages may restrict content scripts - try a different page

**Q: I see "Extension context invalidated" error**
- This usually happens after updating the extension
- Close and reopen Chrome DevTools
- If that doesn't work, reload the extension from `chrome://extensions/`

**Q: Can I use this on localhost or file:// pages?**
- Yes! The extension works on all pages including localhost and file:// URLs

**Q: Does the extension work with iframes?**
- The extension detects iframe tags, but content scripts only run in the main frame by default
- Nested iframe content may not be fully analyzed

**Q: How do I export tag data?**
- Click the "Export" button in the toolbar
- Choose JSON or CSV format
- The file will download to your default download folder

**Q: Can I filter by multiple criteria?**
- Yes! Use the sidebar to filter by type, service, or category
- Use the search box to find specific tags
- Combine filters with the "Issues Only" checkbox

**Q: What services does Tag Inspector detect?**
- The extension recognizes 28+ services including Google Tag Manager, Google Analytics, Facebook Pixel, HubSpot, Bloomreach, Segment, Adobe Analytics, and many more
- See the README.md for the complete list

**Q: Is my data sent anywhere?**
- No! All analysis happens locally in your browser
- No data is collected, stored, or transmitted
- See PRIVACY.md for more details

### 🔧 Troubleshooting

**Extension not appearing in DevTools:**
1. Make sure the extension is enabled in `chrome://extensions/`
2. Reload the extension if needed
3. Close and reopen DevTools
4. Check that you're using Chrome 88 or later

**Tags not showing up:**
1. Click the "Refresh" button
2. Make sure the page has fully loaded
3. Try refreshing the page itself
4. Check the browser console for errors (F12 → Console tab)

**Export not working:**
1. Check that pop-ups aren't blocked
2. Make sure you have download permissions
3. Try a different browser if issues persist

**Performance issues with many tags:**
- The extension is optimized for pages with hundreds of tags
- If you experience slowdowns, try filtering to specific tag types
- Use the "Issues Only" filter to focus on problematic tags

### 💡 Tips & Best Practices

1. **Use keyboard shortcuts** for faster navigation:
   - `Ctrl/Cmd + R`: Refresh
   - `Ctrl/Cmd + E`: Export
   - `Ctrl/Cmd + F`: Focus search

2. **Filter effectively**:
   - Start with the "Issues" tab to find problems quickly
   - Use service-specific tabs to focus on specific tools
   - Combine search with filters for precise results

3. **Export regularly**:
   - Export tag data before making changes
   - Use CSV for spreadsheet analysis
   - Use JSON for programmatic processing

4. **Check performance**:
   - Sort by "Load Time" to find slow tags
   - Look for tags without async/defer attributes
   - Identify large files that might impact performance

### 📞 Contact

- **Email**: isekai.nextgen.apps@gmail.com
- **GitHub Issues**: [Open an issue](https://github.com/isekai-nextgen/Tag-Inspector/issues)
- **Repository**: [Tag Inspector on GitHub](https://github.com/isekai-nextgen/Tag-Inspector)

---

**Thank you for using Tag Inspector!** If you have any questions or need help, please don't hesitate to reach out via email or GitHub issues.
