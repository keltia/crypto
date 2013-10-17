Ciphers algorithms
-------------------------
Openssl : `openssl list-cipher-algorithms`.
<table>
    <tr><th>Ciphers Algorithms</th><th>first published</th><th>Key sizes</th><th>Note</th></tr>
        <tr><td><a href="https://en.wikipedia.org/wiki/Advanced_Encryption_Standard">AES</a></td><td>1998</td><td>128, 192 or 256 bits</td><td><a href="https://en.wikipedia.org/wiki/Advanced_Encryption_Standard_process">AES winner</a></td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/Blowfish_%28cipher%29">Blowfish</a></td><td>1993</td><td>32 - 448 bits</td><td>successor: Twofish</td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/Camellia_%28cipher%29">Camellia</a></td><td>2000</td><td>128, 192 or 256 bits</td><td></td></tr>
    <tr class="error"><td><a href="https://en.wikipedia.org/wiki/Data_Encryption_Standard">DES</a></td><td> 1977/1979</td><td>56 bits</td><td></td></tr>
    <tr class="error"><td><a href="https://en.wikipedia.org/wiki/RC4">RC4</a></td><td>1987</td><td>40–2,048 bits</td><td></td></tr>
    <tr class="good"><td><a href="https://en.wikipedia.org/wiki/Serpent_%28cipher%29">Serpent</a></td><td>1998</td><td>128, 192 or 256 bits</td><td><a href="https://en.wikipedia.org/wiki/Advanced_Encryption_Standard_process">AES finalist</a></td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/Triple_DES">TripleDES</a></td><td>1998</td><td>56, 112 or 168 bits</td><td>a.k.a DES3</td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/Twofish">TwoFish</a></td><td>1998</td><td>128, 192 or 256 bits</td><td><a href="https://en.wikipedia.org/wiki/Advanced_Encryption_Standard_process">AES finalist</a></td></tr>
</table>

Digest algorithms / Hash
---------------------
OpenSSL: `openssl list-message-digest-algorithms`.
<table>
<tr><th>Digest Algorithms</th><th>first published</th><th>Key sizes</th><th>Note</th></tr>
    <tr class="error"><td><a href="https://en.wikipedia.org/wiki/Md4">MD4</a></td><td>1990</td><td>128 bits</td> <td>harmful since 1991, obsolete (collision) since 1995.</td></tr>
    <tr class="error"><td><a href="https://en.wikipedia.org/wiki/MD5">MD5</a></td><td>1992</td><td>128 bits</td> <td>harmful since 1996, obsolete (collision) since 2004.</td></tr>
    <tr class="error"><td><a href="https://en.wikipedia.org/wiki/SHA-0#SHA-0">SHA-0</a></td><td>1993</td><td>160 bits</td> <td>harmful since 1998, obsolete (collision totale) since 2004.</td></tr>
    <tr class="warning"><td><a href="https://en.wikipedia.org/wiki/SHA-1">SHA-1</a></td><td>1995</td><td>160 bits</td> <td>harmful since 2005.</td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/SHA-2">SHA-2</a></td><td>2001</td><td>224/256 bits or 384/512 bits</td> <td>-</td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/SHA-3">SHA-3</a></td><td>soon?</td><td></td> <td>in progress</td></tr>
    <tr class="good"><td><a href="https://en.wikipedia.org/wiki/Whirlpool_%28cryptography%29">Whirlpool</a></td><td>2000</td><td>512 bits</td> <td></td></tr>
</table>

Key agreement
---------------------------
OpenSSL: `openssl list-public-key-algorithms`.
<table>    
    <tr><th>Key agreement</th><th>first published</th><th>Key sizes</th><th>Note</th></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange">DH</a></td><td></td><td></td><td>a.k.a Diffie-Hellman</td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/Digital_Signature_Algorithm">DSA</a></td><td>1991</td><td></td><td></td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/Elliptic_Curve_DSA">ECDSA</a></td><td></td><td></td><td>Elliptic Curve DSA</td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/ECDHE">ECDHE</a></td><td></td><td></td><td> Elliptic Curve Diffie-Hellman</td></tr>
    <tr><td><a href="https://en.wikipedia.org/wiki/RSA_%28algorithm%29#Encryption">RSA</a></td><td>1977</td><td>1,024 to 4,096 bit</td><td></td></tr>
</table>

