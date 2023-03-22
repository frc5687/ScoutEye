# Basic information and installation of ServerEye

# Basic information

ServerEye requires Dot Net 4.8+ to be on the machine, 4.8 comes pre installed on most Windows 10 machines
A guide for identifying the current version of Dot Net can be found [here](https://learn.microsoft.com/en-us/dotnet/framework/migration-guide/how-to-determine-which-versions-are-installed)

FRC 5687 uses our Microsoft sponsorship to host our database in the cloud. Using [Microsoft Azure](https://azure.microsoft.com/en-us)

With cloud hosting comes some caveats and benefits

**Caveats**

- Internet connection required
- Drivers needed

**Benefits**

- Faster processing
- No need to distribute and database to all users
- Can accessed from anywhere
- Easy to intergrade deep learning *coming soon*

## Drivers
ServerEye uses an ODBC connection thus external drivers will need to be installed. **Admin required** [ODBC drivers 18](https://learn.microsoft.com/en-us/sql/connect/odbc/download-odbc-driver-for-sql-server?view=sql-server-ver16)

## Privileges  
All users currently only have readonly


# Installation

ServerEye can be installed from our [GitHub Repo](https://github.com/frc5687/ScoutEye)
Extract all files to desired location -> navigate to ServerEye folder -> double click ServerEye.exe
