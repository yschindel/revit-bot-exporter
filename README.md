# revit-bot-exporter
Export from Autodesk Revit to BOT-compliant Turtle

# Before you begin
1. Make sure you have the [Revit Addin Manager](https://github.com/chuongmep/RevitAddInManager) installed
2. Build the project
3. Copy file `N_Shared_Parameters_GUID_TEST.txt` to `C:\Temp`
4. Load the .ddl in the Addin Manager
5. Use Addin Manager to run `NIRAS.Revit.TLL_Exporter.AddParameters`
6. Go to Project Information and add a value to `Host`
7. Use Addin Manager to run `NIRAS.Revit.TTL_Exporter.Export_TTL_File_Main`

# Known Limitations
- Cannot process groups

## Acknowledgements
The code is initially developed by my Niras collaegue, Jonas Eik Bacher-Jacobsen.
