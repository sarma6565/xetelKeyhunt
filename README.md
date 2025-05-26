This is just controller for Keyhunt and it´s beta version.

Every suggestion for improvement or anything else is welcome, contact me->  opsalter@outlook.com 

Statistics website: https://xetel.duckdns.org

How to use?

1. Enter Your btc address so it can track number of ranges scanned by user(it´s not necessary)
 - Start xetelBitcoin.exe

2.You will be prompted to enter some values like -k 128 (128 takes something like 3.5gb RAM, 4096 takes 32gb RAM),
  -t 8 stands for CPU threads, I usually set that half from CPU threads. ex. Ryzen CPU with 8 cores/16 threads, set 8.
  It usually takes about up to 10 min to create bloom with -t 8 -k 256 on mid-range system.
  Scanning speed depends on you system and settings from before.
  To stop scanning and all processes press "S" while in program.

3.Wait for keyhunt to generate Bloom filter and soon after that keyhunt will start scanning, every next time after
  starting xetelBitcoin you will be prompted to enter values for -t -k, remain it same so you won´t need to wait
  for bloom filter regeneration.

4. After closing software make sure to kill keyhunt.exe in your processes if there are any.

Ranges are stored and pulled from database, and this software act as "solo pool, private key doesn´t leave your PC".
  If you found this project useful i accept donations to keep server alive, but that´s not necessary 
  bc1q89j039meqtn6hr225mhhmavyn0vusyeygdzccc

5. To reset settings delete client_config.json to change btc addres or keyhunt_config.json to change bloom generation settings.

  If somebody who gets to find a private key using this software and is willing to share
    some amount of reward with all users that have been contributing to the pool send some cut to the btc address-
    1NMCMohQJHS9kYhyk375dhY8yqBMPnfUD4
  
 -- I will then share that cut among users that have been using this software. --
