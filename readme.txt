F2 Select Word Hax for Code::Blocks - DLL
=========================================

Generates mouse double click at the position where specified RGB colored 
pixel is found. By default, it's triggered by F2 keyboard key.
It's a filter DLL that can be used in text editors that select 
text by mouse double click.


Instructions
------------------

	* in Code::Blocks IDE settings, make sure key F2 is not assigned to any function.
	* copy "f2sw_dll32.dll" and "f2sw_dll32.ini" into Code::Blocks directory.
	* edit configuration INI file as needed.
	* use dll injector and add "f2sw_dll32.dll" into "codeblocks.exe" import table.
