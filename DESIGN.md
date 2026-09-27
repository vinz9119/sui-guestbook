# Design

The guestbook is modeled as a shared object containing a bounded collection of messages.

## Invariants
- Empty messages are rejected.
- Message length has an explicit maximum.
- Each stored message records its sender.
- Mutation functions operate only on the intended shared object.
- Tests cover both valid and invalid input.

## Future implementation
A Move package can implement the model once the exact Sui framework version is selected and verified against the official toolchain.
