# cerberustesting.github.io
Cerberus documentation website

In case you want to contribute to Cerberus documentation, Don't update it from here.

Documentation has to update from [here](https://github.com/cerberustesting/cerberus-source/tree/master/source/src/main/resources/documentation) in adoc format.


# Cerberus documentation release processes

[Cerberus](http://www.cerberus-testing.org/) is an user-friendly automated testing framework.

This folder is the entry point to release Cerberus documentation project.

## Get started

Prerequisits are to clone the documentation project.
`
git clone https://github.com/cerberustesting/cerberustesting.github.io.git
`

### Cerberus github release

Go to your release folder

`
    cd <path_to_clone>
`

And run the release cmd :

`
 ./runcmds.sh
       -e RELEASE_VERSION <release version> 
       -s ./release.cmds
`

NB : If under Windows, you can submit the command from docker bash.

## License

Cerberus Copyright (C) 2013 - 2017 cerberustesting

This file is part of Cerberus.

Cerberus is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Cerberus is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Cerberus.  If not, see <http://www.gnu.org/licenses/>.
