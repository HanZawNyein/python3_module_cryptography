# Python3 Module Cryptography

## SOURCEdefender 
is the easiest way to obfuscate Python code using AES-256 encryption. AES is a symmetric algorithm which uses the same key for both encryption and decryption (the security of an AES system increases exponentially with key length). There is no impact on the performance of your running application as the decryption process takes place during the import of your module so encrypted code won't run any slower once loaded from a .pye file compared to loading from a .py or .pyc file.

## .ENV

    SOURCEDEFENDER_PASSWORD=1234abcd
    SOURCEDEFENDER_SALT=dcba4321