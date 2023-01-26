# ProjectTemplate_Cpp
Template for cpp cmake project
## Usage

### Get the PC project

Clone the PC project and the related sub modules:

```
git clone --recursive https://github.com/Forairaaaaa/ProjectTemplate_Cpp.git
```

### Build project

```
mkdir build
cd build
cmake ..
make
```

### vcpkg

Run the bootstrap script to build vcpkg

```
./vcpkg/bootstrap-vcpkg.sh
```

Install libraries for your project

```
vcpkg install [packages to install]
```

