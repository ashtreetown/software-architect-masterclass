## This page is dedicated to user-data related topics

1. Registration
   1. Input required for registration
      1. Don't request email address because email is an old technology that we should move away from
      2. Don't request password because passwords are not secure
      3. You can request a username for aesthetic purposes but not for functional purposes
         1. Usernames should not be used in URLs because of duplicate username issues
         2. Usernames should not be used for login purposes because of duplicate username issues
         3. Usernames should not be used to trust a particular account because fake accounts may take advantage of it
   2. A key pair is the recommended approach to registration
      1. The user generates a "data container" with a random seed
      2. The service provides the user an opportunity to enter with their public key
      3. The service explains what data it needs from the users' data container and why it needs it and the user selectively decrypts the requested data on behalf of the service

2. Login
   1. Traditionally users login with an email address and a password but in future users will login with a key pair and a "data container"
   2. Use decentralized alternatives to centralized "Forgot my password" services
      1. Encrypted hardware
      2. Secure third-party backup service
         1. They may hold your key pair and "data container" but do so using end-to-end encryption
        
3. Logout
   1. Traditionally users logout by requesting that the service provider end their session but in future users will "eject" their "data container" which means that logging out will have the same impact as deleting their account and service providers will only be able to utilize their data while they're logged in
      1. In transactional situations, for example when a product is ordered and has to be delievered, the data will be kept by the service provider until the point of delivery or when the transaction is completed
      2. For P2P data sharing situations such as sharing photos with family and friends, only encrypted data will be kept and distributed by the service provider

5. Encryption
   1. Encryption should be designed to be upgraded continuously (with the introduction of AI, quantum computing, etc)
   2. All service providers should have end-to-end encryption on all data
	
6. Data
   1. Data should be portable
      1. A user should be able to use the same "data container" for similar competing services but have the flexibility to have separate "data containers" too
      2. A user should be able to view and modify the data in their "data container" independently or with the help of a third-party service
	
7. Trust
   1. Checkmarks from manual verification should not be used to build trust because it relies on centralized, biased, error-prone processors
   2. Paid verifications should not be used to build trust because it raises the bar of entry, maintains repetitive, stale voices and can compromise security
   3. Trustless systems are preferred where possible
   4. Each time a user posts something or creates new data, they should be given the opportunity to prove their identity via a decentralized identification system so that the content can be marked appropriately for others


### References

1. [P2P dataless social network](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073411649437171713/)
2. [Forget me](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073418246506938369/)
3. [Tagging People in the Cloud](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073420445530193921/)
4. [Email Footer Forget Me](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073445734297632769/)
5. [Real Author Badge](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073467724530188289/)
6. [End-to-End Encrypted Albums](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073473222088327169/)

©️ All Rights Reserved
