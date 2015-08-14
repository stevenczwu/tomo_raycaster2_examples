# Examples for [tomo_raycaster2](https://github.com/kit-ipe/tomo_raycaster2)
## Workflow:
### 1. Clone this repo
```bash
$ git clone https://github.com/kit-ipe/tomo_raycaster2_examples.git
```
### 2. Go to the dir where you cloned repo
```bash
$ cd tomo_raycaster2_examples
```
### 3. Download submodules.
```bash
$ git submodule init
$ git submodule update
```
### 4. Go to the dir where stored tomo_raycaster2
```bash
$ cd tomo_raycaster2
```
### 5. Install npm
* Opensuse 13.2

```bash
$ sudo zypper addrepo http://download.opensuse.org/repositories/devel:/languages:/nodejs/openSUSE_13.2/ Node.js
$ sudo zypper in npm
```
* Archlinux
```bash
$ sudo pacman -S npm
```
### 6. Install plugins for Grunt
```bash
$ ./install.sh
```
### 7. Generate minification version of tomo_raycaster2
```bash
$ grunt
```
### 8. Go back to the dir tomo_raycaster2_examples
```bash
$ cd ..
```
### 9. Start python http server
```bash
$ ./start_server.sh

```
###10. Point your browser to [localhost:10002/examples](http://localhost:10002/examples).

## LICENSE

The MIT License (MIT)
Copyright (c) 2015 Aleksandr Lizin Sergeevich

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.