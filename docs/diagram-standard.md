# Enterprise architecture diagram standard

Each diagram must answer a defined reader question and show accurate causality:
- use nodes for applications, tools, humans, models, data stores, trust domains;
- arrow meaning: data flow, decision, control, feedback, permission or dependency;
- label sources, transformations, permissions, verification, failure and human approvals;
- distinguish proposed vs measured components; never imply a live system based on an illustration;
- preserve readable text at target resolution; supply text alternative and original source format;
- include knowledge IDs for technical assertions and document effective date if volatile.

Color semantics: blue informational flow, green accepted/verified, amber conditional/manual, red denied/error; consistent in all channels.
