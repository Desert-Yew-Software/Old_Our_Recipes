# Our-Recipes
Household sharable recipe book manager/library
This application is refered to as 'Our Recipes' from this point on.
Our Recipes will manage a user's collection of recipies. Multiple collections are 
permitted and the user will need to select one from their directory portion of the app 
in order to View/Edit the recipes it contains.

## For Single Household/Personal Use Only
Our Recipes allows the user to share with all household members who use the same machine [Public].
A user may also chose to store their data on only one machine accessible to just their login [Private].
Another possibility is for the user to have their Documents folder sycnchronized (e.g. OneDrive or DropBox)
with a cloud storage system which makes the data available to the single user on multiple machines [Documents].

## Sharing via Email or Paper
This application allows for PDF printing of any given recipe for ease of portability. 
It also provides an export/import funtion for recipes making it possible to share
recipes with others using the same application. These exported recipes reside in a 
compressed folder and are placed on the user's desktop when created.

## Accessibility
For those who appreciate it, the application provides a means to scale the GUI 
from 75% to 200% of normal size.

## Technical Details
### Application Executibles
These are the executables that are built for this application:
* RecipeData.DLL
* PDF_Printing.DLL
* Our Recipes.DLL
* Our Recipes.EXE
* setup.msi

### Application Runtime Dependencies
The following are provided at installation of Our Recipes:
* Windows v10.22000.0.0
* WinRT.Runtime.dll v1.6.2.38681
* .NET Desktop Runtime v6.0.5
* ICSharpCode.SharpZipLib.dll v4.3.0 (github)
* Microsoft.Windows.SDK.Net.dll v10.0.22000.24 (github)
* MigraDocCore.Rendering.dll v1.3.30 (github)
* MigraDocCore.DocumentObjectModel.dll v1.3.32.0 (github)
* SixLabors.Fonts.dll v1.0.0.0 (github)
* SixLabors.Imagesharp.dll v1.0.4.0 (github)
