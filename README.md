# fork of https://hg.sr.ht/~scoopta/glpaper
Compilation is broken on the original because of API changes in wayland protocols, fixed in this repo, build steps are not interfered with.
No functionality will be added, i would probably rewrite the entire thing from scratch at some point, most likely it will use vulkan instead of opengl.

# GLPaper
GLPaper is a wallpaper program for wlroots based wayland compositors such as sway that allows you to render glsl shaders as your wallpaper
## Dependencies
	libwayland-dev
	libegl-dev
	pkg-config
	meson
## Building
	hg clone https://hg.sr.ht/~scoopta/glpaper
	cd glpaper
	meson setup build
	ninja -C build
## Installing
	sudo ninja -C build install
## Uninstalling
	sudo ninja -C build uninstall
## Bug Reports
You can bug report into issues section of this repo.
## Contributing
I do accept pull requests.
