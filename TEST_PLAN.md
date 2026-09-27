# Test Plan

## Happy paths
- Create a guestbook.
- Add a valid message.
- Read the resulting message data.

## Failure paths
- Empty message.
- Message over the maximum length.
- Attempt to mutate an unrelated object.

## Verification
Tests should be executed against the selected Sui toolchain before any deployment claim is made.
