# MatterOverdrive API

## API Instance

Getting the api instance is a simple method.

```java
MatterOverdriveAPI.getInstance()
```

## Android

```java
instance.getAndroidPlayer(EntityPlayer player)
```

```java
instance.isAndroid(EntityPlayer player)
```

```java
instance.isHuman(EntityPlayer player)
```

```java
instance.isTurning(EntityPlayer player)
```

## Material Matter

```java
instance.getMatterForStack(ItemStack stack, @Nullable EntityPlayer player)
```

```java
instance.getMatterForStackIgnoreCount(ItemStack stack, @Nullable EntityPlayer player)
```

```java
instance.getMatterForItem(Item item, @Nullable EntityPlayer player)
```