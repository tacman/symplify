<div align="center">
    <br>
    <img src="/docs/zen.jpg?v=3">
    <br>
    <br>
    <br>
    <h1>Symplify - Making Everyday PHP Development Simple</h1>
    <br>
</div>

In [this monorepo](https://www.tomasvotruba.com/blog/2019/10/28/all-you-always-wanted-to-know-about-monorepo-but-were-afraid-to-ask/) you'll find PHP packages that help you with:

* your **first coding standard**
* **maintenance of monorepo** and changelog
* **clean Kernel** even with Flex loading methods
* **slim and re-usable Symfony configs**

<br>

You'll find all packages in [`/packages`](/packages) directory. Here is a brief overview (tip: click on the package name to see its `README` with more detailed features):

## Coding Standards

- [Coding Standard](https://github.com/symplify/coding-standard)

## For Symfony

- [Autowire Array Parameter](https://github.com/symplify/autowire-array-parameter)
- [PHP Config Printer](https://github.com/symplify/php-config-printer)

## For Package Development

- [Monorepo Builder](https://github.com/symplify/monorepo-builder)
- [Package Builder](https://github.com/symplify/package-builder)
- [Smart File System](https://github.com/symplify/smart-file-system)
- [Rule Doc Generator](https://github.com/symplify/rule-doc-generator)
- [Symplify Kernel](https://github.com/symplify/symplify-kernel)
- [Config Transformer](https://github.com/symplify/config-transformer)

## For Any Developer

- [Easy Testing](https://github.com/symplify/easy-testing)
- [Symfony Static Dumper](https://github.com/symplify/symfony-static-dumper)

## For PHPStan Lovers

- [PHPStan Rules](https://github.com/symplify/phpstan-rules)
- [PHPStan Extensions](https://github.com/symplify/phpstan-extensions)

## For CI Keeping you Safe

- [Easy CI](https://github.com/symplify/easy-ci)

<br>

## Contributing & Issues

If you have issue and want to improve some package, put it all into this repository.

Fork and clone your repository:

```bash
git clone git@github.com:<your-name>/symplify.git
cd symplify
composer install
```

### 3 Steps to Contribute

- **1 feature per pull-request**
- **new feature must have tests**
- tests and static analysis **must pass**:

    ```bash
    vendor/bin/phpunit
    composer phpstan
    ```

We would be happy to merge your feature then :+1:
