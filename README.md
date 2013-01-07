DlanceaGeneratePhpCrudBundle
=====================

The `DlanceaGeneratePhpCrudBundle` extends the default Symfony2 Doctrine CRUD controllers, created 
by extending the [original Sensio generator bundle](http://symfony.com/doc/current/bundles/SensioGeneratorBundle/index.html).

Since this bundle is an extension of the Sensio one, that bundle is a requirement.

Why is PhpCrudGenerator a re-write of DoctrineCrudGenerator?
=====================

Because DoctrineCrudGenerator uses all private methods instead of protected, so instead of just overwriting
the generate*View methods, I had to copy-paste the whole class (grrr).

Todo
=====================

 + Testing.