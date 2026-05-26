# Lab 8 - Network & ServiceWorkers

## Contributors
- Kareem Nabulsi

## Deployed GitHub Pages URL
https://lumen98.github.io/Lab8_Starter/

## Graceful Degradation and Service Workers
Graceful degradation is the principle of building a web app with full functionality
first, then ensuring it still works in a less-than-ideal
environments. Service workers are a key tool that enables this. They sit between
the page and the network, intercepting fetch requests and serving cached
responses when the network is slow or unavailable. Without a service worker, an
app that loses its connection breaks completely, with one, the app degrades
gracefully, the user still sees the cached HTML, CSS, JS, and recipe data even
while offline. So service workers are one of the main mechanisms that make
graceful degradation possible for modern web apps.

## PWA Screenshot
See `pwa.png` in the repository root.
