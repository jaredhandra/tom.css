# tom.css

> A nostalgic CSS framework with modern, utility classes.

## Features

- **Classic MySpace Design** - Authentic early 2000s social media styling
- **Modern CSS** - Built with CSS Grid, Flexbox, and CSS Custom Properties
- **Style Utilities** - Familiar class naming conventions for easy adoption
- **12-Column Grid System** - Flexible, responsive layouts
- **Responsive Design** - Mobile-first approach with breakpoints at 768px and 576px
- **Lightweight** - Pure CSS with no JavaScript dependencies
- **Easy to Use** - Intuitive class names with `tom-` prefix

## Quick Start

### Installation

Simply include the Tom.css file in your HTML:

```html
<link rel="stylesheet" href="tom.css" />
```

### Basic Usage

```html
<div class="tom-container">
  <div class="tom-navbar">
    <a href="#" class="tom-navbar-brand">MySpace.com</a>
    <ul class="tom-navbar-nav">
      <li><a href="#" class="tom-nav-link">Home</a></li>
      <li><a href="#" class="tom-nav-link">Browse</a></li>
      <li><a href="#" class="tom-nav-link">Search</a></li>
    </ul>
  </div>

  <div class="tom-row">
    <div class="tom-col-3">
      <div class="tom-module">
        <div class="tom-module-header">Profile</div>
        <div class="tom-module-body">Content here</div>
      </div>
    </div>
    <div class="tom-col-9">Main content</div>
  </div>
</div>
```

## Components

### Container

```html
<div class="tom-container">
  <!-- Fixed-width container (960px) -->
</div>

<div class="tom-container-fluid">
  <!-- Full-width container -->
</div>
```

### Grid System

12-column responsive grid:

```html
<div class="tom-row">
  <div class="tom-col-4">Column 1</div>
  <div class="tom-col-4">Column 2</div>
  <div class="tom-col-4">Column 3</div>
</div>
```

**Responsive columns:**

- `tom-col-1` to `tom-col-12` - Desktop (default)
- `tom-col-md-{1-12}` - Tablet (≤768px)
- `tom-col-sm-12` - Mobile (≤576px)

### Modules (Cards)

```html
<div class="tom-module">
  <div class="tom-module-header">Module Title</div>
  <div class="tom-module-body">Module content goes here</div>
  <div class="tom-module-footer">Optional footer</div>
</div>
```

**Module variants:**

- `tom-module-compact` - Reduced padding
- `tom-module-lg` - Increased padding

### Navigation Bar

```html
<div class="tom-navbar">
  <a href="#" class="tom-navbar-brand">Brand</a>
  <ul class="tom-navbar-nav">
    <li><a href="#" class="tom-nav-link">Link</a></li>
  </ul>
</div>
```

### Buttons

```html
<button class="tom-btn">Default</button>
<button class="tom-btn tom-btn-primary">Primary</button>
<button class="tom-btn tom-btn-secondary">Secondary</button>
<button class="tom-btn tom-btn-sm">Small</button>
<button class="tom-btn tom-btn-lg">Large</button>
<button class="tom-btn tom-btn-block">Full Width</button>
```

### Profile Components

```html
<div class="tom-profile-pic">
  <img src="profile.jpg" alt="Profile" />
  <div class="tom-profile-name"><span class="tom-online"></span>Username</div>
  <div class="tom-profile-status">Status message</div>
</div>
```

### Friends Grid

```html
<div class="tom-friends-grid-4">
  <div class="tom-friend-item">
    <img src="friend.jpg" alt="Friend" />
    <a href="#" class="tom-friend-name">Friend Name</a>
  </div>
  <!-- More friends... -->
</div>
```

**Grid variants:**

- `tom-friends-grid-2` - 2 columns
- `tom-friends-grid-4` - 4 columns (default)
- `tom-friends-grid-8` - 8 columns

### Comments

```html
<div class="tom-comment">
  <div class="tom-comment-header">
    <div class="tom-comment-avatar">
      <img src="avatar.jpg" alt="User" />
    </div>
    <div class="tom-comment-meta">
      <a href="#" class="tom-comment-author">Author Name</a>
      <div class="tom-comment-date">Posted on Jan 1, 2026</div>
    </div>
  </div>
  <div class="tom-comment-body">Comment text here</div>
</div>
```

### Tables

```html
<table class="tom-table">
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
</table>
```

**Table modifiers:**

- `tom-table-striped` - Zebra stripes
- `tom-table-hover` - Hover effect
- `tom-table-borderless` - No borders
- `tom-contact-table` - MySpace contact table style

### Badges

```html
<span class="tom-badge">Default</span>
<span class="tom-badge tom-badge-primary">Primary</span>
<span class="tom-badge tom-badge-success">Success</span>
<span class="tom-badge tom-badge-danger">Danger</span>
<span class="tom-badge tom-badge-warning">Warning</span>
```

### Additional Components

```html
<!-- URL Display -->
<div class="tom-url">myspace.com/username</div>

<!-- Music Player -->
<div class="tom-music-player">Now playing: Song Name</div>

<!-- Details Grid -->
<div class="tom-details-grid">
  <div class="tom-label">Label:</div>
  <div>Value</div>
</div>

<!-- Online Indicator -->
<span class="tom-online"></span>
```

## Utility Classes

### Display

```html
tom-d-none
<!-- display: none -->
tom-d-block
<!-- display: block -->
tom-d-inline
<!-- display: inline -->
tom-d-inline-block
<!-- display: inline-block -->
tom-d-flex
<!-- display: flex -->
tom-d-grid
<!-- display: grid -->
```

### Flexbox

```html
tom-flex-row
<!-- flex-direction: row -->
tom-flex-column
<!-- flex-direction: column -->
tom-justify-start
<!-- justify-content: flex-start -->
tom-justify-center
<!-- justify-content: center -->
tom-justify-between
<!-- justify-content: space-between -->
tom-justify-end
<!-- justify-content: flex-end -->
tom-align-start
<!-- align-items: flex-start -->
tom-align-center
<!-- align-items: center -->
tom-align-end
<!-- align-items: flex-end -->
tom-flex-wrap
<!-- flex-wrap: wrap -->
tom-gap-1
<!-- gap: 5px -->
tom-gap-2
<!-- gap: 10px -->
tom-gap-3
<!-- gap: 15px -->
```

### Spacing

**Margin:**

```html
tom-m-0
<!-- margin: 0 -->
tom-m-1
<!-- margin: 5px -->
tom-m-2
<!-- margin: 10px -->
tom-m-3
<!-- margin: 15px -->
tom-m-4
<!-- margin: 20px -->

tom-mt-{0-4}
<!-- margin-top -->
tom-mb-{0-4}
<!-- margin-bottom -->
```

**Padding:**

```html
tom-p-0
<!-- padding: 0 -->
tom-p-1
<!-- padding: 5px -->
tom-p-2
<!-- padding: 10px -->
tom-p-3
<!-- padding: 15px -->
tom-p-4
<!-- padding: 20px -->

tom-pt-{0-3}
<!-- padding-top -->
tom-pb-{0-3}
<!-- padding-bottom -->
```

### Text

```html
tom-text-left
<!-- text-align: left -->
tom-text-center
<!-- text-align: center -->
tom-text-right
<!-- text-align: right -->

tom-text-primary
<!-- color: blue -->
tom-text-orange
<!-- color: orange -->
tom-text-muted
<!-- color: gray -->
tom-text-white
<!-- color: white -->

tom-fw-bold
<!-- font-weight: bold -->
tom-fw-normal
<!-- font-weight: normal -->

tom-fs-small
<!-- font-size: 10px -->
tom-fs-normal
<!-- font-size: 12px -->
tom-fs-large
<!-- font-size: 14px -->
```

### Background

```html
tom-bg-white
<!-- background: white -->
tom-bg-light
<!-- background: light blue -->
tom-bg-primary
<!-- background: blue -->
```

### Borders & Radius

```html
tom-border
<!-- border: 1px solid -->
tom-border-0
<!-- border: none -->
tom-rounded
<!-- border-radius: 4px -->
tom-rounded-circle
<!-- border-radius: 50% -->
```

### Width

```html
tom-w-25
<!-- width: 25% -->
tom-w-50
<!-- width: 50% -->
tom-w-75
<!-- width: 75% -->
tom-w-100
<!-- width: 100% -->
```

### Responsive Utilities

```html
tom-d-md-none
<!-- Hide on tablet and below -->
tom-d-md-block
<!-- Show on tablet and below -->
tom-d-sm-none
<!-- Hide on mobile -->
tom-d-sm-block
<!-- Show on mobile -->
```

## CSS Variables

Customize the color scheme by overriding CSS variables:

```css
:root {
  --tom-blue: #0066cc;
  --tom-link: #0066cc;
  --tom-orange: #ff6600;
  --tom-border: #b2c5d9;
  --tom-header-bg: #6699cc;
  --tom-table-header: #547dae;
  --tom-bg: #e5ecf3;
  --tom-module-bg: #c5d6e9;
  --tom-white: #ffffff;
  --tom-text: #333333;
}
```

## Responsive Breakpoints

- **Desktop**: > 768px (default)
- **Tablet**: ≤ 768px (md)
- **Mobile**: ≤ 576px (sm)

## Example Profile Page

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My MySpace Profile</title>
    <link rel="stylesheet" href="tom.css" />
  </head>
  <body>
    <div class="tom-container">
      <!-- Navigation -->
      <div class="tom-navbar">
        <a href="#" class="tom-navbar-brand">MySpace.com</a>
        <ul class="tom-navbar-nav">
          <li><a href="#" class="tom-nav-link">Home</a></li>
          <li><a href="#" class="tom-nav-link">Browse</a></li>
          <li><a href="#" class="tom-nav-link">Search</a></li>
        </ul>
      </div>

      <!-- Profile Layout -->
      <div class="tom-row">
        <!-- Sidebar -->
        <div class="tom-col-3 tom-col-md-12">
          <div class="tom-module">
            <div class="tom-module-header">Profile</div>
            <div class="tom-module-body tom-profile-pic">
              <img src="profile.jpg" alt="Profile" />
              <div class="tom-profile-name">
                <span class="tom-online"></span>Your Name
              </div>
            </div>
          </div>
        </div>

        <!-- Main Content -->
        <div class="tom-col-9 tom-col-md-12">
          <div class="tom-module">
            <div class="tom-module-header">About Me</div>
            <div class="tom-module-body">
              <p>Your bio here...</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
```

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

MIT License

## Credits

Thanks for the add!

---

Built with love and early 2000s nostalgia
