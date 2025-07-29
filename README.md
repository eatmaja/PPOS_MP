## 👋 Introduction

Personal Point of Sale (sorce code OSPOS) is a web-based point of sale system. The application is written in PHP, uses MySQL (or MariaDB) as the data storage back-end, and has a simple but intuitive user interface.

The latest `3.4.1` version is a complete overhaul of the original software. It uses CodeIgniter 4 as a framework and is based on Bootstrap 3 using Bootswatch themes. Along with improved functionality and security.

The features include:

- Stock management (items and kits with an extensible list of attributes)
- VAT, GST, customer, and multi tiers taxation
- Sale register with transactions logging
- Quotation and invoicing
- Expenses logging
- Cash up function
- Printing and emailing of receipts, invoices and quotations
- Barcode generation and printing
- Database of customers and suppliers
- Multiuser with permission control
- Reporting on sales, orders, expenses, inventory status and more
- Receivings
- Gift cards
- Rewards
- POS Retail Only
- Multilanguage
- Selectable Bootstrap based UI theme with Bootswatch
- MailChimp integration
- Optional Google reCAPTCHA to protect the login page from brute force attacks
- GDPR ready

## 💾 Installation

Please **refrain from creating issues** about installation problems before having read the FAQ and going through existing GitHub issues. We have a build pipeline that checks the sanity of our latest repository commit, and in case the application itself is broken then our build will be as well.

This application can be set up in _many_ different ways and we only support the ones described in [the INSTALL.md file](INSTALL.md).

## ✨ Contributing

Everyone is more than welcome to help us improve this project. If you think you've got something to help us go forward, feel free to open a [pull request]() or join the conversation on [Element](https://app.gitter.im/#/room/#opensourcepos_Lobby:gitter.im).

Want to help translate Open Source Point of Sale in your language? You can find [our Weblate here](https://translate.opensourcepos.org), sign up, and start translating. You can subscribe to different languages to receive a notification once a new string is added or needs updating. Have a look at our [guidelines](https://github.com/opensourcepos/opensourcepos/wiki/Adding-translations) below to help you get started.

Only with the help of the community, we can keep language translations up to date. Thanks!

## 📖 FAQ

- PHP `≥ 8.1` is required to run this app.
