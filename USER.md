## This page is dedicated to user-data related topics

#### 1. Registration

a. Only request user data that is needed in order to benefit the user
	i. The most common practice is to request an email address, a password and an email address confirmation code but this is outdated and should be avoided
b. A random seed/private key is the recommended approach to registration
	i. The service provides the user an opportunity to enter with a public key which is also used for login and data decryption by the user later on
	iii. GDPR has proven that no one can be trusted with peoples' data. It's safe to assume that there are risks any time that data is shared. The user may selectively decrypt certain data for the service provider based on what data they are comfortable sharing

#### 2. Login

a. Users should login with their random seed used during registration
b. Usernames serve the purpose of finding and differentiating one brand from another
	i. Usernames should not be used in URLs because of duplicate username issues
	ii. Usernames should not be used for login purposes because of duplicate username issues
	iii. Usernames should not be used to trust a particular account because fake accounts may take advantage of it

#### 3. Encryption

a. Encryption should be designed to be upgraded continuously (with the introduction of AI, quantum computing, etc)
b. All data should have end-to-end encryption
	
#### 4. Data

a. Data should be portable
	i. A user should be able to move their encrypted data from one service to another
	ii. Using their random seed, a user should be able to view and modify their data independently or with the help of a third-party service
b. Data should not rely on centralized third-parties such as email providers or databases containing user-data
	i. In the past, the only data users needed to store was an email address and password but going forward, they will keep encrypted "data containers" for each service
	ii. Third-parties can provide additional data services such as backup and transfer for encrypted "data containers"
	
#### 5. Trust

a. Checkmarks from manual verification should not be used to build trust because it relies on centralized, biased, error-prone processors
b. Paid verifications should not be used to build trust because it raises the bar of entry, maintains repetitive, stale voices and can compromise security
c. Trustless systems are preferred where possible
d. Each time a user posts something or creates new data, they should be given the opportunity to prove their identity via a decentralized identification system so that the content can be marked appropriately for others


### References

1. [P2P dataless social network](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073411649437171713/)
2. [Forget me](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073418246506938369/)
3. [Tagging People in the Cloud](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073420445530193921/)
4. [Email Footer Forget Me](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073445734297632769/)
5. [Real Author Badge](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073467724530188289/)
6. [End-to-End Encrypted Albums](https://opensea.io/assets/ethereum/0x495f947276749ce646f68ac8c248420045cb7b5e/83473010838008979452047554662756202009949420934210702451763073473222088327169/)

©️ All Rights Reserved
