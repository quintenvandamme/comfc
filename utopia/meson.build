utopia_src = files(
	'comf.c',
)

utopia_deps = [
	wayland_server,
	wlroots,
	pixman,
	xkbcommon,
]

executable(
	'utopia',
	utopia_src,
	include_directories: [inc_folder],
	dependencies: [utopia_deps, wlr_protos],
	install: true
)
