## Offsets
All offsets reference the latest version S4_Main.exe of the History Edition.
The base address is 0, so to calculate the actual offset use the following methods:
- Cheat Engine: `S4_Main.exe+<Offset>`
- IDA: `<Base Offset> + <Offset>`

The default base offset is `0x400000`.
It is recommended to rebase your IDA database to `0x1000`, to ease interaction with Cheat Engine and developing patches.