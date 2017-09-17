# test
Using Local History for Change Tracking
Local History Feature
Basics
Local History is a built-in feature of IntelliJ IDEA that automatically tracks changes you make to the source code on your local computer. Similarly to any  version control system (VCS), it enables you to compare versions and roll changes back, if necessary. Local History, however, does not support shared access – it operates independently from the organization’s VCS. The good news is that it works out of the box even if your project is not under any VCS control, or when you are not connected to the network. 

How It Works
Local History tracks changes you make to the source code, results of refactoring, and state of the source code based on a set of predefined events (testing, deployment, commit or update). 
It applies to any structural artifacts: projects, directories, packages, files, classes, class members, tags and selected fragments of text. 

Local History revisions are marked with labels, which are similar to versions in traditional version control systems. Viewing or reverting or differences is performed against these labels.

Labels based on predefined events are added to the local revisions automatically Besides, you can manually put your own labels to the project artifacts to mark your changes. See “Marking local versions with labels” for details.
Local history is cleared when you install a new version of IntelliJ IDEA or when you invalidate caches . Therefore, before performing these operations, make sure you checked in the necessary changes into your global version control system..

Considerations and limitations
1.	Tracking local changes is only possible for text files. Local History for binary files is not supported.
2.	Limited functionality for large files. or files larger than 1 MB, Local History tracks only the very fact of changes, but does not preserve the respective contents.
3.	As said above, Local History does not support shared access – it is intended for the personal use only.

Tracking and Reverting Changes with Local History
This section describes how to:
•         View local history of a file or folder
•         View local history of a class, method, field or selection
•         View local history of a selection
•         View recent changes
•         Restore files from local history
•         Mark local versions with labels
 

Viewing Local History of a File or Folder
1.      Select a folder or file in the Project tool window, or open a file in the editor.
2.       Do any  of the following:
•	 In the main VCS menu, , select  Local History | Show History. Alternatively, you can invoke this command from the shortcut menu.
•	Press Alt+Back Quote and select the  Show Historycommand from the VCS Operations quick list.
•	Use the  Recent Changes view that shows a summary of recent changes in a single pop-up list. Click a list entry  shows its Local History.
4.	eIn the Local History that opens you can  compare local versions of selected file or folder, and accept or revert changes.
o	local history for a file includes all changes that affect both the selected file and the whole project.
o	local history for a folder shows changes to the source code tree in general.

Each entry is displayed with its time stamp, action and optional label. Select an entry in the left pane to explore changes in detail, accept or revert them.
