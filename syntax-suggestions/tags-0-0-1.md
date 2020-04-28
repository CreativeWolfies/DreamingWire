# Syntax suggestion (tags 0.0.1)

## Introduction

This suggestion is the first syntax suggestion for DreamingWire. Most of it is case insensitive. Except for raw inputs.

## Tags

* `ABSTRACTIVITY(GENERIC|FREE|CONTEXT)`:
  Designates the "type" of abstractivity of the following thought. `GENERIC` will force the interpreter to choose the most generic data for the given thought. For instance, if you write `ABSTRACTIVITY(GENERIC) FIND("car")`, it will output a generic and basic 3D model of a car (if the output format is 3D models). `FREE` lets the interpreter choose the best way to interpret this thought as an individual thought. Example: `ABSTRACTIVITY(FREE) FIND("car")` will maybe output a red car for 5 people. `CONTEXT` lets the interpreter find the best way to interpret it depending on the context.
* `VAGUE`:
  Designates the fact that the following thought is not really the thing that the user wanted but instead a description or a hint to find what he meant. When seeing this tag, DreamingWire will try to find the common nodes between two or more vague-tagged thoughts. DreamingWire could also ask if the found common node is closer to what the user meant or not.
* `FIND(most-explicit-node-path-available)`:
  This tag finds the absolute tree of concepts node path for the parameter. It is more efficient if you convert all of your incomplete node paths into absolute node path before putting the DreamingWire code into an interpreter.
* `LINK(...tags)`:
  Links the current thought to other tagged thought.
* `TAG(name)`:
  Current thought's name. This tag name can be used for the `LINK` tag.
* `RAW(raw-data)`:
  Represents data that the parser understood but do not know how to interpret them.
