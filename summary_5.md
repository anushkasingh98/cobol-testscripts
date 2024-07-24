# SeqFileExample.cbl

### File Handling
- Opens "USERS.DATA" for output and input
- Line sequential organization

### Data Structures
- UserRecord:
  - UserId (numeric, 5 digits)
  - UserNames (UserName: 5 chars, RealName: 10 chars)
  - Password (Salt: 2 chars, Hash: 5 chars)
  - CountryCode (2 chars)
- EndOfUserDb condition variable

### Inputs / Outputs
- Accepts user input for UserRecord
- Displays user prompts and record details

### Main Procedure
- Writes user-entered records to file
- Reads and displays records from file
- Loops for data entry until empty input
- Loops for data reading until end of file
- Calls GetUserRecord subprocedure for input