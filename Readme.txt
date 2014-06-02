This file has the instructions on how to run the project Timezone. 

Installing the program
0.git clone https://www.github.com/rn17/Time
1.su -
2.Change directory to time
3.make install
4.make

The Makefile has the command to install xinetd. But if it fails to install the user can install using 
yum -y install xinetd 

Running the program

1.Basic command line

Step1, Type: main
Step2, Give arguements on command line on the next line with space(for example): Europe Moscow

2.GUI with Localization(Language: Hindi)

Step1, Type: main_gui
Step2: Type 1 for Hindi, Type 2 for English in GUI
Step3: Type Continent, for example: Australia
Step4: Type City, for example: Perth
Step5: The time and date is displayed in the chosen language

3.Network 

Step1: Type: nc localhost 8888 (If this does not work use this command :  /etc/init.d/xinetd restart   )
Step2: In next line type(for example): Europe Paris
Step3: The time and date is displayed.
Step4: Type main_network_gui
Step5: Type(for example)  Asia Kolkata
Step6: The corect time and date is displayed by network application


