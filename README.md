# librarySystemV3

## Description
1. Creates property on libraryStorage object when sent more than one argument
2. Return property value if called with just libraryName

## Parameters
- libraryName
- array
- callback

# Returns
- If called with libraryName only, it returns the callback stored at libraryName
- Else, it returns an error message.

## Notes on Features for librarySystemV3
- librarySystem_v2 does not handle it if dependencies are out of order
- All challenges in librarySystem_v2 should be met
- Creating libraries not in order should still work
- Callback function for each library SHOULD ONLY RUN ONCE
	- Example: If librarySystem('workBlurb') appears 100 times, it ONLY RUNS THE CALLBACK ONCE