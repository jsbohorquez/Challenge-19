# Challenge-19
Cryptocurrency Wallet

## Overview
This program application [fintech_finder.py] allows the user to hire a FinTech professional by selecting a candidate, viewing their hourly rate (in Ether), and selecting the amount of time in hours for hire. Once user has made selections, they will be able to send a transaction to chosen candidate's cryptocurrency wallet. Transaction information will be recorded and shown through Ganache application (screenshots below)

## Technologies Used
The libraries and dependencies used in this program are listed in the first cell of the program which are: streamlit, dataclasses, typing, as well as additional functions from accompanying [crypto_wallet.py] file. 

## Program Layout
This program is divided into the following parts:

**Part 1** - fintech_finder.py code
            This file contains all functions and structure for the interactive structure of the streamlit application.
            Within it are functions which calculate wage of selected candidate in Ether based on 'number of hours', allows for sending transaction to candidate, creates a record of transactions, adds the information to a block and ultimately binds information blocks together. In addition, blockchain update functions as well as structural code for streamlit are included within the file. 
            
**Part 2** - Streamlit Application
            User will run the application using the fintech_finder.py file. Once application is open, user will view their current Ether balance on the left hand sidebar. User will select candidate from drop down menu, input number of hours, and total wage in Ether will be calculated based on each candidate's hourly rate. User will then select 'send transaction' button to confirm selection and send Wage amount in Ether from their crypto wallet to candidate's wallet. Transaction will populate and be visible in Ganache application for verification. 

            The following images show fintech_finder application running:
![Screenshot (8)](https://user-images.githubusercontent.com/101238359/181688928-e1305236-02ef-4f69-a5de-796b36fd7141.png)
![Screenshot (9)](https://user-images.githubusercontent.com/101238359/181688934-d1c4c605-ea50-4c30-a006-c682a2a577ba.png)

            The following image shows account in Ganache:
![Screenshot (10)](https://user-images.githubusercontent.com/101238359/181688935-febcbb0a-e4ca-4cd3-af4f-73ee3d482d28.png)

            The following image shows transactions in Ganache:
 ![Screenshot (11)](https://user-images.githubusercontent.com/101238359/181688936-6dae5019-a875-49c6-8732-b41ad7125797.png)           

## To Run Web APP
-Download program packages, and files under 'starter_code' folder
-Access file through terminal, run command: streamlit run fintech_finder.py 



## Author
Juan Bohorquez
