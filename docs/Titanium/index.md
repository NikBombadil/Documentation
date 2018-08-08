# Titanium Library


## Titanium Modules

- [Cassandra - GUI Module](/Titanium/Modules/Cassandra/)
- [Commodore - Command Module](/Titanium/Modules/Commodore/)
- [Perplex - Multipart Module](/Titanium/Modules/Perplex/)
- [Nucleus - ASM Module](/Titanium/Modules/Nucleus/)

### Installing Modules

You can use the [**Skeleton**](/Titanium/Skeleton/) system instead of manually installing titanium.

#### Maven: 
```gradle
maven { url "https://modmaven.k-4u.nl" }
```

#### Specifying Modules:
Base is a required module, if using seperate installs you must specify base
```
compile 'com.hrznstudio:Titanium:[VERSION]:base'
```

Modules are availible as seperate jars for development to prevent bloating up a dev environment

```
compile 'com.hrznstudio:Titanium:[VERSION]:[MODULE]'
```

To install all modules you can use `all` as a module

```
compile 'com.hrznstudio:Titanium:[VERSION]:all'
```