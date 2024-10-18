# Spryker Feature: Content Item

The Content Items feature implemented in Spryker shop application allows you to focus on creating the content and then selecting where it should be inserted and how it will look.
Content Item is a new abstraction layer for any content, such as image, text, product list, video, etc. you can create, edit, and add to one or several pages or blocks. Content items use a widget that decides where to insert the content and couples the content item with a template that specifies how it is displayed on the page. For example, as a content manager, you can add a banner which is a content item type, along with its template to any placeholder in blocks and pages of your online shop application.

## Installation

```
composer require spryker-feature/content-item
```

## Recommended feature dependencies
- [spryker-feature/spryker-core](https://github.com/spryker-feature/spryker-core)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [ContentBannersRestApi ^2.2.0](https://github.com/spryker/content-banners-rest-api) (Legacy Glue)
- [ContentGuiExtension ^1.1.0](https://github.com/spryker/content-gui-extension) (Extension)
- [ContentProductAbstractListsRestApi ^1.2.0](https://github.com/spryker/content-product-abstract-lists-rest-api) (Legacy Glue)
- [ContentStorageExtension ^1.1.0](https://github.com/spryker/content-storage-extension) (Extension)
