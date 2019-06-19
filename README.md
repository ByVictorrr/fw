# fw - frequency word
## Description
This program return a sorted list of the n most common words in a file or set of
files, sorted by order of frequency. In the case of a frequency tie, words later in the alphabet take
precedence over words earlier. (That is, sort first on numbers, then on the words in lexographical
order, but we’re printing “bigger” things first so the words will wind up in reverse alphabetical
order.)
## Usage
make

./fw [-n num] [ file1 [ file 2 ...] ]
