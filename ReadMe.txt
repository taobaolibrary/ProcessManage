========================================================================
       MICROSOFT FOUNDATION CLASS LIBRARY : ProcessManage
========================================================================









=======================================================================
2015年6月17日 21:49:23
它将陆续支持以下功能:

遍历进程
遍历线程
遍历模块
指定进程的虚拟内存A
结束指定进程线程A
设置优先级A
EASY
CPU使用率,内存使用情况
遍历窗口信息
卸载模块A
关机开机重启.
老板键

HARD
监视窗口进程打开
线性图(依赖CPU使用率,内存使用情况)

///标记A的项目为需要右键盛放的内容.



This file contains a summary of what you will find in each of the files that
make up your ProcessManage application.

ProcessManage.dsp
    This file (the project file) contains information at the project level and
    is used to build a single project or subproject. Other users can share the
    project (.dsp) file, but they should export the makefiles locally.

ProcessManage.h
    This is the main header file for the application.  It includes other
    project specific headers (including Resource.h) and declares the
    CProcessManageApp application class.

ProcessManage.cpp
    This is the main application source file that contains the application
    class CProcessManageApp.

ProcessManage.rc
    This is a listing of all of the Microsoft Windows resources that the
    program uses.  It includes the icons, bitmaps, and cursors that are stored
    in the RES subdirectory.  This file can be directly edited in Microsoft
	Visual C++.

ProcessManage.clw
    This file contains information used by ClassWizard to edit existing
    classes or add new classes.  ClassWizard also uses this file to store
    information needed to create and edit message maps and dialog data
    maps and to create prototype member functions.

res\ProcessManage.ico
    This is an icon file, which is used as the application's icon.  This
    icon is included by the main resource file ProcessManage.rc.

res\ProcessManage.rc2
    This file contains resources that are not edited by Microsoft 
	Visual C++.  You should place all resources not editable by
	the resource editor in this file.




/////////////////////////////////////////////////////////////////////////////

AppWizard creates one dialog class:

ProcessManageDlg.h, ProcessManageDlg.cpp - the dialog
    These files contain your CProcessManageDlg class.  This class defines
    the behavior of your application's main dialog.  The dialog's
    template is in ProcessManage.rc, which can be edited in Microsoft
	Visual C++.


/////////////////////////////////////////////////////////////////////////////
Other standard files:

StdAfx.h, StdAfx.cpp
    These files are used to build a precompiled header (PCH) file
    named ProcessManage.pch and a precompiled types file named StdAfx.obj.

Resource.h
    This is the standard header file, which defines new resource IDs.
    Microsoft Visual C++ reads and updates this file.

/////////////////////////////////////////////////////////////////////////////
Other notes:

AppWizard uses "TODO:" to indicate parts of the source code you
should add to or customize.

If your application uses MFC in a shared DLL, and your application is 
in a language other than the operating system's current language, you
will need to copy the corresponding localized resources MFC42XXX.DLL
from the Microsoft Visual C++ CD-ROM onto the system or system32 directory,
and rename it to be MFCLOC.DLL.  ("XXX" stands for the language abbreviation.
For example, MFC42DEU.DLL contains resources translated to German.)  If you
don't do this, some of the UI elements of your application will remain in the
language of the operating system.

/////////////////////////////////////////////////////////////////////////////
