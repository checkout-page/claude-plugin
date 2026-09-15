# Checkout Page plugin for Claude Code

Connects Claude Code to the [Checkout Page](https://checkoutpage.com) MCP server so you can create and manage checkout pages, event ticketing, forms, customers, payments and subscriptions in plain language.

## Install

```
/plugin marketplace add anthropics/claude-plugins-community
/plugin install checkout-page@claude-community
```

Then run `/mcp`, pick **checkout-page** and sign in with your Checkout Page account. The plugin talks to `https://mcp.checkoutpage.com` and uses OAuth, so there are no API keys to paste.

## What you can do

- List, create and update checkout pages, products and prices
- Create events and manage tickets and bookings
- Look up customers, payments, invoices and subscriptions
- Build forms and custom fields
- Create coupons, tax rates and webhooks

The full tool list is at [checkoutpage.com/docs/build/mcp](https://checkoutpage.com/docs/build/mcp).

## Try it locally

```
git clone https://github.com/checkout-page/claude-plugin.git
claude --plugin-dir ./claude-plugin
```

## Support

Email [support@checkoutpage.com](mailto:support@checkoutpage.com) or use the chat inside the dashboard.
