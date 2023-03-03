# web-applicationsPWA

# Table of Contents
- [web-applicationsPWA](#web-applicationspwa)
- [Table of Contents](#table-of-contents)
- [Description](#description)
- [Installation Instructions](#installation-instructions)
- [Github Account](#github-account)
- [Images](#images)
- [Contacts](#contacts)
- [Code Snippets](#code-snippets)
- [Resources](#resources)


# Description
Your task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

To build this text editor, you will start with an existing application and implement methods for getting and storing data to an IndexedDB database. You will use a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

# Installation Instructions
- Please make sure you install the following package

# Github Account
- [GitHub](https://github.com/ashrean)
- [Deployed Link]()

# Images
![alt text](./client/src/images/Screenshot%202023-03-02%20at%2010.58.08%20PM.png)

# Contacts
- [Email](sese.ashrean@gmail.com)
- [Linkedin](https://www.linkedin.com/in/ashleyrean/)

# Code Snippets
```// TODO: Implement asset caching
registerRoute(({ request}) => ['style', 'script', 'worker'].includes(request.destination),
  new StaleWhileRevalidate({
    cacheName: 'asset-cache',
    plugins: [
      new CacheableResponsePlugin({
        statuses: [0, 200],
      }),
      new ExpirationPlugin({
        maxEntries: 60,
        maxAgeSeconds: 30 * 24 * 60 * 60,
      })
    ],
  })
);
```
# Resources
- Class Activities
-
