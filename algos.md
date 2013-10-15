Symmetric ciphers
-----------------
<table class="table table-striped table-bordered table-condensed">
    <tr><td><strong>Symmetric ciphers</strong></td><td>first published</td><td>Key sizes</td <td><strong>Note(s)</strong></td></tr>
    <tr><td>DHE</td><td></td><td></td><td></td></tr>
    <tr><td>EDH</td><td></td><td></td><td>Ephemeral Diffie-Hellman </td></tr>
    <tr><td>ECDHE</td><td></td><td></td><td> Elliptic Curve Ephemeral Diffie-Hellman</td></tr>
</table>


Algorithme de chiffrement
-------------------------
<table class="table table-striped table-bordered table-condensed">
    <tr><td><strong>Symmetric ciphers</strong></td><td>first published</td><td>Key sizes</td <td><strong>Note(s)</strong></td></tr>
    <tr><td>[AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard)</td><td>1998</td><td>128, 192 or 256 bits</td><td>[AES winner](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard_process)</td></tr>
    <tr><td>[Blowfish](https://en.wikipedia.org/wiki/Blowfish_%28cipher%29)</td><td>1993</td><td>32 - 448 bits</td><td>Successors: Twofish</td></tr>
    <tr><td>cast</td><td></td><td></td><td></td></tr>
    <tr><td>des</td><td></td><td></td><td></td></tr>
    <tr><td>idea</td><td></td><td></td><td></td></tr>
    <tr><td>rc2</td><td></td><td></td><td></td></tr>
    <tr><td>rc4</td><td></td><td></td><td></td></tr>
    <tr><td>rc5</td><td></td><td></td><td></td></tr>
    <tr><td>Serpent</td><td></td><td></td><td></td></tr>
    <tr><td>Twofish</td><td></td><td></td><td></td></tr>
</table>


Public key cryptography and key agreement
-----------------------------------------
<table class="table table-striped table-bordered table-condensed">
    <tr><td><strong></strong></td><td>first published</td><td>Key sizes</td <td><strong>Note(s)</strong></td></tr>
    <tr><td>dsa</td><td></td><td></td><td></td></tr>
    <tr><td>dh</td><td></td><td></td><td></td></tr>
    <tr><td>rsa</td><td></td><td></td><td></td></tr>
</table>

Cypher algorithms
-----------------
`Openssl : <code>openssl list-cipher-algorithms`.
<table class="table table-striped table-bordered table-condensed">
    <tr class="success"><td>AES</td><td>key >=128</td><td></td><td></td></tr>
    <tr><td>BF</td><td></td><td></td><td></td></tr>
    <tr><td>CAMELLIA</td><td></td><td></td><td></td></tr>
    <tr><td>CAST5</td><td></td><td></td><td></td></tr>
    <tr class="error"><td>DES</td><td></td><td></td><td></td></tr>
    <tr><td>DES3</td><td></td><td></td><td></td></tr>
    <tr class="error"><td>RC4</td><td>cf. </td><td></td><td></td></tr>
</table>


Algorithme de hachage
---------------------

<table class="table table-striped table-bordered table-condensed">
<tr><td><strong>Hash</syytrong></td><td>first published</td><td>Key sizes</td <td><strong>Note(s)</strong></td></tr>
    <tr class="error"><td>MD4 (128 bits)</td><td></td><td></td> <td>dangereux depuis 1991, obsolète (collision totale) depuis 1995.</td></tr>
    <tr class="error"><td>MD5 (128 bits)</td><td></td><td></td> <td>dangereux depuis 1996, obsolète (collision totale) depuis 2004.</td></tr>
    <tr class="error"><td>SHA-0 (160 bits)</td><td></td><td></td> <td>dangereux depuis 1998, obsolète (collision totale) depuis 2004.</td></tr>
    <tr class="error"><td>SHA-1 (160 bits)</td><td></td><td></td> <td>dangereux depuis 2005.</td></tr>
    <tr><td>SHA-2 (224 bits)</td><td></td><td></td> <td>-</td></tr>
    <tr class="success"><td>SHA-2 (256 bits)</td><td></td><td></td> <td>standard actuel (2013)</td></tr>
    <tr><td>SHA-2 (384 bits)</td><td></td><td></td> <td>-</td></tr>
    <tr class="success"><td>SHA-2 (512 bits)</td><td></td><td></td> <td>standard actuel (2013)</td></tr>
    <tr><td>SHA-3</td><td></td><td></td> <td>en cours de préparation</td></tr>
    <tr class="error"><td>RIPEMD (128 bits)</td><td></td><td></td> <td> collision partielle en 2004, ne doit plus être utilisé.</td></tr>
    <tr><td>RIPEMD-128 (128 bits)</td><td></td><td></td> <td>pas de problème connu.</td></tr>
    <tr class="success"><td>RIPEMD-160 (160 bits)</td><td></td><td></td> <td>standard actuel (2013), pas de problème connu.</td></tr>
    <tr class="success"><td>RIPEMD-256 (256 bits)</td><td></td><td></td> <td>pas de problème connu.</td></tr>
    <tr class"success"><td>RIPEMD-320 (320 bits)</td><td></td><td></td> <td>pas de problème connu.</td></tr>
    <tr class="warning"><td>TIGER (192/128/160 bits)</td><td></td><td></td> <td> des attaques ont été trouvées.</td></tr>
    <tr class="success"><td>Whirlpool (512 bits)</td><td></td><td></td> <td> standard actuel (2013), pas de problème connu.</td></tr>
</table>

SSL / TLS
---------
<tr><td><strong>SSL/TLS</strong></td><td>first published</td><td>Key sizes</td <td><strong>Note(s)</strong></td></tr>
<tr class="error"><td>SSL v1</td><td></td><td></td> <td>-</td></tr>
<tr class="error"><td>SSL v2</td> <td></td><td></td><td></td></tr>
<tr class="warning"><td>SSL v3</td> <td></td><td></td><td></td></tr>
<tr class="success"><td>TLS v1</td> <td></td><td></td><td></td></tr>
<tr class="success"><td>TLS v1.1</td> <td></td><td></td><td></td></tr>
<tr class="success"><td>TLS v1.2</td> <td></td><td></td><td></td></tr>
</table>
