- Restore built-in pointer grabbing (the shell indirection brought by `sxhkd` slows things down and its asynchronous nature makes resizing jerky). How can we avoid copying too much code from `sxhkd`?.
- Set more attributes in `make_client` (instead of doing it in `apply_rules`) and don't pass `XCB_NONE` as argument.
- Internal nodes selectors/actions: labels?
- Invisible state.
- Use BSD `sys/{queue/tree}.h` for {list,tree} structures?
