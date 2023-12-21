# contek-highway

Build of [https://github.com/google/highway](https://github.com/google/highway)

To avoid install `vcpkg` and run build everytime when build `op-lib`

# Init or update

```
git clone https://github.com/microsoft/vcpkg vcpkg
./vcpkg/bootstrap-vcpkg.sh
./vcpkg/vcpkg install highway
cp -rf ./vcpkg/packages/highway_x64-linux ./
rm -rf vcpkg
```
