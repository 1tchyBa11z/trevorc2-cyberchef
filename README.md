# TrevorC2 cyberchef recipe

## Note this recipe only works if server is using the default CIPHER Key

### To execute this correctly there is a three step process.
a) Get IV which is the first 16 bytes of the base64 decoded cipher text/
b) Add IV to the AES Decrypt recipe
c) enable last two steps after you complete step b

Assuming default settings the command will now be decrypted

TrevorC2 commands are located within the response that you will find by searching for "oldcss=" ( based again on using default settings)

#### Disclaimer : This will not breat AES in any way shape or form and if server is using the any other CIPHER KEY other than the default one it will not work

#### Cipher key used: "Tr3v0rC2R0x@nd1s@w350m3#TrevorForget"
#### Cipher key as Base64 after running through the Create-AesKey function: "Do2wJSdUONy+IWFgvECLj3Lz2TT1XLMvRZoaE0JolTo=" from here https://github.com/trustedsec/trevorc2/blob/master/agents/trevorc2_client.ps1


Step a)
![image](https://github.com/1tchyBa11z/trevorc2-cyberchef/assets/68668887/0ad5c885-784d-411c-9ee7-434a429c9ca9)

Step b)
copy highlighted bits from Output section -> paste into AES Decrypt IV section

![image](https://github.com/1tchyBa11z/trevorc2-cyberchef/assets/68668887/d61ab3d0-933f-4410-85e7-9d2d79fbe1c3)

Step c)

Enable last two recipe components and read decrypted command from Output section

![image](https://github.com/1tchyBa11z/trevorc2-cyberchef/assets/68668887/1c8e80d2-01df-425a-8053-9f49e6d9c136)

