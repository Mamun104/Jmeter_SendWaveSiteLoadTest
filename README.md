# Jmeter_SendWaveSiteLoadTest

# TPS(Transaction Per Second)

TPS(Transaction Per Second) = Number of users/Ramp-up period (seconds)
                            = 3200/600
                            = 5.3333


# Prerequisite

1.Install jdk 8 or any LTS version

2.Download and extract Apache Jmeter 5.4.2 or any latest version

3.Configure JAVA_HOME and Jmeter Home

# How to run this project
 
  1. clone the report

  2. Run CMD in the root folder

  3. Give following command:

            jmeter -n -t SendWaveDemoSiteLoadTest.jmx -l log.csv -e -o Reports
   
   
   ![jmeter_2](https://user-images.githubusercontent.com/78067017/154069816-697ec1cc-68cb-4876-abba-5c6eda486e60.PNG)
   
   ![jmeter-3](https://user-images.githubusercontent.com/78067017/154070824-f70cd7f2-4f89-4b3d-a2d3-b36f648f40ae.PNG)


   
   
   
