# Project Name

This document specifies the YANG modules for MEF 6.2 EVC based Services and MEF 10.3 Ethernet Services Attributes. These modules are for use in Service Orchestration Function (SOF) and to communicate the configuration state for Service attributes and values with other entities, such as Business Applications or Partners or Customers, specified in MEF 55 Lifecycle Service Orchestration Reference Architecture. One use of these modules is for the use cases at Legato reference point for Service Configuration and Activation (SCA) specified in MEF X SCA (Legato) Interface Profile specification. The elements of the YANG modules are aligned with the objects identified in MEF 7.3 Carrier Ethernet Service Information Model MEF 6.2 and in MEF 7.3.


## Installation

To run the tests in the project, you need to have an installation of NSO installed and running on the device where this git is cloned. In addition, you will need a version of pyang that supports the swagger plugin. See https://github.com/ict-strauss/COP/tree/master/pyang_plugins

    cd test/example
    make clean
    make
    make start # to run the tests
    make settest # to run some more tests
    make test    # to run yet more tests

If you do not have access to NSO, and just want to build the models, then just run the following command. You will still need pyang with swagger plugin, both of which are publicly available.

make models

## Usage


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b MEF-GIT/YANG`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin/develop MEF-GIT/YANG`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

This work would not have been possible without the work of Mahesh Jethanandani, David Ball, Jim Boucher and several others.

## License

TODO: Write license