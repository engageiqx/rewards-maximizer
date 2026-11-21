<div align="center">

# 💸 Rewards Maximizer

### Send Claude any product. Get back the cheapest way to buy it.

Claude checks prices, promo codes, cashback sites, discounted gift cards and your own credit cards, then hands you one simple plan to follow at checkout.

<a href="https://github.com/engageiqx/rewards-maximizer/stargazers"><img src="https://img.shields.io/github/stars/engageiqx/rewards-maximizer?style=flat-square&color=2ea44f&label=stars" alt="GitHub stars"></a>
<img src="https://img.shields.io/badge/works_with-Claude.ai_%7C_Claude_Code-orange?style=flat-square" alt="Works with Claude">
<img src="https://img.shields.io/badge/setup-3_questions-blue?style=flat-square" alt="3 question setup">

**[Install](#install) · [How it works](#how-it-works) · [What Claude checks](#what-claude-checks) · [Rules](#rules)**

</div>

---

## How it works

<table>
<tr>
<td align="center" width="33%"><h3>1. Install</h3>Add the skill to Claude<br>in under a minute</td>
<td align="center" width="33%"><h3>2. Answer 3 questions</h3>Your cards, your zip code,<br>cash or travel points</td>
<td align="center" width="33%"><h3>3. Send a product</h3>A name, a link, a screenshot<br>or just a store</td>
</tr>
</table>

### You type

```
How can I get the best deal at Old Navy?
```

### Claude sends back

> **Checkout plan:**
> 1. Click through TopCashback to Old Navy (4% back)
> 2. Add early Black Friday items to your cart (50% off)
> 3. Enter code **EXTRA** at checkout (extra 30% off)
> 4. Buy an Old Navy gift card for the exact total in the Fluz app, paid from your bank (8% back)
> 5. Pay with that gift card
>
> **Total:** about 69% off the regular price.

<sub>Real plan built on November 21, 2026. Codes and rates change, so every plan is built live for that day.</sub>

## What Claude checks

Every time, for every product:

| | Layer | What Claude looks for |
|--:|---|---|
| 🏷️ | **Price** | The exact item at Amazon, Walmart, Target, Best Buy, Costco, the brand's own site and specialty stores |
| 🎟️ | **Promo codes** | Current codes, sign-up discounts, app-only and member pricing |
| 💰 | **Cashback sites** | The real rate for your item across 15+ cashback sites |
| 🎁 | **Gift cards** | Discounted gift cards for that store, in stock today |
| 💳 | **Your cards** | Which of your cards earns the most in real dollars, plus card offers like Amex Offers and Chase Offers |
| 📅 | **Timing** | Upcoming sales, price matching and price-drop refunds |

Claude stacks everything that works together into one plan, and does the math in code so the total is exact.

## Install

### Claude.ai and Claude Desktop

1. Download [`rewards-maximizer.zip`](./rewards-maximizer.zip)
2. In Claude, open **Customize → Skills**
3. Click **+**, then **Create skill**, then **Upload a skill**, and pick the zip

### Claude Code and other agents

```bash
npx skills add engageiqx/rewards-maximizer
```

## Rules

- ✅ **Only your cards.** Never tells you to use a card you don't have.
- ✅ **No credit checks.** Never suggests opening a new card. Free sign-ups only.
- ✅ **No guesses.** If a rate or code can't be confirmed, the plan says so.
- ✅ **Exact item.** Same model, size and color.
- ✅ **US stores, US dollars.** No eBay.

---

<div align="center">

Built by **[engageIQx](https://github.com/engageiqx)**

<sub>Some links in the plans pay a referral bonus.</sub>

</div>
