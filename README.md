﻿Sitecore - Remote Cache Kick
==============

Summary
--------------
Adds a button to the publish ribbon so users (with access) can clear the remote server caches.

![alt text](https://github.com/digitalParkour/Community.Foundation.RemoteCacheKick/raw/master/screenshots/Button.png "Custom cache clear button in publish ribbon")

Implementation
--------------
A custom remote event is used to broadcast the button click.
An event handler is used to respond to the remote event and clear server cache.

Special thanks to [Kasaku on sitecore.stackexchange](https://sitecore.stackexchange.com/questions/2271/clearing-cd-cache-in-code-from-the-cm) for outlining the approach.

Install through a Sitecore package:
--------------
You can find all the releases and packages [here](https://github.com/KayeeNL/Community.Foundation.RemoteCacheKick/releases), but you can also download the correct package for your specific Sitecore version here:

_Right click 'Save link as...'_

- [Remote Cache Kick for Sitecore-9.3](./releases/Community-Foundation-RemoteCacheKick-9.3.zip) (Sitecore 9.3)
- [Remote Cache Kick for Sitecore-10.0.0.0](./releases/Community-Foundation-RemoteCacheKick-10.0.0.zip) (Sitecore 10.0.0.0)
- [Remote Cache Kick for Sitecore-10.0.0.1](./releases/Community-Foundation-RemoteCacheKick-10.0.1.zip) (Sitecore 10.0.0.1)
- [Remote Cache Kick for Sitecore-10.0.0.2](./releases/Community-Foundation-RemoteCacheKick-10.0.2.zip) (Sitecore 10.0.0.2)
- [Remote Cache Kick for Sitecore-10.0.0.3](./releases/Community-Foundation-RemoteCacheKick-10.0.3.zip) (Sitecore 10.0.0.3)
- [Remote Cache Kick for Sitecore-10.1.0](./releases/Community-Foundation-RemoteCacheKick-10.1.0.zip) (Sitecore 10.1.0)
- [Remote Cache Kick for Sitecore-10.1.1](./releases/Community-Foundation-RemoteCacheKick-10.1.1.zip) (Sitecore 10.1.1)
- [Remote Cache Kick for Sitecore-10.1.2](./releases/Community-Foundation-RemoteCacheKick-10.1.2.zip) (Sitecore 10.1.2)
- [Remote Cache Kick for Sitecore-10.2.0](./releases/Community-Foundation-RemoteCacheKick-10.2.0.zip) (Sitecore 10.2.0)
- [Remote Cache Kick for Sitecore-10.3.0](./releases/Community-Foundation-RemoteCacheKick-10.3.0.zip) (Sitecore 10.3.0)
- [Remote Cache Kick for Sitecore-10.4.0](./releases/Community-Foundation-RemoteCacheKick-10.4.0.zip) (Sitecore 10.4.0)

> ***IMPORTANT NOTE FOR SCALED SETUPS***
For scaled setups, also copy the files in the Sitecore package (config and dlls) to the Sitecore CD servers.

About
--------------
_Originally developed by:_

James Gregory - [LinkedIn](https://www.linkedin.com/in/james-gregory-3037a1a/), GitHub: https://github.com/digitalParkour

_Upgraded + tested to support Sitecore 9.3, Sitecore 10.0.0, Sitecore 10.0.1, Sitecore 10.1.0 , Sitecore 10.1.1, Sitecore 10.1.2, Sitecore 10.2, Sitecore 10.3 & Sitecore 10.4_

Robbert Hock - 15x Sitecore MVP (2010-2024)
Twitter: [@kayeeNL](https://twitter.com/kayeenl), GitHub: [KayeeNL](https://github.com/KayeeNL), LinkedIn: [Robbert Hock](https://www.linkedin.com/in/robberthock/)
