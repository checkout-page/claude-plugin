# Checkout Page plugin for Claude Code

Connects Claude Code to the [Checkout Page](https://checkoutpage.com) MCP server so you can create and manage checkout pages, event ticketing, forms, customers, payments and subscriptions in plain language.

## Install

From the Checkout Page marketplace:

```
/plugin marketplace add checkout-page/claude-plugin
/plugin install checkout-page@checkout-page
```

Then run `/mcp`, pick **checkout-page** and sign in with your Checkout Page account. The plugin talks to `https://mcp.checkoutpage.com` and uses OAuth, so there are no API keys to paste.

## What you can do

- List, create and update checkout pages, and update their products and prices
- Get ready-to-paste code to add a checkout page, form or event to your website: embed, popup or link
- Create and update events, add and archive ticket types, and manage tickets and bookings
- Look up and update customers
- Look up payments, invoices and subscriptions, regenerate an invoice, and prepare a subscription cancellation
- Build forms and add, update or delete custom fields
- Create and update coupons, and create tax rates
- Create, update and delete webhooks

The full tool list is at [checkoutpage.com/docs/build/mcp](https://checkoutpage.com/docs/build/mcp).

## Try it locally

```
git clone https://github.com/checkout-page/claude-plugin.git
claude --plugin-dir ./claude-plugin
```

## Support

Email [support@checkoutpage.com](mailto:support@checkoutpage.com) or use the chat inside the dashboard.
