This project proposal entails the development of a blockchain-based system to monitor and 
oversee funds allocated for government infrastructure projects. This decentralized ledger 
incorporates features for budgeting, reporting, and authorization. Its architecture ensures 
transparency, immutability, and auditability of all transactions, thereby mitigating the risk of 
corruption and misallocation of resources. The system is designed for user-friendly 
navigation, while also prioritizing a robust security framework to safeguard sensitive financial 
information.
Problem Background
Governments globally have grappled with the pervasive issues of corruption and financial 
mismanagement, particularly concerning infrastructure projects. Numerous high-profile 
cases highlight the alarming trend of large-scale corruption, with billions of rands being 
misappropriated for projects that remain incomplete. This unfortunate reality has not only 
eroded public trust but has also engendered a profound lack of confidence in the 
government's capacity to effectively oversee and manage such critical initiatives.
To confront this pressing challenge, there arises a critical need for a robust system that 
introduces transparency, immutability, and auditability into all financial transactions 
associated with infrastructure projects. This system serves as a direct response to the 
prevailing issues, aiming to restore faith in the government's ability to handle public funds 
responsibly.
Several existing solutions attempt to tackle the issue at hand, yet none comprehensively 
address the problem. Some governments have opted for financial management systems, 
offering a certain degree of transparency and reporting. However, these solutions tend to be 
intricate and challenging to navigate, lacking complete immutability or auditability. On the 
other hand, blockchain-based systems have been proposed, yet they often prove too 
intricate for government officials to effectively utilize.
In response to these shortcomings, the proposed system strives to bridge the gap by 
presenting a simplified, user-friendly interface. The intention is to streamline the user 
experience for government officials while concurrently upholding the essential features of 
blockchain technology, such as security and immutability. This approach aims to provide a 
solution that not only meets the complex demands of financial oversight but also ensures 
accessibility and ease of use for those responsible for managing government projects.
Solution
I am planning to develop a blockchain system that will facilitate communication between 
government officials and organizations seeking tenders or contracts for government projects. 
Both government officials and potential contractors will be required to log in to the system 
whenever they need to exchange project-related information, such as financial transactions 
and project specifications. When an official initiates a transaction to a contractor, the 
transaction will undergo validation by all participants in the blockchain network. If 
successfully validated, it will be permanently recorded in the blockchain, as will transactions 
initiated by the contractor. This ensures a comprehensive transaction history, readily 
available for investigations into project-related financial activities. Any contracts requiring 
enforcement will be automatically executed through smart contracts, preventing any 
participant from altering the contract to conceal potential corruption.
Since I recognize the imperative to implement a blockchain system, leveraging its potent 
features, include:
Decentralization:
This eliminates the dependence on a single authority for information storage and 
management, mitigating the risk of cyber attacks leading to data loss and the compromise of 
crucial evidence.
Immutability:
Once data is added to the blockchain network and recorded, its alteration or deletion 
becomes exceedingly challenging. This feature ensures that individuals engaged in 
corruption cannot manipulate or conceal evidence of their misconduct.
Transparency:
The entire transaction history is stored on the blockchain network and is accessible to all 
authorized participants. This transparency is crucial, as it persists even through changes in 
officials, providing an ongoing record of transactions.
Security:
Utilizing cryptographic techniques such as hashing enhances transaction security and 
controls access to the blockchain. This robust security measure significantly reduces the 
likelihood of successful cyber-attacks.
Novelty
The problem of corruption is not an easy problem to capture, because before one can say 
that something is corruption there has to be enough evidence to prove that, otherwise what 
may be corruption, due to lack of enough evidence, someone may say that its something 
that was planned to happen and therefore is not corruption. The problem itself is not new 
and unusual, but the way it has not been so easy to catch those involved in it within a short 
period of time makes it a novelty. The novelty of my proposed system also lies in its 
simplicity and ease of use. While there are existing solutions that address some aspects of 
this problem, they are often too complex for the average user. By making the system simpler, 
I hope to make it more accessible and easier to adopt. Additionally, I am proposing a new 
approach to immutability, using a hybrid solution that combines both centralized and 
decentralized approaches. This innovative approach is anticipated to heighten the security 
and reliability of the system, all the while ensuring a friendly and approachable user 
interface.
How it is novel
The innovation in my proposed system stems from its unique combination of simplicity and 
immutability, a synthesis not found in existing solutions. While some systems offer a degree 
of immutability, they tend to be overly intricate for widespread user adoption. Conversely, 
user-friendly systems often lack the robust immutability necessary for certain applications. 
My proposed system bridges this gap by offering both characteristics. Furthermore, the 
novelty of the system extends to its approach in addressing corruption. Many current 
strategies primarily emphasize enhancing transparency and oversight, which, in isolation, 
may not be sufficient to deter corruption. The distinctive aspect of my proposed system lies 
in its provision of not only transparency but also immutability. This dual feature makes it 
significantly more challenging for corrupt practices to occur. The immutability aspect adds an 
extra layer of security by rendering it arduous to falsify or alter records, while transparency 
ensures heightened accountability. Together, these elements create a formidable deterrent 
against corrupt activities.
Logic
In terms of logical structure and intricacy, I propose the implementation of a three-layer 
architecture. The initial layer would encompass the front-end interface, constructed using the 
Spring MVC framework. This choice ensures a responsive and user-friendly interface for 
enhanced user experience. The second layer would constitute the service layer, responsible 
for executing the system's business logic. This encompasses functions such as adding new 
transactions, validating transactions, and updating the blockchain. The third layer would be 
dedicated to the database, serving as the repository for the blockchain and pertinent data.
In terms of data structures, the key data structure would be the blockchain itself. The 
blockchain would be implemented using a linked list data structure. Each block in the chain 
would contain a hash of the previous block, a timestamp, and a list of transactions.
To fortify the system, several external libraries would be incorporated, including:
Spring Security: A robust security framework for safeguarding the system, encompassing 
user authentication and access control.
Hibernate: An object-relational mapping framework facilitating the seamless translation of 
database structures to Java objects within the system.
Jackson: A JSON processing library instrumental in serializing and deserializing Java objects 
to and from JSON format.
JUnit: A unit testing framework pivotal in assessing the robustness and reliability of the 
system's code
