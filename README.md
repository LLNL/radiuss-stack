[WARNING: Archived Repository]
This repository was archived because it is not used and deprecated.

# RADIUSS Stack

The RADIUSS project promotes and supports key High Performance Computing (HPC) open-source software developed at the LLNL. These tools and libraries cover a wide range of features a team would need to develop a modern simulation code targeting HPC plaftorms.

RADIUSS Stack project aims at creating a spack stack (environment) for RADIUSS projects, and test it with CI.

## Getting Started

This project is standalone and mainly consist of configuarion files for spack.

### Prerequisites

This project introduces a radiuss stack described in `spack.yaml`.

### Installing

This project requires no installation. Installing RADIUSS stack simply requires to run spack install in this directory.

This has only be tested on Livermore Computing quartz. The goal being both to extend the number of machines it can be used on and complete the list of packages in the stack.

## Running the tests

Testing consists in building the stack on LC Gitlab CI.

TODO: automate the update of spack.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/LLNL/radiuss-ci/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

version: 1.0.0

TODO: Not even sure how to handle versioning here.

## Authors

Adrien M Bernede

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

All new contributions must be made under the MIT License.

See [LICENSE](https://github.com/LLNL/radiuss-stack/blob/master/LICENSE),
[COPYRIGHT](https://github.com/LLNL/radiuss-stack/blob/master/COPYRIGHT), and
[NOTICE](https://github.com/LLNL/radiuss-stack/blob/master/NOTICE) for details.

SPDX-License-Identifier: (MIT)

LLNL-CODE-793462


## Acknowledgments


