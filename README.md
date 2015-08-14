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