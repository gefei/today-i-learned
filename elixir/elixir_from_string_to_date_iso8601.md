# Convert String to Date

In Elixir, the function `Date.from_iso8601(str, calendar \\ Calendar.ISO)`
is used to create a `Date` object from a String.

```
iex> Date.from_iso8601("2001-01-04")
{:ok, ~D[2001-01-04]}
```

The function `DateTime.from_iso8601/2` is similar, but returns a `DateTime`
object.
