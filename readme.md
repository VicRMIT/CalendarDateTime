Allows cleaner DateTime expressions and operations, with support for calendar objects and calendar based operations.

Forked from FluentDateTime https://github.com/FluentDateTime/FluentDateTime

## Usage

Here is some examples of use cases

```csharp
// DateTime operations
DateTime.Now  - 1.Weeks() - 3.Days() + 14.Minutes()
DateTime.Now  + 5.Years()

// Relative DateTime evalutations
3.Days().Ago()
2.Days().Since(DateTime.Now)

// Fluent DateTime estimations
DateTime.Now.NextDay()
DateTime.Now.NextYear()
DateTime.Now.PreviousYear()
DateTime.Now.WeekAfter()
DateTime.Now.Midnight()
DateTime.Now.Noon()

// Current DateTime manipulation
DateTime.Now.SetTime(11, 55, 0)
```
