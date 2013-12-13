== How to install

Add "new Tutei\SitemapBundle\TuteiSitemapBundle()" to ezpublish/EzPublishKernel.php in the registerBundles function.

Add to ezpublish/config/routing.yml:

tutei_sitemap:
    resource: "@TuteiSitemapBundle/Resources/config/routing.yml"
    prefix:   /
    
    
== How to configure

You can configure the parameters at:

/src/Tutei/SitemapBundle/Resources/config/services.yml
    
To view your sitemap access: /sitemap.xml


