# Use `Enum.scan` to Calculate Prefix Sum


Examples:

```
iex> a = [1,5,3]
[1,5,3]
iex> Enum.scan(a, &(&1+&2))
[1,6,9]
```

Documentation: [https://hexdocs.pm/elixir/Enum.html#scan/2](https://hexdocs.pm/elixir/Enum.html#scan/2)
