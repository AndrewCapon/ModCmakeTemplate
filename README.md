# ModCmakeTemplate

## build for native

```
mkdir nativebuild
cd nativebuild
cmake ..
make
```

## build for Mod Device

first source local.env in mod-plugin-builder

```
mkdir modbuild
cd nativebuild
cmake -DCMAKE_MOD_DEVICES=1 ..
make
```

