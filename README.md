# Blockchain-based-ledger-system


## Overview

The PyChain Ledger System is a blockchain-based ledger application designed to enable secure and efficient financial transactions between users . This system leverages blockchain technology to ensure the integrity and verifiability of data within the ledger. With a user-friendly web interface, the PyChain Ledger System facilitates the transfer of money between senders and receivers, while providing a transparent mechanism for verifying transaction history and ledger integrity.

## How to use

This application should be ran through your command prompt or terminal utilizing the 'streamlit run' function. Within the terminal or command prompt interface navigate to the folder where the 'pychain.py' file is saved and enter 'streamlit run pychain.py'. You will need to pip install the 'streamlit' library to call the function. This will open the aformentioned web interface with several input paramters and data points. The following are individual descriptions of what you'll find.

  Sender ('Withdrawal Address') ~ This is the address where the cryptocurrency will be withdrawn from similar to your checking account number & a posted withdrawal. 
    Must be a string of Letters and Numbers
  
  Receiver ('Deposit Address') ~ Just like the purchase of a merchants product or service and their account posting a deposit, this will set the cryptocurrency deposit address.
    Must be a string of Letters and Numbers

    Test address's:
      0x701fc37f6a595c3D31e23842206c6447322567e0
      0x7105a631DBf7ee77E6327198e6d02565C93290Ae
      0xfCb6c3b85246a4B06A2547C9dA583c907FC3CE8D
      0x1Ca2b8a59A7E8Ab590a0dd01eB0cf46F7170D197
      0x8c84E3C0822F3806d2d2dee4bE0Ac686D48c64cb

          
  Amount ~ Should be an integer (Whole Number)

  Block Difficulty ~ The Block Difficulty slider allows you to adjust the difficulty for miners to mine the block to add it to the blockchain. Crucial in adding security and     stability to the blockchain. High difficulty ensures that it is computationally demanding to mine new blocks, which helps prevent malicious actors from easily adding fraudulent transactions or reorganizing the blockchain.

Validate Chain ~ Feature of blockchain empasizing decentralization. The following image describes the fundemental principle of blockchain validation. ![image](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/5369e850-a6de-4c23-9bc0-3b2b99d66bd8). A hash is a fixed-length alphanumeric string, which is produced by a hash function based on the contents of the block and a nonce. This is a complex process as it involves millions of computers (Network Validators) validating each block as theyre mined and added to the blockchain. The Validate Chain button in the Web application makes you the validator ensuring that the blocks hash matches the previous hash before its addede to the chain.

## Block Inspector 

Provides additional data on the designated block.

creator_id int ~ The ID of the creator of that block. 

nonce int  ~ Reported Nonce value
  The nonce is a number that miners change repeatedly to get different hashes until they find one that is below the target threshold set by the block difficulty.

prev_hash str	~ The previous blocks hash

record str ~ Shares a overview of the transaction that took place

timestamp str	~ Time stamp of the blockis addition to the blockchain.

hash_blockmethod  ~ Method to compute the hash of the block.

Below you will find several examples of test transactions, Block Inspector data, as well as chain Validations
![Block_1](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/2cde52e1-2aea-4559-b22c-84a2b97010ab)
![Block_2](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/dacb7089-5e63-44e1-9741-41de133bbffb)
![Block_3](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/a853c6c2-855b-436d-b91c-bf2d2ad8f4f3)
![Block_4](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/113ca78b-65c1-4146-96a5-80ac070d3922)
![Block_5](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/4f9aac37-0b35-4f7c-baae-8ac488478017)
![Block_6](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/53b02566-4a5b-43de-9627-7ca032703650)
![Block_7](https://github.com/Gino-Petrosian/Blockchain-based-ledger-system/assets/136781611/f4c1f583-a90e-43c9-9487-51a7cd43896a)

In the 'Blockchain transaction web application' folder, you will find a excel spreadsheet showing the blockchain ledger.





  
