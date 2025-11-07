# TAL-example
this is test for TAL example
## Files

| File | Purpose |
|------|--------|
| `GREET.TAL` | **Source code** (TAL program) |
| `GREET`     | **Object & executable** (after compile/bind) |

---

## How to Compile & Run

```bash
# 1. Compile the TAL source
TAL /IN GREET.TAL/ GREET

# 2. Bind into executable
BIND GREET

# 3. Run the program
RUN GREET