# MineSaga-Console-Client
MineSage Console Client (Auto reconnect, join realm, check realm, sell all)

This is a patched version of the client from minesaga fourms: https://github.com/DylanRR/MineSaga-Console-Client
fixed reconnect issues and disabled autoreply.

TO DOWNLOAD GO TO TOP RIGHT [CLONE OR DOWNLOAD] AND CLICK DOWNLOAD ZIP, EXTRACT TO A FOLDER.

Currently setup for kingdom realm with autosell on.
_______________________________________________________________________________________
Setting up your account:

Use notepad to open MinecraftClient.ini
look for the lines 
  login=
  password=
add your email to the account and password after each = sign
save the file
________________________________________________________________________________________

Changing relog from kingdom to another realm:

Use notepad to open AfkRealm.txt
edit "send /joinqueue Kingdom" to your realm
send /joinqueue Space/Jurassic/etc

________________________________________________________________________________________

Disable Autosell or Auto rejoin

Use notepad to open Tasks.ini
To disable a task use the # before every line
ex: 
    #Sell all
     triggerOnInterval=true
     timeInterval=5
     script=AltVoidChest.txt
 becomes:
    #Sell all
    # triggerOnInterval=true
    # timeInterval=5
    # script=AltVoidChest.txt
I reccommend doing this if you have nothing to sell.
_______________________________________________________________________________________
