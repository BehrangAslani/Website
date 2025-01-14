---
title: Folders
---

<script>
  import { InfoBar } from "fluent-svelte";
</script>

## Sync layout and sorting preferences across directories

Located on the folders settings page, enabling this option will sync the layout and other folder settings across all directories.  For example, changing the layout in one folder will automatically change the layout for all other folders.

## Details View columns

Support for additional columns is being planned but in the meantime you can toggle the defaults for the following columns:
- Tags
- Size
- Type
- Date modified
- Date created

To be able to override these options in an individual folder, make sure the option to sync preferences is toggled off.

## Sorting and grouping

### Sort by

Adjusts how items are sorted
- Name
- Date modified
- Date created
- Size
- Type
- Tag

### Sort in descending order

Sorts items in descending order.

### Sort priority

- Sort folders before files
- Sort files before folders
- Sort files and folders together

### Group by

Adjusts how items are grouped
- None
- Name
- Date modified
- Date created
- Size
- Type
- Tag

### Group in descending order

Groups items in descending order.

### Group by date unit

Adjusts the date unit for group by.

## Layout mode

### Details View

Arranges items using a Data Grid with resizable columns. Support for rearranging columns isn't supported yet.

### List View

Displays items in a single column with only the icon and file name.

### Tiles View

Displays larger icons and additional information about the items.

### Grid View

Grid View allows you to view larger icons.

### Columns View

Displays files and folders in a hierarchical structure, with each level shown in a separate column.

### Adaptive

Adaptive automatically chooses the layout based on each folders contents.

## Hidden items

### Show hidden files and folders

This is off by default, enabling it will display hidden files and folders.

### Show dot files

This is on by default and displays files starting with a dot `.`.

### Show protected system files

This is off by default, enabling it will display protected system files.

### Show alternate data streams

This is off by default, enabling it will display alternate data streams.

## Show file extensions

This is on by default and will display file extensions in the file list.

## Show thumbnails

This is on by default and displays file thumbnails. Turning it off will display file icons instead of thumbnails (this can help improve performance).

## Show checkboxes when selecting items

This is on by default and displays a checkbox when an item is selected.

