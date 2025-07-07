Debloater.ps1 is the powershell script that you package with the Intune Prep Tool into a win32 app. 

Debloater.ps1 includes the whitelist of applications.



RemoveBloat.ps1 is the actual removal script. Here is where you can add apps if you want something to be removed.
RemoveBloat.zip is the zip file containing the RemoveBloat.ps1 file. This is downloaded to the computer when the win32 app runs.

If the script is changed. Zip it again. Then update the published zip at link:
"https://github.com/dxmnoc/script/releases/download/v1.0-fixed/RemoveBloat.zip"
