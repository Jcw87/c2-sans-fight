# Jumps #
Some attacks needs to jump to other lines for them to work.
There are commands to provide this functionality.

### Labels ###
You can create a label instead of calling a function by putting the desired label name in column 2 and prefixing it with ":". The label will allow you to peform jumps to this line by using the label name instead of the absolute line number. You can see an example of this [here](Examples/Labels.csv).

Note that the time delay in column 1 is still respected on labels.

### JMPABS (Jump absolute) ###
Jump to a specific line on the attack
* AbsoluteLineNumber

### JMPREL (Jump relative) ###
Jump to a line number relative to the current one. Positive numbers jump forward, and negative numbers jump backward
* RelativeLineNumber

### JMPZ (Jump zero) ###
Jump to a line if the test value is 0
* AbsoluteLineNumber
* TestValue

### JMPNZ (Jump not zero) ###
Jump to a line if the test value is not 0
* AbsoluteLineNumber
* TestValue

### JMPE (Jump equal) ###
Jump to a line if the test values are equal
* AbsoluteLineNumber
* TestValue1
* TestValue2

### JMPNE (Jump not equal) ###
Jump to a line if the test values are not equal.
* AbsoluteLineNumber
* TestValue1
* TestValue2

### JMPL (Jump if less) ###
Jump to a line if the first test value is less than the second test value
* AbsoluteLineNumber
* TestValue1
* TestValue2

### JMPNL (Jump if not less) ###
Jump to a line if the first test value is not less than the second test value
* AbsoluteLineNumber
* TestValue1
* TestValue2


### JMPG (Jump if greater) ###
Jump to a line if the first test value is less than the second test value
* AbsoluteLineNumber
* TestValue1
* TestValue2


### JMPG (Jump if not greater) ###
Jump to a line if the first test value is less than the second test value
* AbsoluteLineNumber
* TestValue1
* TestValue2
