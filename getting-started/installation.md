# Installation

1. Download a zip file of the theme or clone the repo from [https://github.com/aliwaqas333/ckanext-kpodp\_theme.git](https://github.com/aliwaqas333/ckanext-kpodp_theme.git)
2. copy the zip file to `/usr/lib/ckan/default/src`
3. open ckan configuration file, development.ini or production.ini and add kpodp\_theme in ckan.plugins, so that your line should look like `ckan.plugins=plugin1 plugin2 kpodp_theme`
4. cd `/usr/lib/ckan/default/src`
5. run `python setup.py install`
6. After this has completed successfully, add `kpodp_theme` to ckan.plugins in ckan configuration file.



