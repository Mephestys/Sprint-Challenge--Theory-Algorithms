## Regular Expressions

1. **antelope(s) rock(s) out regex:** `/antelopes? rocks? out/g`

1. **goat/moat but not boat regex:** `/[gm]{1}oat/g`

1. **YYYY-MM-DD regex:** `/(\d{1,4})\-(\d{1,2})\-(\d{1,2})/g`

## State Machines

1. **Regex State Machine:** [regex-state-machine.svg](regex-state-machine.svg)

1. **Lion State Machine:** [lion-state-machine.svg](lion-state-machine.svg)

1. **VT-100 Terminal Escape Sequences:** `/(ESC|\e)\[(\d{1,};?m?)(\d{1,}f?)?/g`