# Catalyst

## Installation

Clone the repository:

    $ git clone https://github.com/gevans/catalyst.git

## Usage

Copy the `Vagrantfile.sample` to `Vagrantfile`. Edit as you like then run:

    $ vagrant up

This will start the box and execute the `build` script for the first time.
Packages will can be found in `packages/` after a successful execution. Future
builds can be invoked with:

    $ vagrant provision

## Contributing

1. Fork it (http://github.com/gevans/catalyst/fork)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
