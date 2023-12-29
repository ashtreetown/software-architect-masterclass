## This page is dedicated to user-data related topics

1. Registration
   1. Only request user data that is needed in order to benefit the user
      1. The most common practice is to request an email address, a password, and an email address confirmation code, but this is outdated and should be avoided
   2. A random seed/private key is the recommended approach to registration
      1. The service provides the user an opportunity to enter with a public key which is also used for login and data decryption by the user later on
      2. GDPR has proven that no one can be trusted with peoples' data. It's safe to assume that there are risks any time that data is shared. The user may selectively decrypt certain data for the service provider based on what data they are comfortable sharing

2. Login

   1. Users should login with their random seed used during registration
   2. Usernames serve the purpose of finding and differentiating one brand from another
      1. Usernames should not be used in URLs because of duplicate username issues
      2. Usernames should not be used for login purposes because of duplicate username issues
      3. Usernames should not be used to trust a particular account because fake accounts may take advantage of it
   3. Use decentralized alternatives to centralized "Forgot my password" services
      1. Encrypted hardware
      2. Secure third-party backup service

3. Encryption

   1. Encryption should be designed to be upgraded continuously (with the introduction of AI, quantum computing, etc)
   2. All data should have end-to-end encryption
	
4. Data

   1. Data should be portable
      1. A user should be able to move their encrypted data from one service to another
      2. Using their random seed, a user should be able to view and modify their data independently or with the help of a third-party service
   2. Data should not rely on centralized third-parties such as email providers or databases containing user-data
      1. In the past, the only data users needed to store was an email address and password but going forward, they will keep encrypted "data containers" for each service
      2. Third-parties can provide additional data services such as backup and transfer for encrypted "data containers"
	
5. Trust

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
