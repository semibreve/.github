# Semibreve

Simplifying small-scale authentication.

> [!IMPORTANT]
> It's been a good run! However, from 2024, I'll be officially retiring Semibreve. This means that no Semibreve project will be receiving any updates going forwards (not even security patches). Packages will remain up on Packagist etc. but the Semibreve organization and all projects will be archived and read-only.

## The Mission

Semibreve was a little project I ([@lambdacasserole](https://github.com/lambdacasserole)) started almost a decade ago back in 2016 to bring a set of simple, secure, open-source, databaseless password authentication libraries to PHP. The idea was to allow users to deploy password authentication in their PHP apps in a secure way without the headache of worrying about accidentally building anti-patterns in the process (e.g. plaintext password storage, transmitting session tokens in the clear).

So far, these libraries have mainly been used by me on some small personal projects of mine, but some other folks out there use them too. The Minim and Semibreve libraries are distributed via [Packagist](https://packagist.org/) so you can install them using [Composer](https://getcomposer.org/).

## Projects

- [**Minim**](https://github.com/semibreve/minim): A single-user authentication system designed for simplicity and ease of integration.
- [**Semibreve**](https://github.com/semibreve/semibreve): A multi-user authentication framework, built from multiple Minim instances.
- **Demo projects**: Demo projects showing examples of how to integrate [Minim](https://github.com/semibreve/minim-demo) or [Semibreve](https://github.com/semibreve/semibreve-demo) into your PHP applications.
