# EVE-NG Community version 5.0.1-13
### This is Edited EVE-NG File for Network engineers
##### Web username : admin
##### Web password : eve

##### SSH/SFTP username : root
##### SSH/SFTP password : eve


#### Instructions : 
1. Open Download.txt file to download the rar file from my google drive
   - https://drive.google.com/drive/folders/14KHmDJvKycaheBOxyiUGITxyGnESG7EV?usp=sharing

2. Unzip the file
 
3. Download and install the vmware player workstation from
   - https://customerconnect.vmware.com/en/downloads/info/slug/desktop_end_user_computing/vmware_workstation_player/17_0

4. Open Vmware player , go to File , go to OPEN , Select the OVA file (from the Extracted file you downloaded ) in to the Vmware player

5. Choose "Edit virtual machine settings"

6. Select the correct Memory and CPU depend on your computer resources , for "Network adapter" make sure to choose "NAT"

7. After that press OK and run the VM

8. You will see the ip address in the black screen , type this IP address in you browser (recommended to use firefix)

9. Type the username : admin , password : eve

10. Download and install the EVE Windows Client Side from the Google Drive (This app include Wireshark also) :
    - https://drive.google.com/file/d/1avmi8SyQLKwTDIDciQRpAS1GxB6eoYY-/view

11. Download and install Putty (depend on your system x86 or 64) to enter SSH to device :
    - https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

12. create your own lab and have fun
# YAML

- **Y**et **A**nother **M**arkup **L**anguage
- YAML it is very easy for humans to understand, read and write when compared to other data formats like XML and JSON.
- Extension is “yaml” or “yml”
- Use this website to validate the yaml code —> https://www.yamllint.com/

<aside>
💡 The indention spaces number is up to you (the standard add 2 spaces) but must be identical

</aside>

<aside>
💡 Every YAML file **optionally (May or May not)** starts with `---`  and ends with `...`    (Focus on space after each one of them)

</aside>

## key-value

- YAML uses simple **key-value** pairs to represent the data (Just like dictionary) , There should be space between`:` and value.

```yaml
--- # Optional YAML start syntax 

james:              **# Dict in Dict** 
		name: james john 
		rollNo: 34 
		div: B 
		sex: male

Mustafa: 22.55

Rami: true  # Boolean

... # Optional YAML end syntax
```

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/f7830354-6125-4e3f-8ae7-14a8ef04f9c6/7a4f445f-1cff-4781-81cd-651bd7594872/Untitled.png)

## List

- We can also represent List in YAML .
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/f7830354-6125-4e3f-8ae7-14a8ef04f9c6/dfdbc90c-e97b-4a12-a172-ed7bd9ea789a/Untitled.png)
    
    https://bobbyhadz.com/blog/open-file-in-new-window-vscode#always-open-files-in-a-new-tab-in-vs-code


