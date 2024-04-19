# Issuing_and_verification_of_birth_Certificate

 Issuing and verification of Birth Certificate using Digital Signature
 Issuing Part :
1. RUN hash generator code
   - give input data of person for whom you want to issue certificate
   - Now at output you will get one hash value store that hash value and user details
  2. Now run Encryption code
      - Give Hash value as input
      - you will get output as public key ,private key and signature value
    3. After getting all this values RUN issue certificate code
       - give user details , signature value and public key as Input
       - After submitting Certificate will get issued with username_dob.txt form
       - Now you can convert txt file into pdf file and give it to user

Verificatin Part :
1. At first run Hash generator code
2. Give user details as input as given in issued certificate and Generate Hash Value
3. Now you got the Hash Value
4. Now run Signature Verification Code
 - give input to hash value you generated
 - give signature value given in certificate
 - give public key as input given in certificate
 - after giving all input value click of verify certificate button
5. Now you will get output whether given certificate is verified or not
