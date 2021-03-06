# example

    import "github.com/maiconio/godocdown/example"

Package example is an example package with documentation

    // Here is some code
    func example() {
    	abc := 1 + 1
    }()

### Installation

    # This is how to install it:
    $ curl http://example.com
    $ tar xf example.tar.gz -C .
    $ ./example &

### Index

* [Constants](#constants)
* [Variables](#variables)
* [func  Example](#func--example)
* [type ExampleType](#type-exampletype)
    + [func  NewExample](#func--newexample)
    + [func (ExampleType) Set](#func-exampletype-set)


#### Constants
    const (
    	Another = 0
    	Again   = "this"
    )

Another constant section

    const Other = 3

A constant section

#### Variables

    var (
    	This = 1

    	// A description of That
    	That = 2.1
    )

A variable section

#### func  [Example](#example)

    func Example()

Example is a function that does nothing

#### type [ExampleType](#exampletype)

    type ExampleType struct {
    	First  int
    	Second string
    	Third  float64
    	Parent *ExampleType
    }


ExampleType is a type of nothing

    // Here is how to use it:
    return &ExampleType{
    	First: 1,
    	Second: "second",
    	nil,
    }

#### func  [NewExample](#newexample)

    func NewExample() *ExampleType


#### func (ExampleType) [Set](#set)

    func (ExampleType) Set() bool



--
This was via template
