DlanceaGeneratePhpCrudBundle
=====================

The `DlanceaGeneratePhpCrudBundle` extends the default Symfony2 Doctrine CRUD controllers, created 
by extending the [original Sensio generator bundle](http://symfony.com/doc/current/bundles/SensioGeneratorBundle/index.html) to create PHP view files instead of twig files. Since this bundle is an extension of the Sensio one, that bundle is a requirement.

To use the new command, run the following on the command line:

```php app/console dlancea:generate:phpcrud```

The command uses the same parameters as doctrine:generate:crud.

### Todo

 + Testing
 + Better code re-use(?)
