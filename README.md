<div align="center">

# nG-SetEnvIf
![](https://img.shields.io/badge/nginx-1.27.2-009639?logo=nginx&logoColor=white)
![](https://img.shields.io/badge/Apache-2.4.62-D22128?logo=Apache&logoColor=white)
[![ReDoS detector](https://github.com/t18d/nG-SetEnvIf/actions/workflows/redos-detector.yml/badge.svg?branch=staging)](https://github.com/t18d/nG-SetEnvIf/actions/workflows/redos-detector.yml)
&nbsp;  
[![](https://img.shields.io/badge/Perishable%20Press-8G%20v1.3-dd6d0b.svg?logo=data:image/png;base64,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)](https://perishablepress.com/8g-firewall/)
<p align="right"><em>a project of <a href="https://t18d.github.io/">Open Source by Tonkünstler-on-the-Bund</a></em></p>

&nbsp;  
&nbsp;  
&nbsp;  
nG-SetEnvIf is an [nG Firewall](https://perishablepress.com/ng-firewall/) fork that focusses on performance.

It can be used with both nginx and Apache httpd.

[Installation](#installation) •
[Configuration](#configuration) •
[Recipes](#recipes)

</div>

## Installation

### nginx

In `http` context, add

```Nginx
include /path/to/8g-firewall.conf;
```

In the relevant `server` context, add
```Nginx
include /path/to/8g.conf;
```

### Apache

In the relevant `<Directory>` section, add
```ApacheConf
Include /path/to/8G-SetEnvIf
```

## Configuration

### nginx

To enable logging, add `$ng_reason` to the relevant `log_format` directive.

For best performance, compile nginx `--with-pcre-jit` and add to the main context

```Nginx
pcre_jit on;
```
and place the `include` directive before any `if`, `rewrite` or `set` within the same context.

### Apache

The eponymous module, mod_setenvif, is required, as is mod_authz_core. This is [more efficient](https://httpd.apache.org/docs/trunk/rewrite/avoid.html) than using mod_rewrite.

For best performance, `httpd.conf` [should be used](https://httpd.apache.org/docs/trunk/howto/htaccess.html#when) in preference to `.htaccess`.

> [!WARNING]
> Test with [Starr's logging suite](https://perishablepress.com/ng-firewall-logging/) and mod_rewrite before deploying in production.

## Recipes

If even nG-SetEnvIf fails to satisfy your passion for performance, read on.

- [Post-quantum KEM](https://github.com/t18d/nG-SetEnvIf/wiki/Recipes#post-quantum-kem)
- [URL normalisation](https://github.com/t18d/nG-SetEnvIf/wiki/Recipes#url-normalisation)
- [Block AI crawlers](https://github.com/t18d/nG-SetEnvIf/wiki/Recipes#ai-crawlers)
- [Block spam emails](https://github.com/t18d/nG-SetEnvIf/wiki/Recipes#spam-emails)
- [Replace mod_rewrite](https://github.com/t18d/nG-SetEnvIf/wiki/Recipes#disable-mod_rewrite-altogether) (WP)
- [Rate-limiting](https://github.com/t18d/nG-SetEnvIf/wiki/Recipes#rate-limit-404s) (WP)
- [Integration with Cloudflare](https://github.com/t18d/nG-SetEnvIf/wiki/Recipes#cloudflare)

&nbsp;  
<hr width="50%">

**Our Sponsor:**

<a href="https://tuta.com"><img src="https://github.com/t18d/nG-SetEnvIf/assets/130416721/8d560367-f84b-478b-a9c9-ef1c1dc6331c" width="200"></a>

