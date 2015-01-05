Trailstranscoder Development Environment
========================================

This vagrant+ansible workflow should get you set up with a recent copy of
Ubuntu, Postgres+Postgis, Python, and GDAL/OGR. The main purpose to provide an
environment for working on [trailstranscoder](https://github.com/codeforanchorage/trailstranscoder).

This is a work in progress, use at your own risk. Also, please keep in mind the
settings and configurations employed here are for development purposes only ---
security is your responsibility if you decide to use this outside of a
development setting.

Getting Started
---------------

1. Install the following requirements:
    - [Vagrant](http://www.vagrantup.com/)
    - [Ansible](http://www.ansible.com/)
    - [Virtualbox](https://www.virtualbox.org/)

2. Clone this repository:

        git clone https://github.com/codeforanchorage/trailstranscoder_dev_env.git

3. Launch vagrant (When prompted, the password is `vagrant`):

        cd trailsy_dev_env
        vagrant up

4. Run `vagrant ssh` to log into the development enviroment.

Additional Info
---------------

Questions? Comments? Email us at brigade@codeforanchorage.org.

License
-------

The MIT License (MIT)

Copyright (c) 2014, 2015 Code For Anchorage

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

