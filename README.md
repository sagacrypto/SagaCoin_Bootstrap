# SagaCoin_Bootstrap
SagaCoin's bootstrap data file with script/batch file to make syncing faster.

Latest bootstrap data block height = 169983

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