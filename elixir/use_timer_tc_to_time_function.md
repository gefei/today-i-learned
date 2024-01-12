# Use `:timer.tc` to Time a Function

```
{time_in_microsecond, result_of_the_function} = :timer.tc{function_to_time, [parameters]}
```

Examples:

```
iex> :timer.tc(fn x,y -> x + y end, [3, 5])               
{4, 8}

iex> :timer.tc(IO, :puts, ["hello"])
hello
{53, :ok}

iex> :timer.tc(&IO.puts/1, ["hello"])
hello
{54, :ok}
```

A microsecond is a 1_000_000th of a second
