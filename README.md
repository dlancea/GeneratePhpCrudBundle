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

FYI, I gave up on this project. Trying to use Symfony with PHP templates is just not viable if you want to use additional 3rd party code since libraries use twig almost exclusively and the two don't work together. This library works, but will not be maintained.
