---
title: Create a VSS requestor for use with SharePoint
description: Describes how to create a requestor for use with the Volume Shadow Copy Service (VSS) writer for Microsoft SharePoint.
ms.date: 06/09/2022
ms.prod: sharepoint
ms.assetid: 63b3145b-ece2-4acf-b58a-fd8b50303030
ms.localizationpriority: medium
---


# Create a VSS requestor for use with SharePoint

Learn about how to create a requestor for use with the Volume Shadow Copy Service (VSS) writer for Microsoft SharePoint.

## Writing a requestor

The process of writing a requestor for backing up and restoring SharePoint Foundation by using VSS is the same as that for writing a requestor for any other Windows-based application such as Microsoft SQL Server or Microsoft Exchange Server. Developers of backup applications should follow the procedures outlined in the  [Volume Shadow Copy Service Overview](https://msdn.microsoft.com/library/aa384649%28VS.85%29.aspx) and [Volume Shadow Copy API Reference](https://msdn.microsoft.com/library/aa384648%28VS.85%29.aspx) to build applications that can properly back up and restore SharePoint Foundation data.
  
    
    

## Next steps
<a name="Next"> </a>

Learn how to use the requestor to back up and restore SharePoint and search applications and indexes:
  
    
    

-  [How to: Back up and restore SharePoint using a VSS requestor](how-to-back-up-and-restore-sharepoint-using-a-vss-requestor.md)
    
  
-  [How to: Back up and restore a search service application in SharePoint using VSS](how-to-back-up-and-restore-a-search-service-application-in-sharepoint-using.md)
    
  

## See also
<a name="bk_addresources"> </a>


-  [Overview of SharePoint and the Volume Shadow Copy Service](overview-of-sharepoint-and-the-volume-shadow-copy-service.md)
    
  

