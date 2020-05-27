# PowerSploit
This readme will describe the steps to start working with the Powersploit powershell module for pentesting Active Directory instances.
To get started following steps are required:

1: Two windows machines

2: One windows 2003/2008/2012/2016 Server with Active directory configured.(The server machines)

3: One windows XP/7/8/10 machine attached to the windows machine created in step 2.(The client machine)

4: Download the powersploit module into the Client machine

5: Open a powershell windows(with admin rights) on the client machine

6: Run the following command in the powershell command:
   Set-ExecutionPolicy Bypass
   
7: Find the powershell module path by running the following command in the powershell prompt:
  $Env:PSModulePath
  
8: Copy the powersploit modules folder under the directorty structure found in Step 7

9: Run the following command in the powershell prompt to import powersploit:
   Import-Module PowerSploit
   
10: To confirm if the powersploit is imported successfully run the following command:
   Get-Command -Module PowerSploit
