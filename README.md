[![Build Status](https://travis-ci.org/o10n-x/wordpress-cloudfront-page-cache.svg?branch=master)](https://travis-ci.org/o10n-x/wordpress-cloudfront-page-cache) ![Version](https://img.shields.io/github/release/o10n-x/wordpress-cloudfront-page-cache.svg)

<p align="right"><img src="https://github.com/o10n-x/wordpress-cloudfront-page-cache/blob/master/docs/images/amazon-cloudfront.png" height="125"> <img src="https://github.com/o10n-x/wordpress-cloudfront-page-cache/blob/master/docs/images/aws-cloudfront-100.png"></p> 

## CloudFront Page Cache

This plugin provides a low cost and high performance international page cache solution based on [Amazon AWS CloudFront CDN](https://aws.amazon.com/cloudfront/).

* [Documentation](https://github.com/o10n-x/wordpress-cloudfront-page-cache/tree/master/docs)
* [Description](https://github.com/o10n-x/wordpress-cloudfront-page-cache#description)
* [Version history (Changelog)](https://github.com/o10n-x/wordpress-cloudfront-page-cache/releases)
## Installation

![Github Updater](https://github.com/afragen/github-updater/raw/develop/assets/GitHub_Updater_logo_small.png)

This plugin can be installed and updated using [Github Updater](https://github.com/afragen/github-updater) ([installation instructions](https://github.com/afragen/github-updater/wiki/Installation))

<details/>
  <summary>Installation instructions</summary>

### Step 1: Install Github Updater and first optimization plugin

Installing and updating the plugins is possible using Github Updater. It is easy to install one of the plugins. You simply need to download the Github Updater plugin ([zip file](https://github.com/afragen/github-updater/archive/develop.zip)), install it from the WordPress plugin admin panel and copy the Github URL of the plugin into the Github Updater installer.

![image](https://user-images.githubusercontent.com/8843669/39889846-46158cc2-5499-11e8-824d-720020f758db.png)

### Step 2: Install other optimization plugins with a single click

A recent update of all plugins contains a easy single click install button.

![image](https://user-images.githubusercontent.com/8843669/39661507-cc1eac5e-5052-11e8-8fba-33c0cc959b07.png)
</details>

## WordPress WPO Collection

This plugin is part of a Website Performance Optimization collection that include [CSS](https://github.com/o10n-x/wordpress-css-optimization), [Javascript](https://github.com/o10n-x/wordpress-javascript-optimization), [HTML](https://github.com/o10n-x/wordpress-html-optimization), [Web Font](https://github.com/o10n-x/wordpress-font-optimization), [HTTP/2](https://github.com/o10n-x/wordpress-http2-optimization), [Progressive Web App (Service Worker)](https://github.com/o10n-x/wordpress-pwa-optimization) and [Security Header](https://github.com/o10n-x/wordpress-security-header-optimization) optimization. 

The WPO optimization plugins provide in all essential tools that enable to achieve perfect [Google Lighthouse Test](https://developers.google.com/web/tools/lighthouse/) scores and to validate a website as [Google PWA](https://developers.google.com/web/progressive-web-apps/), an important ranking factor for Google's [Speed Update](https://searchengineland.com/google-speed-update-page-speed-will-become-ranking-factor-mobile-search-289904) (July 2018).

![Google Lighthouse Perfect Performance Scores](https://github.com/o10n-x/wordpress-css-optimization/blob/master/docs/images/google-lighthouse-pwa-validation.jpg)

The WPO optimization plugins are designed to work together with single plugin performance. The plugins provide the latest optimization technologies and many unique innovations.

### JSON configuration

100% of the WPO plugin settings are controlled by JSON. This means that you could use the plugins without ever using the WordPress admin forms.

The JSON is verified using JSON schema's. More info about [JSON schemas](https://github.com/o10n-x/wordpress-o10n-core/tree/master/schemas).

### Local editing of optimization settings

A recently added [Stealth Optimization Config Proxy](https://github.com/o10n-x/wordpress-http2-optimization/releases/tag/0.0.55) concept makes it possible to edit the plugin settings using physical `.json` files from a local editor (with auto upload) making it efficient for fine tuning optimization settings. An update would cost a second compared to using + saving a WordPress admin panel.

https://github.com/o10n-x/wordpress-http2-optimization/releases/tag/0.0.55

## Google PageSpeed vs Google Lighthouse Scores

While a Google PageSpeed 100 score is still of value, websites with a high Google PageSpeed score may score very bad in Google's new [Lighthouse performance test](https://developers.google.com/web/tools/lighthouse/). 

The following scores are for the same site. It shows that a perfect Google PageSpeed score does not correlate to a high Google Lighthouse performance score.

![Perfect Google PageSpeed 100 Score](https://github.com/o10n-x/wordpress-css-optimization/blob/master/docs/images/google-pagespeed-100.png) ![Google Lighthouse Critical Performance Score](https://github.com/o10n-x/wordpress-css-optimization/blob/master/docs/images/lighthouse-performance-15.png)

### Google PageSpeed score is outdated

For the open web to have a chance of survival in a mobile era it needs to compete with and win from native mobile apps. Google is dependent on the open web for it's advertising revenue. Google therefor seeks a way to secure the open web and the main objective is to rapidly enhance the quality of the open web to meet the standards of native mobile apps.

For SEO it is therefor simple: websites will need to meet the standards set by the [Google Lighthouse Test](https://developers.google.com/web/tools/lighthouse/) (or Google's future new tests). A website with perfect scores will be preferred in search over low performance websites. The officially announced [Google Speed Update](https://searchengineland.com/google-speed-update-page-speed-will-become-ranking-factor-mobile-search-289904) (July 2018) shows that Google is going as far as it can to drive people to enhance the quality to ultra high levels, to meet the quality of, and hopefully beat native mobile apps.

A perfect Google Lighthouse Score includes validation of a website as a [Progressive Web App (PWA)](https://developers.google.com/web/progressive-web-apps/).

Google offers another new website performance test that is much tougher than the Google PageSpeed score. It is based on a AI neural network and it can be accessed on https://testmysite.thinkwithgoogle.com

## Description

An advantage of Amazon AWS CloudFront as a page cache is that they provide the lowest costs. For an average business website, the total costs will be literally less than 1 dollar per month. Amazon provides free SSL certificates and there are no hidden costs.

An other advantage is that CloudFront supports root domains when using [Amazon AWS Route53 DNS service](https://aws.amazon.com/route53/), making it possible to use CloudFront's CDN for https://yourdomain.com/

Amazon provides dedicated IP's for geographic regions. This means that a website will physically load from a location near the visitor. For a visitor from Sweden the website may be physically loaded from a server and IP in Stockholm.

![CloudFront performance PageSpeed.pro](https://github.com/o10n-x/wordpress-cloudfront-page-cache/blob/master/docs/images/pagespeed-aws-cloudfront.png)

Amazon AWS CloudFront is among the [fastest](https://encrypted.google.com/search?q=cloudfront+vs) CDN providers available with the greatest global network. This makes it a perfect option for any website that wants to reach an international audience or that simply wants a fast and secure page cache for a low cost VPS.

![CloudFront network 2017](https://github.com/o10n-x/wordpress-cloudfront-page-cache/blob/master/docs/images/aws-cloudfront-network-2017.png)

We are interested to learn about your experiences and feedback when using this plugin. Please submit your feedback on the [Github community forum](https://github.com/o10n-x/wordpress-cloudfront-page-cache/issues).