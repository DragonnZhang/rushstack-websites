---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [PackageJsonLookup](./node-core-library.packagejsonlookup.md) &gt; [instance](./node-core-library.packagejsonlookup.instance.md)

## PackageJsonLookup.instance property

A singleton instance of `PackageJsonLookup` , which is useful for short-lived processes that can reasonably assume that the file system will not be modified after the cache is populated.

<b>Signature:</b>

```typescript
static get instance(): PackageJsonLookup;
```

## Remarks

For long-running processes that need to clear the cache at appropriate times, it is recommended to create your own instance of `PackageJsonLookup` instead of relying on this instance.