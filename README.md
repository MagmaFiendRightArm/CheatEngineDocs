# Cheat Engine Docs

## Value Types

### 1. Binary
- Description: Represents data using 0s and 1s.
- Example: `0` = false (off), `1` = true (on)

### 2. Byte
- Description: Stores small numbers from 0 to 255.
- Example: Health value of `100` is represented as byte `100`.

### 3. 2 Bytes
- Description: Stores numbers from 0 to 65535.
- Example: A score of `30000` is represented as 2 bytes.

### 4. 4 Bytes
- Description: Stores larger numbers from 0 to 4294967295.
- Example: Player experience points of `1500000` is represented as 4 bytes.

### 5. Float
- Description: Stores decimal numbers.
- Example: A speed value of `5.5` is stored as a float.

### 6. Double
- Description: Stores larger decimal numbers.
- Example: A large value like `1234567.89` is stored as a double.

### 7. String
- Description: Stores text values.
- Example: Player name `JohnDoe` is stored as a string.

### 8. 8 Bytes
- Description: Stores very large numbers from 0 to 18446744073709551615.
- Example: A large game currency value like `10000000000` is stored as 8 bytes.

### 9. Array of Bytes
- Description: Stores multiple bytes together.
- Example: A sequence of bytes like `01 02 03 04` represents multiple values.

## Cheat Engine Buttons

### New Scan
- Starts a new memory scan for a specific value.

### Next Scan
- Refines the current search results based on value changes.

### Undo Scan
- Goes back to the previous scan results.

### Add Address Manually
- Lets you enter a memory address by hand.

### Auto Assemble
- Opens the script editor for writing code.

### Pointer Scan
- Starts a scan for pointers to a specific address.

## Latest Update

Cheat Engine 7.5 - Released February 23, 2023

Changes:
- Removed driver requirement for access memory regions tool (no more extra drivers needed to read memory).
- Added 1 byte jmp instructions (allows jumps in code with just one byte, making it faster).
- Added option to skip unpaged memory during scans (avoids scanning unused memory, speeds things up).
- Improved reassemble() function (makes rewriting code instructions better).
- Added option to center highlighted disassembler code (makes it easier to read disassembled code).
- Added individual disable option for memory record hotkeys (turn off specific hotkeys without affecting others).
- Improved codefilter unwind info (gives better results when checking stack unwinding).
- Added support for pseudo-ops like cmpss/sd/ps/pd (improves assembly language support).
- Added ceserver commands to Lua (gives more options for scripting).
- Improved ARM64 disassembler and assembler (better support for ARM64 games).
- Added option to save/load scan regions (saves your memory areas for future scans).
- Added option to skip loading PDB files (speeds up startup by not loading debug files).
- Exposed more functions to newstate threads (more options in scripts).
- Added ranges scans to groupscan (scan multiple memory areas at once).
- Improved freeze+allow increase/decrease for signed values (better control over signed numbers).
- Added DPI scaling for trainer forms and controls (makes UI look good on high-DPI screens).
- Improved record showassigned/showashex behavior (better display of values in records).
- Changed texttraces to save as .txt instead of .cetrace (easier to share and view logs).
- Improved ccode #include functionality (better at including external scripts in Cheat Engine).
- Enhanced internal symbolhandler for stdcalled function symbols (better handling of function symbols in scripts).
