﻿
PRE-REQUISITES BEFORE USING THIS SAMPLE

*************************************************

Step 1: Create the Microsoft.Samples.Waad.PS.dll 

*************************************************

In order to use the PowerShell cmdlets provided under the %ROOT%/php/scripts/ directory, you will need to build the DLL that provides the WAAD functionality. 

We have included the source for building this DLL in this code for your convenience. It is located at:

%ROOT%/csharp/code/libraries/powershell/Microsoft.Samples.Waad.PS/

You have two options to build this DLL:

1. Build using VS 2010 Tools Command Line and included batch file

You can build this DLL easily by running:

 %ROOT%/csharp/code/libraries/powershell/Microsoft.Samples.Waad.PS/buildWaadPS.bat

This will build the DLL and copy the DLL to the correct location under %ROOT%/php/scripts/

2. Load the .csproj file and build under Visual Studio 2010 or higher

This is located under %ROOT%/csharp/code/libraries/powershell/Microsoft.Samples.Waad.PS. You will need to ensure that the Microsoft.Samples.Waad.PS.dll file is moved to the correct location under %ROOT%/csharp/scripts/


The rest of the setup instructions and walk-through are located at:

http://www.windowsazure.com/en-us/develop/php/how-to-guides/web-sso/


********************************************************************

STEP 2: Download the simpleSAMLphp library

********************************************************************

 SimpleSAMLphp is an award-winning application written in native PHP that deals with authentication. The project is led by UNINETT, has a large user base, a helpful user community and a large set of external contributors.

SimpleSAMLphp is having a main focus on providing support for:
 •SAML 2.0 as a Service Provider.
 •SAML 2.0 as a Identity Provider.
 
But also supports some other identity protocols, such as Shibboleth 1.3, A-Select, CAS, OpenID, WS-Federation and OAuth.

You can download this by going to: http://simplesamlphp.org/

and including the base install underneath the root directory such as:

%ROOT/simplesamlphp



Enjoy! 

