# Ideas / Questions for DreamingWire

## Q: How can you formulate any concept, knowing that there isn't necesserally a worldwide way of formulating concepts in people's heads?

A: Yes, by categorising concepts with a "tree of concepts".

For instance, `sphere` would be encoded in the following way:

- mathematical concept
- mathematical object
- geometrical object
- three-dimensional object
- sphere

## Q: How will DreamingWire handle abstractivity?

A: I think by using a tag ("ABSTRACTIVITY") linked to a integer representing the abstractivity of the DreamingWire code. As this integer increases, the interpretation will be adapted depending on the end user or by the DreamingWire Intepreter itself. If it decreases, the DreamingWire Parser or DreamingWire itself (I don't know yet how these parts will act in the final project) will ask the user more accuracy in his representation of his thought/need/will by asking questions or just letting the user writing more precision.

## Q: What if the user's thought/need/will is vague?

A: This is where the "tree of concepts" comes into place. The parser will try to find one or multiple common nodes to the vague thought/need/will. A tag ("VAGUE") will specify that this category was found using common nodes, which can then be interpreted differently.

## Q: What is the essential data to store one thought/will/need DreamingWire?

A: The "tree of concepts"'s category or leaf of every part of the thought/will/need, its abstractivity, its position at every time, when the thought/will/need is "valid", its importance, the personal value attached to it, and metadata. Metadata is here to store every kind of data like the feeling when thinking about it, why it is there, etc.

## Q: What is DreamingWire?

A: Think of it that way : First, you have got an interface which could be a microphone, a webcam, a picture or whathever you want.

Then, there is the DreamingWire Parser. Its role is you to understand and convert your input into the DreamingWire "code" format. There can be multiple DreamingWire Parsers. Some of them will handle multiple input formats, some of them will not. Some will understand your input different way, etc.

After that, you have your DreamingWire code. Its only function is to represent one or multiple thoughts/wills/needs.

Once this is done, you can give your DreamingWire code to a DreamingWire Interpreter. The role of the interpreter is to convert your thoughts/wills/needs into a concrete thing in the desired format. As well as the DreamingWire Parser, there can be multiple interpreters. Each one can handle multiple formats or not. Mutliple ways of understanding, etc. You get it.

Finally, you have the application, which is the concrete representation of your thoughts/wills/needs in the desired format(s). It could be audio, video, 3D models, etc.

## Q: How will a DreamingWire-encoded will look like?

A: I think a bit like SQL: a lot of text and some symbols like parentheses.
