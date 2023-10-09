# execute magma cube command

Sends a command to all magma cube entities that are matched by the given selector. This
block uses EntitySelectors from this extension and not TargetSelectors from the mobs
category.

```sig
mobEvents.executeMagmaCubeCommand(mobEvents.createSelector(), MagmaCube.BecomeCalm)
```

## Parameters

* **selector**: A EntitySelector specifying which entities to send the command to
* **command**: An MagmaCube for the command to send to the selected entities.

```package
makecode-minecraft-mob-events=github:microsoft/makecode-minecraft-mob-events
```
