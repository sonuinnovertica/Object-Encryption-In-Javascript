# Object-Encryption-In-Javascript
The project shows how to directly encode object without converting it to string, this is written in plain Javascript, no any other file required and it is not dependent of anything.
You can download this and check that how to use this methods.<br />
to clone this project simply run: <br/>

<pre>git clone https://github.com/sbamniya/Object-Encryption-In-Javascript.git</pre>
Optionally you can also download Zip of the same.

Add <code>ObjectBase64.js</code> file to your project.

It's pretty simple.

# Encrypt Object
After adding the required file all you need to do is call the encryption function, like below:

<pre>var encryptedObj = ObjEncrypt(Object, Salt)</pre>

# Dencrypt Object
After adding the required file all you need to do is call the decryption function, like below:

<pre>var decryptedObj = ObjDecrypt(encryptedObj, Salt)</pre>