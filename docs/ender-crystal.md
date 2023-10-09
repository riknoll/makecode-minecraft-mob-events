# execute ender crystal command

Sends a command to all ender crystal entities that are matched by the given selector. This
block uses EntitySelectors from this extension and not TargetSelectors from the mobs
category.

```sig
mobEvents.executeEnderCrystalCommand(mobEvents.createSelector(), EnderCrystal.Explode)
```

## Parameters

* **selector**: A EntitySelector specifying which entities to send the command to
* **command**: An EnderCrystal for the command to send to the selected entities.

```package
makecode-minecraft-mob-events=github:microsoft/makecode-minecraft-mob-events
```
