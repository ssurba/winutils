## How to compile Hadoop Winutils on Visual Studio 2022:

### 1. Add configuration variables:
      Configuration properties --> C/C++ --> Preprocessor --> Preprocessor Definitions
      WSCE_CONFIG_DIR=../etc/hadoop
      WSCE_CONFIG_FILE=wsce-site.xml

### 2. Winutils.h:
      Rename GetFileInformationByName() to GetFileInformationByNameW() throughout the solution
