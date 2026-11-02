<p align="center">
  <a href="https://github.com/jonaaix/laravel-archipelago">
    <img src="https://raw.githubusercontent.com/jonaaix/laravel-archipelago/main/laravel-archipelago.svg" alt="Laravel Archipelago Logo" width="200">
  </a>
</p>

<h1 align="center">Laravel Archipelago</h1>

<p align="center">
The whole <a href="https://github.com/jonaaix/laravel-islands">Laravel Islands</a> set in one install: islands, data grid, search, gallery and file manager.
</p>

<p align="center">
  <a href="https://packagist.org/packages/aaix/laravel-archipelago"><img src="https://img.shields.io/packagist/v/aaix/laravel-archipelago.svg?style=flat-square" alt="Latest Version on Packagist"></a>
  <a href="https://packagist.org/packages/aaix/laravel-archipelago"><img src="https://img.shields.io/packagist/dt/aaix/laravel-archipelago.svg?style=flat-square" alt="Total Downloads"></a>
  <a href="https://github.com/jonaaix/laravel-archipelago/blob/main/LICENSE.md"><img src="https://img.shields.io/packagist/l/aaix/laravel-archipelago.svg?style=flat-square" alt="License"></a>
</p>

---

It installs every Laravel Islands package in one step. Each package is required with `^1.0`, so
`composer update` brings each of them up to its latest release without a new version of this
package.

## Installation

```bash
composer require aaix/laravel-archipelago
```

The packages keep their own setup — Vite plugin, Tailwind source, configuration. Follow the README
of each package below.

## Laravel Boost

Laravel Boost only picks up skills from packages your `composer.json` requires directly, so the
skills of the five packages stay out of reach through this one. It ships a skill of its own instead,
`archipelago-development`, which names the package skill to read for a task. Add
`aaix/laravel-archipelago` to the packages in `boost.json` and run `php artisan boost:update`.

## Packages

<table>
  <tr>
    <td width="96" align="center"><a href="https://github.com/jonaaix/laravel-islands"><img src="https://jonaaix.github.io/laravel-islands/logo.svg" alt="Laravel Islands" width="80" height="80"></a></td>
    <td><a href="https://github.com/jonaaix/laravel-islands"><strong>Laravel Islands</strong></a> · <code>aaix/laravel-islands</code><br>Frontend islands for Laravel: server-driven props, real-time model subscriptions, a framework-agnostic core with a Vue adapter. The foundation of every package below.</td>
  </tr>
  <tr>
    <td width="96" align="center"><a href="https://github.com/jonaaix/laravel-islands-datagrid"><img src="https://jonaaix.github.io/laravel-islands-datagrid/logo.svg" alt="Laravel Islands DataGrid" width="80" height="80"></a></td>
    <td><a href="https://github.com/jonaaix/laravel-islands-datagrid"><strong>Laravel Islands DataGrid</strong></a> · <code>aaix/laravel-islands-datagrid</code><br>Server-driven data tables: one composable for state, one shell for the toolbar, header, skeleton, empty state and pagination.</td>
  </tr>
  <tr>
    <td width="96" align="center"><a href="https://github.com/jonaaix/laravel-islands-search"><img src="https://raw.githubusercontent.com/jonaaix/laravel-islands-search/main/laravel-islands-search.svg" alt="Laravel Islands Search" width="80" height="80"></a></td>
    <td><a href="https://github.com/jonaaix/laravel-islands-search"><strong>Laravel Islands Search</strong></a> · <code>aaix/laravel-islands-search</code><br>A keyboard-driven global search: one modal, any number of sources, grouped hits, recent hits and search tips, with an optional Filament integration.</td>
  </tr>
  <tr>
    <td width="96" align="center"><a href="https://github.com/jonaaix/laravel-islands-gallery"><img src="https://raw.githubusercontent.com/jonaaix/laravel-islands-gallery/main/laravel-islands-gallery.svg" alt="Laravel Islands Gallery" width="80" height="80"></a></td>
    <td><a href="https://github.com/jonaaix/laravel-islands-gallery"><strong>Laravel Islands Gallery</strong></a> · <code>aaix/laravel-islands-gallery</code><br>An image gallery: an inline carousel with thumbnails and a full-screen lightbox with zoom, swipe, slideshow and download.</td>
  </tr>
  <tr>
    <td width="96" align="center"><a href="https://github.com/jonaaix/laravel-islands-filemanager"><img src="https://raw.githubusercontent.com/jonaaix/laravel-islands-filemanager/main/laravel-islands-filemanager.svg" alt="Laravel Islands File Manager" width="80" height="80"></a></td>
    <td><a href="https://github.com/jonaaix/laravel-islands-filemanager"><strong>Laravel Islands File Manager</strong></a> · <code>aaix/laravel-islands-filemanager</code><br>A file manager: folders, list and thumbnail views, notes and comments, previews, keyboard shortcuts and full-text search, including Office files and scanned documents.</td>
  </tr>
</table>

## License

[MIT](LICENSE.md)
