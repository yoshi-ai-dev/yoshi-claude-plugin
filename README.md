# Yoshi for Claude

Yoshi is a personal finance app with cash, investing, and money movement in one place. This plugin lets you use your Yoshi account from Claude: ask about your accounts, spending, and investments, and prepare transfers, trades, checks, and automations in conversation.

## What you need

A Yoshi account. Sign up at [yoshi.ai](https://yoshi.ai/).

## What is in the plugin

- **The Yoshi connector.** A remote MCP server at `https://agents.yoshi.ai/mcp`. You sign in with your Yoshi account and choose what Claude can access. The plugin stores no credentials.
- **The Yoshi skill.** Instructions that tell Claude how to use the Yoshi tools and how to present the results: exact amounts, what the data covers, and the real state of any action.

## Setting it up

1. Add the plugin in Claude.
2. Connect the Yoshi connector that comes with it and sign in to Yoshi when asked. Adding the plugin does not connect your account for you.
3. Ask a question, such as "Show me my accounts and balances" or "Where did my money go last month?"

## How actions work

Claude never moves your money. When you ask for a transfer, a trade, a mailed check, or an automation, Yoshi prepares a request and gives you a link. Nothing happens until you open the Yoshi app, review the details, and approve with your passkey. You can ask Claude whether a request was approved and whether it went through.

Personal calls on a security, such as whether to buy or sell, come from Yoshi and are relayed as written. Claude does not add its own.

## Privacy and support

- Privacy policy: https://yoshi.ai/privacypolicy/
- Terms of service: https://yoshi.ai/termsofservice/
- Support: https://yoshi.ai/support/
- Connector documentation: https://docs.yoshi.ai/guides/mcp
