# png_splitter

This program splits a 360x120 png into 12 80x80 pngs.  Please note that it requires a 'black' and 'white' folder to properly execute ( it's perfect for chess ).

## Requires

* png++
* libpng

## Installation

    $ g++ -lpng png_splitter.cpp -o png_splitter

## Usage

    $ mkdir black white
    $ ./png_splitter new_pieces.png

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
