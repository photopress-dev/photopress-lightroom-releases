# PhotoPress for Lightroom Classic

Publish photos from Lightroom Classic straight to your WordPress website, and update them later without breaking the pages they appear on.

PhotoPress for Lightroom Classic is a Lightroom export and publish service. It works with the [PhotoPress](https://photopress.io) WordPress plugin.

![PhotoPress in Lightroom's Export dialog](https://raw.githubusercontent.com/wiki/photopress-dev/photopress-lightroom-releases/images/hero.png)

This repository is where you **download releases**, **read the documentation** and **report problems**. The plugin's source code is not published here.

**[Download the latest release](https://github.com/photopress-dev/photopress-lightroom-releases/releases/latest)** · **[Documentation](https://github.com/photopress-dev/photopress-lightroom-releases/wiki)** · **[Report a problem](https://github.com/photopress-dev/photopress-lightroom-releases/issues/new/choose)**

## Features

### Publish from Lightroom

Select photos, choose **File › Export**, pick **PhotoPress (WordPress)** and your website, and export. Lightroom renders the photos with your settings, and the plugin uploads them to the WordPress Media Library. Title, caption, alt text and keywords come from your photos' metadata. [More](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Publishing)

### Keep a website in step with a Publish Service

Set PhotoPress up as a Lightroom **Publish Service**. Lightroom tracks which photos are on your site, collects the ones you've edited since, and updates them all with one click on **Publish**. [More](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Publish-services)

### Update photos in place

Edit a photo and publish it again: the plugin finds it on your site by its file name and **replaces it in place**. Its URL, its attachment page, and every post and gallery that shows it stay as they are, and now show the new version. Optionally, its keywords, alt text and captions are updated wherever it's used. [More](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Updating-images)

### Add photos to galleries

Add the photos you publish to the gallery on a page, or **replace a gallery's images** with a new set, in the order you publish them. Works with pages that have several galleries, and with galleries that show a page's attached images. [More](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Galleries)

![Adding photos to a page's gallery](https://raw.githubusercontent.com/wiki/photopress-dev/photopress-lightroom-releases/images/publish-section-gallery.png)

### Attach new photos to a page

Attach newly uploaded photos to a post or page, chosen from the site's recent posts and pages, drafts included. [More](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Attaching-images-to-a-page)

### Keep to your site's limits

The plugin checks your site's image size limit before uploading, so WordPress never shows a scaled-down copy of what you exported. [More](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Image-size-limit)

### Several websites, one plugin

Add every site you publish to, each with its own login, and choose one each time you export, or give each its own Publish Service. **Test Connection** checks the site, your login and PhotoPress, and says exactly what to fix. Passwords are kept in Lightroom's encrypted password store. [More](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Setting-up-a-website)

## Requirements

- **Lightroom Classic** (tested on macOS)
- **WordPress 6.6** or later, with the **PhotoPress** plugin installed and active
- A WordPress account that can upload media (Author role or higher), and an **application password** for it

## Install

1. Download the latest `PhotoPress-Lightroom-x.y.z.zip` from [Releases](https://github.com/photopress-dev/photopress-lightroom-releases/releases/latest).
2. Unzip it, and move **PhotoPress.lrplugin** to Lightroom's Modules folder: on a Mac, `~/Library/Application Support/Adobe/Lightroom/Modules`.
3. Restart Lightroom Classic.

Or keep **PhotoPress.lrplugin** anywhere you like and add it in **File › Plug-in Manager** with **Add**.

Then [set up your website](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Setting-up-a-website).

## Get help

- **Documentation:** the [wiki](https://github.com/photopress-dev/photopress-lightroom-releases/wiki), including [Troubleshooting](https://github.com/photopress-dev/photopress-lightroom-releases/wiki/Troubleshooting).
- **Found a problem?** [Open an issue](https://github.com/photopress-dev/photopress-lightroom-releases/issues/new/choose). The form asks for the details that help most.
- **What's changed:** the [changelog](CHANGELOG.md) and [Releases](https://github.com/photopress-dev/photopress-lightroom-releases/releases).
- **Security issues:** please don't post them publicly. See [SECURITY.md](SECURITY.md).
- **Using Capture One?** See [PhotoPress for Capture One](https://github.com/photopress-dev/photopress-capture-one-releases).
