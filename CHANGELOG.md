# Changelog

Each version's notes are also on its [release](https://github.com/photopress-dev/photopress-lightroom-releases/releases).

## 1.0.0

The first release, with the features of PhotoPress for Capture One 1.3.3.

- Publish from **File › Export**, or as a Lightroom **Publish Service** that updates edited photos with one click.
- Photos already on the site are **replaced in place**, matched by file name, including names WordPress changed on upload and names with accents in either Unicode form. **Duplicate existing images** uploads them as new copies instead.
- **Add images to a page's gallery**, with an optional gallery anchor for pages with several galleries, and **Remove existing images from the gallery** to replace a gallery's images with the published set.
- **Attach new images to a page**, chosen from the site's recent posts and pages.
- Publishing is refused, before anything is uploaded, if a photo is larger than the site's size limit.
- Several websites, set up in **File › Plug-in Manager › PhotoPress**. **Test Connection** checks the site, the login, PhotoPress, the account's permissions, and the WordPress features publishing needs.
- New export settings start as JPEG, quality 85, 2560 px on the long edge, with location metadata removed.
