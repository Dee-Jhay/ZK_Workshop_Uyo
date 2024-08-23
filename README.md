# Moov_bootcamp Uyo
This is the overview of what I learnt on aleo blockchain using the leo language

# Installation
I am using Windows Os, so I had to use the Microsoft Visual installer so I could install Rust. After installing rust and ensuring that the Visual Studio Installer has been downloaded successfully, i ran this command on my terminal, (cargo install --path .), this to install Leo and to make the Cargo cli available.

then I cloned the Leo programming repo https://github.com/ProvableHQ/leo and switched to the testnet-beta branch

we created three programs and deployed them. Since the cargo install --path . was not complete, i made use of playground throughout the bootcamp. 
https://github.com/user-attachments/assets/1a37be7e-d8ec-4218-ba45-f151b23df61f

# Workshop 1
The first program was a simple Leo progam that add two variables together and mine was deployed here. we were to print Hello world

leo run main 3u32 2u32. Where main =》transition function name, 3u32 2u32 is the inputs. since i used playground, on the examples i clicked on hello world then move to the build folder and click main.aleo then navigated to the developer tools by using inspect. i copied the code and pasted it here https://demo.leo.app/deploy for deployment, i set the gas fee for the transaction and it was confirmed and deployed.

https://github.com/user-attachments/assets/2cb17ff9-5cf0-4462-bf25-912f0bb71c8e
https://github.com/user-attachments/assets/50790ac1-8e07-4c40-af08-eba99f8fb12e

https://testnet.aleoscan.io/transaction?id=at1znj3afmawu43yt3659t8dsaep397ey42yf3ylyel6s4y4y4nqygqrzl5nl

# Workshop 2
The second program was create a token. We used the mint and transfer functions(transitions) then deployed the token to the testnet but since i used the playground, i navigated to the examples and picked simple_tokens

1st Command : leo run mint <type_aleo_address> <type_amount>u64

2nd command: leo run transfer "<Token_Record>" <to_address> <amount>u64 We were able to use the generated record from 1st command to input into the second command's first input and then our to address and amount

https://testnet.aleoscan.io/transaction?id=at1j9mu93zzp9w8ykennttlzuy5gtf4gc8nlsee2r69wehclzkl3czsdlkdnr

# Workshop 3
leo run combine_hash_owner_receiver <type_your_address> <type_friend_address> This has only 2 inputs where first input is owner address (self.caller) and second input is the receiver address. i changed the default reveal key in the env. and i inputted mine. went to the deployed section and deployed it.
https://github.com/user-attachments/assets/a91cc282-3f0b-4c0e-8c84-e24e2652885d

https://testnet.aleoscan.io/transaction?id=at1pygdxmlxply2ch5vylltp328wdp574jlpwt8y9tnv8vtthjf05xqkzly7e


# Leo Wallet Activities
https://github.com/user-attachments/assets/a3be4df7-a624-4dd1-9b7f-f4e3655f9b22


