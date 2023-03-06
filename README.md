# modern-design-landing-page
A landing page for a mockup company: Modern Design, a brand, web, and graphic design company.

## My Favorite Code Snippets

1. This Creates a Small Indicator For Navbar Links

```CSS
.selected::after {
  position: absolute;
  content: '';
  width: 12ch;
  height: 2px;
  border-bottom: 5px var(--primary) solid;
  border-radius: 24px 24px 0 0;
  bottom: 0;
}
```

2. This Clips Top `box-shadow`

```CSS
.dropdown__contents {
  box-shadow: 0 0 8px rgba(0, 0, 0, 0.2);
  clip-path: inset(0px -10px -10px -10px);
  /* clips anything starting from the top, but allows 10px on all other sides */
}
```