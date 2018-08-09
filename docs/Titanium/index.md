# Titanium Library


## Titanium Modules

- [Base - Main Module](/Titanium/Modules/Base/)
- [Cassandra - GUI Module](/Titanium/Modules/Cassandra/)
- [Commodore - Command Module](/Titanium/Modules/Commodore/)
- [Corporis - Resource Module](/Titanium/Modules/Corporis/)
- [Perplex - Multipart Module](/Titanium/Modules/Perplex/)
- [Nucleus - ASM Module](/Titanium/Modules/Nucleus/)

### Installing Modules

You can use the [**Skeleton**](/Titanium/Skeleton/) system instead of manually installing titanium.

#### Maven: 
```gradle
maven { url "https://modmaven.k-4u.nl" }
```

#### Specifying Modules:

[__Base__](/Titanium/Modules/Base/) is a required module, if using seperate installs you must specify base, see [~~Base - Installation~~](/Titanium/Modules/Base/#installation)

Modules are availible as seperate jars for development to prevent bloating up a dev environment

```
compile 'com.hrznstudio:Titanium:[VERSION]:[MODULE]'
```

To install all modules you can use `all` as a module

```
compile 'com.hrznstudio:Titanium:[VERSION]:all'
```