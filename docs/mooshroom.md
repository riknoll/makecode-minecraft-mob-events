# execute mooshroom command

Sends a command to all mooshroom entities that are matched by the given selector. This
block uses EntitySelectors from this extension and not TargetSelectors from the mobs
category.

```sig
mobEvents.executeMooshroomCommand(mobEvents.createSelector(), Mooshroom.TransformIntoACow)
```

## Parameters

* **selector**: A EntitySelector specifying which entities to send the command to
* **command**: An Mooshroom for the command to send to the selected entities.

```package
makecode-minecraft-mob-events=github:microsoft/makecode-minecraft-mob-events
```
