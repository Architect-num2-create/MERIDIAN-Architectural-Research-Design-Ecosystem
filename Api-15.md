# API

Not code yet — the shape code will eventually take, so the Core can be queried instead of just read.

`get_canon()` → the current Canon list, numbered.
`get_claim(id)` → a Claim, its epistemic tag, and its full provenance chain back to a Source.
`get_contradiction(id)` → a Contradiction Map entry, both sides stated, no resolution forced.
`get_rejected()` → the Rejected register, with what each rejection was tested against.
`get_unresolved()` → the Unresolved register, with what each item blocks downstream.
`submit_fork(type, source_list, contradiction_map)` → registers a new Fork under one of the four Taxonomy types; rejects submissions missing a Contradiction Map, per Fork Protocol step 3.

Nothing here writes to Canon directly. Canon only changes through the Constitution's amendment rule — the API can read everything and propose a Decision, but it can't ratify one by itself.
