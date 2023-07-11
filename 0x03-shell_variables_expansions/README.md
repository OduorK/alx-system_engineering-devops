0x03. Shell, init files, variables and expansions
0. <o>
#!/bin/bash

1. Hello you
#!/bin/bash
echo "hello $USER"

2. The path to success is to take massive, determined action
#!/bin/bash
export PATH=$PATH:/action

3. If the path be beautiful, let us not ask where it leads
#!/bin/bash
echo $((' echo $PATH | grep -o ":/" | wc -1 ' +))

4. Global variables
#!/bin/bash
printev

5. Local variables
#!/bin/bash
set

6. Local variable
#!/bin/bash
BEST = "School"

7. Global variable
#!/bin/bash
export BEST="School"

8. Every addition to true knowledge is an addition to human power
#!/bin/bash
echo $(($TRUEKNOWLEDGE + 128))

9. Divide and rule
Write a script that prints the result of POWER divided by DIVIDE, followed by a new line
#!/bin/bash
echo $(($POWER/$DIVIDE))

10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
Write a script that displays the result of BREATH to the power LOVE
#!/bin/bash
echo $(($BREATH**LOVE))

11. There are 10 types of people in the world -- Those who understand binary, and those who don't
Write a script that converts a number from base 2 to base 10
#!/bin/bash
echo $((2#$BINARY))

12. Combination
Create a script that prints all possible combinations of two letters, except oo
#!/bin/bash
echo {a..z}{a..z} | tr "" "\n" | grep -v "oo"

13. Floats
Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM
#!/bin/bash
printf "%.2f" $NUM | sort

14. Decimal to Hexagon
#!/bin/bash
printf "%x\n" $DECIMAL

15. Everyona is proponent
#!/bin/bash
tr A-Za-z N-ZA-Mn-za-m

16. 102 odd
#!/bin/bash
paste -d, -- | cut -d, -f1

17. Instant start
#!/bin/bash
printf "%o\n" $(( $((5#$(echo $WATER | tr water 01234))) + $((5#$(echo $STIR | tr stir. 01234))) )) | tr 01234567 bestchol
