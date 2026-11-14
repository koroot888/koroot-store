# KOROOT website starter

## Important
This folder is a website starter. The storefront preview works locally with sample products. It is **not yet a live store**, and the admin dashboard/database are not connected.

## Open locally
Keep all files together in one folder. The stylesheet must be named exactly `styles.css` because `index.html` links to `styles.css`. Open `index.html` in a browser. For best results, publish the folder to a static host rather than opening it as a local `content://` file.

## Add your logo banner
The top currently has a text banner saying KOROOT. Once you provide your logo image, place it in this folder and update the `.logo-banner` section in `index.html` to use it as a background or image.

## Before launch
- Connect a real database and secure authentication for owner/admin access.
- Configure stock variants and order storage.
- Test checkout and WhatsApp order details.
- Add real product photos, sizes, prices, shipping fees, and policies.
- Do not put private service-role keys in browser files.
- Payment choices currently send an order message to WhatsApp; InstaPay and Telda are manually confirmed, not integrated payment gateways.
