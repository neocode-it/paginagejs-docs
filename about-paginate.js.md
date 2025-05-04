# About Paginate.js

#### What's the core purpose of this Library? <a href="#why-another-print-solution-for-frappe" id="why-another-print-solution-for-frappe"></a>

The initial reason for this library was, as in many cases, a own need to convert html into a paged preview. In our specific case, we needed a way to create a pixelperfect and reliable print preview with full html/css support. This leads us to the next question:

#### What Paginate.js can do

* Create reliable paged preview of html content
* Print&#x20;

#### What Paginate.js won't do

When we first considered Frappe Framework for our company, Print Formats have been quite limited. wkhtmltopdf isn't maintained anymore and frappe\_pdff as well as Print Designer is still somewhere limited for specific needs. This lead us to the decision to develop a better solution.

Frappe Betterprint is OpenSource and [available on Github - Contributions are Welcome!](https://github.com/neocode-it/frappe_betterprint)

#### How is Betterprint working under the hood? <a href="#how-is-betterprint-working-under-the-hood" id="how-is-betterprint-working-under-the-hood"></a>

Frappe Betterprint is heavily relying on an extended version of [paginate.js](https://github.com/neocode-it/paginatejs), which renders the html content into pages. This library has solely been developed for Frappe Betterprint. Besides this library, Betterprint is relying on [Playwright python](https://github.com/microsoft/playwright-python) to control a headless, chromium based browser and create PDF files.

#### Who's behind Frappe Betterprint? <a href="#whos-behind-frappe-betterprint" id="whos-behind-frappe-betterprint"></a>

Frappe Betterprint has been developed & is maintained by [Neocode.ch](https://neocode.ch), a Company located in Switzerland.

#### Contact <a href="#contact" id="contact"></a>

Have you found any security concerns or urgent need? Feel free to contact us:

info@neocode.ch
