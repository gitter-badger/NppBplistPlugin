Notepad++ bplist plugin
==============
>Check out plugin in Notepad++ plugin manager

NotepadBplistPlugin supports viewing\editing binary plist files. As long as ordinary plist files comes in XML format, this plugin dont supports them. It loads only binary plist files ( bplist ).

#Installation
- Use Notepad++ plugin manager to manage binary plist plugin

#How it works
Just open bplist file with notepad++. You are free to edit is as usual as long as you will do it in a valid XML way. You could type an invalid XML code - in this case when you will try to save bplist, plugin will be not able to conver invalid XML to bplist and will restore original bplist data ( before your modifications )


#Dependencies
- [libimobiledevice]  - for libplist library
- [libxml2] - xml reader\writer

[libimobiledevice]:http://www.libimobiledevice.org/
[libxml2]:http://xmlsoft.org/
