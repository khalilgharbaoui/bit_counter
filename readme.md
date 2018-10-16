--------------------------------------------------------------
COMMANDLINE:
--------------------------------------------------------------

USAGE:    bit_counter filepath length offset

EXAMPLES:
          bit_counter ./rubber-duck-image.jpg 200 3

          bit_counter rubber-duck-image.jpg 200 3

ℹ️        lenght and offset are optional.
⚠️        filepath is a must!

--------------------------------------------------------------
CONSOLE: (irb or pry)
--------------------------------------------------------------

USAGE:    BitCounter.count_bits, filepath, length, offset

EXAMPLES: load './bit_counter'

          BitCounter.count_bits, "./rubber-duck-image.jpg", 5, 3

          BitCounter.count_bits, "rubber-duck-image.jpg", 5, 3

ℹ️        lenght and offset are optional.
⚠️        filepath is a must!

--------------------------------------------------------------
maintainer: Khalil Gharbaoui <khalilgharbaoui@hotmail.com>
