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
- Initiates a new memory scan for a specific value.

### Next Scan
- Refines the current search results based on value changes.

### Undo Scan
- Reverts to the previous scan results.

### Add Address Manually
- Allows manual entry of a memory address.

### Auto Assemble
- Opens the script editor for writing assembly code.

### Pointer Scan
- Initiates a scan for pointers to a specific address.

## Latest Update

Cheat Engine 7.5 - Released February 23, 2023

Changes:
- Removed driver requirement for access memory regions tool
- Added 1 byte jmp instructions
- Added option to skip unpaged memory during scans
- Improved reassemble() function
- Added option to center highlighted disassembler code
- Added individual disable option for memoryrecord hotkeys
- Improved codefilter unwind info
- Added support for pseudo-ops like cmpss/sd/ps/pd
- Added ceserver commands to Lua
- Improved ARM64 disassembler and assembler
- Added option to save/load scanregions
- Added option to skip loading PDB files
- Exposed more functions to newstate threads
- Added ranges scans to groupscan
- Improved freeze+allow increase/decrease for signed values
- Added DPI scaling for trainer forms and controls
- Improved record showassigned/showashex behavior
- Changed texttraces to save as .txt instead of .cetrace
- Improved ccode #include functionality
- Enhanced internal symbolhandler for stdcalled function symbols
- Added ImageIndex property to TTreeNode in Lua
