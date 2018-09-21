

# CnMToken

[CnMToken](https://xxxxxxxxxxxxxxx/) is a two-factor authentication application for systems
utilizing one-time password protocols. Tokens can be added easily by scanning a QR code.

CnMToken implements open standards:

* HOTP (HMAC-Based One-Time Password Algorithm) [RFC 4226](http://www.ietf.org/rfc/rfc4226.txt)
* TOTP (Time-Based One-Time Password Algorithm) [RFC 6238](http://www.ietf.org/rfc/rfc6238.txt)

This means that no proprietary server-side component is necessary: use any server-side component
that implements these standards.

## Download CnMToken for Android

* [Google
Play](#####)
* [F-Droid](#####)

## Contributing

Pull requests on GitHub are welcome under the Apache 2.0 license, see [COPYING](COPYING).

## Permissions

The FreeOTP app uses the following permissions

| Permission | Usage                    | Required | Permission type |
|------------|--------------------------|----------|-----------------|
| Camera     | Recognition of QR codes  | No       | Dangerous       |
| Internet   | Token image provisioning | No       | Normal          |
