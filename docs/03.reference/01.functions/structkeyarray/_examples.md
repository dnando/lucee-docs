### Unordered Structs (default)

```luceescript+trycf
animals = {
	cow: "moo",
	pig: "oink",
	cat: "meow",
	bird: "chirp"
};
dump(StructKeyArray(animals));
```

### Ordered Structs

```luceescript+trycf
animals = [
	cow: "moo",
	pig: "oink",
	cat: "meow",
	bird: "chirp"
];
dump(StructKeyArray(animals));
```