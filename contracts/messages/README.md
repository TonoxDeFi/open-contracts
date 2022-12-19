# messages.func
`messages.func` is a library that provides easy function to craft messages.

## Note
Use **OR** for mode modifiers. For example, if you want to send a message that carry unused gas and ignore if it fails, use `CARRY_REMAINING_GAS | IGNORE_ERRORS`.

## Functions
- `() messages::send_empty(coins amount, address to, int mode)`
- `() messages::send_simple(coins amount, address to, cell body, int mode)`
- `() messages::send_nobounce(coins amount, address to, cell body, int mode)`
- `() messages::send_with_stateinit(coins amount, address to, cell state_init, cell body, int mode)`