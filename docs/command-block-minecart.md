# execute command block minecart command

Sends a command to all command block minecart entities that are matched by the given selector. This
block uses EntitySelectors from this extension and not TargetSelectors from the mobs
category.

```sig
mobEvents.executeCommandBlockMinecartCommand(mobEvents.createSelector(), CommandBlockMinecart.CommandBlockActivate)
```

## Parameters

* **selector**: A EntitySelector specifying which entities to send the command to
* **command**: An CommandBlockMinecart for the command to send to the selected entities.

```package
makecode-minecraft-mob-events=github:microsoft/makecode-minecraft-mob-events
```
