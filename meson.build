project(
    'quatro',
    meson_version: '>= 1.9.1',
)

py = import('python').find_installation(pure: false)

py.install_sources('pyproject.toml', subdir: 'quatro')

subdir('src/quatro')
