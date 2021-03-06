# Gravity

A set of modular SCSS components that can be used for building responsive websites.

Unlike bigger frameworks such as Bootstrap and Foundation, Gravity is very minimal.

It gives you the essential components (grids, mixins, good default styles) 
without including a ton of stuff you don't need.

Gravity uses bourbon for mixins and neat for grids

+ http://bourbon.io/
+ http://neat.bourbon.io/

## Modules

+ Base (essential styles, reset etc)
+ Grid (grids via neat)
+ Typography (headings, paragraphs, website typography)
+ Components (styling for tables, forms, buttons etc )

## Use

This framework requires Ruby.

The following task will install the dependencies (gems, build the assets).

After this task has run all css should be available under /compiled/all.css

```
rake gravity:build
```

## Updating

To update the framework run

```
rake gravity:update
```

## Compile

To watch and compile all SCSS files into CSS run the following command. 

It will create a file called all.css in compiled/all.css.

```
./compile
```

