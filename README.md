# markgraziano.com

Portfolio site for Mark Graziano's development work.

## Deploy

Push to `main` and GitHub Pages will auto-deploy.

**Live:** https://graz-claw.github.io/markgraziano.com/

### Custom Domain

To use `markgraziano.com`:

1. **In GitHub → Settings → Pages**: Set custom domain to `markgraziano.com`
2. **In your domain registrar**: Add these DNS records:

   | Type    | Name  | Value                    |
   | ------- | ----- | -------- |
   | CNAME   | `www` | `graz-claw.github.io` |
   | A       | `@`   | `185.199.108.153` |
   | A       | `@`   | `185.199.109.153` |
   | A       | `@`   | `185.199.110.153` |
   | A       | `@`   | `185.199.111.153` |

3. **Enable HTTPS** in GitHub Pages settings after DNS propagates

## Stack

- Plain HTML + CSS (no framework)
- Google Fonts: Inter + JetBrains Mono
- Responsive, minimal, card-based layout
- Subtle animations, accent colors per project

## Projects

| Project | Link | Tag |
|---------|------|-----|
| Bivvi | [bivvi.app](https://bivvi.app) | Video Communication |
| Summa | [summahq.com](https://summahq.com) | Sales Enablement |
| TXR Studio | [txrstudio.com](https://txrstudio.com) | Web Application |
| Everyday Chaplet | [everydaychaplet.com](https://everydaychaplet.com) | Faith & Community |
| The GRC Podcast | [Spotify](https://open.spotify.com/show/4vD7XV8vP323P7raPjtAq0) | Podcast |

## Logos

The Bivvi logo uses a CSS gradient fallback. To use the real logo:

1. Put `bivvi-logo.png` in `assets/`
2. Swap the `<span class="logo-bivvi">` back to `<img>` in `index.html`

## GRC Podcast

Condensed about description: *GRC doesn't have to be boring. Join Mark as he partners with security champions to challenge the stereotype and outline strategies you can implement today.*
