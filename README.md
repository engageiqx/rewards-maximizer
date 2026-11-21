<div align="center">

# 💸 Rewards Maximizer

### Never pay full price again.

**Send Claude a product. Get back the single cheapest way to buy it, step by step.**

<a href="https://github.com/engageiqx/rewards-maximizer/stargazers"><img src="https://img.shields.io/github/stars/engageiqx/rewards-maximizer?style=flat-square&color=2ea44f&label=stars" alt="GitHub stars"></a>
<img src="https://img.shields.io/badge/works_with-Claude.ai_%7C_Claude_Code-orange?style=flat-square" alt="Works with Claude">
<img src="https://img.shields.io/badge/setup-3_questions-blue?style=flat-square" alt="3 question setup">

**[Install](#install) · [What it stacks](#what-it-stacks) · [Example](#example) · [Rules it never breaks](#rules-it-never-breaks)**

</div>

---

<table>
<tr>
<th width="50%">😐 How most people buy</th>
<th width="50%">💸 With Rewards Maximizer</th>
</tr>
<tr>
<td valign="top">

> Google the product. Click the first store. Try a coupon that doesn't work. Pay with whatever card is in your wallet.

</td>
<td valign="top">

> 1. Enter code **SAVE25** (25% off)
> 2. Pay the first $125 with your Amex (Amex Offer, $20 back)
> 3. Pay the rest with a Fluz Fanatics gift card (10%)
>
> **Total: about 40% back.**

</td>
</tr>
</table>

**Same item. Same store. One plan that stacks every discount that legally stacks.**

## What it stacks

Most deal tools check one thing. Rewards Maximizer checks six, every time, then combines them into one checkout plan:

| # | Layer | What it finds |
|--:|---|---|
| 1 | 🏷️ **Best price** | The exact item across Amazon, Walmart, Target, Best Buy, Costco, the brand's own site and specialty stores |
| 2 | 🎟️ **Promo codes** | Current codes, sign-up discounts, app-only and member pricing |
| 3 | 💰 **Cashback site** | The highest real rate for your exact item across 15+ cashback sites, not the "up to" headline |
| 4 | 🎁 **Discounted gift cards** | Fluz, CardCash, Raise and more, only stores in stock today |
| 5 | 💳 **Your best card** | Which of *your* cards earns the most, in real dollars, plus card-linked offers like Amex Offers and Chase Offers |
| 6 | 📅 **Timing** | Whether a sale is coming, price matching, and price-drop refund deadlines |

Then it runs the math in code, so the total is exact every time.

## Install

### Claude.ai and Claude Desktop

1. Download [`rewards-maximizer.zip`](./rewards-maximizer.zip)
2. In Claude, open **Customize → Skills**
3. Click **+**, then **Create skill**, then **Upload a skill**, and pick the zip

### Claude Code and other agents

```bash
npx skills add engageiqx/rewards-maximizer
```

Or copy the skill straight into your skills folder:

```bash
mkdir -p ~/.claude/skills/rewards-maximizer && curl -o ~/.claude/skills/rewards-maximizer/SKILL.md https://raw.githubusercontent.com/engageiqx/rewards-maximizer/main/rewards-maximizer/SKILL.md
```

## Setup: 3 questions, once

The first time you use it, Claude asks:

1. **Which credit cards do you have?**
2. **What's your zip code?** (for sales tax)
3. **Do you cash out your points, or use them for travel?**

That's it. Every plan after that uses only your cards.

## Example

Just send a product, a link, a screenshot, or a store name:

```
best way to buy AirPods Pro 3
```

```
Vuori
```

```
https://www.bestbuy.com/site/...
```

You get one checkout plan back. Follow the steps in order at checkout.

## Rules it never breaks

- ✅ **Only your cards.** Never tells you to pay with a card you don't have.
- ✅ **No credit checks.** Never suggests opening a new card or financing. Free sign-ups only.
- ✅ **Proof, not guesses.** If a rate or code can't be confirmed, the plan says so.
- ✅ **Live stock only.** A gift card or cashback site only makes the plan if the store is available there today.
- ✅ **Exact item.** Same model, size and color. A cheaper wrong version is not a deal.
- ✅ **US stores, US dollars.** No eBay.

---

<div align="center">

Built by **[engageIQx](https://github.com/engageiqx)**

<sub>Some links in the plans pay a referral bonus.</sub>

</div>
