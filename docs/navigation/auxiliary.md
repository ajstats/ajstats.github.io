---
#title: Auxiliary Links
title: 주가예측모델(시계열)
#parent: Navigation
parent: 지도학습
nav_order: 2
---

# 주가예측모델

주식 종가 고가 시가 를 가져와서, 크롤링해 가져와서 n all pages. You do this by including the `aux_links` [configuration option]({% link docs/configuration.md %}#aux-links) in your site's `_config.yml` file.

## Example Auxiliary Link
{: .text-delta }

This website has an auxiliary link: "Just the Docs on GitHub". It is rendered with the following code:

```yaml
aux_links:
  Just the Docs on GitHub:
    - https://github.com/just-the-docs/just-the-docs
```
