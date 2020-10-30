Update submodules:

	git submodule update --init --recursive
	
Bootstrap vcpkg:

	cd <project folder>
	.\vcpkg\bootstrap-vcpkg.bat
	
To use vcpkg with Visual Studio, run (this may require administrator elevation):

	.\vcpkg\vcpkg integrate install
	
Install gtkmm library and it's dependencies

	.\vcpkg\vcpkg install gtkmm
