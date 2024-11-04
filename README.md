
## Assets

- Always load assets from a folder called "assets".

> Why? It models good project organization. It's also required for assets to load on the p5.js website. Place assets in the following folders to include them in our online documentation:
- [public/assets](https://github.com/processing/p5.js-website/tree/main/public)

```javascript
let img;

// Bad.
function preload() {
  img = loadImage('moonwalk.jpg');
}

// Good.
function preload() {
  img = loadImage('assets/moonwalk.jpg');
}
```

**[⬆ back to top](#table-of-contents)**
