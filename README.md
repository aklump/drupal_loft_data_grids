##Summary
Integrates the [loft_data_grids][ldg] module with Drupal

##Installation
1. Download and unzip this module into your modules directory.
1. Goto Administer > Site Building > Modules and enable this module.
2. Download [loft_data_grids][ldg] from github and install in `sites/all/libraries` as `sites/all/libraries/loft_data_grids`
3. Visit `admin/reports/status` and confirm the library is being detected and loaded correctly.


##Usage
To use any of the classes in [loft_data_grids][ldg] just add the following line of code before instantiating the first object:

    libraries_load('loft_data_grids');
    
Refer to the library for more info on how to use each class.


##Contact
* **In the Loft Studios**
* Aaron Klump - Developer
* PO Box 29294 Bellingham, WA 98228-1294
* _aim_: theloft101
* _skype_: intheloftstudios
* _d.o_: aklump
* <http://www.InTheLoftStudios.com>

[ldg]: https://github.com/aklump/loft_data_grids