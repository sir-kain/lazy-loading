# Lazy loading and perf

## loading="lazy" on image

```html
 <img src="..." alt="image alt" loading="lazy">
```

ref: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/img#loading

## Balise picture

- Quand charger?
- Comment charger? 
- Quoi charger? 

```html
<picture>
  <source srcset="for-desktop.jpg" media="(width >= 600px)" />
  <source srcset="for-mobile.jpg" media="(width < 600px)" />
  <img src="..." alt="image alt" />
</picture>
```

```html
<picture>
  <source srcset="logo-dark.png" media="(prefers-color-scheme: dark)" />
  <source srcset="logo-light.png" media="(prefers-color-scheme: light)" />
  <img src="logo-light.png" alt="Product logo" />
</picture>
```

```html
<picture>
  <source srcset="photo.avif" type="image/avif" />
  <source srcset="photo.webp" type="image/webp" />
  <img src="photo.jpg" alt="photo" />
</picture>
```

##
https://x.com/_sir_kane/status/1448984677440700450

https://www.youtube.com/watch?v=e0OHgC677ec

https://www.youtube.com/watch?v=YbAQC1yetUM