# my-LanguageTool-docker-compose
LanguageTool Is a Open-Source Best Free Alternative to Grammarly for Multiple Languages.

| Domain | CDN/DDoS Protection | Provider | Country |
| -- | -- | -- | -- |
| [langapi.whateveritworks.org](https://langapi.whateveritworks.org/) | Cloudflare | Hetzner | Germany (Official)
If you use my public api instance, it has a ratelimit/return vistor ips to prevent abuse. All ngrams now supported on my api. :)

## Usage:

1. Buy [Hetzner.com](https://hetzner.com) it's 100% renewal hardware and you get affordable dedicated servers, and you also help save the world.

2. Get [Cloudflare](https://cloudflare.com) it's carbon renewal and you help save the world.

3. ```apt install git```

4. ```git clone https://github.com/WhateverItWorks/my-LanguageTool-docker-compose.git lang```

5. ```nano docker-compose.yml```

6. ```docker-compose up -d```

```http://localhost:8010```

### Self-Host Custom URL Support (Extensions)

- [Firefox](https://addons.mozilla.org/en-US/firefox/addon/languagetool/)
- [Chrome](https://chrome.google.com/webstore/detail/grammar-checker-paraphras/oldceeleldhonbafppcapldpdifcinji?utm_source=lt-homepage)

### Self-Host Custom URL Support (Mobile)
iOS & Android has yet to have custom self-host url support.

### Sources

[Self-host LanguageTool Official Guide](https://dev.languagetool.org/http-server) + [Add Ngrams Support](https://dev.languagetool.org/finding-errors-using-n-gram-data.html)

[Erikv187's LanguageTool Docker Version](https://github.com/Erikvl87/docker-languagetool)

[Silvio's LanguageTool Docker Version](https://github.com/silvio/docker-languagetool)
