---
title: "Application and Thread Support Classes"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
f1_keywords: 
  - "vc.classes.support"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "application objects [C++], thread support classes"
  - "lock classes"
  - "thread support classes [C++]"
  - "threading [MFC]"
  - "synchronization classes, multithreading"
  - "application support classes [C++]"
ms.assetid: 3c1d14fd-c35c-48f1-86ce-1e0f9a32c36d
caps.latest.revision: 8
ms.author: "mblome"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# Application and Thread Support Classes
Each application has one and only one application object; this object coordinates other objects in the running program and is derived from `CWinApp`.  
  
 The Microsoft Foundation Class (MFC) Library supports multiple threads of execution within an application. All applications must have at least one thread; the thread used by your `CWinApp` object is this primary thread.  
  
 `CWinThread` encapsulates a portion of the operating system's threading capabilities. To make using multiple threads easier, MFC also provides synchronization object classes to provide a C++ interface to Win32 synchronization objects.  
  
## Application and Thread Classes  
 [CWinApp](../mfcref/cwinapp-class.md)  
 Encapsulates the code to initialize, run, and terminate the application. You will derive your application object from this class.  
  
 [CWinThread](../mfcref/cwinthread-class.md)  
 The base class for all threads. Use directly, or derive a class from `CWinThread` if your thread performs user-interface functions. `CWinApp` is derived from `CWinThread`.  
  
## Synchronization Object Classes  
 [CSyncObject](../mfcref/csyncobject-class.md)  
 Base class of the synchronization object classes.  
  
 [CCriticalSection](../mfcref/ccriticalsection-class.md)  
 A synchronization class that allows only one thread within a single process to access an object.  
  
 [CSemaphore](../mfcref/csemaphore-class.md)  
 A synchronization class that allows between one and a specified maximum number of simultaneous accesses to an object.  
  
 [CMutex](../mfcref/cmutex-class.md)  
 A synchronization class that allows only one thread within any number of processes to access an object.  
  
 [CEvent](../mfcref/cevent-class.md)  
 A synchronization class that notifies an application when an event has occurred.  
  
 [CSingleLock](../mfcref/csinglelock-class.md)  
 Used in member functions of thread-safe classes to lock on one synchronization object.  
  
 [CMultiLock](../mfcref/cmultilock-class.md)  
 Used in member functions of thread-safe classes to lock on one or more synchronization objects from an array of synchronization objects.  
  
## Related Classes  
 [CCommandLineInfo](../mfcref/ccommandlineinfo-class.md)  
 Parses the command line with which your program was started.  
  
 [CWaitCursor](../mfcref/cwaitcursor-class.md)  
 Puts a wait cursor on the screen. Used during lengthy operations.  
  
 [CDockState](../mfcref/cdockstate-class.md)  
 Handles persistent storage of docking state data for control bars.  
  
 [CRecentFileList](../mfcref/crecentfilelist-class.md)  
 Maintains the most recently used (MRU) file list.  
  
## See Also  
 [Class Overview](../mfc/class-library-overview.md)