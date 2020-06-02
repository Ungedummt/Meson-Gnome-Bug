project('gnome.compile_resources_bug')
gnome = import('gnome')

subdir('ui')

gnome.compile_resources('meson_bug',
    'meson_bug.gresource.xml',
    dependencies: window,
    gresource_bundle: true,
    install: true,
    install_dir: 'meson_bug'
)
