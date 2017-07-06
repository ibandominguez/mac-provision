# General scripts

A collection of scripts from day2day tasks to env setup

# Getting started

```sh
git clone https://github.com/ibandominguez/provisioning-scripts.git
cd provisioning-scripts
```

# Provisionning your macos

```sh
curl https://raw.githubusercontent.com/ibandominguez/scripts/master/macos/general-dev.sh | sh
```

# Vagrant and Ubuntu scripts

Keep in mind you need Vagrant and a VM provider

```sh
vagrant up
vagrant ssh
cd /vagrant # default shared folder
bash ubuntu/lamp.sh # run the script you would like to use
```

# License

The MIT License (MIT)

Copyright (c) 2015 Iban Dominguez

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
