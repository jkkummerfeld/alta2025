# ALTA 2024 Official Website

This is the code for the official website for the 2024 Annual Workshop of the Australasian Language Technology Association ([ALTA 2024](https://alta2024.alta.asn.au/)), based on the code for [ALTA 2023](https://alta2023.alta.asn.au/) and [EMNLP 2022](https://github.com/yxni98/EMNLP_2022). It's currently using the [Minimal Mistakes Jekyll Theme](https://github.com/mmistakes/minimal-mistakes).


## Building the website locally

The following steps are tested on Ubuntu 22.04.

First, set up ruby
```bash
$ sudo apt-get install ruby-rubygems ruby-dev g++ make
$ echo "export GEM_HOME=$HOME/.local/share/gem/ruby/3.0.0" >> ~/.bashrc
$ echo "export PATH=$GEM_HOME/bin:$PATH" >> ~/.bashrc
$ source ~/.bashrc
$ gem install --user-install bundler
$ bundle config set path $GEM_HOME
```
Now clone the repository
```
$ git clone https://github.com/cdawei/alta2024
```
Then install gems needed by this repository (if this step fails, check error messages to see if additional packages need to be installed)
```bash
$ cd alta2024/
$ bundle install
```
To start the jekyll server
```bash
$ bundle exec jekyll serve
```
Lastly, visit http://localhost:4000 in a web browser to see the website.


## License

The MIT License (MIT)

Copyright (c) 2024 Association for Computational Linguistics.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
