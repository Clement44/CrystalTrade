### **How to set up your project**

STEP 1 : 
A project developer complete the following Typeform : https://8qs718i444z.typeform.com/to/PLdXgH1F
STEP 2 : 
An admin will check the information on the Carbon registry (like VCS here) to check that the project developer has really retired its carbon credits from the registry
and then complete this form : https://8qs718i444z.typeform.com/to/KgWrzklJ
STEP 3 : 
Automatically, Zappier will create the related ERC1155 with : 
- A token
- A "Retired Token" 
And each of them with the number of carbon credits retired from the carbon registry


### Problem

When we see what is happening to the Earth's climate, we have understood that we need to act quickly by lowering our carbon emissions and be more respectful toward our nature. Eco credits are a solution to develop the Regenerative Finance. 
Starting with carbon credits, Carbon offsetting is a complex and controversial topic, and has serious limitations. Indeed, legacy carbon markets are broken. Voluntary carbon markets are fragmented, opaque, rife with middlemen and, as a result, suffer from questionable quality and lack transparent price signals.



### Solution

We bring a lot of traceability into the voluntary market. Indeed, since 2016, Crystalchain has developed a traceability expertise in different industries (food, luxury, circular economy). 
Today, we are bringing our traceability expertise into the carbon credit market using the blockchain technology.

Our solution is using an ERC1155 to keep the traceability of all the information around the project (where is the project, ESG audit, PDD verification, ecosystem around the project...) and the carbon credit issue on a carbon registry like VCS. 

First, we needed a way for anyone to bring credible offsets from existing legacy offset registries onto smart contract-enabled blockchains. To achieve this, we've developed an ERC1155 that is doing the link between tokenization and the carbon registry. When the user ask for a retirement of its carbon credits from the carbon registry, a member of Crystalchain will check that he has really retired his carbon credits and then, the user will receive token representing the tokenized carbon tonnes. 

Then, when the user decides to offset (retire) its emissions, the related token is burnt and a NFT is created called "Retired NFT", taking all the information about the project but that is impossible to transfer and will prove the offset of the user for the whole life. 



### Team and comments

Antoine & Clément are part of Crcreditystalchain (discord : Cc#1202). 
We learnt a lot about Starton (we both ask a lot of questions in Gather) but also we learnt how to industrialize the process using Zapier. 
We have elaborated the design of the architecture on Monday and then implemented it until Friday. Really happy to have discovered Starton and the wide range of services it provides ! 

### Project Submission

Features of the solution : 
-CREATE() : Once the carbon credits are retired from the carbon registry, we call a custom function which is "create" and that create the related ERC1155 semi-fongible token with the following parameters (address initalOwner, uint256 initialSupply, string tokenUri, string retiredTokenUri, bytes data). Initial supply is the number of carbon credits retired and for the Uri, it's where we do the link with all the traceability of the carbon credits and its issuance from a project.
- RETIRE() : Then, when a user wants to retire its carbon credits (it means to offset its emissions), we call this function and as an input, it generates a ERC1155 semi-fongible token immutable (like a certificate). 


- Demo of the project : 


- Partners : 
We have used the **Starton** API on the **BNB Chain** blockchain. We were planing to use **Ledger** for the wallet and **iex** for the marketplace but did not had time to do it. 
