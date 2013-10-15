Ciphers algorithms
-------------------------
Openssl : `openssl list-cipher-algorithms`.
<table class="table table-striped table-bordered table-condensed">
    <tr><td>Ciphers Algorithms</td><td>first published</td><td>Key sizes</td><td>Note</td></tr>
    <tr><td>[AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard)</td><td>1998</td><td>128, 192 or 256 bits</td><td>[AES winner](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard_process)</td></tr>
    <tr><td>[Blowfish](https://en.wikipedia.org/wiki/Blowfish_%28cipher%29)</td><td>1993</td><td>32 - 448 bits</td><td>successor: Twofish</td></tr>
    <tr><td>[Camellia](https://en.wikipedia.org/wiki/Camellia_%28cipher%29)</td><td>2000</td><td>128, 192 or 256 bits</td><td></td></tr>
    <tr class="error"><td>[DES](https://en.wikipedia.org/wiki/Data_Encryption_Standard)</td><td> 1977/1979</td><td>56 bits</td><td></td></tr>
    <tr class="error"><td>[RC4](https://en.wikipedia.org/wiki/RC4)</td><td>1987</td><td>40–2,048 bits</td><td></td></tr>
    <tr class="good"><td>[Serpent](https://en.wikipedia.org/wiki/Serpent_%28cipher%29)</td><td>1998</td><td>128, 192 or 256 bits</td><td>[AES finalist](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard_process)</td></tr>
    <tr><td>[TripleDES](https://en.wikipedia.org/wiki/Triple_DES)</td><td>1998</td><td>56, 112 or 168 bits</td><td>a.k.a DES3</td></tr>
    <tr><td>[Twofish](https://en.wikipedia.org/wiki/Twofish)</td><td>1998</td><td>128, 192 or 256 bits</td><td>[AES finalist](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard_process)</td></tr>
</table>

Digest algorithms / Hash
---------------------
OpenSSL: `openssl list-message-digest-algorithms`.
<table class="table table-striped table-bordered table-condensed">
<tr><td>Digest Algorithms</td><td>first published</td><td>Key sizes</td><td>Note</td></tr>
    <tr class="error"><td>[MD4](https://en.wikipedia.org/wiki/Md4)</td><td>1990</td><td>128 bits</td> <td>harmful since 1991, obsolete (collision) since 1995.</td></tr>
    <tr class="error"><td>[MD5](https://en.wikipedia.org/wiki/MD5)</td><td>1992</td><td>128 bits</td> <td>harmful since 1996, obsolete (collision) since 2004.</td></tr>
    <tr class="error"><td>[SHA-0](https://en.wikipedia.org/wiki/SHA-0#SHA-0)</td><td>1993</td><td>160 bits</td> <td>harmful since 1998, obsolete (collision totale) since 2004.</td></tr>
    <tr class="warning"><td>[SHA-1](https://en.wikipedia.org/wiki/SHA-1)</td><td>1995</td><td>160 bits</td> <td>harmful since 2005.</td></tr>
    <tr><td>[SHA-2](https://en.wikipedia.org/wiki/SHA-2)</td><td>2001</td><td>224/256 bits or 384/512 bits</td> <td>-</td></tr>
    <tr><td>[SHA-3](https://en.wikipedia.org/wiki/SHA-3)</td><td>soon?</td><td></td> <td>in progress</td></tr>
    <tr class="good"><td>[Whirlpool](https://en.wikipedia.org/wiki/Whirlpool_%28cryptography%29)</td><td>2000</td><td>512 bits</td> <td></td></tr>
</table>

Key agreement
---------------------------
OpenSSL: `openssl list-public-key-algorithms`.
<table class="table table-striped table-bordered table-condensed">
    <tr><td>Key agreement</td><td>first published</td><td>Key sizes</td><td>Note</td></tr>
    <tr><td>[DH](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)</td><td></td><td></td><td>a.k.a Diffie-Hellman</td></tr>
    <tr><td>[DSA](https://en.wikipedia.org/wiki/Digital_Signature_Algorithm)</td><td>1991</td><td></td><td></td></tr>
    <tr><td>[ECDSA](https://en.wikipedia.org/wiki/Elliptic_Curve_DSA)</td><td></td><td></td><td>Elliptic Curve DSA</td></tr>
    <tr><td>[ECDHE](https://en.wikipedia.org/wiki/ECDHE)</td><td></td><td></td><td> Elliptic Curve Diffie-Hellman</td></tr>
    <tr><td>[RSA](https://en.wikipedia.org/wiki/RSA_%28algorithm%29#Encryption)</td><td>1977</td><td>1,024 to 4,096 bit</td><td></td></tr>
</table>

