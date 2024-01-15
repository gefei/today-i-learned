# Use `length` to Get the Number of Parameters Expected by a Function

```
> function f(a) { console.log(a) }
undefined
> f.length
1
> 
> function f(a, b) { console.log(a+b) }
undefined
> f.length
2
> 
```

Note that parameters with default values do not contribute to `length`
```
> function f(a, b=1) { console.log(a+b) }
undefined
> f.length
1
> 
```