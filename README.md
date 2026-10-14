# convobuy-wp
Let customers send their order to you on WhatsApp in one tap, pre-filled with product, variation, quantity and price.

== Description ==

Many customers prefer to chat before they buy, and many shops close their sales on WhatsApp. ConvoBuy adds an "Order via WhatsApp" button to your WooCommerce store that opens a chat with you and a ready-made order message.

**Features**

* **Product page button** – message includes product name, selected variation, quantity, price, total, SKU and link. Updates live as the customer changes options.
* **Cart page button** – sends the whole cart (items, options, quantities, line totals and cart total) in one message.
* **Shop and category buttons** – optional quick-order button under simple products.
* **Floating chat button** – optional, bottom left or right.
* **Editable message templates** with placeholders. Lines with empty values are removed automatically.
* **Shortcodes** for page builders: `[convobuy_button]` and `[convobuy_cart_button]`.
* Choose button colors and shape. Works with any theme.
* Lightweight: no external requests, scripts load only where needed.
* HPOS compatible.

Set up takes about two minutes: install, enter your number, done.

**Disclaimer:** This plugin is not affiliated with, endorsed by or sponsored by WhatsApp, Meta, WooCommerce or Automattic. WhatsApp and WooCommerce are trademarks of their respective owners.

== External services ==

This plugin creates links to WhatsApp's click-to-chat service (https://wa.me). When a visitor clicks a button, their browser opens that link and the pre-filled message text is passed to WhatsApp. No data is sent to WhatsApp or anyone else until the visitor clicks. See WhatsApp's Terms of Service (https://www.whatsapp.com/legal/terms-of-service) and Privacy Policy (https://www.whatsapp.com/legal/privacy-policy).

== Installation ==

1. Upload the plugin to `/wp-content/plugins/` or install it from the Plugins screen.
2. Activate it. WooCommerce must be active.
3. Go to WooCommerce > ConvoBuy.
4. Enter your WhatsApp number in international format (for example 919876543210) and save.

== Frequently Asked Questions ==

= Do I need the WhatsApp Business API? =
No. The plugin uses standard click-to-chat links and works with the regular WhatsApp or WhatsApp Business app.

= Can I change the message? =
Yes. Edit the templates under WooCommerce > ConvoBuy. Available placeholders are listed under each template.

= Does it support variable products? =
Yes. On the product page the message includes the chosen options and the variation price. If the customer has not chosen options yet, they are asked to do so first.

= Does the cart button work with the WooCommerce Cart block? =
The cart button currently works with the classic cart template. Product, shop and floating buttons work everywhere. Cart block support is planned.

== Changelog ==

= 1.0.0 =
* Initial release.
