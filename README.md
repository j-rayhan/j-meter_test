# j-meter_test

##  Step - 1

1.  Check java is installed on your system
        `java -version`
OR install [java](https://www.youtube.com/watch?v=FqpmH8MVO6A&list=PLhW3qG5bs-L_qj1L5hnHvJYeFpQ_g4UuU)

2 : Download Jmeter from internet

3 : Unzip and keep Jmeter folder at any location

4 : Start Jmeter
             **Windows** - jmeter/bin - jmeter.bat
             **Mac** - open terminal - jmeter/bin - sh jmeter.sh

## Step - 2

 1. Add Chrome [extension](https://www.blazemeter.com/)

 2. Go to gmail.com

 3. Click on extension // add image 

 4. Input the Name && Click on Start Recording button

 5. Insert credential

 6. Log in Success

 7. Stop recording

 8. Click Save
        
 * Select script(s) to save -> jmeter only(JMX)

 * Select domains to include in your JMeter script

        1. google.com
        2. clients6.google.com
        3. click save

## Step - 3

    1. Run Jmeter App

    2. Open The dounloded file *.jmx
        File -> Open -- select file (**/Downloads/*.jmx)

    3. Select 
        * Mouse Right Click on __File_name__ -> Add -> Listener -> View Results Tree
        * Mouse Right Click on __File_name__ -> Add -> Listener -> View Results in Table

    4. Click on __Thread Group__
        * Input Number of Threads (users): 100
        * Ramp-Up Period (in seconds): 10
        * Loop Count: 1
    
    5. Click on Run -> Start

## Step - 4

    1. Create Folder in jmeter/bin/examples/__folder_name__/

    2. Create Folder in jmeter/bin/examples/html/__folder_name__/__folder_name__/

    4. Run this Command
    ```
    ./jmeter.sh -n -t ../backups/*.jmx -l ./examples/__folder_name__/__file_name__.csv -e -o ./examples/html/__folder_name__/__folder_name__/ 
    
    ```
