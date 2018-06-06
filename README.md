# flownav

Created by Danesh Iqbal - Email: [DIqbal](mailto:daneshiqbal95@hotmail.co.uk?Subject=Github%20flownav).

### What is flownav
<p>flownav is a fully customisable navbar created with simple and clean HTML and CSS</p>

### Implementation
<p>flownav can be implemented using CDN</p>

```html
<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/DIqbal/flownav/53607f2f/CSS/flownav.min.css">
```

### Styles
flownav comes in two different styles which are demonstrated in [flownav-thin] and [flownav-thick]

### Using flownav
<p>Using flownav is very easy and intuitive.</p>
  
```html
<div class="flownav-thin">
		<img src="logo.svg" class="flownav-logo-thin">
		
		<div class="flownav-lh-thin">
			<a href="#" class="flownav-link-thin">Link</a>
			<a href="#" class="flownav-link-thin">Link</a>
			<a href="#" class="flownav-link-thin">Link</a>
			<a href="#" class="flownav-link-thin">Link</a>
			<a href="#" class="flownav-link-thin">Link</a>
		</div>
</div>
```

### Note

<p>In the flownav CSS file the margin of the body is currently set to 0 so that the navbar fills the entire browser window.</p>

```CSS
body{
  margin: 0;
}
```

<p>You can remove this from the CSS file and it will work perfectly fine.</p>


### Planned Updates
- Hamburger Menu for smaller mobile screens
- More style variations
- Dropdown menu incorporation
