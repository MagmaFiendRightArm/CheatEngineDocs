# Cheat Engine Value Types

this repository contains information about different value types in cheat engine.

## Value Types

### 1. Binary
- **Description:** represents data using 0s and 1s.
- **Example:** `0` = false (off), `1` = true (on)

### 2. Byte
- **Description:** stores small numbers from 0 to 255.
- **Example:** health value of `100` is represented as byte `100`.

### 3. 2 Bytes
- **Description:** stores numbers from 0 to 65535.
- **Example:** a score of `30000` is represented as 2 bytes.

### 4. 4 Bytes
- **Description:** stores larger numbers from 0 to 4294967295.
- **Example:** player experience points of `1500000` is represented as 4 bytes.

### 5. Float
- **Description:** stores decimal numbers.
- **Example:** a speed value of `5.5` is stored as a float.

### 6. Double
- **Description:** stores larger decimal numbers.
- **Example:** a large value like `1234567.89` is stored as a double.

### 7. String
- **Description:** stores text values.
- **Example:** player name `JohnDoe` is stored as a string.

### 8. 8 Bytes
- **Description:** stores very large numbers from 0 to 18446744073709551615.
- **Example:** a large game currency value like `10000000000` is stored as 8 bytes.

### 9. Array of Bytes
- **Description:** stores multiple bytes together.
- **Example:** a sequence of bytes like `01 02 03 04` represents multiple values.
