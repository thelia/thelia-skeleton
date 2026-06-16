# Thelia skeleton

This package lists the parts that make up a Thelia 3 installation: the core, the Flexy front-office template, the default-twig back-office template, and the email and PDF templates. A project depends on this single package instead of pinning each part by hand.

You do not install this package directly. To create a Thelia project, use the project skeleton:

```bash
composer create-project thelia/thelia-project:dev-twig my-shop
```

See [thelia/thelia-project](https://github.com/thelia/thelia-project) for the installation guide, and [thelia/thelia](https://github.com/thelia/thelia) to work on Thelia itself.
