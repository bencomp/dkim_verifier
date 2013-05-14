DKIM Verifier
=============

This is an Add-on for Mozilla Thunderbird, that verifies DKIM Signatures according to the RFC 6376 (http://tools.ietf.org/html/rfc6376)

The source code is availabe at https://github.com/lieser/dkim_verifier.
A packed version can be downloaded at https://addons.mozilla.org/addon/dkim-verifier/.

Please report bugs to http://forums.mozillazine.org/viewtopic.php?f=48&t=2704121 or https://github.com/lieser/dkim_verifier.

Included third-party Libraries
------------------------------
 - Tom Wu's jsbn library - BigInteger and RSA (http://www-cs-students.stanford.edu/~tjw/jsbn/)
  - jsbn.js - basic BigInteger class
  - jsbn2.js - BigInteger class extension
  - rsa.js - RSAKey class for RSA public key encryption
  - rng.js - Random number generator
  - prng4.js - Random number generator
  - base64.js - String encoder for Base64 and Hex
 - Kenji Urushima's 'RSA-Sign JavaScript Library' (http://kjur.github.com/jsrsasign)
  - asn1hex.js - simple ASN.1 parser to read hexadecimal encoded ASN.1 DER
  - rsasign-1.2.js - RSAKey class extension for RSA signing and verification
 - Joshua Tauberer's DNS Libary (part of Thunderbird Sender Verification Extension) (http://razor.occams.info/code/spf/)
  - dns.js - DNS Library