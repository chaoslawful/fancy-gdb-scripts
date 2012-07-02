fancy-gdb-scripts
=================

Publish/collect some fancy gdb scripts to aid debugging

How to use
==========

Just copy the script you want to use to $HOME/.gdbinit, restart gdb or source
.gdbinit to load it.

Scripts
=======

peek-lua-vm			-	provide commands lbt/ll/lu/lg/lr to peek into Lua VM
step-over-longjmp	- 	make it possible to step over longjmp calls by hooking
						next/step/start/run commands

