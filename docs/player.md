# execute player command

Sends a command to all player entities that are matched by the given selector. This
block uses EntitySelectors from this extension and not TargetSelectors from the mobs
category.

```sig
mobEvents.executePlayerCommand(mobEvents.createSelector(), Player.GainBadOmen)
```

## Parameters

* **selector**: A EntitySelector specifying which entities to send the command to
* **command**: An Player for the command to send to the selected entities.

```package
makecode-minecraft-mob-events=github:microsoft/makecode-minecraft-mob-events
```
