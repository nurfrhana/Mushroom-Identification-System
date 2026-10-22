# Requirements

## Functional requirements (what the system must DO)
1. The system shall let users upload photos of mushrooms.
2. The system shall provide detailed explanation of the mushrooms.
3. The system shall also provide a detailed explanation of the toxic lookalike mushroom (if any) within the same page.
4. The system shall let users to save each identification photo, date, and GPS location of their findings.
5. The system shall let the users know if the mushroom type is unknown or cannot be identified by the system and suggest them to avoid from consuming it.

## Non-functional requirements (how the system must PERFORM)
1. The identification page shall load in under 3 seconds.
2. The system shall shows the unknown-species warning if the model confidence is below 70%.
3. The system shall achieve an identification accuracy of at least 80% on the test set of selected mushroom species.
