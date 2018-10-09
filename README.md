# SagaCoin_Bootstrap
SagaCoin's bootstrap data file with script/batch file to make syncing faster.

Latest bootstrap data block height = 276226

NOTE:-

We just notice that github supports files larger than 100MB, so we decided to put bootstrap file back to github releases instead of google drive.

HOW TO USE:-

1) Download latest bootstrap file from https://github.com/sagacrypto/SagaCoin_Bootstrap/releases.

2) Unzip downloaded file to same your SagaCoin executable file's folder.

3) Run the following script/batch file according to your Operating System and wallet mode:-

   [Windows] Saga_Loadblocks_Windows_GUI.bat
   
   [MacOS X] Saga_Loadblocks_Mac_GUI.sh
   
   [Linux (CLI mode)] Saga_Loadblocks_Linux_CLI.sh
   
   [Linux (GUI mode)] Saga_Loadblocks_Linux_GUI.sh
   
   
   
OR if you are good in command prompt, you may just run the wallet with parameter as following:-

   ./sagacoind -loadblock=blk0001.dat
   
   [we use linux CLI wallet in this example, you may replace it with the SagaCoin wallet executable filename]
   
   
-----------------------------------------------------------------   
   
ERROR SOLUTION: If you encounter error message of "Error Loading Block Database", here is the solution:-

   Remove data folder (Remember to backup your wallet.dat file first if you have coin in your wallet) and re-try again with step 3 above.
   
   Here is the data folder location:-
      Linux : ~/.SagaCoin/
      Windows : C:\Users\[username]\AppData\Roaming\SagaCoin\
      Mac : /Users/[username]/Library/Application Support/SagaCoin/
      
      