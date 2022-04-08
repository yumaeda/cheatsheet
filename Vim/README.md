# Vim
## Prepend text to all the lines
```sh
:%s/^/TEXT/g
```

## Append text to all the lines
```sh
:%s/$/TEXT/g
```

## Remove `abc` from the beginning of lines
```sh
:%s/^abc//
```

## Remove BOM
```sh
:set nobomb
:w 
```

## Remove lines, which contains certain text
```sh
:g/TEXT/d
```

## Remove empty lines
```sh
:g/^$/d
```

## Remove duplicate lines and sort
```sh
:sort u
```
