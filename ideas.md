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

A: Think of it that way : Interface (microphone, webcam, picture, text, ...) -> DreamingWire Parser (one parser per format. There can be multiple versions of DreamingWire Parser for one format.) -> DreamingWire (code/text) -> DreamingWire Interpreter (one Interpreter per format. There can be multiple versions of DreamingWire Interpreter for one format to allow different ways of interpretation) -> Application (audio, video, image, text, ...)

## Q: How will a DreamingWire-encoded will look like?

A: I think a bit like SQL: a lot of text and some symbols like parentheses.
