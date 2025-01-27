# Intersections and Unions
Pandas deprecated (and finally removed) the use of the operators `&` and `|` for set intersections and unions.

Instead, you now need to use the `.intersection()` and `.union()` methods that index objects have.

For example, instead of writing:

```python
index_1 & index_2
```

you need to write:

```python
index_1.intersection(index_2)
```

Similarly for unions, instead of this:

```python
index_1 | index_2
```

you need to write this:

```python
index_1.union(index_2)
```

