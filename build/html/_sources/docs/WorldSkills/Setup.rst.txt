World Skills Software Setup Guide
=================================

.. note:: This setup is for Java/C++ only

.. tabs::

   .. tab:: Windows

      Online Installer
      ----------------------
		
      .. warning:: Windows 7: You **must** install the standalone version of .NET Version 4.62+ which can be found `here <https://support.microsoft.com/en-us/help/3151800/the-net-framework-4-6-2-offline-installer-for-windows>`__.
      
      Download the installer (32bit or 64bit) `from WPI <https://github.com/wpilibsuite/allwpilib/releases>`__. 
		
      .. image:: images/windows/worldskills-software-setup-1.png
      
      Installing for *All Users* will require admin privileges and install for all users on the machine.
      
      .. note:: Software will be installed to ``C:\Users\Public\wpilib\YYYY``. YYYY Corresponds to the currently suppored year.

      **Download VS Code**
      
         Due to licensing reasons with VS Code the installer does not contain it bundled in. To overcome this hit the *Select/Download VS Code* button.
      
         .. image:: images/windows/worldskills-software-setup-2.png
         
         This will open up the selector tool.

         .. image:: images/windows/worldskills-software-setup-3.png
         
         Select the *Download* option and VS Code will be downloaded.
         
         .. image:: images/windows/worldskills-software-setup-4.png
         
         Once VS Code is downloaded the window will auto change back to the installer window and *Execute Install* can be run. 
         
         .. image:: images/windows/worldskills-software-setup-5.png
      
      **What was just Installed**
      
         -  *Visual Stuido Code* - The prefered and suppored IDE for robot code development. 
         -  *C++ Compiler* - Toolchains required for building C++ code.
         -  *Java JDK/JRE* - Specific version of the JDK/JRE that is used to build code. 
         -  *Gradle* - Specific version of Gradle used for building and deploying Java or C++ code to the VMXpi
         -  *WPILib Tools* - Tools used for robot enhancement
         -  *WPILib Dependencies* - OpenCV, etc.
         -  *VS Code Extensions* - WPILib extensions for robot code development
         
         .. important:: The installer creates a seperate version of VS Code for robotics development, even if VS Code is already installed locally. This is done to prevent workflows from breaking.
         
      Offline Installer
      ----------------------
 		
      .. warning:: Windows 7: You **must** install the standalone version of .NET Version 4.62+ which can be found `here <https://support.microsoft.com/en-us/help/3151800/the-net-framework-4-6-2-offline-installer-for-windows>`__. Before preceding!
      
      The offline installation files will be located in the USB provided inside the collection. Locate and run the file named ``WPILibInstaller_Windows64-2020.3.2.exe`` or ``WPILibInstaller_Windows32-2020.3.2.exe`` based on your OS. 
		
      .. image:: images/windows/worldskills-software-setup-1.png
      
      Installing for *All Users* will require admin privileges and install for all users on the machine.
      
      .. note:: Software will be installed to ``C:\Users\Public\wpilib\YYYY``. YYYY Corresponds to the currently suppored year.

      **Download VS Code**
      
         Due to licensing reasons with VS Code the installer does not contain it bundled in. To overcome this hit the *Select/Download VS Code* button.
      
         .. image:: images/windows/worldskills-software-setup-2.png
         
         This will open up the selector tool.

         .. image:: images/windows/worldskills-software-setup-3.png
         
         Select the *Select Existing Download* option and then select the file ``OfflineVsCodeFiles-1.41.1.zip``. This will change back to the installer window and *Execute Install* can be run. 
         
         .. image:: images/windows/worldskills-software-setup-5.png
      
      **What was just Installed**
      
         -  *Visual Stuido Code* - The prefered and suppored IDE for robot code development. 
         -  *C++ Compiler* - Toolchains required for building C++ code.
         -  *Java JDK/JRE* - Specific version of the JDK/JRE that is used to build code. 
         -  *Gradle* - Specific version of Gradle used for building and deploying Java or C++ code to the VMXpi
         -  *WPILib Tools* - Tools used for robot enhancement
         -  *WPILib Dependencies* - OpenCV, etc.
         -  *VS Code Extensions* - WPILib extensions for robot code development
         
         .. important:: The installer creates a seperate version of VS Code for robotics development, even if VS Code is already installed locally. This is done to prevent workflows from breaking.     
      
   .. tab: macOS
   
   **Installing VS Code**
   
   .. tab:: Linux
   
   **Installing VS Code**
 
