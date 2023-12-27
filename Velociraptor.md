A DFIR (Digital Forensics and Incident Response) Tool

To run the Velociraptor executable, download in a VM and run via command prompt

![Screenshot 2023-12-27 145734](https://github.com/hetp1/Cyber-Tools/assets/108355131/85ed70b0-62e3-4a33-beb8-689c686ccd76)

Web Gui will open in the default browser

Configure Velociraptor Server (Keep Defaults for test purposes)
![Screenshot 2023-12-27 152925](https://github.com/hetp1/Cyber-Tools/assets/108355131/76b6adc7-e451-49ee-ba25-a20c8aba256c)



Once its configured, you should see client and server config files in the same directory
![Screenshot 2023-12-27 153009](https://github.com/hetp1/Cyber-Tools/assets/108355131/60515d99-8edb-4557-ad44-2856a11e08d3)


Run with 
          
          velociraptor-v0.7.1-1-windows-amd64.exe gui 

and change/edit root or admin password for security purposes

To add a machine to the Velociraptor server run the executable on the machine using the command prompt:
  
        velociraptor-v0.7.1-1-windows-amd64.exe --config client.config.yaml client -v

View the connected client under the show all drop-down menu 

![Screenshot 2023-12-27 154047](https://github.com/hetp1/Cyber-Tools/assets/108355131/f9a1d695-a670-469e-80ed-5e5e6ce8d01e)


