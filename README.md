# Pinny

Easily jot down invaluable thoughts & tasks

![Screenshot](data/screenshot.png?raw=true)

## Installing and Running 

### Dependencies 

	gtksourceview-3.0
	json-glib-1.0
	gee-0.8
	gtk+-3.0
	libgranite-dev
	fonts-firacode
	valac

### Build and install 

Just type from a command line:

	mkdir build && meson build --prefix=/usr
    cd build
    ninja
	./pinny
