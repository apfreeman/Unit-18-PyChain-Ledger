# PyChain Ledger

![alt=""](Images/application-image.png)

I am a fintech engineer working at one of the five largest banks in the world. I have recently been promoted to act as the lead developer in their decentralized finance team. I have been tasked to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

I have made the following updates to the the basic `PyChain` ledger structure:

1. Create a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2. Modify the existing `Block` data class to store `Record` data.

3. Add Relevant User Inputs to the Streamlit interface.

4. Test the PyChain Ledger by Storing Records.


# Pychain - Streamlit Interface

I have tested my complete `PyChain` ledger and user interface by running my Streamlit application and storing some mined blocks in my `PyChain` ledger. I have then tested the blockchain validation process by using my `PyChain` ledger. To do this, I completed the following steps:

1. In the terminal, navigate to the project folder where I coded this assignment.

2. In the terminal, run the Streamlit application by using `streamlit run pychain.py`.

3. Enter values for the sender, receiver, and amount, and then click the Add Block button. Do this several times to store several blocks in the ledger.

4. Verify the block contents and hashes in the Streamlit dropdown menu. 

5. Test the blockchain validation process by using the web interface. 

![Application Walk Through](https://github.com/apfreeman/Unit-18-PyChain-Ledger/blob/main/Images/capture.gif?raw=true)

## Pychain - Blockchain

The following is a screenshot of the Streamlit application page, which details a blockchain that consists of multiple blocks. 

![Blocks](https://github.com/apfreeman/Unit-18-PyChain-Ledger/blob/main/Images/blocks.PNG?raw=true)

## Pychain - Validity 

The following is a screenshot of the Streamlit application page, which indicates the validity of the blockchain. 

![Validation](https://github.com/apfreeman/Unit-18-PyChain-Ledger/blob/main/Images/validate.PNG?raw=true)
