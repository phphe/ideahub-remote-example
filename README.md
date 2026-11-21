# IdeaHub Remote Repository

IdeaHub is an open-source tool that lets users prove an idea existed before a given point in time, without making it public first.

It computes a content fingerprint from the original idea text and writes the fingerprint into the tag of an immutable GitHub Release (for example, `ideahub-<sha256>`), which serves as the idea's timestamp proof. Once the idea is published, anyone can independently verify it.

This repository stores timestamp proofs for ideas and the published original idea content.

Do not modify the contents of this repository manually, as doing so may invalidate the proofs.

For details, see [IdeaHub](https://github.com/phphe/ideahub).
