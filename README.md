# Menumatic

Create professional looking dynamic selection menus quickly and easily!

## Usage:

```
$ ls | menumatic
```

```
$ ruby -e 'Path["*"].map{|fn| {title: fn, command: "open #{fn}", icon: fn.ext} }.to_json' | menumatic
``` 
