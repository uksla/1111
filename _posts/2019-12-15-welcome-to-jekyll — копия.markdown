---
layout: post
title:  "Welcome to Jekyll!"
date:   2020-03-15 21:51:06 +0300
categories: jekyll update
---
## Overview

Lunacy allows you to export your designs into the following formats:

<table>
  <thead>
      <tr>
        <th>Format type</th>
        <th>Supported formats</th>
      </tr>
  </thead>
  <tbody>
      <tr>
        <td>Raster</td>
        <td>PNG, JPEG, BMP, TIFF, ICO, WEBP, GIF</td>
      </tr>
      <tr>
        <td>Vector</td>
        <td>SVG, PDF</td>
      </tr>
  </tbody>
</table>

You can export:

* Individual or multiple objects (both separately or as a single image)
* Content of certain artboards (together with the artboards or without them)
* Content within slices
* Document pages
* Entire projects

You can save export files to:

* Your computer
* Icons8 cloud

Moreover, within one export procedure you can get multiple files of different formats and sizes.

All these is detailed in the sections below. Also, here you will learn how to print your designs and how to get CSS, XAML and SVG code of your designs.

**Tip:** You can also use Sketch Cloud for saving you projects and sharing them with other people. For details about working with Sketch Cloud from Lunacy, read <a href="https://docs.icons8.com/cloud/" target="_blank">here</a>.

## Important notices

* Remember that during export Lunacy ignores all guides, square and layout grids, artboard names, as well as prototyping arrows and canvas color (not to be confused with the artboard color). There is now way to include them into export files.

* Also, note that if there is at least one artboard in your project, during *export of a project* Lunacy ignores all objects that are beyond artboards, as well as main symbols.

* The maximum dimension (height or width) of resulting raster files is limited to 16,000 pixels.

## Export settings (size, suffix/prefix, format)

Almost all export-related controls sit in the Inspector panel. The appearance of the export section depends on what you select on the canvas. For instance, when nothing is selected, you will see **Export project**. When you select an object or several objects, the export section appears as **Make exportable** (scroll to the bottom of the Inspector, if you don't see it on the screen).

![Make exportable](public/export-panel1.png)

Click the plus icon. The **Export assets** panel appears.

![Common export settings](public/export-panel.png)

The basic controls in this panel are the following:

* **Size**. By default, Lunacy offers to export the selection or project in its original size (*1x*). But you can select any of the preset values or enter your own. For example, *8x*, *10x* or *0.3x*.
* **Prefix/Suffix**. This control allows you to define the suffix/prefix (click over the edit field to select, suffix is default) that will be added to the respective file name. Lunacy automatically generates values in the `@<size>` format for all sizes other than *1x*. But you can enter any string of your own in this field (symbols disallowed for file names will be ignored).
