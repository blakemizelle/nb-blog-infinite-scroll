# NationBuilder Infinite Scroll Blog Template

A clean implementation of infinite scroll functionality for NationBuilder blog pages. This template demonstrates how to extend NationBuilder's default blog template to create dynamic content feeds.

## Overview

This template provides a modern infinite scroll solution for NationBuilder blogs that:
- Loads content dynamically as users scroll
- Maintains consistent styling between loaded content 
- Provides visual feedback during loading
- Requires no external dependencies

## Features

- 🚀 Fast initial page load (5 posts)
- 📜 Smooth infinite scrolling
- 🔄 Loading indicator
- 📊 Post counter display
- 💅 Consistent styling
- ⚡️ Debounced scroll detection
- 🎯 Edge case handling

## Implementation
**Implementation Note**: This template modifies NationBuilder's default Bootstrap blog template and should only be used to replace existing NationBuilder blog page templates.

### Setup

1. Create or edit a blog page in NationBuilder admin
2. Replace the default template with contents of `blog.html`
3. Publish changes
4. Test scroll functionality

## Customization

You can easily customize:
- Initial post count (`limit: 5`)
- Scroll trigger distance (`offsetHeight - 1000`)
- Loading indicator style
- Post counter position/style
- Post spacing and borders

## Support

For implementation support, contact your NationBuilder account representative or development team.

## Contributing

This is an example implementation. Feel free to fork and customize for your specific needs.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Note**: This template demonstrates a clean implementation of infinite scroll in NationBuilder. Production deployment should include proper error handling and testing.
