---
layout: reference
section: learn
title: Delay
permalink: /learn/ref/Microsoft.Coyote.SystematicTesting.Interception/ControlledTask/Delay
---
# ControlledTask.Delay method (1 of 4)

Creates a Task that completes after a time delay.

```csharp
public static Task Delay(int millisecondsDelay)
```

| parameter | description |
| --- | --- |
| millisecondsDelay | The number of milliseconds to wait before completing the returned task, or -1 to wait indefinitely. |

## Return Value

Task that represents the time delay.

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# ControlledTask.Delay method (2 of 4)

Creates a Task that completes after a specified time interval.

```csharp
public static Task Delay(TimeSpan delay)
```

| parameter | description |
| --- | --- |
| delay | The time span to wait before completing the returned task, or TimeSpan.FromMilliseconds(-1) to wait indefinitely. |

## Return Value

Task that represents the time delay.

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# ControlledTask.Delay method (3 of 4)

Creates a Task that completes after a time delay.

```csharp
public static Task Delay(int millisecondsDelay, CancellationToken cancellationToken)
```

| parameter | description |
| --- | --- |
| millisecondsDelay | The number of milliseconds to wait before completing the returned task, or -1 to wait indefinitely. |
| cancellationToken | Cancellation token that can be used to cancel the delay. |

## Return Value

Task that represents the time delay.

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# ControlledTask.Delay method (4 of 4)

Creates a Task that completes after a specified time interval.

```csharp
public static Task Delay(TimeSpan delay, CancellationToken cancellationToken)
```

| parameter | description |
| --- | --- |
| delay | The time span to wait before completing the returned task, or TimeSpan.FromMilliseconds(-1) to wait indefinitely. |
| cancellationToken | Cancellation token that can be used to cancel the delay. |

## Return Value

Task that represents the time delay.

## See Also

* class [ControlledTask](../ControlledTaskType)
* namespace [Microsoft.Coyote.SystematicTesting.Interception](../ControlledTaskType)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
