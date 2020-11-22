# In Development

# **Slabserver Plugins**

Name<br>
Description/Purpose<br>
Non-default config values<br>
Expected permissions

### **AFKSleep**
A combination of both our AFK functionality, and group majority sleep plugin

### **Coreprotect**
A fast, efficient, data logging and anti-griefing tool, allowing us to check player block or container interactions, and roll them back.<br>

Example commands:

`u:<user> t:<time> r:<radius> a:<action> b:<blocks> e:<exclude>`
```
/co lookup a-block b:diamond_ore t:1d
/co lookup u:Etho a-block b:diamond_ore t:1w
/co rollback u:Etho #preview
```
<br>

### **DiscordSRV**

Creates a Minecraft and Discord chat link for the `#ingamechat` Discord channel.

A number of commands can be run via this channel using `!c`, returning the same result you'd get ingame.
```
!c who
!c tps
```
<br>

### **Dynmap**
The live map accessible at [map.slabserver.org](https://map.slabserver.org/index.html)

[Available Dynmap Icons](https://camo.githubusercontent.com/9db598a2984ee843180041450e7292f284208624/687474703a2f2f6d696b657072696d6d2e636f6d2f696d616765732f4d61726b6572732e706e67)

```
/dmarker add "Mancave"
/dmarker add "Mancave" icon:"big house"
/dmarker add "Mancave" set:"markers" icon:"big house"
```
For deletion:
```
 /dmarker remove "Mancave"
```

<br>

### **F3Name**


### **InventoryRollback**
```
# Opens a GUI to select the backup you require
/ir restore <Etho>

# Forces a backup for an online player
/ir forcebackup <Etho>
```

### **LightningFire**
Disables lightning from fire unless it hits netherrack or magma blocks

### **OpenInv**
Lets us open the inventories and enderchests of players

```
/oi Etho
/oe Etho
```
<br>

### **PetOwner**
Lets us check the owner of a pet

N.B. Plugin does not support cats, or any newer pets that get implemented.
```
/pet check  -  Check the owner of a pet
/pet set <new-owner>  -  Transfer ownership of a pet to <new-owner>
/pet unset  -  Remove ownership from a pet
```
<br>

### **Plan**

UI link
<br>

/afk command and #away #idle #bed status in the tab list

### **PremiumVanish**
A player hiding plugin achieved through packet interception with ProtocolLib.
```
/vanish - Makes the player appear as if they have log
```

### **spark**
Used for /tps and java profiles for if timings fail us

### **WorldborderGateKeeper**

<br>

## **Dependencies**

### **PlaceholderAPI**
Allows other plugins to register placeholders our other plugins can process.
<br>
Plugins that use this:

### **ProtocolLib**
Allows read and write access to the Minecraft protocol. Handles most overhead for reflection and channel injection, providing wrappers to simplify packet modification.<br>
Plugins that use this:

### **Vault**
Permissions, Chat, & Economy API
<br>
Plugins that use this:

### **WorldEdit**
Used only for the selection tool in CoreProtect

## **Generated Folders**
PluginMetrics

update

Updater

# **Proxy Plugins**

### **Advanced Ban**

### **BungeeRcon**

### **Luckperms**

### **PremiumVanish**

### **Slabungee**

### **VentureChat**

### **Yamler-Bungee*

Upgrade Procedure

### Resource World

Plugins
Paper

### Main
Plugins
Paper

### Bungee
Plugins
Paper

### Validation:
Enter Resource World
Send message - is it viewable on main world and discord?
Exit Resource World
Send message - is it viewable on rw and discord?
