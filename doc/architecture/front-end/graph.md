digraph {
  node [shape=plaintext];
  _1 [label="1. Record architecture decisions"; URL="0001-record-architecture-decisions.html"]
  _2 [label="2. frontend must be responsive"; URL="0002-frontend-must-be-responsive.html"]
  _1 -> _2 [style="dotted"];
  _2 -> _3 [label="Superceded by"]
  _3 [label="3. Frond end must be responsive in Ipad"; URL="0003-frond-end-must-be-responsive-in-ipad.html"]
  _2 -> _3 [style="dotted"];
  _3 -> _2 [label="Supercedes"]
}
