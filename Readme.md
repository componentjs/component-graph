
# component-graph

  Dependency graphs for component(1).

## Installation

    $ npm install -g component-graph

Also requires graphviz:

    $ brew install grapviz

## Example

```
$ cd myproject && component graph --out graph.png
```

## Usage

```

  Usage: component-graph [options]

  Options:

    -h, --help           output usage information
    -t, --type <name>    graph type [neato|twopi|fdp|dot]
    -f, --format <name>  set output format [png]
    -o, --out <path>     output to the <path> [out.png]

```

## Types

### dot

  ![](http://f.cl.ly/items/2H0K2h0I0B460V0A2G3n/dot.png)

### twopi

  ![](http://f.cl.ly/items/3g3I283o3U0K0F0X3o3m/twopi.png)

### fdp

  ![](http://f.cl.ly/items/3T1N373F1h1k1L0Z0s1G/fdp.png)

## License

  MIT
