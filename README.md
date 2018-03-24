# Boris Bikes

Using Ruby Object Oriented Programming to design docking stations for Boris Bikes.

## Installation

`git clone path-to-repo`

## Usage

Feature Driven in irb:

`irb`

## Running Tests

Unit Testing with RSpec:

`rspec`

## User Stories

```
As a person,
So that I can use a bike,
I'd like a docking station to release a bike.

As a person,
So that I can use a good bike,
I'd like to see if a bike is working
```

## Features

* Docking Station is an object that has as an empty container attribute
* Bike starts as a dumb object
* Docking Station can store bikes in its container
* Docking Station can release a bike from its container
* Docking Station can only release a bike if it is working
* Bike knows if it is working or not
