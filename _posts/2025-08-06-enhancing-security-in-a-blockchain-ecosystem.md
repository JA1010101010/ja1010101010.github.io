---
layout: post
title: "Enhancing security in a blockchain ecosystem"
date: 2025-08-06 12:00:00 +0800
---

# **Introduction**
Cryptographic techniques are a pillar of digital security today, and they have a very essential role in data security and safe communication. Cryptographic techniques such as advanced mathematical algorithms are pivotal to security provision in online banking and e-commerce, government communications, and blockchain technology. Basically, these techniques are designed to provide confidentiality, integrity, and authenticity of information. With the advancement in the types of digital attacks, cryptography as a discipline, keeping pace with new and innovative solutions to fight such attacks.

In this essay, we will speak of a few of the advanced cryptographic methods and their application, benefits, and drawbacks. We start with multi-signature methods, which introduce additional security with the use of multiple keys to authenticate a transaction. We continue to use ring signatures and zero-knowledge proofs that offer greater privacy and anonymity for electronic transactions. We then look at critical security vulnerabilities such as reentrancy attacks and arithmetic and access control flaws and how to avoid them. 

Finally, we look at improved privacy solutions such as threshold cryptography, homomorphic encryption, stealth addresses, and confidential transactions and the security best practices for smart contracts and cryptographic protocols. This in-depth look will uncover the significance of all these cryptographic methods to enable a private, secure, and virtual world.




## **Cryptographic Techniques - multi-signatures**

### **Advantages** 
Multi-signature cryptographic techniques - enables one to merge several various signatures for validation of documents or cryptocurrency transactions. It has many advantages when used in digital asset management and protection. The primary advantage is that there is greater security, since multi-signatures wallets require several private keys to make transactions, reducing the threat of a sole point of failure. (Lin, 2024) This means that even if there is one breached key, the money is still safe. (QuickNode, 2025)

A further advantage is the sharing of trust across more than one party, which is beneficial in cooperative contexts such as firm assets, or joint family accounts. (CoinTelegraph, 2023) Distributing trust so that a single person has unilateral control over the money, promoting responsibility and accountability. (Singh, 2024)

Multi-signatures wallets also provide convenience in setting the number of signatures required to authorise a transaction. It can also, reduce the extent of unauthorised access and fraud. By requiring more than one signature, they are more difficult for an attacker to orchestrate a spoof transactions. (Lin, 2024) This is particularly helpful where funds are managed by groups of individuals or organisations


### **Limitations**
Cost - primary restrictions is an increased transaction size and cost. Multi-signatures transactions occupy more information to encode in the blockchain, since they must include multiple signatures and public keys. This makes them more expensive transactions, as the cost is typically based on how many bytes are used. (Random Oracle, 2018)

Flexibility - it is a laborious and exhausting process to alter the number of signatures to be requested or the distribution of the keys after the wallet has been set up. It is a process that forces wallet owners to create a new wallet, rebalance the keys, and no money should be earned by the existing wallet, which is time-consuming and 
error-prone. (Turner & Schaad, 2010)

Usability - Multi-sig wallets will attract unnecessary scrutiny because they consist of a non-standard design and hence are more likely to be discovered by potential attackers. (Turner & Schaad, 2010) Multiple keys may introduce additional failure points, especially when undefended.


##Zero-Knowledge Proofs

### **Advantages**
Zero-knowledge proofs (ZKPs) are a cryptographic protocol where one party (the prover) is able to prove to another party (the verifier) that a statement holds without revealing any of the underlying data. 

ZKPs provide for some significant advantages, including enhanced privacy and data protection. This reduces exposure of sensitive information, which reduces the risk of data breaches in an efficient way. (Shoemaker, 2025) They also reduce dependency on trust as they enable the creation of trustless systems. This enhances security and transparency in applications from election systems to financial transactions. (Shoemaker, 2025) 

ZKPs provide good security guarantees by not permitting any information extraction except for the validity of the proof, thereby protecting sensitive systems and data against probable attacks. (Shoemaker, 2025) ZKPs are malleable and adaptable, i.e., they can be made to suit various applications and industries, thereby making them an adaptable solution to many issues. (Shoemaker, 2025) In blockchain, ZKPs enhance privacy, scalability, and security via secure confidential transactions and reduction in computational overhead and transaction verification time. (SoluLab, 2024) 

Also enhancing blockchain protocol scalability and effectiveness. (SoluLab, 2024) In voting systems, ZKPs enhance security and integrity by enabling voters to prove they had cast valid votes without revealing their choices, retaining anonymity, avoiding vote manipulation, and establishing trust in electoral processes. (SoluLab, 2024) In authentication protocols, ZKPs allow one to prove one's identity without disclosing sensitive information such as passwords or biometric material, thus facilitating privacy-preserving and secure authentication protocols. (SoluLab, 2024) 

ZKPs can facilitate more convenient authentication for platforms and users through the identity authentication via ZK-proofs without retaining significant amounts of user data

### **Limitations**
One of the key limitations of ZKPs is that they are computationally intensive. ZKPs may be computationally costly to prove and generate, which may limit their scalability and real-world usability. (Shoemaker, 2025) This computational intensity may delay transactions processing and may limit the use of ZKPs in systems with weak computational powers. (Etugbo, 2025)

The other primary challenge is that it is specialist expertise-intensive. Secure ZKP systems development and deployment demand a high degree of knowledge of the subject matter in cryptography, a potential hurdle for organisations lacking such the respective expertise. (Shoemaker, 2025) The complexity also presents opportunity for vulnerabilities when not applied appropriately.

ZKPs have their own limitations when it comes to usage too. They are general-purpose but may not necessarily be optimal for every application. (Shoemaker, 2025) Certain constraints or needs can become their limiting points. Further, the lack of standardisation across ZKP protocols can become a source of hindrance for interoperability and mass adoption since implementations may contain varying security and efficiency features. (Shoemaker, 2025)

Some ZKP implementations, such as ZK-SNARKs, employ a trusted setup with possible security vulnerabilities. If the setup process is ever breached, insecurity to the system would follow. (Infisign, 2025) As countermeasures to this, other options such as zk-STARKs have been developed, which eliminate the need for a trusted setup and thereby introduce a tremendous leap in security. (Etugbo, 2025)

Apart from this, ZKPs are also vulnerable to attacks by quantum computing. Some ZKP protocols are vulnerable to quantum computing attacks, which can potentially undermine the cryptographic security of ZKPs. (Kochan, 2025)

## **Ring Signatures**
Ring signatures are a digital cryptographic signature that allows a signer to demonstrate that they signed a message without disclosing their identity to other would-be signers

### **Advantages**
Privacy and Anonymity During Transactions: Ring signatures provide users of crypt with privacy and anonymity during transactions. They ensure that the signer's identity is preserved in a list of possible signers such that it's difficult for a third party to identify who signed a transaction. (Unchained Crypto, 2023)

Greater Security: Third parties cannot forge or alter ring signatures, ensuring more secure communication and transactions. (Unchained Crypto, 2023)
Scalability: The concept of message signing on behalf of numerous users can have applications outside of transactions, such as anonymous messaging, whistleblowing, group authentication, and voting schemes. (Unchained Crypto, 2023)
Non-traceability and Anonymity: Ring signatures also enhance the anonymity and non-traceability of the signature. They allow any member of the group to sign a message on behalf of the group without disclosing their identity, thus offering more privacy for them. (Teng et al., 2025)

Plausible Deniability: Ring signatures ensure that the outputs of the transactions are not traceable. That is, there is no way to identify which one of the possible signers in a signature group of a person's account, thus giving plausible deniability. (Monero Project, n.d.)

Efficiency Improvements: Other ring signature schemes have been proposed in an effort to improve efficiency in signature verification and generation. (Teng et al., 2025)
Low Key Leakage Risk: By utilising distributed key generation (DKG), ring signatures can reduce the risk of key leakage in case a trusted authoriser (TA) is breached. The approach does away with one trusted third party, thus providing overall security improvements. (Teng et al., 2025)

### **Limitations**
There are a few Limitations of a ring signature. These include the size of the ring signature being proportional to the number of participants, and this may lead to inefficiencies in practice. (ScienceDirect, n.d.)

Another limitation is that ring signatures make it impossible for the actual signer to be able to prove that he signed and claim credit for what he has done. This is a disadvantage in cases where the signer needs to be identified for a specific reason. (Gao et al., 2019) Anonymity of ring signatures can be used to conceal the identity of an adversarial signer, causing suspicion to fall on other members of the ring. (Gao et al., 2019)

The original ring signature proposal introduced by Rivest, Shamir, and Tauman requires the signer to combine his own private key with other members' public keys in the group in order to create a signature. Although this ensures that the true signer cannot be identified, it has the unpleasant consequence of enabling any member of the group to create a valid signature, and it cannot be shown that a particular individual was the actual signer. (Coin360, n.d.)

Security-wise, ring signatures must ensure both non-traceability and anonymity. non-traceability ensures that it is not possible for an attacker to generate a signature on behalf of an honest group of signers, while anonymity ensures that any signature will not yield any information about the identity of the signer. (Hara & Tanaka, 2021) These security properties can be difficult to achieve, especially if one considers side-channel attacks capable of exploiting information leaks such as time consumption, power, and electromagnetic radiation. (ScienceDirect, n.d.)



##Addressing Vulnerabilities and Specific Measures to address these Vulnerabilities

## **Reentrancy**
Reentrancy is a critical vulnerability in smart contracts where a function calls out to another contract externally first before changing its own state, allowing the external contract to reenter the original function and reuse behaviour, with potential effects of unauthorised state changes or loss of money. (Open Web Application Security Project [OWASP], 2023) Reentrancy comes in various types, including single-function reentrancy, cross-function reentrancy, and cross-contract reentrancy. (QuickNode, 2025)

Single-function reentrancy occurs when an external call within a function calls the same function, leading to a sequence of state changes. For example, in the legendary DAO hack, the exploit occurred when they continued withdrawing funds before modifying the user balance. This can be prevented by developers ensuring state changes occur before external calls, like in the revised code snippet where the balance is modified before the external transfer. (Open Web Application Security Project [OWASP], 2023)

Cross-function reentrancy is when two or more functions have the same state variables and an attacker can exploit one function in order to manipulate others. For instance, an attacker could employ the withdraw function and then reenter the contract using the transfer function and conduct unauthorised fund transfer. (QuickNode, 2025) Countermeasures include inhibiting reentrancy by making use of function modifiers like OpenZeppelin's ReentrancyGuard. (Open Web Application Security Project [OWASP], 2023)

Cross-contract reentrancy suggests weaknesses that extend beyond one contract, whereby the state of one contract is relied upon by another. In modularised systems, this can be particularly dangerous as an attacker can manipulate the state of one contract to affect another. Read-only reentrancy is the corner case where the functionality of one contract is based on the state of another, and attackers can exploit stale state knowledge. (QuickNode, 2025)

To avoid and monitor reentrancy attacks, software has been developed like BlockWatchdog. This type of software is targeted to identify attacker contracts using call chain and dataflow analysis, thus enabling the detection of actually exploitable reentrancy attacks. It is also good practice to implement the Check-Effects-Interaction (CEI) design pattern, in which state modifications are executed before calls to the outside world. (Open Web Application Security Project [OWASP], 2023)

## **Access Control**
Access control occurs when applications fail to impose correct limitations on resource or function access. Breakdown in access control allows users to perform unauthorised actions, such as accessing administrative capabilities (vertical privilege escalation) or viewing another user's details (horizontal privilege escalation). (Sodha, 2023) Vulnerabilities like Insecure Direct Object References (IDOR) or missing authorisation checks allow attackers to modify parameters or URLs and view restricted content. (Sodha, 2023) Obscurity (such as secret URLs) is employed in certain systems and fails if the URLs become evident in code or logs. (PortSwigger, n.d. , Sodha, 2023)


## **Arithmetic Issues**
Weaknesses in the arithmetic foundations of cryptographic systems, for instance, the security of many cryptographic algorithms, relies on the difficulty of solving certain mathematical problems. (Wikipedia, n.d.) If these problems become tractable, the security of the corresponding cryptographic systems can be compromised.

One specific area of concern is the key length. Key length is just one factor in the quality of both symmetric key and public key cryptography calculations. The longer that a secret key or private key is used, the more vulnerable it is to attack. (Muqeet, 2018) The use of weak or outdated algorithms can introduce vulnerabilities. For example, the Data Encryption Standard (DES) algorithm, once considered secure, has become vulnerable due to advances in computing power. (VPN Unlimited, n.d.)

Another vulnerability is related to the randomness of generated keys. Weak or predictable random number generators can compromise the unpredictability essential for cryptographic security. One notable historical example is the Dual EC DRBG algorithm, which was found to have a backdoor that allowed attackers to predict the output. (VPN Unlimited, n.d.)

## **Compromised Oracles**
Attacks exploit the fact that the utilisation of smart contracts relies on external information sources, oracles, to modify the operation of the contract or get unauthorised information. (Smart Contract Security Field Guide, n.d.) Oracles are systems that allow smart contracts to communicate with the outside world, and this is important for most decentralised applications (dApps) to work in their best capacity. 

They provide data like prices or other off-chain data that the smart contract ought to base its decision on. (Smart Contract Security Field Guide, n.d.) The oracle attack might be caused when an attacker manipulates the information from the oracle such that it misdirects the smart contract to function in an unpredictable or malicious manner. This causes unwanted effects, loss of money, or insecurity. (Smart Contract Security Field Guide, n.d.)

A single point of failure is a major defect, wherein dependency on a single oracle or small set of oracles may cause a single point of failure. If the oracle gets compromised, hacked, or crashes, the whole smart contract could be affected. (Smart Contract Security Field Guide, n.d.) Flash loan-sourced spot price manipulation is another threat where an attacker takes out a flash loan to drain one side of a Uniswap pool and rig the protocol's internal price. (Smart Contract Security Field Guide, n.d.) 

Centralised oracles and trust also are vulnerabilities as there could have been a centralised oracle used in projects and individuals must believe the data will be placed in correctly and on schedule. (Smart Contract Security Field Guide, n.d.)

In order to limit oracle attacks, it is important for blockchain developers to implement appropriate security protocols, such as the use of various independent oracles with variant sources providing the same information, diversification of data sources, verification of the data by cryptographic proof or signatures, time-stamping of the data provided by oracles, threshold signatures, randomised oracles, decentralised oracle networks, off-chain verification of data, emergency shutdown mechanism, and continuous monitoring and auditing. (Smart Contract Security Field Guide, n.d.)

While they are highly useful, oracles add additional risks to blockchains. It is essential to know these risks to make decentralised applications secure. Centralised oracles or single-source oracles add a point of failure. When the oracle is offline, the integrity of data given by the oracle is disrupted, and that leads to false contract execution and financial loss. (RocketMeUpCybersecurity, n.d.) Oracles are susceptible to deception by information, which can be controlled by attackers. This is done through hacking external information or defacing the oracle itself in order to feed the blockchain false information. (RocketMeUpCybersecurity, n.d.)

Enhancing Privacy and additional measures for Enhanced Privacy

## **Stealth Addresses**
Stealth Addresses enhances the anonymity of cryptocurrency transactions by generating new, temporary addresses for each transaction. This renders the recipient address not obvious, and it becomes difficult for third parties to trace the transaction history or conglomerate multiple transactions into one recipient (Hacker Noon, n.d.)

The system involves the sender using the recipient's public key and a mathematical random number to generate an ephemeral address for receiving the transaction. The money is paid to this address, and the sender also broadcasts an ephemeral public key on the blockchain, which the recipient uses to locate and acquire the funds. (Singh, 2023) The recipient then uses his own private key to compute the individual stealth address and receive the funds. (Hacker Noon, n.d.)

Stealth addresses do have their advantages, including enhanced privacy, greater security, and immunity from blockchain analysis. Stealth addresses prevent address reuse and reduce the risk of address-based attacks, so it becomes harder for third parties to de-anonymise transactions. (Hacker Noon, n.d.)

This technique is used by anonymity coins such as Monero and Zcash, which utilise other methods like ring signatures and zero-knowledge proofs to further enhance privacy and anonymity. (Vaia, n.d.) In Ethereum, the ERC-5564 standard establishes a means by which stealth addresses can be put into practice, allowing senders to develop private accounts that are accessible only to their receivers

## **Confidential Transactions** 
Cryptography is essential to facilitate privacy in anonymous transactions. Confidential Transactions (CT) enhance Bitcoin privacy by hiding the transaction sizes, keeping financial details secret while still proving the transactions are valid and secure. (NAD-CAB, 2025) Cryptographic techniques, i.e., range proofs, are utilised by these transactions to prove the transactions are valid without revealing the actual amount. (NAD-CAB, 2025) Meaning that although the network can confirm the transaction as valid, the amount being transferred information is still not publicly known, giving users extra anonymity. (NAD-CAB, 2025)

CT are important because they eliminate the issue of increased privacy in Bitcoin transactions. Without these transactions, anyone on the blockchain can see the amount being transferred, which can expose weak financial data and ruin user confidentiality. (NAD-CAB, 2025) By using CT, a Blockchain Development Company is able to guarantee that figures in transactions are not exposed but are still secured and verified. (NAD-CAB, 2025) This added privacy feature is needed to protect user data and provide financial security in an increasingly open digital world. (NAD-CAB, 2025)

CT solve several problems by enhancing privacy and security in Blockchain Development Services. They address the issue of concealing transaction values, exposing the sensitive financial details and increasing the susceptibility to focused attacks or data breaches. By hiding such amounts, CT preserve user privacy, inhibit financial data analysis, and maintain regulatory compliance for data protection. (NAD-CAB, 2025) 

They support practices like PoW Validate Bitcoin Transactions to ensure secure and verifiable transactions. (NAD-CAB, 2025) This ensures that transaction information is not made public, resulting in a safer and more personal financial system. (NAD-CAB, 2025)

CT ensure anonymity by using advanced cryptographic techniques that hide transaction amounts without interfering with their authenticity. This is achieved through range proofs, which allow the network to verify that the amounts in the transactions are correct without exposing them. (NAD-CAB, 2025) 

With the integration of this technology, Nadcab Labs ensures enhanced Bitcoin anonymity and protection, preventing sensitive financial data from public visibility. (NAD-CAB, 2025)

In addition to CT, other cryptographic methods such as zero-knowledge proofs, ring signatures, and stealth addresses are utilised to construct greater privacy in blockchain transactions. Zero-knowledge proofs allow a user to prove knowledge of given data without revealing the actual data. (naeemhasan588, n.d.) 

Ring signatures allow a user to sign a transaction on behalf of a group so that it becomes impossible to determine the actual signer within the group. (naeemhasan588, n.d.) Stealth addresses provide unique addresses for each transaction so that one cannot correlate addresses on the blockchain. (Abbas, 2024)

These cryptographic techniques are utilised in privacy coins like Monero, Zcash, and Dash as well. Monero uses ring signatures, stealth addresses, and Ring Confidential Transactions (RingCT) to hide transactions. (Khaliq, 2025) Zcash uses zk-SNARKs (Zero-Knowledge Succinct Non-Interactive Arguments of Knowledge) to enable shielded transactions that encrypt the amount, recipient, and sender, offering robust privacy. (Khaliq, 2025) 

Dash offers a voluntary privacy feature called PrivateSend, which allows private transactions, encouraging more confidentiality in financial transactions. (Abbas, 2024)

## **Homomorphic Encryption**
Calculations to be performed on encrypted data without decryption to ensure that the data remains secure throughout. (Khaliq, 2025) The feature plays a key role in preserving privacy and security in various applications such as cloud computing, data processing, and secure voting. (Khaliq, 2025)

Homomorphic encryption (HE) takes plaintext information and transforms it into cipher-text using what is known as a HE scheme. The cipher-text can then be processed using mathematical operations (addition, multiplication, etc.) without anyone being able to see the original information. The cipher-text can then be decrypted to display the outcome of the operations as if they had been performed on the original plaintext. (Supermicro, n.d.)

There exist several types of homomorphic encryption that provide varying capabilities and security. The primary ones include:
Partially Homomorphic Encryption (PHE): It facilitates either addition or multiplication but not both. An example is Paillier crypto-system, which provides the additive property, with which it is possible to compute the sum of cipher-texts without possessing a private key. (Ogburn et al., 2013)

Somewhat Homomorphic Encryption (SHE): Allows a limited set of operations over cipher-texts, typically a limited number of additions and multiplications.
Fully Homomorphic Encryption (FHE): Allows addition and multiplication operations to be performed infinitely on cipher-texts and support arbitrary computation. FHE is the most secure form of homomorphic encryption and is based on lattice-based cryptography, making it quantum-proof. (Supermicro, n.d.)

HE has certain advantages in data privacy and cybersecurity, such as:
Data Privacy: Safeguards data in an encrypted and secure format while being processed, protecting sensitive information from unauthorised use. (Supermicro, n.d.)
Regulatory Compliance: Ensures organisation conformity with data protection rules by making data confidential even while performing arithmetic operations. (Supermicro, n.d.)
Cloud Security: Allows secure offloading of data processing onto the cloud provider without exposing the underlying data. (Supermicro, n.d.)
Collaboration: Allows secure collaboration and sharing of information between different parties without compromising privacy. (Supermicro, n.d.)

Despite its advantages, HE has some drawbacks: computational overhead and storage consumption. The first FHE schemes had tremendous slowdowns, but today's optimisations have succeeded in reducing this gap to 10³-10⁶ times. HE is also storage-intensive, and it becomes challenging for low-end devices. (Cybersnowden, n.d.)

New breakthroughs have made HE a reality, with Intel, NVIDIA, and Google creating FHE hardware accelerators to increase efficiency. Microsoft SEAL, IBM HELib, TFHE by Google, and PALISADE offer optimised libraries for the implementation of homomorphic encryption. (Cybersnowden, n.d.)
HE is being used in numerous practical applications, some of which include:
Secure Data Processing: Enables companies to store encrypted data and process it in the cloud without compromising confidentiality. (Cybersnowden, n.d.)
Privacy-Preserving AI: Allows machine learning algorithms to analyse encrypted information without access to sensitive information. (Cybersnowden, n.d.)
Secure Financial Transactions: Protects financial transactions, records, and audits by encrypting the sensitive information and allowing financial analysis. (Cybersnowden, n.d.)
Genomic Research: Allows researchers to securely analyse DNA data to ensure medical data privacy. (Cybersnowden, n.d.)

HE in the healthcare sector guarantees secure analysis of patient information so that doctors can work together and conduct data analysis on encrypted information without risking the privacy of patients. This proves useful in the case of personalised medicine, wherein patient-specific information needs to be analysed to tailor treatment. (Supermicro, n.d.)

HE is also being used inside the Apple ecosystem to uphold the pledge of protecting user privacy while building on-device experience supplemented with knowledge from server databases. (Apple Machine Learning Research, n.d.) 

By employing HE and a combination of privacy-friendly technologies like PIR and PNNS, ML models for both on-device and server-side, and other privacy-friendly techniques, Apple is able to offer features like Enhanced Visual Search without revealing to the server any information on a user's on-device activity and content. (Apple Machine Learning Research, n.d.)

## **Threshold Cryptography**
Threshold cryptography is a cryptographic technique that introduces privacy and security by distributing the control of the cryptographic keys among greater than one party. The technique guarantees that no party has complete control over the key, thereby reducing the chance for unauthorised use and improving the overall security of the system. (Abbas, 2023)

In threshold cryptography, a secret key is split into multiple shares and distributed among parties. The key is reconstructed only when a predetermined number of parties come together to combine their shares into one key. This provides no participant with total access to the key, thus reducing the threat of unauthorised access. (parth51199, 2023)

Threshold cryptography is normally blended with Multi-Party Computation (MPC), through which multiple parties can carry out a computation on their input without the revelation of their input. This blending provides an additional layer of protection, making unauthorised access or manipulation of data even more challenging. (Abbas, 2023)

Multi-party approach of threshold cryptography enables threshold schemes, to provide secure distribution of trust in operation of cryptographic primitive. Using a "secret sharing" protocol, the secret key is split into multiple "shares". 

Then, even when some (a maximum of f out of n) among the parties are compromised, the key remains secret. The cryptographic operation based on the key is subsequently performed through a threshold scheme, through secure multi-party computation (MPC), such that the key does not have to be reconstructed (i.e., the secret-sharing remains even during the computation). (National Institute of Standards and Technology, n.d.)
National Institute of Standards and Technology (NIST) also engages in the development of threshold cryptography. The upcoming NIST Call for Multi-Party Threshold Schemes will solicit public proposals of threshold scheme (multi-party protocols) for various cryptographic primitives. This considers many cryptographic techniques of interest, such as MPC, ZKP, FHE, and IBE/ABE. (National Institute of Standards and Technology, n.d.)

Smart Contract Security Impacts and Recommendations to Mitigate these concerns

Incorrect Deployment Settings 
Smart contract security is also heavily affected by the wrong deployment settings, which may lead to vulnerabilities and potential exploits. The hack of Yearn Finance illustrates how the wrong settings in a smart contract setup can lead to tremendous financial loss. An attacker was able to exploit a weakness in one of its lending pools of DAI so that they could drain $11 million using manipulated settings and the inclusion of flash loans. (Horbonos, 2021)

Incorrect deployment settings can also lead to other security flaws, such as reentrancy attacks, in which an external contract can repeatedly call into the same contract prior to updating its state, and which could lead to undesired behaviour and the draining of funds. (Cobalt, 2024) Incorrect configuration can also give rise to business logic errors, in which the contract is functioning differently than intended, and which allows for attackers to manipulate the contract and steal funds. (Scarfone & Cobb, 2025)

To minimise such risks, developers must make all configurations thoroughly reviewed and ensure that smart contracts are tested and audited rigorously before deployment. Implementation of best practices such as the utilisation of reentrancy guards, input validation, and access control can significantly improve security in smart contracts. (Cobalt, 2024)

## **Delegate Call Attacks**
Smart contract delegate call positions are a serious security issue that allows an attacker to modify the state of a contract through function calls external to the contract. The attacks can leverage the delegate call functionality, which executes code in the context of the calling contract, to introduce unexpected state modifications and vulnerabilities. (ahmetw.eth, 2023)

Such attacks can wreak havoc, as witnessed in the DAO hack and Parity wallet bug, where attackers exploited the vulnerabilities of delegate calls to drain their money and compromise contract integrity. 

Delegate call Vulnerabilities: The delegate call vulnerability occurs when an attacker manipulates the storage layout of a contract so as to overwrite specific key state variables in order to obtain unauthorised control over the contract's behaviour. (ahmetw.eth, 2023)

Mitigation Strategies: Developers can defend against attack from calls by delegate ensuring that there is uniform storage structure between contracts, employing proxy contracts with less logic, and employing well-regarded libraries like OpenZeppelin for secure deployment. (ahmetw.eth, 2023)

Real-World Impacts: The 2016 DAO hack and the Parity wallet vulnerability in 2017 provide a perfect example where vulnerabilities in delegate calls led to unprecedented financial losses and brought about a shift in blockchain security practice (Nadiger, 2023).

Sanitisation issues in function parameters on smart contract security

Sanitisation issues in function arguments impacting smart contract security are an issue of monumental proportion, where unvalidated input poses serious vulnerabilities and exploits. Sushi-swap, for instance, was exploited because an external function argument hadn't been sanitised, showing the necessity of input validation. (RareSkills, 2023) 

Loose input validation can offer a method for attacking function arguments and lead to unintended consequences with monetary loss. (Rishabh Kumar, 2025) Agree that strong input validation and data sanitisation controls, i.e., range checking, type checking, boundary checking, must be used by developers to check for input parameters in proper form and boundaries. (Cypherock, 2025) Such practices mitigate side effects of bad or malicious inputs and hence make smart contracts safer overall.



## **Mitigating External Threats and Strategies to Minimise the Impact of these External Threats.**

### **Denial-Of-Service Stacks**
Cryptographic measures play a role in protecting against external attacks, such as denial-of-service (DoS) attacks. Among the methods is the use of robust encryption techniques such as encryption hash functions and cryptographic random numbers in sequence number generation to prevent predictability. (SubRosa Cyber, 2024) 

This avoids network systems from being attacked based on vulnerabilities in the TCP protocol, such as TCP Sequence Number Approximation-Based Denial of Service attacks. (SubRosa Cyber, 2024)

The randomisation of sequence numbers, strong cryptographic key management needs to be implemented. This includes the employment of strong cryptographic key length and algorithms, rotation and revocation procedures of keys to ensure keys are protected from unauthorised access and disclosure. (Mehta, n.d.) 

The security practices contribute to a multi-layered security posture that not only protects against compromise by cryptography but also against other types of security threats. (Mehta, n.d.)

For defending against DDoS attacks, some of the mechanisms involve reducing the attack surface by deactivating mDNS services and also disrupting external traffic to the local link. (Altulaihan et al., 2022) Blocking specific Time to live (TTL) values on the basis of the network path length may also be considered for blocking spoofed attacks. (Denial-of-service attack, n.d.)

### **Bad Randomness** 
Cryptographic controls play a significant role in providing security against external threats, primarily those that emanate from "bad randomness." Bad randomness is due to the use of insecure random number generators that are not cryptographically secure, and it can lead to predictable cryptographic keys and susceptibility to being manipulated by attackers. This is provided for by the requirement that cryptographically secure pseudo-random number generators (CSPRNGs) be used when generating keys and initialisation vectors (IVs). (Open Web Application Security Project, n.d.)

For example, in generating RSA keys, if the random number used is not random, it may be compromised and attackers would have access to decrypt messages. This has been witnessed in malware like Reductor, where the random number generator of a browser was used to decrypt TLS traffic. (SecurityWeek, 2021)

To prevent such attacks, developers must:
Use widely accepted, secure algorithms such as AES-256 for encryption, RSA with secure padding for key exchange, and SHA-256 or higher for hashes. (Banach, 2025)
Prevent use of custom or legacy algorithms, especially those previously known to have vulnerabilities or with low entropy. (Banach, 2025)
Create encryption keys with sufficient randomness to make them unpredictable. (Banach, 2025)
Use secure key management systems and rotate the keys regularly in order to limit exposure. (Banach, 2025)
Utilise authenticated encryption over plain encryption to provide data confidentiality and integrity. (Open Web Application Security Project, n.d.)
Keep secret data in environment variables or secret vaults (e.g., HashiCorp Vault). (Monga, 2024)
Use secure, not legacy, algorithms like SHA-256. (Monga, 2024)

And the threat of quantum computing actually represents a significant threat to current cryptographic measures. Quantum computers, if used to full capacity, could in fact break the majority of the algorithms used in practice currently, including RSA and ECC, since they would factor large numbers efficiently with Shor's algorithm. (SecurityWeek, 2021)

As a countermeasure, quantum-resistant algorithms and quantum random number generators (QRNGs) are being developed and deployed. For instance, companies like Cambridge Quantum Computers (CQC) are offering quantum key distribution products that utilise quantum mechanics to generate truly random numbers. (SecurityWeek, 2021)

By embracing such cryptographic best practices and staying one step ahead of threats from around the corner, organisations can significantly enhance their security posture and defend against current and potential vulnerabilities 

### **Timestamp Dependence**
Cryptographic means are also crucial in mitigating external threats, including timestamp dependence threats. Timestamp dependence is where the execution or logic of a smart contract is intrinsically linked to the timestamp of the block that it is included in, and can be manipulated by validators or miners. (Bains, 2023) This can be exploited to interfere with contract outcomes, e.g., in gambling contracts where a miner will be able to manipulate the timestamp to suit their timely bet. (Bains, 2023)

To minimise timestamp reliance, block numbers can be made a unit of time by coders rather than timestamps since block numbers grow in a predictable way and are less prone to manipulation. (Bains, 2023) The addition of randomness to smart contract decision-making is another method of minimising predictability and susceptibility to manipulation. (Bains, 2023)
For time-constrained operations, the use of trusted external sources for validating timestamps can provide an added layer of security and integrity. (Bains, 2023)

Timing attacks are a side-channel attack of cryptography which are founded on differences in the time taken to perform cryptographic operations. Timing attacks can leak secret information, e.g., encryption keys, through examination of timing differences in operations. (Timing attack, n.d.) 

Cryptographic implementations have to be constant-time so that the time of execution is not dependent on secret values for timing attack resistance. (Intel, 2022) This may be achieved through techniques such as constant-time algorithms, in which operations are designed to be of the same time for all inputs. (Intel, 2022)

In addition, timing attacks can similarly be prevented through secure hardware tokens as well as side-channel attack-resistant algorithms. (Trowbridge, 2025) Such techniques prevent attackers from receiving key information on the basis of timing variations. 

Organisations can quickly shift to stronger encryption methods in reaction to newly arising threats by constantly testing cryptographic solutions and applying the principles of algorithm agility. (Sumner, 2024)


### **Short Addresses** 
Cryptography is required to help counterattack external attacks by ensuring confidentiality, integrity, and authenticity of information. Cryptography is the operation of converting information into an unreadable format by using algorithms and keys and leaving it there in an unavailable way for non-authorised users. (Sumner, 2024)

In effectively countering external attacks, the necessity of using good, up-to-date cryptographic algorithms and protocols is essential. Symmetric and asymmetric are a few of the examples which include symmetric cryptography, like the Advanced Encryption Standard (AES), employing a shared key for both encryption and decryption, and asymmetric cryptography, like RSA, employing a public key for encryption and a private key for decryption.  Apart from this, hash functions, like SHA-2, are used to verify data integrity by creating fixed-length output from any input data. 

Using cryptographic techniques, the Zero Trust model is based on the "never trust, always verify" principle. No device or user is considered trusted in this model, and robust access control, ongoing authentication, and least privilege concepts are implemented, constraining data exposure. 

Few of the most critical components of a Zero Trust environment include micro-segmentation, Identity and Access Management (IAM), and least privilege access. IAM merely blocks authenticated devices and users from accessing resources, and micro-segmentation divides the network into secure pieces, isolates workloads, and constrains lateral movement. 

Implementation of the models and methods includes adherence to best practice such as secure key management, regular key rotation, and the use of industry-accepted algorithms. Strategic planning, the acquisition of the correct tools, and constant education of users also have important roles to play in the prevention of solutions barriers to cryptographic sophistication and the move away from the old security paradigms. 

By combining robust cryptographic approaches with the Zero Trust model, organisations can enhance their cybersecurity stance, reduce the attack surface area, and augment data privacy and regulatory compliance. 

### **Race Conditions**
Race condition vulnerabilities occur when the outcome of a process is time- or order-dependent in a way that it can be manipulated by attackers with the ability to manage the timing of requests in a manner that causes unusual behaviour. (PortSwigger, n.d.) Cryptographic techniques and other security measures can be used to ensure the integrity and consistency of operations to reduce these vulnerabilities.

One of the most widespread methods of preventing race conditions is by using atomic operations, which ensure that areas of code which are critical in nature are run in a single, indivisible unit of work, eliminating interference from other processes or threads. (Joseph, 2024) It works most well for cases involving multiple threads or processes accessing shared resources.

Another key method is the use of locks such as mutexes, semaphores, and monitors to control access to shared resources. These mechanisms ensure that only one thread or process can utilise a resource at any one point, and so prevent conflicting actions. (GeeksforGeeks, 2024) Within Java, as an example, the synchronised keyword can be used to create blocks of code that will only be run by one thread at a time. (Imperva, 2025)

In addition to traditional synchronisation techniques, modern programming languages and libraries provide native thread synchronisation capabilities, which make it easier to write secure and reliable concurrent code.  Static code analysis tools can be used to identify potential race conditions in code so that they can be addressed before deployment. (Poston, 2021)

For web servers, single-packet attacks have been an efficient way to exploit race conditions by issuing multiple requests over a single TCP connection to ensure the server will execute them sequentially one behind the other in rapid succession. (PortSwigger, n.d.) It is particularly useful in reducing the impact of network jitter and internal delay, which optimise the likelihood of inducing a race condition.

In order to further avoid race conditions, the developers will have to stress thread-safe design so that functions could be executed in parallel without interference. (Poston, 2021) This includes avoiding the deployment of more than one store of data that could develop consistency problems and the use of atomic queries at the database level to manage query concurrency

### **Frontrunning**
Cryptography is utilised in a critical manner to deter front-running attacks within blockchain networks as well. One such method is the use of verifiable delay functions (VDFs) and aggregate signatures, and those are employed within the FIRST framework so that delays are enforced on transactions and there is safe verification kept intact. (Sariboz et al., 2022) VDFs are designed to be calculated in a certain amount of time, so that malicious agents cannot frontrun transactions by quickly executing their own. (Sariboz et al., 2022) The delay is statistically derived based on the usage of the network, providing a more responsive and efficient alternative to uniform delays. (Sariboz et al., 2022)

Another cryptographic technique is the utilisation of zero-knowledge proofs, through which the Injective blockchain secures sensitive information in transactions. The nodes on the Injective network have access to transaction data encrypted and zero-knowledge proofs but not the sender, recipient, or transaction amount. (Tripathi, 2023) The encryption technique is used to safeguard transaction details from visibility, hence maintaining the front-running risk low.

In addition to VDFs and zero-knowledge proofs, aggregate signatures are used to aggregate the verification result of a VDF proof, making verification more efficient and secure. (Sariboz et al., 2022) This cryptographic tool allows for multiple signatures to be combined into a single signature, which can be verified efficiently.

The BackRunner approach proposes a new solution with preemptive hijack and attack back-running to counter the attacks against smart contracts. This solution includes modulating the exploit used in the attack to the same or similar contracts before and after the attack to safeguard the assets. (Shou et al., 2024) In reducing adapting exploits as a program repair issue, BackRunner uses proven techniques to implement its solution into a full framework.

These cryptographic techniques, including VDFs, zero-knowledge proofs, and aggregate signatures, serve a critical purpose in combating front-running attacks and enhancing the security of blockchain networks. They provide an effective defence against malicious actors via delays, encrypting transaction data, and effectively authenticating transactions.

# **Conclusion**
Cryptography is an ever-evolving science, and techniques like multi-signatures, zero-knowledge proofs, and ring signatures bring new security and anonymity techniques. As already presented in this essay, multi-signatures enhance security by decentralising control, zero-knowledge proofs protect secret data without revealing it, and ring signatures ensure anonymity. Such techniques come with limitations like computational expense and operational sophistication. The constant threat of attacks such as reentrancy attacks, access controls vulnerabilities, and oracle attacks necessitates a vigorous and disciplined security strategy. 

Innovations in privacy-preserving technologies such as stealth addresses, private transactions, and homomorphic encryption illustrate growing efforts to secure user data in an ever-opened digital landscape. These efforts guarantee that even while processing or storing data, confidentiality is maintained. The continuous pressure by organisations like NIST for standardising threshold cryptography only underscores the necessity for distributing trust and making cryptographic systems more fault-tolerant. After everything else, there is a security strategy that is multi-faceted consisting of robust cryptographic practices supplemented with best contract design practices and regular audits that is needed. By uncovering the strengths and weaknesses of these technologies, we can build a more secure, private, and trusted digital foundation for the future.



###References
Abbas, S. H. (2023, June 28). Revolutionising Security and Privacy: A Deep Dive into Multi-Party Computation (MPC) and Threshold Cryptography. Medium. Retrieved from https://medium.com/@krayon_digital/revolutionizing-security-deep-dive-into-mpc-threshold-cryptography-89659a979320
Abbas, S. H. (2024, January 21). Privacy Coins and Confidential Transactions: The Next Frontier in Cryptocurrency Privacy. Medium. Retrieved from https://medium.com/@zee.associates001/privacy-coins-and-confidential-transactions-the-next-frontier-in-cryptocurrency-privacy-925ab50a89c3
ahmetw.eth. (2023, December 31). Smart Contract Security: Delegate call Function Attack Vectors. Medium. Retrieved from https://medium.com/coinmonks/smart-contract-security-delegatecall-function-attack-vectors-1c3b6879369c
Altulaihan, E., Almaiah, M. A., & Aljughaiman, A. (2022). Cybersecurity Threats, Countermeasures and Mitigation Techniques on the IoT: Future Research Directions. Electronics, 11(20), 3330. https://doi.org/10.3390/electronics11203330
Apple Machine Learning Research. (n.d.). Homomorphic Encryption. Retrieved from https://machinelearning.apple.com/research/homomorphic-encryption
Bains, A. (2023, August 15). Cryptography Attacks: 6 Types And Prevention Measures. CCN. Retrieved from https://www.ccn.com/education/cryptography-attacks-6-types-and-prevention-measures/
Banach, Z. (2025, May 15). Guide to cryptographic failures: A 2025 OWASP Top 10 threat. Invicti. Retrieved from https://www.invicti.com/blog/web-security/cryptographic-failures/
Bitpanda Academy. (n.d.). What are multi-signature wallets and how do they work? Bitpanda. Retrieved from https://www.bitpanda.com/academy/en/lessons/what-are-multi-signature-wallets-and-how-do-they-work/
Cobalt. (2024, December 3). Smart Contract Security Risks: Today's 10 Top Vulnerabilities and Mitigations. Retrieved from https://www.cobalt.io/blog/smart-contract-security-risks
Coin360. (n.d.). Ring Signature. Retrieved from https://coin360.com/glossary/ring-signature
CoinTelegraph. (2023, November 23). What is a multisignature wallet, and how does it work? CoinTelegraph. Retrieved from https://cointelegraph.com/learn/articles/what-is-multisignature-wallet
Cybersnowden. (n.d.). Homomorphic Encryption. Retrieved from https://cybersnowden.com/homomorphic-encryption/
Cypherock. (2025, January 21). Smart Contract Security: Best Practices for Writing Secure and Auditable Code. Retrieved from https://www.cypherock.com/blogs/smart-contract-security-best-practices-for-writing-secure-and-auditable-code
Denial-of-service attack. (n.d.). In Wikipedia. Retrieved August 5, 2025, from https://en.wikipedia.org/wiki/Denial-of-service_attack
Etugbo, J. (2025, March 25). Why Zero-Knowledge Proofs Are the Future of Blockchain Security. Built In. Retrieved from https://builtin.com/articles/zero-knowledge-proof-blockchain-security
Gao, W., Chen, L., Hu, Y., Newton, C. J. P., Wang, B., & Chen, J. (2019). Lattice-based deniable ring signatures. International Journal of Information Security, 18(3), 355–370. https://doi.org/10.1007/s10207-018-0417-1
GeeksforGeeks. (2024, May 22). Race Condition Vulnerability. Retrieved from https://www.geeksforgeeks.org/race-condition-vulnerability/
Hacker Noon. (n.d.). Blockchain Privacy-Enhancing Technology Series: Stealth Address (I). Retrieved from https://hackernoon.com/blockchain-privacy-enhancing-technology-series-stealth-address-i-c8a3eb4e4e43
Hara, K., & Tanaka, K. (2021). Tightly secure ring signatures in the standard model. Theoretical Computer Science, 892, 208–237. https://doi.org/10.1016/j.tcs.2021.09.022
Horbonos, P. (2021, August 3). 9 Most Common Smart Contract Vulnerabilities Found by Blaize. Blaize. Retrieved from https://security.blaize.tech/blog/9-most-common-smart-contract-vulnerabilities/
Imperva. (2025, July 11). Race Condition Vulnerability | Causes, Impacts & Prevention. Retrieved from https://www.imperva.com/learn/application-security/race-condition/
Intel. (2022, June 29). Guidelines for Mitigating Timing Side Channels Against Cryptographic Implementations. Retrieved from https://www.intel.com/content/www/us/en/developer/articles/technical/software-security-guidance/secure-coding/mitigate-timing-side-channel-crypto-implementation.html
Joseph, R. (2024, August 28). Understanding Race Conditions in Cybersecurity: Vulnerabilities, Attacks, and Prevention. Uproot Security. Retrieved from https://www.uprootsecurity.com/blog/race-condition-vulnerabilities-an-ultimate-guide
Khaliq, W. (2025, July 27). Best Privacy Coins: Discover The Top 5 Picks For Anonymous Crypto Transactions. CoinBureau. Retrieved from https://coinbureau.com/analysis/top-privacy-coins/
Kochan, F. (2025, March 18). Intro to Zero-Knowledge Proofs. QuickNode Guides. Retrieved from https://www.quicknode.com/guides/custom-chains/intro-to-zero-knowledge-proofs
LearnCrypto. (2024, August 6). What is multi-signature? Multi-sig wallets explained. LearnCrypto. Retrieved from https://learncrypto.com/knowledge-base/how-to-use-crypto/what-is-multi-signature
Lin, J. (2024, January 3). Multi-signature wallets: Are they right for you? SecuX. Retrieved from https://secuxtech.com/blogs/blog/multi-signature-wallets-are-they-right-for-you
Mehta, J. (n.d.). What is Cryptographic Failure? Real-life Examples, Prevention, Mitigation. Certera. Retrieved August 6, 2025, from https://www.certera.com/blog/what-is-cryptographic-failure-real-life-examples-prevention-mitigation/
Monero Project. (n.d.). Ring Signatures. GetMonero.org. Retrieved from https://www.getmonero.org/resources/moneropedia/rings-signatures.html
Monga, A. (2024, December 8). Cryptographic Failures: Understanding and Preventing Vulnerabilities. Medium. Retrieved from https://medium.com/@ajay.monga73/cryptographic-failures-understanding-and-preventing-vulnerabilities-91c8b2c56854
Muqeet, B. (2018, November 4). Cryptography Vulnerabilities - Guide for Beginners. PrivacyEnd. Retrieved from https://www.privacyend.com/cryptography-vulnerabilities/
NAD-CAB. (2025, June 5). What are Bitcoin Confidential Transactions? Retrieved from https://www.nadcab.com/blog/bitcoin-confidential-transactions
Nadiger, A. (2023, February 11). Various types of attacks on Smart Contracts. LinkedIn. Retrieved from https://www.linkedin.com/pulse/various-types-attacks-smart-contracts-amit-nadiger
naeemhasan588. (n.d.). Privacy and Confidentiality in Blockchain Development. Medium. Retrieved from https://medium.com/@naeemhasan588/privacy-and-confidentiality-in-blockchain-development-b13ed2fb8d7f
National Institute of Standards and Technology. (n.d.). Privacy-Enhancing Cryptography. Computer Security Resource Center. Retrieved from https://csrc.nist.gov/projects/pec
National Institute of Standards and Technology. (n.d.). Threshold Cryptography. Computer Security Resource Center. Retrieved from https://csrc.nist.gov/projects/threshold-cryptography
nfisign. (2025, May 14). Zero Knowledge Proof: Complete Guide and Applications. Retrieved from https://www.infisign.ai/blog/what-is-zero-knowledge-proof-zkp
Ogburn, M., Turner, C., & Dahal, P. (2013). Homomorphic Encryption. Procedia Computer Science, 20, 502–509.
Open Web Application Security Project. (n.d.). A02:2021-Cryptographic Failures. OWASP. Retrieved August 5, 2025, from https://owasp.org/Top10/A02_2021-Cryptographic_Failures/
Open Web Application Security Project (OWASP). (2023). SC01-Reentrancy Attacks. OWASP Smart Contract Top 10. Retrieved from https://owasp.org/www-project-smart-contract-top-10/2023/en/src/SC01-reentrancy-attacks.html
parth51199. (2023, August 7). Understanding MPC Wallets: Enhancing Security and Privacy in Cryptocurrency Management. dev.to. Retrieved from https://dev.to/parth51199/understanding-mpc-wallets-enhancing-security-and-privacy-in-cryptocurrency-management-4oa
PortSwigger. (n.d.). Access control. Web Security Academy. Retrieved from https://portswigger.net/web-security/access-control
PortSwigger. (n.d.). Race conditions. Retrieved August 5, 2025, from https://portswigger.net/web-security/race-conditions
Poston, H. (2021, January 6). How to mitigate Race Conditions vulnerabilities. InfoSec Institute. Retrieved from https://www.infosecinstitute.com/resources/secure-coding/how-to-mitigate-race-conditions-vulnerabilities/
QuickNode. (2025). A broad overview of reentrancy attacks in Solidity contracts. Retrieved from https://www.quicknode.com/guides/ethereum-development/smart-contracts/a-broad-overview-of-reentrancy-attacks-in-solidity-contracts
Random Oracle. (2018, July 22). Threshold ECDSA, key sharding and multi-signature: a comparison. Random Oracle Blog. Retrieved from https://blog.randomoracle.io/2018/07/22/threshold-ecdsa-key-sharding-and-multi-signature-a-comparison/
RareSkills. (2023, May 5). Smart Contract Security. Retrieved from https://rareskills.io/post/smart-contract-security
Rishabh Kumar. (2025, February 21). OWASP Smart Contract Top 10 Security Risks and Vulnerabilities: A Deep Dive with Real-World Exploits and CredShields' Contribution. SolidityScan. Retrieved from https://solidityscan.com/discover/owasp-smart-contract-top-10-security-risks-and-vulnerabilities-a-deep-dive-with-real-world-exploits-and-credshields-contribution/
RocketMeUpCybersecurity. (n.d.). Blockchain Oracle: Types, Uses, and How It Works. Medium. Retrieved from https://medium.com/@RocketMeUpCybersecurity/blockchain-oracle-types-uses-and-how-it-works-5a14dda69e44
Sariboz, E., Panwar, G., Vishwanathan, R., & Misra, S. (2022). FIRST: FrontrunnIng Resilient Smart ConTracts (Version v4). arXiv. https://arxiv.org/abs/2204.00955
Scarfone, K., & Cobb, M. (2025, June 26). 12 smart contract vulnerabilities and how to mitigate them. TechTarget. Retrieved from https://www.techtarget.com/searchsecurity/tip/12-smart-contract-vulnerabilities-and-how-to-mitigate-them
ScienceDirect. (n.d.). Ring Signature. Retrieved from https://www.sciencedirect.com/topics/computer-science/ring-signature
ScienceDirect. (n.d.). Ring Signature. Retrieved from https://www.sciencedirect.com/topics/computer-science/ring-signature
SecurityWeek. (2021, July 20). Mitigating Threats to Encryption From Quantum and Bad Random. Retrieved from https://www.securityweek.com/mitigating-threats-encryption-quantum-and-bad-random/
Shoemaker, P. (2025). What Are Zero-Knowledge Proofs? Identity.com. Retrieved from https://www.identity.com/zero-knowledge-proofs/
Shou, C., Li, S., Zhang, Y., Wu, Z., Chen, G., Zhang, S., Yang, M., Peng, Y., Liu, H., Li, T., & Guan, C. (2024, September 10). BACKRUNNER: Mitigating Smart Contract Attacks in the Real World. arXiv. https://arxiv.org/abs/2409.06213
Singh, D. (2024, December 27). Multisig wallets explained: Top picks, benefits, and use cases. Debut Infotech. Retrieved from https://www.debutinfotech.com/blog/what-are-multisig-wallets
Singh, O. (2023, December 15). What are stealth addresses, and how do they work? Cointelegraph. Retrieved from https://cointelegraph.com/explained/what-are-stealth-addresses-and-how-do-they-work
Smart Contract Security Field Guide. (n.d.). Oracle manipulation attacks. Retrieved from https://scsfg.io/hackers/oracle-manipulation/
Sodha, M. (2023, September 14). Introduction to Access Control Vulnerabilities. Cobalt. Retrieved from https://www.cobalt.io/blog/introduction-to-access-control-vulnerabilities
SoluLab. (2024, August 14). What is Zero Knowledge Proof Used For? Retrieved from https://www.solulab.com/zero-knowledge-proof-uses/
SubRosa Cyber. (2024, July 1). Understanding TCP Sequence Number Approximation-Based Denial of Service: A Dive into Cybersecurity Threats. Retrieved from https://www.subrosacyber.com/en/blog/tcp-sequence-number-approximation-based-denial-of-service
Sumner, M. (2024, February 17). Timestamped Encryption for Content Protection Explained. ScoreDetect. Retrieved from https://www.scoredetect.com/blog/posts/timestamped-encryption-for-content-protection-explained
Supermicro. (n.d.). Homomorphic Encryption. Retrieved from https://www.supermicro.com/en/glossary/homomorphic-encryption
Teng, D., Yao, Y., & Huang, C. (2025). Optimizing signature space performance in privacy-enhanced blockchains: novel ring signature solutions. EURASIP Journal on Information Security, 2025(1). https://doi.org/10.1186/s13635-025-00192-9
Timing attack. (n.d.). In Wikipedia. Retrieved August 5, 2025, from https://en.wikipedia.org/wiki/Timing_attack
Tripathi, P. (2023, August 23). Preventing Front-Running Attacks: How Injective Blockchain Architecture Resists Manipulation. Medium. Retrieved from https://0xprtk.medium.com/preventing-front-running-attacks-how-injective-protocols-architecture-resists-manipulation-3703c8013424
Trowbridge, E. (2025, May 27). Exposed by Time. Excuse Me Your Data Is Leaking. Retrieved from https://emmatrowbridge.github.io/Excuse-Me-Your-Data-Is-Leaking/2025/05/27/Exposed-by-Time.html
Turner, S., & Schaad, J. (2010). Multiple signatures in cryptographic message syntax (CMS) (RFC 5752). IETF. Retrieved from https://datatracker.ietf.org/doc/html/rfc5752
Unchained Crypto. (2023, September 14). What Are Ring Signatures? Retrieved from https://unchainedcrypto.com/ring-signatures/
Vaia. (n.d.). Privacy coins. Retrieved from https://www.vaia.com/en-us/explanations/computer-science/blockchain-technology/privacy-coins/
VPN Unlimited. (n.d.). What is Cryptographic Vulnerability - Cybersecurity Terms and Definitions. Retrieved from https://www.vpnunlimited.com/help/cybersecurity/cryptographic-vulnerability
Wikipedia. (n.d.). Cryptography. Retrieved August 1, 2025, from https://en.wikipedia.org/wiki/Cryptography
