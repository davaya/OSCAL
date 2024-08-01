# OSCAL Information Model

> An OSCAL Metaschema defines the information structures that define an OSCAL model in a format-neutral form.
Documentation about the meaning (semantics) and use of a given metaschema structure is provided on the
Metaschema [website].

An OSCAL Abstract Information Model is an alternate method of specifying the information structures that define an
OSCAL model in a format-neutral form.
A Logical Data Model, or *Information Model*, defines the OSCAL model structure, and Logical Data, or
*Information*, is the format-neutral internal representation of OSCAL documents
that allows them to be loaded and saved in multiple formats. Internal representation refers to
the state of the program/application variables holding an IM.

The goals of the IM project are to:
* Develop an Information Model that can perform all functions currently performed by Metaschema
* Introduce the Information Model to the OSCAL community to get feedback on its appearance, approachability
and usability compared to Metaschema XML source documents
* Examine Metaschema from another viewpoint, identify potential improvements to the Metaschema models

The project does not propose any modification to the OSCAL development and release process. It is a
proof of concept that uses Metaschema as the source of OSCAL releases and OSCAL content as the test material
to validate equivalence between the Metaschema and Information Model approaches. Any differences in test
results between the two approaches may lead to change proposals to the Metaschema models, the Information models,
or both.

Terminology: data modeling has traditionally described conceptual, logical, and physical data models.
The information models discussed here are **logical data models**, or abstract schemas, and are designed to
be as familiar and compatible as possible with data modeling practice. The XML and JSON schemas derived from the
Metaschema modules or information models are **physical data models**, or concrete schemas.

The proof-of-concept goals are to:
* validate JSON and XML OSCAL data directly against the IM
* generate JSON and XML OSCAL schemas that can also validate that data with results identical to the
Metaschema-generated schemas
* demonstrate additional serialization formats from the same IM

For detailed information on the IM approach, see [An Abstract OSCAL Information Model](oscal-im.md)