```
# download and untar
cd <android root>/external
curl http://www.iozone.org/src/current/iozone3_487.tar -o iozone3_487.tar
mkdir iozone
tar -xvf iozone3_487.tar -C iozone --strip-components 3

# make
cd <android root>
source ./build/envsetup.sh
lunch <target>
make iozone
# or use mm in external/iozone folder
```

