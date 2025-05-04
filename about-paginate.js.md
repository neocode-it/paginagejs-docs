# About Paginate.js

#### What's the core purpose of this Library? <a href="#why-another-print-solution-for-frappe" id="why-another-print-solution-for-frappe"></a>

The initial reason for this library was, as in many cases, a own need to convert html into a paged preview. In our specific case, we needed a way to create a pixelperfect and reliable print preview with full html/css support. This leads us to the next question:

#### What Paginate.js can do

* Create reliable paged preview of html content
* Ensure that printed copies maintain the exact layout as seen in the preview.
* Full CSS support

#### What Paginate.js won't do

* Limited CSS @media print support -> based on the fact that the preview should be identical to the print.

#### How is Betterprint working under the hood? <a href="#how-is-betterprint-working-under-the-hood" id="how-is-betterprint-working-under-the-hood"></a>

This library operates through the following steps:

1. Create empty page and add page skeleton with all fixed dimensions
2. Iterate over the source-content and copy one element after another into the current-page content. If there's a overflow, a new page will be added.
3. After all content is rendered, the header content is set, depending on the set page content

#### Who's behind Frappe Betterprint? <a href="#whos-behind-frappe-betterprint" id="whos-behind-frappe-betterprint"></a>

Frappe Betterprint has been developed & is maintained by [Neocode.ch](https://neocode.ch), a Company located in Switzerland.

#### Contact <a href="#contact" id="contact"></a>

Have you found any security concerns or urgent need? Feel free to contact us:

info@neocode.ch
