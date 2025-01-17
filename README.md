Progress.Sitefinity.Samples.Charity
==================================

### This repository is not automatically upgraded to latest Sitefintiy version. The repository is monitored for pull requests and fixes. The latest official version of Sitefinity that supports this sample is 9.1. Be aware that using a higher version could cause unexpected behavior. If you successfully upgrade the example to a greater version, please share your work with the community by submitting your changes via pull request.

The Charity starter kit (Telerik Charity) can be used to quickly create an interactive and engaging non-profit website. Originally inspired by the Microsoft GiveCamp charity events, the Charity starter kit contains a suite of useful custom widgets and helps educate developers about Sitefinity CMS.

Using the Charity starter kit, you can create:

* Social media widgets - including Facebook, Twitter, and Flickr 
* Donation widget with PayPal integration 
* Maps widget - with Bing Maps integration 
* iCal reminder and feeds for events 
* Custom templates and themes 
* Sample contact form 
* Volunteer and job opportunity pages 



### Requirements

* Sitefinity CMS license
* .NET Framework 4.5
* Visual Studio 2012
* Microsoft SQL Server 2008R2 or later versions

### Prerequisites

Clear the NuGet cache files. To do this:

1. In Windows Explorer, open the **%localappdata%\NuGet\Cache** folder.
2. Select all files and delete them.

### Nuget package restoration
The solution in this repository relies on NuGet packages with automatic package restore while the build procedure takes place.   
For a full list of the referenced packages and their versions see the [packages.config](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.Charity/blob/master/SitefinityWebApp/packages.config) file.    
For a history and additional information related to package versions on different releases of this repository, see the [Releases page](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.Charity/releases).    


### Installation instructions: SDK Samples from GitHub

1. In Solution Explorer, navigate to _SitefinityWebApp_ » *App_Data* » _Sitefinity_ » _Configuration_ and select the **StartupConfig.config** file. 
2. Modify the **dbType**, **sqlInstance** and **dbName** values to match your server settings.
3. Build the solution.

For version-specific details about the required Sitefinity CMS NuGet packages for this sample application, click on [Releases](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.Charity/releases).

### Login

To login into the Sitefinity CMS backend, use the following credentials:   
**Username:** admin   
**Password:** password
