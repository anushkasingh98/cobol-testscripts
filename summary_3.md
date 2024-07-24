# NestedIFExample.cbl

### Data Structures
- A: 2-digit numeric
- B: 2-digit numeric
- RESULT: 4-digit numeric
- FORMATTED: 9-digit numeric with leading zero suppression

### Inputs / Outputs
- Inputs: Two user-entered values (A and B)
- Outputs: Display of entered values and computation result

### Main Procedure
- Accept two values from user
- Compute sum of A and B
- Nested IF structure:
  - Outer condition: A < 10 AND B > 10
  - Inner condition: RESULT > 50
- Display result based on conditions:
  - If RESULT > 50: Display message
  - Else: Display formatted result
- If outer condition false: Display "Whatever"