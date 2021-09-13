# H5P DRUPAL7 DDEV

drupal7 is recommended for H5P content type development (https://h5p.org/development-environment)

Currently included:

- drupal-7.82
- h5p-7.x-1.49

## Install drupal & setup database

- `ddev start`
- `ddev launch`
- Navigate to https://h5p-drupal7-ddev.ddev.site/install.php
- Complete install process with option "Minimal"
- Go to Administration > Modules > H5P > Configure
- Activate "Enable H5P development mode" &
- Activate "Enable library development directory (for programmers only)"

## Start developing

See https://www.youtube.com/watch?v=xEgBJaRUBGg :-)


## TODOs / Ideas

- add gitpod link

## How it was done

Just copied drupal7 files to project root (https://www.drupal.org/project/drupal), ran `ddev config` (drupal7 is automatically recognized as project type) and afterwards copied H5P to modules/ (https://www.drupal.org/project/h5p).
