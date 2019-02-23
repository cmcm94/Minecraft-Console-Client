MineSaga Console Client

This is an edited version of ORelio console client to fit better with Minesaga.
Feel free to ask me any questions.

TO DOWNLOAD GO TO TOP RIGHT [CLONE OR DOWNLOAD] AND CLICK DOWNLOAD ZIP, EXTRACT TO A FOLDER.

Currently setup for autojoin kingdom realm with autosell off
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
