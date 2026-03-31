# Nuvols Agentic Commerce for WooCommerce

> **Early Access** — This plugin is under active development and not yet production-ready. APIs, features, and data formats may change without notice. We welcome testers and feedback via the [contact form on nuvols.app](https://nuvols.app/woocommerce).

Connect your WooCommerce store to [nuvols.app](https://nuvols.app) for AI-powered commerce. Enables your products to be discovered and purchased through AI agents like Google Gemini and ChatGPT via the Universal Commerce Protocol (UCP) and Agentic Commerce Protocol (ACP).

## How It Works

This lightweight plugin connects your WooCommerce store to [nuvols.app](https://nuvols.app), which handles all protocol logic. Your store's product data is synced to nuvols.app, and AI shopping agents communicate with nuvols.app to browse, build carts, and complete purchases on behalf of customers.

- No protocol logic runs on your server
- Automatic compliance with UCP and ACP spec updates
- AI agents never access your store directly

## Requirements

- WordPress 6.0+
- WooCommerce 7.0+
- PHP 7.4+
- SSL/HTTPS enabled

## Installation

1. Download the latest release ZIP from [Releases](../../releases)
2. In your WordPress admin, go to **Plugins > Add New > Upload Plugin**
3. Upload the ZIP file and click **Install Now**
4. Activate the plugin
5. Go to **WooCommerce > Nuvols Agentic Commerce**
6. Click **Connect to nuvols.app**

That's it. Your store is now AI-discoverable.

## Features

**Handled by nuvols.app (SaaS):**
- UCP and ACP protocol endpoints
- AI agent checkout sessions
- Google Pay and payment gateway mapping
- Business profile and discovery responses
- Analytics dashboard
- Spec version compliance

**Handled by the plugin (on your server):**
- One-click connection to nuvols.app
- Product data sync (push on save)
- Per-product AI commerce toggle
- Google Shopping feed rewriting
- Discovery profile at `/.well-known/ucp`

## Documentation

Visit [nuvols.app/woocommerce](https://nuvols.app/woocommerce) for full documentation, FAQs, and support.

## Support

For questions or issues, visit [nuvols.app](https://nuvols.app) and use the contact form, or open an issue in this repository.

## License

This plugin is licensed under the [GNU General Public License v2.0 or later](https://www.gnu.org/licenses/gpl-2.0.html).
