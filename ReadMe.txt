Update submodules:

	git submodule update --init --recursive

Windows with visual studio:

1. Bootstrap vcpkg:

	cd <project folder>
	.\vcpkg\bootstrap-vcpkg.bat
	
2. To use vcpkg with Visual Studio, run (this may require administrator elevation):

	.\vcpkg\vcpkg integrate install
	
3. Install gtkmm library and it's dependencies

	.\vcpkg\vcpkg install gtkmm:x64-windows

