If you are using an apex domain as your custom domain, we recommend also setting up a `www` subdomain. If you configure the correct records for each domain type through your DNS provider, {{ site.data.variables.product.prodname_pages }} will automatically create redirects between the domains. For example, if you configure `www.example.com` as your custom domain for your site, and you have `ALIAS` and `CNAME` records set up for the apex and `www` domains, then `example.com` will redirect to `www.example.com`. For more information, see "[Managing a custom domain for your {{ site.data.variables.product.prodname_pages }} site](/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site/#configuring-a-subdomain)."