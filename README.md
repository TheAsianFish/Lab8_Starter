# Lab 8 - Fetch API & Service Workers

## Team
- Patrick Chung

## Deployed GitHub Pages URL
https://theasianfish.github.io/Lab8_Starter/

## Graceful Degradation & Service Workers

Graceful degradation is the practice of building an application so that it
still functions at a basic level even when certain technologies or resources
are unavailable. It maintains core functionality and user experience while preventing total failure. Service workers are a direct implementation of this principle
in web development. When a user has a network connection, the app fetches
fresh data and caches it via the service worker. When the network is
unavailable or slow, the service worker intercepts those requests and serves
the cached versions instead, allowing the app to remain functional offline.
Without service workers, losing internet access would mean losing the app
entirely. With them, the app degrades gracefully by falling back to cached
resources rather than breaking completely.

## PWA Screenshot
![PWA Screenshot](pwa.png)