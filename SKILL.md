---
name: oficina-fideliza
display_name: Oficina Fideliza
description: "Generates complete automated post-service sequences for Brazilian auto repair shops and dealerships — NPS, future service reminders, no-show recovery, and seasonal alerts. Turns one-time customers int"
version: 1.0.0
author: claudio_felix
license: MIT
tags:
  - "automotive"
  - "retention"
  - "whatsapp"
  - "brazil"
  - "nps"
  - "post-service"
  - "customer-success"
marketplace_url: "https://myclaude.sh/p/oficina-fideliza"
user-invocable: true
---

# Oficina Fideliza

Generates complete automated post-service sequences for Brazilian auto repair shops, autocenters, and dealerships — NPS, future service reminders, no-show recovery, and seasonal campaigns.

## What it does

- Generates personalized D+0 to D+365 sequence based on service type
- Creates 1-click NPS script with routing (promoter → referral request / detractor → human service)
- Produces no-show recovery sequence (3 messages with correct timing)
- Generates contextual seasonal alerts (IPVA, rainy season, school holidays, summer)
- Includes referral request script and reactivation sequence
- Defines success metrics by objective

## How to install

```bash
myclaude install oficina-fideliza
```

## How to use

```
/oficina-fideliza
```

With direct context:

```
/oficina-fideliza type=shop service="oil-change" client="João, Civic 2021" tone=informal
```

## Requirements

- Claude Code (any version)
- To implement: WhatsApp Business API or partner platform (BotConversa, Letalk, Z-API)
- Minimum customer database (name + phone + vehicle + service performed)

## Target market

Brazilian automotive sector — generated messages are in Portuguese (pt-BR) as they are intended for Brazilian end customers.

---

[![MCS-2](https://myclaude.sh/badge/mcs/2.svg)](https://myclaude.sh/quality)
[![Available on MyClaude](https://myclaude.sh/badge/available.svg)](https://myclaude.sh/p/oficina-fideliza)

<sub>Built with MyClaude Studio Engine</sub>

