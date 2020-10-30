

Windows with visual studio
===========================

1. Update submodules:

	git submodule update --init --recursive

2. Bootstrap vcpkg:

	cd <project folder>
	.\vcpkg\bootstrap-vcpkg.bat
	
3. To use vcpkg with Visual Studio, run (this may require administrator elevation):

	.\vcpkg\vcpkg integrate install
	
4. Install gtkmm library and it's dependencies

	.\vcpkg\vcpkg install gtkmm:x64-windows

Linux
=======

1. Install libgtkmm-3.0-dev:

	sudo apt install libgtkmm-3.0-dev

