# Rewards Maximizer

A Claude skill that finds the cheapest way to buy anything. Send Claude a product, link or store name, and get one checkout plan that stacks the best price, promo code, cashback site, discounted gift card and your own credit card rewards.

The first time you use the skill, Claude asks three quick questions: which credit cards you have, your zip code, and whether you cash out your points or use them for travel. Plans only ever use cards you have.

## Install

Claude app (claude.ai): download `rewards-maximizer.zip` from this page, then in Claude open Customize, then Skills, click +, then Create skill, then Upload a skill, and pick the zip.

Claude Code:

```
mkdir -p ~/.claude/skills/rewards-maximizer && curl -o ~/.claude/skills/rewards-maximizer/SKILL.md https://raw.githubusercontent.com/engageiqx/rewards-maximizer/main/rewards-maximizer/SKILL.md
```

## Use

Send Claude something like "best way to buy AirPods Pro 3" or "Vuori".

Some links in the plans pay a referral bonus.
