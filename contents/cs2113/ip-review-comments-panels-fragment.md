
%%[This page was last updated on Feb 08 2026]%%

    
<panel type="info"  collapsed>
<div slot="header">

### 1. LOU ..U YU `@lukelouyu` (18 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761733636" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Follow the switch statement standrard for CS2113, Good Job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761738859" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Implement SLAP on your code, very good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761762712" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

printer(String line) doesn’t use line and only wraps printHorizontalLine()—suggest remove it or rename to printDivider() and drop the parameter for readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761767369" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good use of constant 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761785359" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Code quality: String stringAfterCommand = line.substring(line.indexOf(' ') + 1); will crash for commands with no space (e.g., "list", "bye"). Also line.split(" ") may produce unexpected empty tokens if multiple spaces exist.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761786776" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Coding quality: Consider adding a default: branch in the switch to handle unknown commands (e.g., show “invalid command”).
Improves readability because the control flow becomes explicit and user feedback is predictable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761789818" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Naming/readability: storeActivity(Task activity) stores tasks, not “activity”. Consider renaming to addTask(Task task) / storeTask(Task task) for clearer intent.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761794177" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Remove unused local variable String line = "" in getFirstScanner() (keeps code clean and reduces noise).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761795738" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

label: + break label; works but is uncommon and reduces readability. Consider using a boolean isRunning loop condition or return; after exitMartin().
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761800209" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

You put "Yes Sir ......." three times in three different functions. Maybe try to do a seperate function for this line of code to ensure good readability  
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761801295" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

personally i feel it is quite redudant to have a separation for printer. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761801959" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Good jon on putting a description for each function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761802553" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

valid naming for boolea function name
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#pullrequestreview-3748459089" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED

Generally you have mostly followed the coding standard (such as he code is fairly readable (good use of constants and a clear switch for commands) ) but there is always a room for improvement. Also, you can try to consider to create more class for Todo, Dealine, Event for better cohension. (Like dont congest every function into one Martin.java) Keep it up!!!!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#discussion_r2762378970" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

recommend to do a function for this part of the code to ensure the SLAM 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#discussion_r2762381591" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

use switch instead of if-else for better readibility. (Be aware of special coding standard for CS2113 regarding the switch)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#discussion_r2762385226" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

consider to create a function these code for better readibility
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#pullrequestreview-3749199583" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED

Generally your code is quite fine, just need to improve on readibility
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 2. WANG..UHAO `@w-chuhao` (19 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2761784007" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Very smart idea to filter the commands out as another class, makes the code cleaner
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2761791893" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Very very clean Main, because you used a lot of classes for your various functions, very easy to read and understand what your code is trying to do. Good use of abstraction
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2761797888" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Return on a separate line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2761798985" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good indentation for switch/case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2761800883" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Good use of comments throughout the whole code, helps me understand what each part of your code is doing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2761803702" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Include plural form for your public classes, e.g Event should be events, Task should be Tasks as you will be creating more than one Task/event
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2761804682" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Overall very clean and readable code, follows coding conventions well
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#pullrequestreview-3748515039" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761731608" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Maybe you can put this class Task in a separate java file
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761736182" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Maybe instead of using if/else, can use switch statements incase there are more functions for you to add in the future, if/else can get a bit messy
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761738305" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Good that you use different functions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761740100" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Nice indentations for the if/else block
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761755439" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

For your class Task, it needs to be be in plural form as you will be creating more than 1 Task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761763716" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Mostly correct coding standard conventions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761773262" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

Good naming standard, proper use of capitalisation for the naming conventions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761775279" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

Good white spacing between the lines of code which improves readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761778839" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

Great to split into various functions in main, improves readabilityto help me understand what main is supposed to do.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#pullrequestreview-3748456844" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#pullrequestreview-3748503020" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 3. NI S..YONG `@shiyong52` (17 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772037785" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Maybe can use explicit imports instead of wildcare imports here to make it clearer what dependencies this class relies on
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772041392" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Perhaps a more intuitive variable name here, like tasks instead of "li"?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772044216" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Nicely formatted ASCII art 👍Since it is a constant, should the name be in SCREAMING_SNAKE_CASE to match the standard for constants?

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772048108" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good that sc.close() is called to release resources. 👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772059975" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Should the event block prints "Todo Added" instead of "Event Added"?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772066449" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

i like that K&R (Egyptian) brace style is used consistently throughout the code👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772068184" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Nice use of @OverRide on annotations 👍 This clearly communicates intent and follows best practices.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772078858" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Should the class name be singular, like "Event", since it represents one object?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#pullrequestreview-3760522050" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I found your code easy to read and well-structured. I like the consistent use of K&R brace style and the nicely formatted ASCII art 👍. A few minor nits: consider using explicit imports instead of wildcards, and perhaps a more intuitive variable name than li. Also, the event block currently prints "Todo Added" instead of "Event Added". LGTM otherwise!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771963708" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I like that constants are consistently named using SCREAMING_SNAKE_CASE 👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771974628" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

MAX_TASKS is clearly named and easy to understand. Nice use of a constant instead of a magic number.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771984151" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

i like that the main method is short and well-structured 👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771985807" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Nice use of the DIVIDER constant instead of a hardcoded string.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771995325" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Method name parseTaskNumber is clear and descriptive 👍

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2772003812" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

i like that K&R (Egyptian) brace style is used consistently throughout the code👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2772022748" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

Nice use of @Override on annotations 👍  This clearly communicates intent and follows best practices. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#pullrequestreview-3760427722" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I like the consistency in naming, indentation, and brace usage throughout the file👍
The code follows the stated Java coding standards closely. LGTM.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 4. AARA..JESH `@aaravvr` (18 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767409253" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Should there be consistent spacing around operators? Line 28 has "i+1" but standard practice is "i + 1" for readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767412735" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

these markers in the code need to be resolved
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767413910" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Should the magic number 7 (in "unmark" + 7) be explained? Perhaps a comment or constant like UNMARK_PREFIX_LENGTH would make this clearer?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767415919" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Similar to above, the magic number 5 in "mark"+5 could be clearer. What does the 5 represent?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767419364" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

The main method is quite long (40+ lines) with multiple levels of if-else nesting. Would it make sense to extract some logic into separate methods like handleListCommand(), handleMarkCommand(), etc.? This would improve readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767420910" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like the ASCII art logo! Clean and well-formatted
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767422953" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like the class name "Task". It's a noun and clearly describes what the class represents. Follows the naming guidelines well!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767423880" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice use of "getStatusIcon()", uses a verb and clearly explains what the method does
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767428134" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like the inline comment explaining the ternary operator. Helpful for readability!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#pullrequestreview-3754870363" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

The code has multiple markers that must be resolved first. For code 
quality: the main method could benefit from being broken into smaller methods 
to reduce length and nesting. A few magic numbers could be replaced with named 
constants for clarity. Good naming conventions overall!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2767361042" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

I noticed there's no Javadoc comment for the Timer class. Would it be good to add one describing what this class does?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2767363476" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Should there be a space after the period for better readability? 
Currently: "." but perhaps ". " would be clearer
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2767365125" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Should handleMark() have a Javadoc comment? I noticed the same issue in several other methods too (printList, printTaskAdded, parseIndex, etc.)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2767365890" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

I like how you've used SCREAMING_SNAKE_CASE for LINE and MAX_TASKS, and the clean refactoring into helper methods. Code is much more readable now!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2767368277" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

Should the Task class have a Javadoc comment? I noticed the same for Todo, Deadline, and Event classes too.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2767370455" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

I like the use of 'final' for fields throughout Task, Deadline, Event, and Todo classes. Good practice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#pullrequestreview-3754510697" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED

Nice work following the SE-EDU coding standards. I like the consistent naming and bracket usage throughout! The main thing I noticed was missing Javadoc comments for classes and methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#pullrequestreview-3754819236" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED

Code is clean with classes refactored into separate files. Code follows SE-EDU 
naming standards well. Main feedback will be to add Javadoc comments for classes and 
methods
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 5. JOVI..JOSH `@JovianJosh` (17 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771861184" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Class is written clearly in PascalCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771863249" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Constant is written correctly in full uppercase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771872222" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Class name is defined clearly in PascalCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771872894" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Constants are declared clearly in full uppercase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771879148" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Indentation is done correctly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771881422" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Uses K&R style bracket, Good coding standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771883696" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good import statement, only import what is needed
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#pullrequestreview-3760284528" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

Commit message  can be more specific
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#pullrequestreview-3760299154" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Commit can be more specific and split into multiple commits
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771900477" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good import statement, only imported what is needed
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771902172" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Consider adding some comments on the code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771905617" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

The naming of the variable can be quite confusing as both variables has the same name
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771909477" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Add more comments for this chunk of code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771911209" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Good naming with camel case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771913839" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

Good and clear class definition
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760337695" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good and clear commit message, clearly stated the changes
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760339526" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 6. NICH..NGYI `@nicholaslauhy` (15 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2767407817" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Nice catch with the .equalsIgnoreCase for error catching! Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2767409655" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I think for variables it should be in camel case (for example: String longLine)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2767422401" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Typical Java formatting would be size++ or size+=1, not size ++
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2767424809" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Instead of size, maybe you could give a more informative variable name?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2767429832" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

To increase clarity for the reader, you can set 100 as a static final constant and call it
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#pullrequestreview-3754868996" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job so far, hope to see more from you!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767439221" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Nice error catching with the trim()! Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767445002" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice error catching again for equalsIgnoreCase(), also good use of camelCase, following the Java standards. Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767447462" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Instead of using System.out.println("-----------"), you can declare the ----- as a divider instead, so that it looks cleaner on your code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767456442" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good use of commenting to help a user that is not very proficient with Java to understand. Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767458536" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Very neat and readable, making it very pleasant to read - goodjob!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767464150" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Good use of multiple methods to help you to neaten the code and increase readability, using the SLAP framework. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767469135" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Good use of switch instead of if-else statements to apply what we learnt... goodjob!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#discussion_r2767473332" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

I think having many variables in one method is not very neat, even though it is a constructor. I think can use getter and setters if you need to use private variables.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#pullrequestreview-3754903135" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job so far! Look forward to reading more of your code :)
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 7. KOH .. RUI `@kohtzerui` (14 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762310003" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Noice! Really like the ASCII art
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762312394" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Really nice, creating a DIVIDER string to properly format a line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762313766" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Maybe logo could be defined together with DIVIDER est. in a separate file
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762317970" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good habit! Importing specific files :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762319033" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Agreed, well managed code into a Class :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762321270" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Not sure if the 4 spaces rule is upheld, but based on Github as long its consistent its good :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#pullrequestreview-3749122342" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

NICE, really neat PR compared to my first one, Thanks :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762282846" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Not a coding standard issue: 

'String logo = """
    ______________________________
    |  ___________________________ |
    | |                                         | |
    | |             FRIDAY                 | |
    | |___________________________| |
    |_____________________________|
    """;

System.out.println("Hello I'm\n" + logo + "What can I do for you?");'

You can consider using a formatted string to present the initial interface better :)

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762288273" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I realised the formatted string got compressed, hopefully the idea is clear
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762293045" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Maybe you consider adding all this formatting into a separate file import since there is no GUI to this project :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762302746" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Personally, I think you did a great job! I think having nested if statements help with readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762304007" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Yup agreed here, should just define a static constant at the start here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762304776" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Good idea!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#pullrequestreview-3749090886" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 8. SIM ..LSON `@alsonsim` (14 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2766792512" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Command dispatch fall-through: All switch cases lack proper breaks after most branches. This causes unintended fall-through, so “list” may fall into “mark”, “unmark”, or default behavior. Add appropriate breaks to each case (including after validations and error messages).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2766793828" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Test for empty tasks: In “list”, if there are no tasks, you should handle it gracefully (e.g., print a message saying the list is empty).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2766797686" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Clear structure: A simple REPL loop with commands (list, mark, unmark, bye) and a Task class (assumed) is a good starting point for a small console chatbot.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2766797954" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Multilingual touch: Mixing Japanese and English prompts gives character and could be useful for UX in your project.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2766798270" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Visuals: The ASCII logo and borders help delineate output sections and give Sallybot personality.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2766799620" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Use private fields instead of protected unless you specifically plan subclassing; protected exposes state to subclasses and same-package classes, which weakens encapsulation. This is the biggest improvement.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#pullrequestreview-3754215104" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

The main things holding it back are a couple of correctness bugs in command parsing/control flow and some structure choices that will make the code harder to extend. Well done!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2766805432" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Donny is a really good name!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2766805915" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

You create the Scanner once and reuse it, which avoids the repeated-allocation pattern from your earlier code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2766806588" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

equalsIgnoreCase("list") / equalsIgnoreCase("bye") is a reasonable quick way to support case-insensitive commands
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2766807301" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

String[] list = new String[100]; with list[size] = line; size++; will throw ArrayIndexOutOfBoundsException once the user adds the 101st task (index 100 is outside a length-100 array).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2766807697" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Fix: use ArrayList&lt;String> (dynamic growth) or at least check if (size == list.length) before inserting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#discussion_r2766813992" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

list prints an extra blank line per item because you do System.out.println((i + 1) + "." + list[i] + "\n"); (println already ends with a newline).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/163#pullrequestreview-3754227624" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, clean, readable loop and the Scanner is created once, which is good practice for console apps.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 9. LIM ..THAN `@Kailer811` (15 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772561787" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good method naming
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772564064" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good usage of method to print the divind lines, method naming is correct as well
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772569681" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good use of inheritance
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772572432" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good use of override and proper commentation of it
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#pullrequestreview-3761124776" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2772579996" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Maybe opening method could have been in another file, but crazy good intro
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2772583026" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of inheritance of Task class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2772584735" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

good use of super 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2772587026" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

done should be named to isDone to match coding standards

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#pullrequestreview-3761145279" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772595383" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

good use of startswith to find which command
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772599735" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

maybe should bring the classes to another .java file
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772603895" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

good use of super
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772606928" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

ternary operator is abit complicated, maybe could be broken done, or add comment for clarity
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#pullrequestreview-3761161395" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 10. ABHI..AJEE `@AbhijitBalajee` (15 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#discussion_r2766912276" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#discussion_r2766914324" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good use of a separate helper method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#discussion_r2766917631" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good edge case handling
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#discussion_r2766924899" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Consider using "else if" statements instead of "if.. continue" as a good practice
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#discussion_r2767770773" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

You could alternatively directly assign the description and isDone using "this" 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#discussion_r2767894084" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Do consider using more helper methods to make the code more readable 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#discussion_r2767903204" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

The mark and unmark blocks are almost identical except for a few changes, so consider using a helper method to avoid duplication
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#pullrequestreview-3754331611" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job on what you have done so far
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/49#pullrequestreview-3755499812" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2767804379" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Violates "Practice KISSing" principle, do consider using a task class to encapsulate both properties
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2767828187" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Avoid magic numbers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2767831219" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Do try to avoid deep nesting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2767834760" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

You could alternatively use helper methods for a cleaner code and avoid SLAP violations
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2767861548" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Good use of scanner cleanup
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#pullrequestreview-3755377601" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job on what you have done so far, but do try to implement more methods to make the code more readable and neat
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 11. RAJA..VEEN `@rpraveen7` (15 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2762476731" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Methods have camelCase, good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2762479384" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Boolean variables/methods is named to sound like booleans, good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2762481958" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good comments, makes it easier for me to understand your code.

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2762489952" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Could use a case statement here and the variables such as mark, unmark, todo, deadline and event can be constants which you can declare at the start of the code. 

E.g private static final String MARK_COMMAND = "mark";
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#pullrequestreview-3749305981" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2761905498" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Avoid this long method in your main argument. Can make a seperate function saying printLogo().
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762370030" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Avoid magic numbers. Define a constant like private static final int MAX_TASKS = 100; and use it throughout your code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762378808" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Guideline violated: Use Name to Explain 
The names should explain the entity accurately and make it clear to readers.
outputDivider or taskListBorder instead of separator for the name.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762394992" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I would say avoid deep nesting, maybe clean up the code by having an early return to function.        
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#pullrequestreview-3748651684" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/171#discussion_r2761888868" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Could have made a seperate function such as printWelcomeMessage() to display this. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/171#discussion_r2761893028" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Followed instructions properly, good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/171#discussion_r2761894287" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Not sure what this is, could have commented to make the readers understand.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/171#discussion_r2761895318" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Same issue, could have commented to make the readers understand what you are trying to do here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/171#pullrequestreview-3748633683" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED

Clean code for level 1, simple questions
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 12. LOH ..IANG `@HX2003` (14 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2766935878" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good job in writing a clean class to achieve OOP.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2766938159" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good that you have considered to use a constant to avoid magic literals. However, it would be better to move the declaration outside of the main method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2766946493" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Great job in providing feedback to the user, so that the user knows what went wrong.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2766946957" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good error handling during parsing of input
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2766949444" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

In this part, its good that you dealt with unusual conditions as soon as they are detected, to prevent too much nesting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2766950794" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Some refactoring may be required to reduce the amount of nesting here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#pullrequestreview-3754353340" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766902062" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Consider what happens if users input an invalid string, or that the parsed integer is out of bounds of the task array.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766904496" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Excellent! By using a helper method to print divider line, you minimize amount of code being repeated.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766911384" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Great job, in conforming to the coding standard (plural form should be used on names representing a collection of objects).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766913917" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Consider what happens if users input an invalid string, or that the parsed integer is out of bounds of the task array.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766918213" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Great job, in conforming to the coding standard! Your boolean variable is named to sound like boolean, and follows the camelCase convention.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766925296" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Great job, in conforming to the coding standard! You did use K&R style brackets.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#pullrequestreview-3754322304" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 13. LIM ..TORE `@tlimnus` (14 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2771874359" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of comments
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2771874816" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Nice logo
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#pullrequestreview-3760302239" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771879600" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Great use of event handler
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771881308" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Leave comments for better understandability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771882501" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Great use of Override
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771887414" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Great use of Override
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771888832" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good idea giving a list of commands
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#pullrequestreview-3760310153" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2771864675" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Use comments to make code more readable but good idea to filter out unknown 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2771867308" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Good use of Override for printTask
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2771869672" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Use comment to make code more understandable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2771871265" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

super use of super
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#pullrequestreview-3760288352" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 14. TAN ..YUAN `@Yengfuan` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2767408517" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good way of avoiding deep nesting!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2767411928" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good work overall with the method calls as they do not exceed 30 LOC!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2767415326" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Logic for this file is structured well and logically
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2767417803" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Consider combining line 62 & 63
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2767418755" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consider changing taskcount to CamelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2767423385" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Cosnsider combining line 34 & 35
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2767426242" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Code is kept simple! Good job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#pullrequestreview-3754869636" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

Well done
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2767386285" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

This variable can be called isAdded instead of added.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2767388187" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good job on the boolean coding standard here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2767389723" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Good work on following the camelCase method naming standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2767397815" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Good job naming this a plural to represent a collection of Tasks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#pullrequestreview-3754845364" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 15. VINA..RAVI `@VinayVR26` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762025697" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I see that you have many methods which handle a portion of the logic which is very good. However, a suggestion I have is within each method, ensure that there is the same level of asbtraction. Because here for example in handleEvent() method there are combination of method calls and logic.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762028085" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

These variables could be named more meaningfully, because for instance "command", I can not understand what it refers to.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762029710" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good use of making the "Happy Path" prominent. Lines 122 - 128 are outside an if-else statements which makes the code quality good.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762031522" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

The methods that are called such as markTask(), printList() are meaningful and easy to understand what logic the method is performing.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762033140" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Good job in creating a Java constant for the maximum number of size of tasks. This helps removes any "magic numbers" from appearing in your code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#pullrequestreview-3748773492" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, well done
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/98#discussion_r2761992111" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

All code logic is in the single method - main which makes it difficult to see the flow in code and what each sub-part is doing. Perhaps you can create more methods and break the logic down
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/98#discussion_r2761994209" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The logic in printing your custom logo can be in a single method, so abstract the logic away to a method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/98#discussion_r2761997241" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

You could create a Java constant with a meaningful name to replace the "9" so that such magic numbers are not present. This applies to other parts of the code too.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/98#discussion_r2761999828" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

This part has too deep-nesting, which makes it hard to trace program flow
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/98#discussion_r2762005882" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

"line" is not a very meaningful variable name. Perhaps consider something better
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/98#discussion_r2762011936" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

As mentioned before on abstracting away logic to a method, you can create a new method and put all the logic on handling mark command. Additionally, ensure that in that method, all lines have the same level of  abstraction
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/98#pullrequestreview-3748740291" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 16. CHON..DRIC `@Cydriccwx` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2767681789" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

this. is not necessary in this method since there are no parameters with the same name. this.isDone can be replaced with isDone
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2767682944" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

this. is not necessary in this method since there are no parameters with the same name. this.isUndone can be replaced with isUndone
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2767683631" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

this. is not necessary in this method since there are no parameters with the same name. this.getStatusIcon can be replaced with getStatusIcon and this.getDescription can be written as getDescription
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2767712863" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good job in making the code more tidy by assigning a string to the introduction message!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2767767121" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

the string array name "components" can be changed to a different name to make the function of it clearer.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#discussion_r2767773973" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

some refactoring could be used here in order to reduce the amount of nesting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/38#pullrequestreview-3755208275" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

overall, the code was written very well, mostly following the coding standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2768552125" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good use of named constant, avoiding magic numbers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2768871377" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

good use of method to print horizontal lines, keeping code tidy.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2768886890" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

good naming of method, keeps the function of the method clear

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2768965919" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

good work combining smaller methods into a bigger method to pass into main, keeping the code clean and tidy.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2768974758" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

this is not a review comment but rather a question. how did u get this emoji smiley face to print? so cool HAHAHA
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#pullrequestreview-3756364116" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED

overall really good and clean code! i aspire to write code like this, teach me your ways.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 17. WU Z..JOHN `@elliotjohnwu` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2761743557" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Class should be placed in another file, and not in main
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2761757191" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good naming of functions as verbs
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2761759106" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good naming that describes boolean variables  
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2761761551" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

overall good indentation of lines
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2761766527" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

can true be replaced by a boolean variable?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#pullrequestreview-3748469992" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761778181" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Replace this line with a string variable/constant as it's repeated 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761779869" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

can you replace this boolean with a variable that describes the specific condition for this loop
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761781226" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Add class to a separate file from main
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761782325" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good overall naming of functions as verbs
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761786399" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Good naming of boolean variable to describe status of condition
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761791651" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Overall good naming of variables with camel case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#pullrequestreview-3748508337" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 18. VANS..PURI `@benguy6` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767349557" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Any reason for these fields to be protected rather than private? 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767352859" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Do we want to validate description here? If not, should the caller be responsible for validation and show a clearer error message to the user when description is missing?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767357050" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Should we validate by here (empty string) or rely on the command parser to guarantee it’s non-empty? If validation stays in the parser, maybe a comment clarifying that assumption could help future readers.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767361280" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Do we want to enforce that from is not after to chronologically at some point?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767363466" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Would you consider adding a separator between from and to like "(from: ... / to: ...)" for readability?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767368942" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Would final fields make sense here (private final String from; ...)? It might signal these are set once at creation.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#pullrequestreview-3754807446" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767483828" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

good function to add
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767692007" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

why didnt you print the bye message immediately in the bye branch instead of relying on the code after the loop
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767695725" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Why dont you consider also printing the horizontal lines for unknown commands for UI consistency (since most other outputs are framed)?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767699812" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

should updateTaskStatus also receive count so it can validate index bounds (e.g., mark 999) to prevent crashes
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767702712" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

consistent!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#pullrequestreview-3754951550" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 19. YAP .. WEI `@heeelol` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2762011652" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Should there be whitespaces between the variable ("taskCount") and the increment operator ("++")?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2762015696" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good use of switch logic but ensure a spacing between the "if" operator and the open brackets 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2762018148" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good abiding to PascalCase for all the Class names
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2762020073" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good abiding to the camelCase and verb convention for all methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2762020748" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Good abiding to the camelCase convention to all variable names
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2762022591" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Should the names representing a collection of objects be in singular form?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#pullrequestreview-3748760381" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Casing conventions are abided well, good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2762050989" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Can override the toString() method in the Task class so the printing is standardised
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2762059304" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Magic number of "100", extract to a named constant "MAX_TASKS" to explain its meaning

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2762064046" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

UI logic scattered in main(), standard violation of SLAP. Maybe extract UI operations into separate Ui class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2762066800" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Missing toString() override, should standardize printing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2762069224" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Numbers 5 and 7 are magic numbers. Extract to constants explaining they are command prefix lengths.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#pullrequestreview-3748803704" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good effort!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 20. NG S..ENIA `@infinitymehs` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2766798980" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

maybe can consider using another object to store the lists of tasks? can use a TaskList object
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2766801952" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

the Todo object name is abit unclear, maybe can change to "task" or "todoTask"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2766808553" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

same with the todo object above, the naming is abit unclear
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2766811486" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

same as the 2 comments above
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2766814179" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like this todo task :D
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#discussion_r2766830461" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like how you handle any errors using try catch statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/65#pullrequestreview-3754221535" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766818410" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

maybe you can consider using another object to store the tasks? Can consider using a TaskList object
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766822431" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

nice using camelCase for object methods :D
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766824178" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

if you print the "-------" often, maybe you can consider saving it as a constant String variable, helps with readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766827999" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

there might be a bug if inData startswith "Mark " (basically this line of code does not take into account if the user enters the input with capital letters)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766828629" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

same as the comment on line R35
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#pullrequestreview-3754239977" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 21. TAYA..NISH `@Yonish18` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2761914648" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Maybe consider adding more comments to increase readability?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2761918093" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Should this be added in class Rohan as a class method?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2761918582" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Should this be added in class Rohan as a class method?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2761922367" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I like it that you put the strings as descriptive variables
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2761925982" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Maybe work on the layout a bit by reducing the number of classes?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2761928087" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like that the case statements aren't too deep
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#pullrequestreview-3748660650" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2761882174" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Maybe consider a more efficient function name?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2761888965" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like the function naming, with first letter of every word capitalized
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2761891828" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

the if-statement formatting looks good!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2761895448" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

While the function names are descriptive, maybe consider adding additional comments to improve readability?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2761898434" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

This indentation looks correct.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#pullrequestreview-3748627114" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 22. YI Y..YANG `@yy43yy` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/11#discussion_r2762302266" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Consistent and correct  PascalCase naming for classes!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/11#discussion_r2762306477" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Correct plural form used for this variable! Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/11#discussion_r2762308954" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Correct naming for boolean. Great!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/11#discussion_r2762311735" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Correct form for if-else statement. Nice work!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/11#discussion_r2762314311" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

camelCase used correctly for all variables. Good Job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/11#pullrequestreview-3749114113" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

The code follows the coding standard. Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2762333562" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Maybe can seperate this into 2, markAsDone and markNotAsDone. This way would be clearer
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2762336498" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Similar for this, maybe can seperate. Cos your function name is markAsDone, might cause confusion. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2762338906" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

maybe can add a toSting() function 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2762340200" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Correct checking logic! Nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2762341231" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Maybe can trim the input first.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#pullrequestreview-3749149836" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Generally not bad! Hope my review can help!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 23. RAJA..THAA `@sushmiithaa` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767429475" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps can include this in the toString() method in the Task.java file?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767450556" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Perhaps can create a separate function for adding tasks?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767456488" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Perhaps can create a constant called LINE to save the LINE then place that variable?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767460607" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Maybe can change the name of the List to tasks to make it more intuitive?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767465000" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like the use of input validation
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#pullrequestreview-3754892415" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2767357395" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Perhaps can rename the String list to ? so maybe private String[] tasks?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2767368811" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like the use of Use K&R style brackets (aka Egyptian style) that follows the coding standard.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2767381982" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like the use of  PascalCase to name the class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2767390667" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I like the use of 8 spaces for wrapped lines 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2767397274" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

I like the case indentation that follows the coding standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#pullrequestreview-3754815400" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 24. NG Z..MENT `@klementng` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766675108" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Be consistent with the use of the `this` keyword; It is used in the constructor but not here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766679085" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

You can consider declaring a constant here like INDENTATION for " ".repeat(8)

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766683224" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good use of a helper function here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766686237" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Consider removing this comment as it misleading for this function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766687747" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

You can consider creating another helper function


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#pullrequestreview-3754099311" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Generally, looks good in terms of naming and coding standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766693156" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

You can consider creating a helper function for printing the lines 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766695981" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Consider using OOP to encapsulate the logic for tasks
 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766700361" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

be specific on the exact Exception you are catching, this will catch all Exception 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766705879" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

This should be declare as a constant like LOGO
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766708351" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

isDone name implies a single variable naming; should not be used for an array  
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#pullrequestreview-3754118424" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Main comment is to use OOP and create a new class for Task 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 25. MEHT..YESH `@veermehta270` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/113#discussion_r2762313732" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

You have used a magic number here. You declare the number 100 as a public static variable. `public static MAX_NUMBER_OF_TASKS = 100`
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/113#discussion_r2762314529" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Another magic number. Please declare it as a static variable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/113#discussion_r2762317958" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

You have commented out a code here. Please remove such comments before commiting.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/113#discussion_r2762320255" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

You have commented out a code here. Please remove such comments before commiting.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/113#discussion_r2762326613" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

The naming of the variable does not justify its use. You may name the variable as `input` or as `answer`
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/113#pullrequestreview-3749126351" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall this is good. But please take case about the extra comments, be professional.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2762286900" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good observation. A static variable can be declared such as :`public static MAX_NUMBER_OF_TASKS = 100`
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2762289515" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Instead of using an empty print() statement for spacing, consider adding a newline character (\n) to the end of the previous string. This keeps the logic contained in a single statement and is a bit more idiomatic
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2762297552" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Instead of using an empty print() statement for spacing, consider adding a newline character (\n) to the end of the previous string. This keeps the logic contained in a single statement and is a bit more idiomatic
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2762300800" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

It is good that you have followed proper code quality and structure, the main method is clean.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2762309757" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

You may add a TextParser class inorder to handle the inputs and also add a Printing class to print all the messages. You are just doing this in the main file. You may follow good code quality standards.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#pullrequestreview-3749096273" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall the code looks good. Just make the small changes as suggested.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#pullrequestreview-3749122086" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 26. SING..AYAN `@siddhant2118` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766801307" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like that uses camelCase, as recommended by the coding standard for variable names. Is this naming style used consistently throughout the codebase?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766804087" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I like that the collection variable is named tasks (plural), which matches the coding standard for collections. Are all collection variables in the codebase named in plural form?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766805308" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I like that the opening braces for classes and methods are on the same line as the declaration, following the K&R style recommended by the coding standard.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766812541" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I like how the code is consistently formatted and indented, which makes it easy to read and matches the coding standard recommendations.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766813393" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like that the array specifier is attached to the type, which matches the coding standard recommendation for array declarations.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#pullrequestreview-3754223872" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I found your code easy to read and well-structured. The use of constants, camelCase naming, and consistent formatting matches the coding standard recommendations. I especially like the use of random messages and custom separators for personality. Just a few minor suggestions regarding comment formatting and magic numbers, but otherwise, LGTM! 👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766887497" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Should these magic numbers be replaced with named constants or calculated dynamically?
Using hardcoded indices for command parsing can make the code harder to maintain. Consider using named constants or parsing based on command length or keywords.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766887878" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Should this magic number be a constant?
The array size 100 could be defined as a named constant (e.g., private static final int MAX_TASKS = 100;) for better maintainability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766888418" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like how the code is structured into separate methods for adding, listing, and marking tasks. This logical separation improves readability and maintainability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766890203" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I like that class names are nouns and method names are verbs, which matches the naming guidelines and makes the code easier to understand.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766890952" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

I like that the command parsing in the main method is explicit and straightforward, which makes the code easy to follow and avoids clever tricks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#pullrequestreview-3754308666" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, the code is well-structured and readable, with clear separation of concerns and good naming practices. There are a few places where magic numbers could be replaced with named constants or dynamic parsing for better maintainability. The command parsing is clear and the class structure is logical. LGTM! 👍
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 27. BAJA..SHNA `@KrishnaBajaj1506` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772636209" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Readability: Avoid Deep Nesting
In parseArgs(), you have a nested if structure to handle multiple dividers.

Suggestion: Try to use Guard Clauses to handle simpler cases (like no dividers) early and return. This keeps the "happy path" of your logic at a lower indentation level, making it much easier to follow.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772638661" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Readability: "Magic Numbers"
You are using several hardcoded indices in your substring() calls:
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772643736" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Class Member Modifiers
Many of your helper methods (like printList() or parseArgs()) are currently public.

Suggestion: Following the principle of Encapsulation, these should likely be private unless you specifically intend for other classes to use them.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772645436" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Commenting Standards
While the method names are generally clear, adding Header Comments (Javadocs) for your more complex logic would greatly help other developers understand how you are splitting the input strings.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#pullrequestreview-3761207807" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772573950" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

You have followed the naming standards perfectly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772578260" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Method Length
Following the point above, the main method is becoming quite large. Under our coding standards, we should aim to keep methods short and focused. A method that spans 50+ lines and handles 7 different logic branches is a prime candidate for refactoring.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772580425" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Missing Javadoc
While your other methods are documented, the main method is missing a Javadoc header. Every non-trivial method should have a /** ... */ block explaining its purpose and parameters.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772581664" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Suggestion: You should mark it as final: private static final Task[] tasks = new Task[MAX_TASKS]; This is a good practice to prevent accidental reassignment elsewhere in the code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772582973" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

The main method is currently violating SLAP. It is handling high-level control flow (the while loop), mid-level UI logic (the greetings), and low-level string parsing (the substring and split calls) all in one place.

Suggestion: Refactor the main method by extracting the command handling logic into separate private methods, such as handleMarkCommand(), handleTodoCommand(), etc. This keeps your main method clean and easy to read at a glance.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772583760" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

add javadoc comments
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#pullrequestreview-3761137903" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 28. ALEX.. MUN `@alexanderYaw` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2766963561" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of naming convention: "isVar" to denote a boolean
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2770259482" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Great use of camelCase and naming of variables are intuitive and their meaning is clear
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2770344768" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

'''suggestion
    public static void printSentence(String x) ``{``
        printLine();
        System.out.println(x);
        printLine();
    ``}``
    
    public void add(Task t) ``{``
        taskList[nTasks] = t;
        nTasks += 1;
    ``}``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2770426241" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good definition of array as "String[] sentence" and not "String sentence[]"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2772709572" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

consider naming this taskCount instead for better readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#pullrequestreview-3754380950" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall follows Java coding standards well, with proper and intuitive naming, and formatting is well done.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2766917709" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good naming conventions; use of camel case and it is intuitive to understand the meaning of the variables
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2766919445" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

'''suggestion
            ``}`` else if (userCommand[0].equalsIgnoreCase("list")) ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2766921929" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

'''suggestion
            if (userCommand[0].equalsIgnoreCase("bye")) ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2766930477" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

'''suggestion
                for (int i=0; i&lt;taskList.size(); i++) ``{``
                    String status;
                    if (!doneList.get(i)) ``{``
                        status = "[ ]";
                    ``}`` else ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#discussion_r2766934624" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

'''suggestion
            ``}`` else if (userCommand[0].equalsIgnoreCase("mark") && userCommand.length>1) ``{``
                int taskNumber = Integer.parseInt(userCommand[1]) - 1;
                if (taskNumber >= 0 && taskNumber &lt; taskList.size()) ``{``
                    doneList.set(taskNumber, true);
                    System.out.println("Nice! I've marked this task as done:");
                    System.out.println("  [X] "+ taskList.get(taskNumber));
                ``}``
            ``}`` else if (userCommand[0].equalsIgnoreCase("unmark") && userCommand.length>1) ``{``
                int taskNumber = Integer.parseInt(userCommand[1]) - 1;
                if (taskNumber >= 0 && taskNumber &lt; taskList.size()) ``{``
                    doneList.set(taskNumber, false);
                    System.out.println("OK, I've marked this task as not done yet:");
                    System.out.println("  [ ] "+ taskList.get(taskNumber));
                ``}``
            ``}`` else ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/144#pullrequestreview-3754336647" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good use of naming conventions and well structured code, but could do with some spacing for better readability!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 29. TAN ..PANG `@Tan-Pang` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/33#discussion_r2761872346" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Should have a space after the close bracket for while loop
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/33#discussion_r2761873911" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Same issue as the while loop.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/33#discussion_r2761881418" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good naming format following camelCase!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/33#discussion_r2761884459" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of .equals() function instead of "==".
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/33#discussion_r2761888239" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

You may want to leave out the escape character "\n" when calling println as it may cause unexpected behaviour
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/33#pullrequestreview-3748617458" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good job on following the coding standards.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761897906" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Try to avoid printing statements directly in the main method. Can consider to extract a method just to print standard outputs.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761905812" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

For this if else statement, should consider to use switch case statements instead since all the conditionals are with relation to the value of the variable _command_.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761909500" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Similar to first comment, can consider to extract the printing statements to another method to maintain minimal levels of abstraction within main method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761913732" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good naming of variable to make it readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761922326" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

You may want to consider creating more methods to aid in breaking down lower level functions in main to make it more readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#pullrequestreview-3748643748" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 30. BENJ.. WEI `@benthejarofmint` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2767380742" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

i like how you split the functionalities into separate functions with only one function each !
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2767393963" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

the naming of the function call for the command "unmark" as handleMarkTask seems quite misleading to me, maybe using a separate function would be better?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2767395401" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

great that you are using `switch()` statements to increase the readability of the code!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2767400465" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

another suggestion could be to change the number 100 and define a constant instead (eg. MAX_TASKS)?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2767403169" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

great naming for this variable - it's clear and helps with understanding it immediately.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#pullrequestreview-3754839943" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767337992" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

a suggestion could be to replace the long string of dashes with `.repeat(n)`. might help with readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767345756" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

a small thing but i feel that you could be more consistent with the spacing. (eg. `int count = 0;`)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767354363" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

for the `System.out.println(...)` on line 27 to 29, i do feel like you could format it from splitting the code into 3 different lines into 1 line to make the code more readable. i do see this same problem in other parts of the code as well !
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767358771" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

would like to clarify what does the number 5 in `.substring(5)` mean?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767367347" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

i do feel that the number 100 could be replaced with a more descriptive constant naming. (eg. `MAX_TASKS`)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#pullrequestreview-3754795902" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Looks good to me.
Just a few code readability issues to look at!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 31. JOHN..PAOA `@j-kennethh` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772590639" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good naming of class attributes 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772594066" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Line is too long, not very readable, suggest extracting the printing to a function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772595816" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good use of overiding the toString() method 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772599469" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of inheritance
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772602007" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consider adding comments for each case for better readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#pullrequestreview-3761156706" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, good naming but readability could be improved
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2772571816" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of plural form for tasks array
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2772575097" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good layout using K&R style brackets
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2772577277" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good explicit import of class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2772580018" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good use of annotation for overriden method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2772582480" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Not really necessary to comment constructor
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#pullrequestreview-3761135180" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, good coding standards!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 32. WANG..AWEI `@wjw55` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2771860819" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of uppercase and underscore to separate words for constant names.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2771875952" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good use of verbs and camelCase for names representing method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2771879935" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

The if-else class statements are of correct form.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2771885056" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

You can remove the empty line. Since the method is short and the logic is continuous, it's cleaner to keep the code block together.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2771891064" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

You can remove the empty line here as well to make the code block together.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#pullrequestreview-3760283886" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Looks good! The code follows the Java naming conventions well (especially the constants). I've suggested a few small style adjustments in the comments below. Nice job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771903068" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like how you use uppercase and underscore for all constants. Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771904352" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I'd suggest remove the empty line to keep the code block cleaner. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771909524" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good use of using the correct format for the if-else statements.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771911564" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Comments are clear and useful. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#discussion_r2771913942" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Great job with the @Override annotations. It makes it clear which methods are being customized from the Task class.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/192#pullrequestreview-3760342956" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great work on this PR! The code is clean and well formatted. The comments are clear and useful.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 33. TAN ..IANG `@revaria` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771849760" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps the variable name (list) can be more representative of Task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771860847" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

You might want to reduce the number of characters in this line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771868606" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

You can consider replacing your magic number '5' with a named variable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771870652" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I noticed the same issue from line R92
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771873630" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I noticed the same issue from line R92
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771874662" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good job for class naming!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#pullrequestreview-3760269053" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771888707" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

If user inputs 'Bye' instead of 'bye', the bot might not exit
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771892236" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

This can be defined as a constant, since there is no need to change this variable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771897485" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good job with naming conventions!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771900798" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

You can consider assigning a boolean variable instead, to make it more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#pullrequestreview-3760323137" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job overall!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 34. NAVA..NJAI `@N-SANJAI` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2767386791" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

The variable "Subparts" should be in lower camelCase, e.g. "subParts" or "subparts". This applies to all the other locations this variable is used in

'''suggestion
                    String[] subParts = input.split(" ");
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2767394756" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

line = "____..." is duplicated (in main and again in replyRoutine). Consider making it a static final String LINE = "..." and reuse it. Also, constant names should be uppercase with underscores (e.g. LINE_SEPARATOR).


'''suggestion
        static final String LINE = "____________________________________________________________";
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2767409631" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

consider formatting as 

'''suggestion
                    System.out.println((i + 1) + ". " + list.get(i).toString());
'''

so there’s a space after the dot, and spacing around + is consistent.

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2767421197" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

println will call toString() automatically
Can remove redundant toString calls
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2767422633" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like the creative use of ██ style for the logo!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#pullrequestreview-3754845844" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job on the iP so far!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2767464438" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

markTask and unmarkTask are almost identical except for the done state and message. Consider extracting a helper like setTaskDone(index, boolean) to reduce repetition and keep changes localized.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2767468811" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The long chain of if (...) return; is workable, but consider using a switch case to make the command routing easier to read/extend.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2767470211" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Nice use of early returns and helper methods (addTodo, addDeadline, addEvent) which keeps the logic from becoming deeply nested and hard to follow.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2767476667" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

the way you used fromIdx / toIdx is nice and consistent. 
For split, consider similar naming like byIdx to make related indices look related.

'''suggestion
        String byIdx = rest.substring(split + 5).trim();
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2767482188" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Strings like "list", "bye", "mark ", "unmark ", "todo ", "deadline ", "event " are repeated. Defining constants (eg CMD_LIST, CMD_MARK_PREFIX) improves readability and reduces typo risk.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#pullrequestreview-3754929422" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

great job on the progress so far Alson!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 35. SRIN..THAN `@RANGANATHAN21` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2770715950" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Suggestion: rename to taskCount to make intent immediately clear, as it's not immediately obvious what it is counting without reading comments.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2770723890" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Consider method name addTaskFromInput or addTask to accurately describe behavior.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2770733554" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Consider modifying the variable and method names appropriately to accurately describe what they represent, as vague naming is repeatedly showing up.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2770748750" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Consider replacing 9 with a static variable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2770757635" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

'''suggestion
    public Event(String description, String from, String to) ``{``
'''
Consider using consistent spacing across the code as it improves readability and professionalism.

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3758913715" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job writing functional code, with better naming and standardisation, it would become more readable and intuitive.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/188#discussion_r2770616608" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

'''suggestion
    private static final int MAX_TASKS = 100;
    private static Task[] tasks = new Task[MAX_TASKS];
'''
This avoids magic numbers in the code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/188#discussion_r2770627523" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

correctly used Override in subclasses
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/188#discussion_r2770637633" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good job extracting the greeting into a method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/188#discussion_r2770648719" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good job with handling the edge cases
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/188#discussion_r2770663569" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Consider adopting method-level Javadoc, since the IDE is able to help generate them too
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/188#pullrequestreview-3758789133" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall well-written code paying attention to proper use of indentation and CamelCase naming.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 36. ARIF..SAIN `@Ariff1422` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766914605" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

As mentioned above, you can declare them as final or call methods which could make the code cleaner and more debuggable as the code grows longer
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766924700" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

You can avoid including breaks as the if else if already fulfils that which makes the code cleaner
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766968921" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

According to the coding standard, constants or variables that are effectively constant should use UPPER_SNAKE_CASE. Additionally, if this isn't meant to change, consider adding the final modifier. Suggested change: private static final String HORIZONTAL_LINE = "...";
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766973889" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

There seems to be redundant declaration here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766976669" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Coding standards generally discourage placing a space between the method name and the opening parenthesis. Suggested change: System.out.println(CLOSING_GREETING);
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766983514" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

The number 100 here is a 'magic number.' It's better to define this as a constant at the top of the class (e.g., MAX_TASKS) so it's easier to find and modify later if the capacity needs to change
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#pullrequestreview-3754333792" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Generally looks good! Some minor changes to take note for future commits 👍 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766902465" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

You could also consider using ArrayLists which prevent the need to keep changing the size
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766919471" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

You can consider making the Comments more descriptive, to better describe what the method does
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2767010527" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Even though these are local variables in main, they are acting as constants. According to the coding standard, if you move these to be class-level constants (fields), they should be static final
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2767063568" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Field visibility should be as restrictive as possible. Unless you expect a subclass of Deadline to need direct access to the by field, it is better to mark it private.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#pullrequestreview-3754322625" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Generally very-well structured and there are not much to change other than the minor changes suggested
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 37. CHEN..HSIN `@Nishuy52` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2767330628" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of try-catch statements for error catching
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2767349283" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Array specifiers must be attached to the type (String[] inputs)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2767354867" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Magic number, could declare constant instead
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2767367324" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Magic number, could set as constant char like UNDONE_SYMBOL and DONE_SYMBOL
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2767377058" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Logo could be set as a constant 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#pullrequestreview-3754788507" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767394789" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Missing blank line after import statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767399735" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Use a constant string literal instead of "-------------------------------------------"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767405714" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Could use constant characters instead like DONE_SYMBOL =  "X"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767410778" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

count could be more descriptive like taskCount
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2767418043" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Good use of equalsIgnoreCase to clean inputs
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#pullrequestreview-3754855049" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 38. EMRY..HIFF `@EmDani3l` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2767403058" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Can consider using clearer naming conventions instead of "by" such as "deadline".
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2767409305" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good use of @OverrideImproves readability and enables the compiler to catch mistakes. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2767415224" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Fantastic use of constants to avoid appearance of magic strings in code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2767421898" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Suitable use of switch block that is readable and simple to follow.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2767430594" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like the storing of special customised messages in a separate file!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2767436829" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Javadoc comments are missing from these methods.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#pullrequestreview-3754863815" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall nice job on the code! There are a few minor adjustments that could be made in order to slightly improve on readability or more consistent naming conventions. 

Jesse, we must be on the same page here!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767308143" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Should follow coding standard for if-else statements, avoid 'arrowhead' blocks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767312324" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Can leave out redundant comments for now even if planned to add on later on.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767324479" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Should add javadoc comments describing class methods and functionalities.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#discussion_r2767330722" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Can consider utilising constants in place of 'magic string' like the one here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/78#pullrequestreview-3754765945" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall creative implementation and code, but could do with improving logic to appear nicer such as if-else statements and replacing magic strings.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 39. BAOR..ARAV `@AaravBaori` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762290281" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

You can include everything related to Tasks inside the Task class so there's proper segregation of functions. You can create a class variable allTasks inside Task.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762293021" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good job on making functional blocks for these repetitive statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762296097" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good job using switch case for this part rather than using multiple if and else if block. Makes it readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762299814" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good job on segregating these from the while loop and keeping them independent. This way it makes it easier to independently change code in the future without affecting other blocks of code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762311727" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

You should include everything related to Task in the task class, 
an allTask class variable and taskCount class variable can be added here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#discussion_r2762315013" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Define getters and setters for the variables defined
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/87#pullrequestreview-3749100512" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall the code structure is quite good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762325112" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Use your Task class! Instead of two arrays, use one Task[] allTasks. The Task object should "encapsulate" both its description and its status.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762328759" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Start moving logic into methods. For example, instead of parsing Integer.parseInt(parts[1]) - 1 twice in different cases, create a method like getTaskIndex(String input).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762331465" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Move this to an addTask(String description) method. This violates SLAP. The "High-level" logic (deciding what to do with a command) is mixed with "Low-level" logic (manually updating array indices).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762335122" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Move this logic into a getStatusIcon() method inside your Task class. The Olaf class (the UI/Main class) shouldn't care how a task represents its status. This is a "Feature Envy" smell.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#pullrequestreview-3749141279" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall the code is good but each functionality should be segregated into it's code blocks so that making changes in the future becomes easier. Having independent blocks allows you to change code in the future without affecting the rest of the code.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 40. CHEN..NGYU `@Hongyu1231` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771901863" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good practice that do not miss the "by" statement after override
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771906138" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

There is no need to add a method here since you don't change the method from parent class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771907673" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good layout. Divide 3 lines of print statements into 3, make it very readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771909556" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

"content" naming is not very good, makes it not so clear what content it is
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771911116" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Layout can be improved by divide each "else if" statement with 1 line indentation
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#pullrequestreview-3760341377" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Decent commit. Can try to improve layout to improve readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2771881992" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

The indentation is not consistent among all the methods. Make it less readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2771886601" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Clear comments on how the chunk of code works. Improve the readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2771889350" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Not so clear code. It's not readable enough for collaborators to read
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2771890605" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Clear comment to explain how this line works. Make it more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2771893314" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Clear comments on the loop to explain how the loop works. Make it more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#pullrequestreview-3760313847" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great commit. Can clearly comment out the comments to make it more readable
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 41. SHAH..AMIT `@jainamashah` (22 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2772605042" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Appropriate use of OOP inheritance to inherit from parent class Task. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2772615956" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

You can consider inheriting from deadline Class and using 'by' variable for 'to' variable as both share same functionality. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2772624800" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Todo and Task class are the same. Avoid duplicating code and confusing the audience. Can you try merging these classes? 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2772630004" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Appropriate use of @Override to change the function of the toString method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2772634296" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

It is confusing how IsValidNum is determined. Can you maybe insert some javadoc comments to explain how this boolean was determined? 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#pullrequestreview-3761172497" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#pullrequestreview-3761184440" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#pullrequestreview-3761193753" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#pullrequestreview-3761200113" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#pullrequestreview-3761205498" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#pullrequestreview-3761207982" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Completed commenting on Code Quality. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772577816" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Try providing a translation or omitting usage of foreign words as part of your chatbot dialogue. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772588147" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Is this space required line break required? If so, try being consistent throughout. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772592370" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Good use of camelCase for booleans
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772595670" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

Methods have also been named appropriately 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772600097" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

Isn't indentation supposed to be 4 spaces?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#pullrequestreview-3761142641" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#pullrequestreview-3761154327" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#pullrequestreview-3761158370" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#pullrequestreview-3761161682" expanded>
<div slot="header">

**20 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#pullrequestreview-3761167076" expanded>
<div slot="header">

**21 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#pullrequestreview-3761168531" expanded>
<div slot="header">

**22 :fas-comment:**
</div>

**Review Status:** COMMENTED

Completed review with comments. 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 42. ADVA..AGRI `@Advait-B` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766797839" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Use UPPER_CASE naming convention for 'final' objects
So I suggest can either modify this to be final or change casing format
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766798907" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Additionally, I believe you can extract these into functions like 'greeting()' and 'goodbye()', as defining them at the top may not be required, and makes the code harder to read
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766800921" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Try to keep main as uncluttered as possible by extracting the other codes into functions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766801945" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Be careful with this - may lead to errors, consider handling cases where the users input is not in the appropriate range
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#discussion_r2766802660" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I think you're still working on task 4 but rmb to add the other classes for todo, event, deadline etc
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/112#pullrequestreview-3754220401" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766814941" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

You can consider extracting all the greetings into a method to ensure your code follows OOP standards and is as readable as possible
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766815446" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like this line LOL
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766816217" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good job with the error handling
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766817183" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Consider adding comments to explain your code to the user
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766818737" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

You can make this a static object to make main less cluttered
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#pullrequestreview-3754236857" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 43. GE W..QING `@XiaoGeNekidora` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771851255" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Maybe the `done` argument can be renamed to `isDone` so it follows the standard?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771856194" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Great! You used plural forms.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771860442" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Any reason why you use an adjective for variable name here?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771865653" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Clear naming here👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#discussion_r2771869440" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Same as above. Maybe try renaming to `isActive`?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/86#pullrequestreview-3760270612" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2771883579" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Should this be named as `list`?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2771886327" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Why suddenly a newline here?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2771891704" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

How about renaming to `taskCount` so that it follows the same style as the rest of your code?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2771899674" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

It's OK. But maybe it is better if we make it a constant in the class?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2771904324" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Is it better for the tasks to be global instead of as a local variable? Currently a new `tasks` array will be created every time `list` is called.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#pullrequestreview-3760316067" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 44. JAIN..SHAM `@jainsaksham2006` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2767258009" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

toString() should not throw exceptions, as it is commonly used for logging and debugging. Throwing IllegalArgumentException here may cause unexpected runtime failures. Consider validating inputs in the constructor instead and ensuring toString() is side-effect free.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2767262228" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Subclasses directly access the superclass field description. To improve encapsulation, consider using a getter method (e.g. getDescription()) instead of accessing the field directly.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2767264058" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

The field description is declared as protected while isDone is private. This inconsistent access level weakens encapsulation. Consider making description private and accessing it through a getter.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2767265622" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

The NumberFormatException is caught but ignored without handling or feedback. Consider logging the error or informing the user to improve debuggability and user experience.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2767267535" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

The task list is implemented as a static mutable field, which tightly couples application state to the class. Consider encapsulating task management in a dedicated class to improve testability and design clarity.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#pullrequestreview-3754713983" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, this is a well-structured and readable implementation. The design demonstrates a good understanding of object-oriented principles, with clear separation between task types and consistent formatting of output. The use of constants for command prefixes and separators improves maintainability, and the command parsing logic is easy to follow. The code largely meets its intended functionality, and with a few refinements to validation placement, encapsulation, and error handling, it would be even more robust and aligned with standard Java best practices.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2766911428" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Method name getnTasks() does not follow Java naming conventions. Consider renaming it to getTaskCount() or getNumTasks() to improve clarity and consistency with camelCase standards.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2766915746" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The boolean field isDone does not have a corresponding isDone() accessor method. Consider adding a properly named getter (isDone()).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2766923118" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Repeated string concatenation inside a loop is inefficient. Consider using StringBuilder to improve performance and follow Java best practices.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2766930523" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

this.isDone is redundant here since there is no local variable shadowing the field. You can simply write isDone = true; to keep the code concise and consistent with Java style conventions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#discussion_r2767205687" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Same issues, this.description is redundant here since there is no local variable shadowing the field. You can simply write description to keep the code concise and consistent with Java style conventions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/44#pullrequestreview-3754330699" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, the code is well-structured and demonstrates a good understanding of object-oriented principles such as inheritance and method overriding. The separation of different task types into their own classes improves clarity, and the functionality is implemented correctly. With some improvements to formatting, naming consistency, and separation of concerns, the code would be more readable, maintainable, and aligned with standard Java coding conventions.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 45. SIDD..INAR `@Sid3024` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/29#discussion_r2766815433" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

add documentation for method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/29#discussion_r2766818435" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Maybe consider using a switch (extract first word using .split) for readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/29#discussion_r2766824139" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

add documentation/what this method does
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/29#discussion_r2766825317" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

appropriate use of PascalCase and CamelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/29#pullrequestreview-3754237283" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766833192" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

good abstraction of marking as done/not done to separate methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766868387" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I would recommend abstracting out each of the cases in a separate helper method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766870364" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I would recommend storing the tasks list/count as either a private attribute of Willa class or create a new class to store and handle the list
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766876349" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

add method documentation
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766876985" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I dont think you should create a new class for every level, just update the code for each level and tag them?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#pullrequestreview-3754254538" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 46. GARG..AJAY `@AnnikaGarg` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772594144" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good Job on adding Javadoc comments for public methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772607439" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Consider renaming this method to getIsDone() as it gives more description what the method is supposed to do.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772622776" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

This variable name can be changed to something like doneIcon as it is more descriptive of its function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772632352" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Check the spacing for (i+1) part. It should be (i + 1).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#pullrequestreview-3761160109" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall a great job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772651184" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Great job on using constants instead of magic numbers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772670988" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good job on maintaining the same level of abstraction.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772694957" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good job on handling exceptions/unusual conditions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772705070" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

There should be no indentations for the case clause in switch.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772732566" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Consider making the comments more reader friendly like:
/** helper method for handleTodo, handleDeadline, handleEvent methods to add tasks*/
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#pullrequestreview-3761226767" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall its a great job. The code is very consistent and readable.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 47. LEE ..N YI `@AK47ofCode` (20 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766801654" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

The addition of comments with the correct indentation for methods is good. I've noticed you've done the same for other methods too
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766818338" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

The addition of a help command with a clear detailed description of the commands is very nice
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766823944" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

The addition of the logo and divider is a great touch that adds personality to Lumi
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766825048" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Perhaps this gap between the switch and comment lines can be removed?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766826554" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

These messages from Lumi are so hilarious, they add a lot of personality and uniqueness to it!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#pullrequestreview-3754224181" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#pullrequestreview-3754239920" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#pullrequestreview-3754245182" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#pullrequestreview-3754246212" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#pullrequestreview-3754247684" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#pullrequestreview-3754252827" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Impressive work so far in programming Lumi while adhering to the coding standards. Well done!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2766834686" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

The addition of Javadoc comments for methods while making sure each starting letter is capitalised and each sentence ends with a full stop is good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2766849166" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Addition of the ASCII logo and dividers adds visual appeal to the CLI. But perhaps these can be made constant/final?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2766860636" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Perhaps name this boolean "areCompleted"?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2766870379" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

Perhaps there should be a full stop at the end of this line, as well as replace the comma with a full stop at the next line too?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#pullrequestreview-3754256034" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#pullrequestreview-3754271111" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#pullrequestreview-3754282417" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#pullrequestreview-3754292406" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#pullrequestreview-3754295421" expanded>
<div slot="header">

**20 :fas-comment:**
</div>

**Review Status:** COMMENTED

Other than a few non-standard code bits, the code largely follows the coding standards. Well done!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 48. RUSS..HENG `@RNJH224` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772612137" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Super Use of Super ;)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772614288" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Great use of inheritance to make the code more compact and readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772617629" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Great use of comments to ensure readers understands what are your intentions for this function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772621249" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good use of spaces to ensure good separation between methods and variables
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#pullrequestreview-3761180664" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772571771" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good use of switch and case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772575408" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

great use of switches to make the code much more readable and understandable made the code more compact and less messy
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772585630" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

good use of K&R style brackets
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772591973" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

if follows the the if-else statement guideline
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#discussion_r2772602221" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good use of comments to ensure readables understand intent in writing this code 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/141#pullrequestreview-3761135132" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 49. YEO ..XIAN `@Notchennie1` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762019529" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Maybe add
private static final int MAX_TASK = 100; (as a constant) and input it here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762023107" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good consistent camelcase throughout
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762081924" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good K&R bracing and good structure.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762083455" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Very good use of single level of abstraction principle but can consider switch cases
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#pullrequestreview-3748767905" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall coding standard looks good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#pullrequestreview-3748837798" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

GOOD JOB!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2762036753" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Can explore creating a string LINE constant and input them in the print function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2762052050" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Naming of stringParts may seem generic maybe instead name it as what you are using oneAndTwo
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2762062695" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Might prefer to do the code segmentation in function Event itself to allow for unit testing for easier debugging and to reduce the LOC of your main
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2762069177" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

May consider incrementing the numberrOfTasks counter before the println to reduce the need to extra +1 in println
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2762075566" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Might consider breaking the ORs ( || ) into smaller functions for easier readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#pullrequestreview-3748786955" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, minor issues with code quality but very well done
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 50. HU X..IRAN `@xiranhu` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761910638" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I agree with the earlier comment about the unused Arrays import. Removing unused imports helps keep dependencies minimal and makes the file easier to scan.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761920105" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I find the nested if–else structure here a bit hard to follow as the logic grows. Would extracting some of the command handling into helper methods help reduce nesting and improve readability?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761921618" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I like how the variables (such as markDone, getStatusIcon...) in Task are clearly named and make the purpose of the class easy to understand. It was straightforward to see how task state is represented and updated.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761924212" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I like how the inline comments explain the intent of different sections of the code. They helped me understand the flow more quickly, especially in the command-handling logic.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#pullrequestreview-3748656491" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761891444" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I see very similar logic repeated in both the mark and unmark command sections. Would extracting the shared parts into a helper method help reduce duplication and make the code easier to maintain?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761893620" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I noticed getStatusIcon() was changed from public to protected. Could you share the reasoning behind this change? I’m curious how this affects accessibility from other parts of the codebase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761894715" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how the Event class clearly separates from and to as distinct fields.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761896574" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like how the loop uses early continue statements after handling each command. It makes each command block feel self-contained and keeps the control flow easy to follow without deep nesting.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761900494" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I like that the variable name is descriptive and make the intent of each variable clear. It made the flow of the main method easier to read.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#pullrequestreview-3748636728" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

I found the code generally easy to follow, especially the clear command handling structure and descriptive variable names. The changes fit well with the existing codebase, and the formatting made the control flow straightforward to read.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 51. LI L..YING `@liny666` (20 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761907688" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Helper methods such as verifyDeadline, verifyEvent, helloGreeting, and byeGreeting help separate concerns and improve readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761910935" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Indentation and brace placement are consistent throughout this loop, which helps with readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761912411" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

words[0] is accessed repeatedly. Extracting it into a variable (for example, command) once would improve clarity and reduce duplication.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761913277" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Variable name idx is slightly abbreviated. A more descriptive name like taskIndex would improve readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#pullrequestreview-3748653891" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#pullrequestreview-3748656751" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#pullrequestreview-3748658254" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#pullrequestreview-3748659175" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#pullrequestreview-3748660567" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, the code demonstrates good effort in structuring functionality through helper methods and performing basic input validation.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761890002" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Not sure I see Arrays being used anywhere in this class . Would removing the unused import help keep things minimal?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761891230" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

I like that you introduced isBye to make the loop condition explicit
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761895398" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Commented-out code appears in multiple places. should these be removed to keep the codebase clean?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761896300" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

This line is getting long. would wrapping it across multiple lines improve readability and keep within the recommended line length?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#discussion_r2761897634" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Minor style note: there is an extra space before the closing parenthesis . would tightening the spacing match the standard formatting?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#pullrequestreview-3748635036" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#pullrequestreview-3748636484" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#pullrequestreview-3748640843" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#pullrequestreview-3748641767" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#pullrequestreview-3748643408" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/70#pullrequestreview-3748645813" expanded>
<div slot="header">

**20 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, the code mostly follows the Java coding standard in terms of indentation, brace usage, and array declaration style.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 52. WAI .. YAN `@wy208` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771879890" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Since logo is a constant, it should be in SCREAMING_CAMEL_CASE. It should be named LOGO.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771886577" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Would be better to name it to isExit instead of exitFlag.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771889648" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good job in trying to work on Single Level Of Abstraction.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771892295" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good job in naming all the functions well in camelCase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771894287" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Clear and good comments given to make the code readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#pullrequestreview-3760310428" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2771857542" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good job on the correct indentation for case statements. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2771866662" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good try of trying to use Single Level of Abstraction Principle with meaningful names for each functions. However, I feel like it is possible to add more Abstract functions for example for case "mark",

index = Integer.parseInt(parts[1]) - 1;
task = list.get(index);
task.markAsDone();
ConsoleUI.showTaskMarked(task, true);

The code above could be be abstracted into one function called markTask();
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2771868430" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good job adding a new file, makes the code cleaner and more readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2771874407" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good job following coding conventions on brackets and indentations. Eg. not putting all the code in one line.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#pullrequestreview-3760275048" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 53. LEE ..RIAN `@brianerino` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2772577604" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of class name in PascalCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2772579864" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good use of methods as a verb and is written in camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2772588428" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

case statements do not need to have " "
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2772601424" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good if-else statements; indentation and bracket are done according to standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2772603909" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

well done; all statements are indented correctly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#pullrequestreview-3761142350" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772614159" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of Override on subclass of Task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772615737" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

empty line is redundant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772619078" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

else if/else can be placed on the curly brace on the prev line so that code is not too stretched and long
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2772622706" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

good use of camelCase for methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#pullrequestreview-3761182706" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 54. KUAH..RYAN `@bryankuah` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766925478" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

impressive. methods are well commented to explain their purpose.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766926550" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

impressive. good use of inheritance here, Todo correctly extends Task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766929657" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

handleEvent method is very long. Consider extracting some of the logic into a separate method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766933161" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

impressive. there is no deep nesting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766935246" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

the code for printing a task create is repeated in Todo, Deadline and Event. Consider making a separate method for this that can be reused.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#pullrequestreview-3754343664" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766908530" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

impressive. you are using camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766911314" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

impressive. your classes are named using PascalCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766912754" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

impressive. indentations are 4 spaces.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766913528" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

impressive. method names start with a verb.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#pullrequestreview-3754328098" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 55. RYAN..HANG `@ryantrc` (20 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771889450" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good method syntax of overriding superclass methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771897804" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

big block of code, put more comments to explain what u are doing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771898619" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

same, more comments

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771900664" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good subclass insantiation
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760323956" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760336491" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760337266" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760339860" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760343694" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Ryan Tan finished first PR review 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2771906803" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

appropriate naming of subclass Deadline
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2771909767" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

event subclass has readable syntax
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2771910584" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

include more comments. code is not very readable here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2771912012" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Task superclass appropriately names
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#discussion_r2771914308" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

comment here to explain why exception is thrown
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#pullrequestreview-3760347398" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#pullrequestreview-3760351172" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#pullrequestreview-3760352453" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#pullrequestreview-3760354644" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#pullrequestreview-3760357238" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/95#pullrequestreview-3760357929" expanded>
<div slot="header">

**20 :fas-comment:**
</div>

**Review Status:** COMMENTED

Ryan Tan PR review 2 done
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 56. CHNG..SEAN `@SeanChng` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/55#discussion_r2767415593" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like how you abstracted the functions. Very good!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/55#discussion_r2767444774" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good use of comments to describe the intended use of the function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/55#discussion_r2767451200" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Consider moving all variables before any methods if possible
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/55#discussion_r2767459634" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Consider extracting literals to a class for managing tasks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/55#pullrequestreview-3754877007" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2767348477" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Please be consistent when splitting functions into multiple lines
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2767363011" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Should there be tab spaces for switch-case statements?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2767378080" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I would prefer if these Strings were extracted out to a separate class for parsing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2767389640" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Should be a constant and named using SCREAMING_SNAKE_CASE
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2767405356" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

i like the effort in changing the greeting, but class static variables should always be organized before methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#pullrequestreview-3754806355" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 57. SARA..ANAV `@AkshayPranav19` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761738832" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Consider using switch case statements. Too many conditional if else statements used, Deep nesting can affect readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761747549" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

consider renaming count variable to something more specific like number of tasks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761755300" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

consider standardizing the indents, "     ", try using a variable to store the indent string for better ui consistency
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761807510" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

avoid using magic numbers, use constants for numbers like 9
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#pullrequestreview-3748464999" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall Good structure, try to adhere to coding standards like avoiding deep nesting and Single layer abstraction
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#pullrequestreview-3748551974" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761784399" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Avoid using magic numbers like 7, use constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761789517" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

the method handleUserInput is very long, consider making another class and try to follow single layer abstraction principle (SLAP)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761792256" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Consider adding default case 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761794937" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Inconsistent bracing style, case statements don't need ``{````}`` 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761799158" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Consider standardizing utility function, Method parseTaskIndex() is private but some similar utility methods like printInput() are public
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#pullrequestreview-3748515401" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good attempt, try to improve code quality by following the standards
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 58. XU Z..IHAO `@zihaoalt` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766819771" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Agreed, this helps reduce repetitive code 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766822848" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good use of ternary operator to make it cleaner
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766830376" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Searching for task numbers seems an important function that may come in handy later so maybe consider making it a helper function to improve readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766831617" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Agreed, same for the code below
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2766834277" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consider make it a private method since its only usage is in the toString() method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#pullrequestreview-3754241217" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great work so far
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/140#discussion_r2766768234" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Should this start with a blank line at the start to keep it consistent with other files
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/140#discussion_r2766790744" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Should this be stored in a new variable since args is meant for arguments when the program starts
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/140#discussion_r2766798614" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Maybe this could be changed to use println to keep it consistent with other parts of the file
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/140#discussion_r2766804150" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

love how you add detail comment for methods and class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/140#pullrequestreview-3754192469" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great work so far maybe consider change some of function calls to make it more consistent throughout the file
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 59. CHAN..FENG `@Chanyf123` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762004538" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

hey, I like how you implemented exceptions 👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762014740" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Is there a better way of finding the substring and starting/ending index?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762019015" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Should switch statements have 4 spaces indentation instead?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762024117" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I like the personality given to your chatbot.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762025899" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Good job on the 8 spaces.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#pullrequestreview-3748753431" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Looks good. Overall, I found your code easy to read for the most part.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2762058115" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Is the else if too long? Perharps can be extracted out?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2762059252" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how u made a variable for the chatbot name.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2762064141" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Not sure i like the nested if-else conditions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2762067097" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good comments given for easy following of code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#pullrequestreview-3748811385" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, code looks good, apart from the spaces after the brackets and before the curling brackets.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 60. CHEO..THEU `@matheuczx` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762025991" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

The 'main' method is really long, >30 loc, perhaps you could define some other methods to help shorten this?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762028614" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Could this deep nesting be resolved for better code flow quality?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762032239" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Perhaps you could try avoiding complicated expressions such as nested parenthesis?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762044476" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good and logical code structure overall in this class. Good job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#pullrequestreview-3748773782" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job with the iP so far!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2761997039" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like how concise your toString() override is! 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762001133" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Perhaps you could add a comment to specify that 'msg' represents message? Or use message as variable name.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762003852" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Remember to declare these two variables as Protected
'''suggestion
    Protected String start;
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762012921" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good job consistently naming boolean variables throughout the repo
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762015993" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

You might have missed out that there should be no indentation for case clauses in switch statement.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#pullrequestreview-3748745519" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good Job!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 61. YEO ..ZHAO `@YeoSiZhao` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761783128" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Can use break instead of boolean flag to exit while loop
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761796315" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Consider using switch statements instead of nested if-else for better readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761802123" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Consider keeping naming consistent as line 14. If same name variable is used, then use `this.done`
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761803050" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Consider using global variable for "100"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#pullrequestreview-3748514095" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job, no major issues! All the best for Week 4's tasks!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2761739997" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Clear documentation
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2761749373" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Correct coding standard of boolean variables
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2761754113" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Correct subject verb agreement - indicate plural form of tasks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2761758967" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Correct camel casing of variable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#discussion_r2761765364" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Correct capitalization of class name
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/159#pullrequestreview-3748466103" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job, no major errors on coding standards, can think about using switch statements instead of nested if-else loops.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 62. LIM ..HIAS `@ChickenPancakeBeef` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766918607" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I may be wrong but I feel like there is excessive comments? Also, if the comment is one line, I think can just use // instead, so the code takes less lines.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766921902" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good use of inheritance
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766922660" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Correct and meaningful use of polymorphism
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766924974" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of camel case and appropriate variable names
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766925930" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consistent and correct indentation spacing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#pullrequestreview-3754337429" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good Job overall
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/124#discussion_r2766901804" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of using camel case naming style, with variables well labelled and consistent indentation spacing


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/124#discussion_r2766908146" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Really good and meaningful use of inheritance which adds value and fulfills the requirement
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/124#discussion_r2766910461" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good that you did not indent case, which I think is a common mistake

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/124#discussion_r2766937145" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

polymorphism also used well and correctly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/124#pullrequestreview-3754322077" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job overall
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 63. SUWE..STHA `@Suwei02` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/3#discussion_r2761870298" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Names representing methods are verbs and written in camelCase. Good job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/3#discussion_r2761874265" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Used K&R style brackets, good spacing that follows the coding standard. Nice job.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/3#discussion_r2761878593" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Put every class in a package. So you should have a package named task maybe and put all the task classes inside.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/3#discussion_r2761880778" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Boolean variables/methods are named to sound like booleans. Nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/3#discussion_r2761883809" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Iterator variables appropriately called i. Well done.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/3#pullrequestreview-3748615212" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

coding standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761898024" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

(code quality) Good naming of variables in general.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761899533" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Avoid magic numbers, change 100 to something like this: private static final int MAX_TASKS = 100;
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761909697" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

To make the code more easy to read, I suggest you can extract out all the printing lines as another method. for example having methods like printMarkTask, printTodoTasks, printList
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2761912778" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

This block of code can be extracted, like public static void greet() ``{`` ``}``. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#pullrequestreview-3748643930" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Coding quality. I'm very impressed actually, your code is very neat! You used if continue instead of if else if, making it very clean.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 64. KYNA..U QI `@wKynaston` (19 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767405659" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

good overall structure your  main reads clearly from top to bottom 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767406113" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Proper use of polymorphism
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767406920" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

clear constants avoid the use of magic numbers 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2767408557" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of index validation, clearly separated into its own method for clear reading
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#pullrequestreview-3754866721" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#pullrequestreview-3754867304" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#pullrequestreview-3754868109" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#pullrequestreview-3754869664" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#pullrequestreview-3754872566" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

good job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2767382174" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Very clear structure, the use of the helper functions makes the programs easier to follow 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2767386296" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Good use of polymorphism where the Task datatype can be used in the event, deadline, and todo class 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2767387871" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

meaningful variable names that give intent on what you are about to do
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2767391266" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

creating a new scanner every loop is not a great idea can cause potential problems 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2767399246" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

good use of camelcase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3754841156" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3754845385" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3754847095" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3754851482" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3754859797" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

**Review Status:** COMMENTED

good job
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 65. DENG..AOFU `@GGBondxX` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766710994" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good extraction of methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766715006" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good handling the different scenarios
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766719247" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good converting the input to lowercase so its not case sensitive
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766719552" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good use switch

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766721541" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Perhaps more spaces can be added to make the code more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#pullrequestreview-3754135908" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2766681266" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good that you have a botName variable to make the code more readable 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2766693854" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good handling wrong user inputs
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2766697088" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Perhaps the name you wanted to put is trackTask
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2766703273" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good use of switch
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#pullrequestreview-3754107442" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good job
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 66. AFSH..ULAM `@AfshalG` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2766926727" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like how you followed the PascalCase convention for the class names (e.g., Deadline, Event). It makes the type hierarchy very clear!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2766928257" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Great job naming the boolean method isDone(). Using the is prefix makes it read very naturally in English, just like the core Java packages.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2766967050" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I noticed the current structure uses multiple if statements for command handling. If you decide to use a switch statement later, remember our style guide suggests no indentation for case clauses relative to the switch block. Perhaps something to keep in mind for future refactoring?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2766989521" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

The variable i is used here. Nothing is wrong with that. However, I suggest a more descriptive name if it wasn't a simple loop for readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2767000019" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Good use of magic line at top level. This ensures no repetition of these lines. Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#pullrequestreview-3754344892" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, Well Done!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767041776" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like that this method name is explicit, but perhaps a more descriptive parameter name than bool would help the reader? For example, isTaskDone or newStatus explains what that boolean actually represents in the context of a task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767065115" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how you extracted the logic for finding the task number into its own method! This is a great example of SLAP Hard, it keeps the higher-level handleMarkCommand clean and focused on the logic of marking tasks rather than the low-level details of string parsing.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767074246" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good use of the guard clause here! By checking if the task list is full and returning early, you’ve kept the 'happy path' (adding the task) un-indented and easy to follow at the end of the method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767082813" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I noticed the string "/by" (and similarly "/from"/"/to") is used for parsing. We can consider using named constants in the future. It would make the code more robust and easier to update if the command syntax ever changes.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#pullrequestreview-3754466562" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good Job! 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 67. JOEL..N YI `@JellybeanJoel` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772210144" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good implementation that deals with errors that may occur from certain messages
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772216482" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good change of variable that uses getTotalNumberOfTasks from Task class instead
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772224131" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Indentation not adhered to coding standard but already changed in subsequent commits
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772225732" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of comments to explain the code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772248883" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Can consider usinh switch case statements instead of multiple if else
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#pullrequestreview-3760347936" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771833799" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

The code is very clean and neat.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771855851" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Space here should be removed
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771865802" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

else if and else statements should follow behind the if statement brackets instead of being on the next line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#discussion_r2771872897" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Nice use of split
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/94#pullrequestreview-3760248545" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 68. LAM ..THAN `@lamzl` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2761903563" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

there is a coding violation in the naming convention of this variable, please rename this
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2761938874" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good naming convention, following coding standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2761940874" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good naming convention, following camelCasing for functions.

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2761947184" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good camelCasing, following coding standards

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#discussion_r2761960697" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

magic number, please avoid using, declare a static constant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/118#pullrequestreview-3748649751" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good code, there are some minor fixes to conform to conding standards, but otherwise good code!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2761920117" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Avoid long expressions. Can try if (choice &lt; 4) or something. Or use an array to check whether the result exists inside the array.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2761968066" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

good following camelCasing to name methods and functions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2761990040" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

can declare a variable for input.toLowerCase() to make the code less clunky.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2761992294" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

use constant variable instead of declaring magic number of 100
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#pullrequestreview-3748665675" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

good code quality, just minor fixes, good job!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 69. CALV..UANG `@Calvin-GH` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766907479" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Could use more consistent verb such as

markAsDone
markAsNotDone
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766912039" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

@override Improves readability and lets the compiler catch mistakes good job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766913127" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Follows good coding standard on nesting 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766914592" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

add @override to toString() for better readability and lets the compiler catch mistakes
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#pullrequestreview-3754327162" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766930129" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Could split up different class files for for better code quality and also improve readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766935867" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Follows good code quality guidelines on nested
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766943035" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how you are reusing BAR for consistent formatting makes things abit neater. Maybe suggesting extracting this message into a helper method like printTaskAdded might make future message changes easier?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766946397" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like that you make the constructor ensures that a new task starts as not done. im not sure if initializing isDone at the field declaration be another easier option to consider could probably consider that?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766947631" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Overall follows good code quality guidelines however just take not to split up to multiple classes so that the code does not end up in one huge chunk
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#pullrequestreview-3754348146" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 70. DENY..MADA `@denyh6` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2766934375" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Please leave a blank line after the import lines 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2766937015" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Remember to leave blank lines between every function declaration as per the standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2766938670" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Appreciate these comment lines that clearly show what each case is for
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2766941008" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

As per the standards, try to leave a space between phrases. Like tasks.markDone(idx - 1); instead of tasks.markDone(idx-1);
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#discussion_r2766946917" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Indentation issue. Should be ``}`` else ``{`` in a single line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/77#pullrequestreview-3754352058" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766913859" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I appreciate you using a helper function, keeps the code neater
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766921023" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

More comments like these would be helpful in clearly showing what each else if branch is for
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766923619" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Although it is helpful and clear to leave blank lines before and after the task assignment, like markAsDone or markAsNotDone, please check if that would be accepted and within the coding standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766932443" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Maybe can be more descriptive in the name, like taskDescription
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#pullrequestreview-3754333118" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 71. TAN ..COLM `@natmloclam` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2766798142" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

these lines do not comply with the coding standards: 
should be like 
```
public static String getAddMessage() ``{``
    return getRandom();
``}``
```
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2766824251" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

This function is easy to understand because of the printLine() extraction 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2766829482" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good use of final here since they are constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#discussion_r2766831196" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

short form of a conditional statement makes the code easier to read
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/61#pullrequestreview-3754220737" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

great work so far
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2768200913" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

possible to extract these into another method like printMarkTaskMessage()
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2768211798" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

possible to simplify to one method like 
```
public void setDone(done) ``{`` 
    this.isDone = done;
``}``
```
also the method name should be in camelCase 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2768232894" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

main function is very long, can extract most of the stuff out 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2768246929" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I think you can create another Java class file called Task.java instead of creating it inside 67
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2768270662" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

variables should be in camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#pullrequestreview-3755921649" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

good job, main problem that I can see is that your main function is very long, can try to extract the bulk into portions like readInput, markItem, printItem, printList etc. 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 72. TAN ..YANG `@yueyang1111` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761767573" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Correct spacing around the operator "-"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761780113" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Correct use "tasks", but maybe can extract the "100" magic number
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761783388" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

The line is repeated in multiple print statements. Would it improve readability to define it as a constant?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2761866793" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Indentation and alignment are consistent throughout the file.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#pullrequestreview-3748496827" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall the code is neat with consistent indentation and alignment. Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2761803828" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Can consider using case switch to improve the readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2761806128" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Perhaps can avoid nesting if else statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2761807807" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Can extract the different print statement as a separate method, to improve readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2761810326" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Maybe can extract "100" to avoid magic numbers and improve readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2761862716" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

If the user type mark with no number, this might fail, so maybe could do a try catch block to avoid this
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#pullrequestreview-3748548678" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 73. ZHU ..HENG `@yc-zzz` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2767433212" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Great use of constants for repeating value!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2767449333" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Can afford to use constants too to replace the 2 too, such as STRING_LIMIT.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2767468821" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Great use of comments to make things understandable for the readers!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2767488537" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good job keeping the function names as verbs!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#pullrequestreview-3754896418" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great adherence to coding standard overall, very few magic numbers and good naming of constants and functions!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2767330136" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Great job catching edge cases!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2767362363" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Would be great to use a constant for the 2. Is it to indicate the max array number?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2767389822" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Will be great to have spaces for i + 1 according to coding standard!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2767403141" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Recommended to use try() catch() finally() according to coding standard.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2767416562" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Great job following the coding standard for switch statement!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#pullrequestreview-3754788006" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good adherence to coding standards overall!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 74. ONG ..JOEL `@jwelo` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761808166" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Should you consider refactoring the print statements into a method?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761810835" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Should you consider renaming your announce method? As it is not intuitive to what the method is doing 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761812573" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I like the use of inheritance here from the superclass method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761813560" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good job on annotating the Override method, it is helpful for readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761815167" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like how the variable is named in camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#pullrequestreview-3748552646" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, good job on the code. The classes are described well with use of inheritance. There are some minor readability tweaks but code largely follows coding quality guidelines.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#discussion_r2761753103" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Is there a need for the access type to be protected?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#discussion_r2761762750" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Should you consider extracting out the horizontal line as a function?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#discussion_r2761768956" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Consider using switch-case block instead of if-else for better readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#discussion_r2761773677" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I like how the boolean variables sound like boolean variables
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/120#pullrequestreview-3748480417" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

I like how Variable and method names following coding standards. However, there are a few improvements I suggested that might improve readability
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 75. LAU ..I NA `@lauwn-mower` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2762001904" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Can consider using switch statements instead :0
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2762010967" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Could have made use of toString() method instead of hardcoding the checkboxes imo
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2762035882" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good code structuring according to what each section seeks to achieve
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2762041130" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Perhaps can name this as KanadeGreeting instead? Since Kanade and Chat may sound like they serve similar functions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#pullrequestreview-3748748183" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2762019440" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good that you wrote and used a succinct method to printLine()
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2762021881" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Can consider switch statements instead of multiple if-statements?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2762023939" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

(Not code quality) typo here &hat;&hat;
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2762025884" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Perhaps can put these lines under the same paragraph/structure since they focus on splitting and decoding the user input
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#discussion_r2762030110" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Consider creating subclasses in a separate file?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/108#pullrequestreview-3748767808" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 76. SRIM..IJAL `@TrijalSrimal` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772583713" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

A long if else chain, a few comments could be added here to ensure clarity
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772585857" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Great job on breaking the task into multiple functions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772590607" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

A few comments could be added to make the functions easier to understand and make the code more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#discussion_r2772601472" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

A comment could be used here to describe what the event class does
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/96#pullrequestreview-3761149601" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772656704" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

The main method is currently violating SLAP. It is handling high-level control flow (the while loop), mid-level UI logic (the greetings), and low-level string parsing (the substring and split calls) all in one place.

Suggestion: Refactor the main method by extracting the command handling logic into separate private methods, such as handleMarkCommand(), handleTodoCommand(), etc. This keeps your main method clean and easy to read at a glance.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772658116" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Method Length
Following the point above, the main method is becoming quite large. Under our coding standards, we should aim to keep methods short and focused. A method that spans 50+ lines and handles 7 different logic branches is a prime candidate for refactoring.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772659917" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

It is better to not use magic numbers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772661267" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

A few comments could be added here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#discussion_r2772665270" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

The absence of javadoc comments makes this code unreadable, a few comments could be added here to make the code more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/99#pullrequestreview-3761232358" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 77. VIHA..HAAN `@Novgor0d` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2766811739" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

would making this **private static final String LOGO** better reflect that it's a constant?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2766824380" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good job for following the collection naming guideline and keeping it plural.

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2766830286" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Boolean variable naming follows the convention and reads naturally.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2766833010" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good job for following the class naming convention and using PascalCase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2766837988" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Good use of curly braces even for one line conditionals.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#pullrequestreview-3754233881" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2771948964" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Inconsistent capitalization here which doesn't match the naming style seen in the rest of the code such as *eParts*, *Dparts*. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2771971740" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The `main()` method is handling multiple levels of abstraction and could be refactored to align with the Single Layer of Abstraction Principle (SLAP).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2771978055" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

The Ui class is consistently formatted and separates responsibilities well
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#discussion_r2771997067" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

`input.substring(7)` uses a magic number to parse the input, it would be better to define a `static final int REMOVE_COMMAND_LENGTH = 7;` to explain what this number represents.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/160#pullrequestreview-3760407568" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 78. SANG..CHAY `@Nishchay2576` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2772645275" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Can use switch case instead of so many if else

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2772646911" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

ou've broken down the UI logic into small methods like greetUser(), printLine(), and printExitMessage(). This is a good start toward SLAP.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2772649428" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

In addEvent and addDeadline, you use hardcoded values like substring(5, ...) or substring(8, ...). Instead of using  magic numbers like this, declare them as variables instead and use variables
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#discussion_r2772653229" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

There is significant duplication in the 'add' methods. You should centralize the 'add to array' and 'print confirmation' logic into a single addTask(Task t) method to ensure consistency and reduce code duplication.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/39#pullrequestreview-3761218992" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2772576588" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Keeping all user-facing strings in one file is excellent. It makes tweaking Steve's personality and responses really easy
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2772583135" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Haven't added javadoc comments
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2772596807" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice way to print the formatted text in the output console
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2772624839" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Great application of SLAP here. The main method stays at a high level of abstraction, focusing only on the program's lifecycle (starting, looping, and terminating). By delegating the heavy lifting to processCommand, you’ve kept the entry point clean and easy to read.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2772629674" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

variable name for the parameter t should be renamed to something like task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#pullrequestreview-3761141146" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 79. HU L..IFAN `@Anormalm` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2772597277" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

main method is considered too long, consider rather breaking it down to multiple methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2772600664" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

while(true) and nested else may curb readability, consider using continue/break
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2772603576" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

may lead to blank separators.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2772606529" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Consider using split(), substring() could be risky when user inputs e.g."mark [enter] / mark abc def"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2772617953" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consider edge cases, splitting using regex is not recommended.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#pullrequestreview-3761163390" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2772577924" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

The class name List may conflict with java.util.List. Consider renaming it to something more specific like Task or TodoItem.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2772579920" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Method name should have a lowercase start like runList[].
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2772581745" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Consider closing the Scanner after using it.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#discussion_r2772584475" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

line.contains("mark") can bring up unexpected input like "remark" taken, consider a stricter fix like startsWith().
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/180#pullrequestreview-3761142856" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 80. HUAN..NJIN `@hykzr` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761875513" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

good: separate task managing to a separate class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761881164" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

there's an extra space before the last `)`, maybe it's better to format this file
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761884785" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

there's comment about format for `event` but not `deadline` and `todo`, maybe consider adding comments as well
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761889009" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good: all classes follows naming conventions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761891024" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

if taskID is negative or greater than total tasks it will crash, maybe add bound checking
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#pullrequestreview-3748620924" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2761909519" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

good: avoid magic number and hard coded printing. although i think you don't need `STARTING_INDEX_OF_..._TASK_DESCRIPTION`, just extract the first word, then `firstWord.length() + 1` should be the index you want 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2761913082" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

could use `enum` to represent position instead of `String`

coding standard:
>  Use enumerations when a certain variable can take only a small number of finite values. For example, instead of declaring the variable 'state' as an integer and using values 0, 1, 2 to denote the states 'starting', 'enabled', and 'disabled' respectively, declare 'state' as type SystemState and define an enumeration `SystemState` that has values 'STARTING', 'ENABLED', and 'DISABLED'.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2761914865" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

consider store `userTaskArray` as a member of `taskManager` so that you don't need to pass it every call
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2761925035" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

remeber to increment taskIndex after adding task, or abstract it into another insert function so that you can meet the standard "Avoid having multiple levels of abstraction within a code fragment"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#pullrequestreview-3748655497" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 81. WANG..GJIN `@E1484104` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2762298576" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Maybe this part can be extracted to a seperate method called handleCommands to improve your main function readability, make the code inside at the same abstraction level.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2762300203" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good initialization to avoid troubles. Nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2762302793" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Here are 2 magic numbers 5 and 9. Maybe you can define 2 constants to store them named XXX_PREFIX. Making the code more readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2762305585" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

How about newTask == null? Would you like to report error flag or just leave it there?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2762308693" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

if user input 2 consecutive spaces then some errors might occur. Maybe you can use another .trim() function to clear the substring.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#pullrequestreview-3749110572" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Very good coding standard and code quality! There's only several issues to be modified. And I noticed that you paid attention to several corner cases and improve your codes robostness. That's very nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762272046" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Here the viriable is supposed to be a noun, used like a counter. So a better variable name could be "taskCounter".
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762282337" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

It's better to define a constant for the spaces at the beginning of the output line. It could be more convenient for programming and easy to unify the format.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762284741" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

All spaces can be defined into different constants.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762286952" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

This 5 here is a magic number. Maybe you can use a constant named XXX_PREFIX to record this number.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#pullrequestreview-3749077629" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

The coding standard is quite well, but there are some magic numbers and strings in your code. Maybe you can define some constants to store these variables to improve your code quality.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 82. CHEN..DONG `@Alex-Chen-666` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762029451" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good PascalCase class naming!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762032132" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good camelCase naming of the variable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762035892" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Using abstraction at the same level, following SLAP - Single Level of Abstraction Principle, nice.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#discussion_r2762046840" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

nice logical structure which avoids deep nesting!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/88#pullrequestreview-3748777349" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, your code looks good to me and has a good coding quality.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762004720" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Imported classes are listed explicitly, nice.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762006601" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

great use of constants! Constants names are all uppercase, nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762009192" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Use K&R style brackets, nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762011938" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

nice use of switch statement!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2762014391" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

nice indentation!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#pullrequestreview-3748753629" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, the codes looks good to me. They follow the coding standard.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 83. VION..JOGO `@vionyp` (13 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#discussion_r2761826589" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

if the users inputed event doing homework and forget to provide the /by then the program will crash beacause of  ArrayIndexOutOfBoundsException, so maybe can check the length of parts before accessing index 1 or 2
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#discussion_r2761833794" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

if the user typed mark with no number, or like  mark everything, then the Integer.parseInt will fail. suggestion: can store the split result first and check whether it is a number or not and give try-catch function after that
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#discussion_r2761872932" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

instead of putting the indentation inside your println maybe it will be easier to make a helper method to add the indentation for you
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#discussion_r2761877383" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

when calling  addTodo(parts[1], taskCount) the program might crash if there is no space "todo", so maybe can validate parts.length > 1 before trying to access index 1
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#pullrequestreview-3748570477" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#pullrequestreview-3748618297" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2761803137" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Variables should be nouns that describe the data they hold (violation). Suggestion : use variable's name like taskList.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2761803810" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

equalsIgnoreCase() will be better to ignore the cases of the character (whether it is uppercase or lower case)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2761804717" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

what if the user type a space before the mark? maybe can try check if the command is exactly mark followed by a space, or split the string by spaces.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2761805183" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

can try use the try-catch function because if there is no number detected then the program will crash due to NumberFormatException
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2761853192" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

using if else might cause a deep nesting so to avoid that it is suggested to use switch case statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#pullrequestreview-3748548034" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#pullrequestreview-3748597552" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 84. TANG..AVEN `@Simplificatedd` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2766935106" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Nice one making an enum to store the Task types as it will make your code cleaner and safer and will enable you to use switch statements!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2766944763" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

why not use Enum to fetch the [T] [D] and [E]s?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2766953153" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good use of K&R style brackets.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2766956846" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good use of SCREAMING_SNAKE_CASE for constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#pullrequestreview-3754352727" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766906000" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like that you have a function for printing error messages. Good reusability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766908505" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like that you defined constants to reduce magic numbers.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766911867" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Amazing job following the naming conventions for constants by using SCREAMING_SNAKE_CASE.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766913125" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good use of inheritance here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766913967" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Good job on the inheritance here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#pullrequestreview-3754325866" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 85. KHOO..SAAC `@cyanduck32` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2766687867" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

ideally variable name should be in camelCase so you may consider changing to that 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2766688948" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

likewise! Consider changing to camelCase for variable names

or if it is a constant name, you may use SCREAMING_SNAKE_CASE
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2766698782" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

consider adding a space between the ToDo ``{`` 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#discussion_r2766706764" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

follows Lambda-style switch statement. Looks good.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/117#pullrequestreview-3754113577" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

looks good to merge!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766711904" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

good customisation
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766718333" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

can consider putting this as a constant above 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766721961" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

consider breaking the content of the case statements into separate methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766737757" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

likewise you may consider splitting into methods and reduce nesting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#pullrequestreview-3754136845" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

looks good !
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 86. CHUA..IANG `@chuayongliang6` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761895951" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

If/else block for coding standards is correct, put in the same line as the close brace of the previous block.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761897318" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Agree that Task should be in plual form
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761905447" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Correct use of K&R style bracket
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761906954" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good that you listed out all the libraries
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761918591" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

The dividers could be extracted out as a static final String DIVIDER at the top
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761922151" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

could be intialise () instead of initialisation() because it is a verb
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2761925483" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

this is good. very clear about what the main function runs
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#discussion_r2762151370" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The function seems to be mixing multiple levels of abstraction, e,g, getting inputs, followed by a while loop doing low-level tasks. Perhaps you could abstract the low level tasks into functions so that receiveInputAndPrint() have more or less same level of abstraction
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#pullrequestreview-3748632044" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall coding standards are adhered to. good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/133#pullrequestreview-3748664217" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Generally good code quality, with some minor adjustments
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 87. TONG..GAIL `@abigailtong` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762326461" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

could make printing as a separate function as its repeated
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762329155" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

avoid magic numbers, can make a named constant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762332580" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

could try to separate into multiple methods 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762335803" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good on avoiding arrowhead style
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3749142580" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762300830" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

i like how you made this into multiple methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762311212" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

could consider making it switch case instead of multiple if else
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762311335" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

code is readable and fairly well organized.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#discussion_r2762313937" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

good for making this a constant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/155#pullrequestreview-3749112787" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 88. POH .. HAO `@woshiweiha0` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771873412" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

good use of printLine() method so no hardcoding
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771874939" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

try not to have too much nested stuff, looks like an arrow
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771877136" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good use of if else statement
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#discussion_r2771878206" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good use of using EXPECTED to check
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/20#pullrequestreview-3760300942" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2771855805" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

good use of method so you do not have to hard code startWith("unmark ") etc.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2771859669" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

repetitive of hard coding the lines, suggest to use methods like printLine() (i notice this in other areas too)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2771862539" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

do we need the logo?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#discussion_r2771869064" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

try not to use nested code too much
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/35#pullrequestreview-3760276868" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 89. CHIA.. JUN `@tablehao` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766829470" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good practice of naming variables. Most might have just named it as a generic "count" variable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766831913" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good practice of abstraction to make the code more readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766847725" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Maybe naming the variable as "deadline" would be more clear?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766849435" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Missing space between name and bracket.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#pullrequestreview-3754250586" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766802638" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

May consider creating a helper function to print a line with various lengths.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766813639" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Vague variable naming. Project scope is still narrow so it is still obvious it's referring to task count but would be good to name it properly now to prevent renaming it in the future.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766816425" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good practice of error handling early on in the project.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#discussion_r2766822505" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good practice of sanitising user input, maybe the next step would be to strip user inputs.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/67#pullrequestreview-3754225103" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 90. TIRO..LIND `@omcodedthis` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761740741" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like how you had reused method getStatusIcon() in yout toString() function, instead of printing it from scratch.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761748354" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I like the use of in-line comments, perhaps you could add javadoc comments to make it more clear & separate the main() method into sub-methods, for better readability and maintenance.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761758248" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

You could consider putting the characters of the print statement into a constant instead, any reason why you had done it in this way?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761803989" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I like the use of in-line comments!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#pullrequestreview-3748466869" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

LGTM. Your code was clear for the most part with a few changes required here and there.

Great work!

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#pullrequestreview-3748548803" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#discussion_r2761782088" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Consider adding javadoc comments to this method so that it is more clear on what this method does.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#discussion_r2761784748" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how well this segment was structured - consider the use of a enum, for each case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#discussion_r2761787843" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like the use of abstraction to print the horizontal line - maybe you could consider putting this into a constant instead of making it a separate method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#discussion_r2761792213" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I like the use of other methods of the class for the toString() - great work!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#pullrequestreview-3748512925" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

LGTM. Just a few suggested changes, - great work!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 91. JAIR.. RUI `@Jairusljr` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767405567" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like the application of SLAP here. By delegating commands like addTodo and handleMarkCommand to separate methods, the 'story' of the main command loop remains high-level and easy to follow. The reader can see the logic of what the program does without being bogged down by the details. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767417964" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Nice job using SCREAMING_SNAKE_CASE for your constants. This clearly distinguishes your fixed configuration values from variable state, making it obvious to other developers what should and shouldn't be modified at runtime
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767423350" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Great use of the @Override annotation here! I like how you called super.toString() instead of re-writing the description and status logic. This follows SLAP and the DRY principle
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#discussion_r2767428739" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Avoid use of magic numbers here. 

To make the code more obvious and robust, you could define a constant for this value or, even use a guard clause that checks the condition more explicitly.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/174#pullrequestreview-3754866608" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good job following the coding standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/191#discussion_r2767437831" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good job on SLAP. By separating your logic into Ui, TaskList, and Task, the run() method in your main class reads exactly like a high-level story. A reader can understand the program flow immediately without needing to know how the list is stored or how the strings are printed.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/191#discussion_r2767451964" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like that you used an ArrayList instead of a fixed-size array. This allows standard Java collections to handle dynamic sizing automatically, avoiding the need for manual 'full list' checks that most other students used. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/191#discussion_r2767462882" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

According to Coding Standards, we should avoid redundant comments. Try to use Javadoc only to explain the behavior or constraints that aren't immediately obvious from the method name.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/191#discussion_r2767483283" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

In this method, you’ve included int total in the signature, but it isn’t used in the print statements. According to Coding Standards, this is a data flow anomaly.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/191#pullrequestreview-3754901628" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 92. MOHA.. HUK `@fmohamedfaras` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#discussion_r2761804670" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

This name SixSeven could have been a constant since it is the name of the bot, instead of defining it in the method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#discussion_r2761812111" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

The code has logical structure which makes it readable and easy to understand
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#discussion_r2761849124" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

your else statement, the else should be after the ``}`` bracket of the if block

if (condition) ``{``
    statements;
``}`` else ``{``
    statements;
``}``
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#discussion_r2761857403" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I like your attention to detail in the case of displaying task or tasks based on the number of tasks available
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#pullrequestreview-3748549374" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761751180" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like that you defined the LINE constant so that you can reuse it easily throughout the code. The usage of CREAMING_SNAKE_CASE makes it clearer that it is a constant.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761766686" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like your usage of the prefix "is" for boolean.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761834494" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Not a standard violation but just a suggestion, could this have been a switch case instead of if statements?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761839691" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Although your loop only had one statement, it is good that you put it in brackets
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#pullrequestreview-3748478300" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 93. TANP..PRAN `@PanGDX` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766663315" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like how you use .equalsIgnoreCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766674050" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I like how you use polymorphism on the class Task to store other child classes
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766680646" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

consider what happens if the array is out of bound
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#discussion_r2766682222" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

consider putting distinct classes in distinct files for ease of reading
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/126#pullrequestreview-3754085981" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall very good and readable!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766686893" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like how you encapsulate the welcome message in a function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766688821" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

consider what happens when the input is capitalised, for instance "Mark"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766690033" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how you encapsulate all your printing operations
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#discussion_r2766692340" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like how you use overriding to keep the function readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/129#pullrequestreview-3754112749" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

overall, great!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 94. HAO ..YIAN `@Yian123330` (18 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761923817" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Would it better if named as input/scanner?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761942430" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Clear separation of commands using if conditions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761945791" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Consistent use of "LINE" throughout
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#discussion_r2761952436" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Inconsistent spacing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#pullrequestreview-3748669042" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#pullrequestreview-3748688602" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#pullrequestreview-3748692022" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#pullrequestreview-3748698197" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/92#pullrequestreview-3748698600" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good Job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#discussion_r2761888925" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

The code is simple and well-organized, followed the indentation and spacing requirements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#discussion_r2761899780" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

 The UI class is well-designed with clear separation of concerns. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#discussion_r2761906387" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

There is inconsistent spacing: addTask(String task) ``{``
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#discussion_r2761909918" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

The addTask method doesn't check if taskCount has reached MAX_TASKS
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#pullrequestreview-3748633749" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#pullrequestreview-3748645712" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#pullrequestreview-3748652617" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#pullrequestreview-3748655853" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/169#pullrequestreview-3748657743" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good OOP design with separation of concerns!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 95. JERR..IKKO `@Elegazia` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761758678" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Well done using camelCase for method usage.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761832404" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Should there be a space for correct formatting?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761840862" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Change to singular noun as each Todo is a singular thing/object?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#discussion_r2761846060" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

maybe avoid too many levels of nesting for these conditional statements.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/24#pullrequestreview-3748486539" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good overall codebase, following a large majority of the rules required!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2761797456" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

exitFlag being true implies that you should exit when it becomes true. Maybe it should be reversed?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2761803910" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Should there be a named constant and enums instead of a magic number e.g. TASK_LENGTH?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2761811149" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good use for line wrapping given the large number of text in the logo!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2761814270" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good practice of @Override annotation to let the reviewer/yourself know
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#pullrequestreview-3748537346" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good attempt at creating your codebase!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 96. LIU ..KUAN `@llk214` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2762535649" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Nice to see you have a text-ui-test folder with test files! The structure looks clean with input.txt, EXPECTED.TXT, and run scripts for both Windows (.bat) and Unix (.sh). 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2762540413" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I see you've separated the code into multiple files - that's great for maintainability! However, with 10 Java files now and more in the future, it might be helpful to add some documentation explaining the architecture.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2762553040" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good job extracting the horizontal line and header strings as constants in CommandRunner! This follows the DRY principle nicely. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#discussion_r2762595741" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Very good idea. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/14#pullrequestreview-3749366508" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Very impressive.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2762302863" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Class name should be PascalCase - The class name clowns should be Clowns to follow Java naming conventions for classes.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2762305346" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Variable naming - Could usr_input be renamed to userInput to follow camelCase convention and avoid underscores?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2762321623" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Boolean variables should be named to sound like booleans. The exitFlag boolean is initialized to true but becomes false to exit. Would shouldContinue or similar be more intuitive? 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#discussion_r2762327392" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Plural class name - Class names are typically singular nouns. Should this be Deadline instead of Deadlines?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/45#pullrequestreview-3749114684" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Nice project
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 97. ADIT..SWAS `@adbsw` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2761838570" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Easy to read flow of code in the conditional statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2761856083" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Verb used for method good, could camelCase be used for the method name? Noticed the same issue in some places
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2761885184" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Could the boolean variable 'newStatus' be named to sound like boolean by using a prefix 'is', 'has' or 'was'?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#discussion_r2761910926" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Looks good to me
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/12#pullrequestreview-3748582640" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2761776581" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Looks good, a space could be given before the opening curly bracket, noticed the same in other places
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2761784065" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

'''suggestion
        ``}`` else ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2761795860" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The else or else-if statement could be on the same line as the preceding closed curly bracket, noticed the same in other places too
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#discussion_r2761804003" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Like that comments are given for easier following of the code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/102#pullrequestreview-3748506739" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 98. YAN ..NGYU `@Jas0n-yxy` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2762302982" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

maybe add the condition that the input number of the task is out of the total  number of the tasklist can help the code more complete
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2762308106" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

the use of line variable indeed save a lot of time of coding, good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2762311360" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

the comment in your code make the reader review the code more easily. nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2762315703" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

yeah a printWelcome() function can make the code more readable and efficient
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#pullrequestreview-3749114809" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

good job! the code is quite readable and easy to understand
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2762335919" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

good use of the switch case instead of while if, this make the code more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2762337857" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

maybe use a printWelcome function can make the code more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2762346111" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

add this line variable "-------------" inside the answer of your chatbot maybe can make it look nicer
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2762350095" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

the use of inheritance from the Tasks class is quite good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#pullrequestreview-3749152781" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

nice, your complete the tasks of the previous weeks quite well
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 99. JANS..ASIO `@kenpegrasio` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761780776" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Not a violation. But, for readability, you should be consistent when writing spaces around operators. Here you don't use space, but at other place you use it. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761786714" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good job for using PascalCase! Alternatively, you can name it UserInterface. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761790044" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Variable name `j` should be use on nested loops only for readability. You can name the variable with a more meaningful name like `endDate` for example.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761799668" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Same comment! Naming can be more meaningful. Consider naming it as `startDate`, for example. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#pullrequestreview-3748511272" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

All the best!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#discussion_r2761809000" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Consider overriding `public String toString()` function instead of creating a new one. This is such that your function will not be bloated!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#discussion_r2761813743" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Consider setting the access type as `private` by default. If later in time, `protected` is necessary, then change it to `protected`. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#discussion_r2761814514" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Why there is double space between `protected` and `String` keywords?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#discussion_r2761815671" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Funny! Like it!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#pullrequestreview-3748553445" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 100. RAJE..SWIN `@Aswin-RajeshKumar` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2764745447" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Avoid hardcoded magic numbers. Replace it with named constants like MAX_TASKS
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2764757747" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Avoid creating long methods  by extracting parts of this logic into helper methods.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2764777335" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good separation of classes and overall structure
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#discussion_r2764816978" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Should there be a line break for the return statement?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/36#pullrequestreview-3751892617" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2762293774" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I liked that you have separated the classes into two different files.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2762310589" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Avoid duplicating the greeting block. Try reusing the code in clever ways.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2762315193" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

This code line is too big, making it less readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2762322206" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good variable names, but you could just use private?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#pullrequestreview-3749105187" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 101. IAN ..HENG `@KOIiiii07` (18 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762022575" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I think you should avoid deep nesting. Refer to textbook w4.6c.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762028318" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

You can use .split("/", 3), then .replace("from", "") etc to minimise the number of lines of code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762032590" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I think that if the input doesn't fulfill any of the commands. The bot should inform the user of "invalid command" and state the correct format. Thus, the usability of the bot would be improved substantially.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762035597" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Well done! If the variable requires more description, from -&gt; startTime, to -&gt; endTime. This is just a recommendation.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#pullrequestreview-3748770608" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#pullrequestreview-3748776209" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#pullrequestreview-3748780903" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#pullrequestreview-3748785376" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#pullrequestreview-3748786791" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

4 comments by Ian Choo Tzie Zheng
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761972293" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

The level of abstraction of this method is the same. Well done.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761980491" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

I think you structure the code as such: (textbook: w4.6g)

LOGIC STATEMENTS
SPACE
PRINTING STATEMENTS
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761991783" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

I think you should display the valid command options here for usability purposes.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761995764" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

can try, split by "/", then .replace("from", ""). could save few code of lines.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3748717976" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3748727838" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3748739922" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3748744053" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3748754243" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED

4 Comments by Ian Choo Tzie Zheng
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 102. CHON.. JIE `@ffluryy` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766901657" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Would be better to make the greeting a method, so you can separate the printing from main
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766909286" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good naming
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766911141" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good use of boolean naming

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#discussion_r2766912152" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

you should use a switch here instead of a bunch of if statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/21#pullrequestreview-3754321942" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766915555" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

would be better to put the parser logic in a separate method so your main is clean and short
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766920636" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

you can make a method that handles the different task classes and call it, then your case can be "todo", "deadline", "event"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766921781" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

good use of static variable to track total number of tasks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766924097" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

could potentially use enhanced switch instead, they are more powerful and do not need a break line, which would minimise bugs but good use of switch
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#pullrequestreview-3754334686" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 103. LOUI..ERIN `@AgaraNUS` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2766943002" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of PascalCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2766943974" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good that boolean sounds like a boolean
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2766947868" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Can use comments to highlight the expected output
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2766949633" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Use comments to make this code more understandable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#pullrequestreview-3754359840" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766904378" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Nice that you named the array in plural form
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766908015" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good that your boolean sounds like a boolean
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766926643" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Surround operators by spaces. Somthing like "counter - 1" would be better.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766932810" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Add space between while and opening bracket
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3754324355" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 104. CEDR..I YU `@CedricTan24` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2767449411" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of switch cases. Could align the other code to this line, or separate it below the rest of the code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2767461094" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

weird name formatting of ackTask, maybe you meant trackTask?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2767472411" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

A bit of clustering between the cases, could consider separating it for better readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#discussion_r2767476981" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Try to avoid the use of the magic number "3", maybe an explanation with a comment or a named constant could be better to improve readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/62#pullrequestreview-3754913448" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767352582" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

From the above, excellent use of switch cases to make it easier. Could consider using a standard case for invalid command cases too.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767399860" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of static commands in replace of input.equals(), which makes it more cleaner and readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767402709" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Excellent use of the printHorizontalLine() command, which removes the need to System.out.println everytime.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2767411677" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Very clean and readable code for your Task 4 code. Great job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#pullrequestreview-3754810583" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, code has very good readability.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 105. MELV.. HAO `@Unicornyingg` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2771870890" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

CAn try to use constants

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2771872273" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

can try to use methods so you don have to type again and again
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2771873246" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good use of overriding methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2771873937" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

can try yo use substring index of
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#pullrequestreview-3760297874" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771856300" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good use of constants.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771864650" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

good use of overriding method so you don't need to keep retyping
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771865892" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice and clean way instead of typing it again and again
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771868700" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

good method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#pullrequestreview-3760277602" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 106. TEO ..SIUS `@5iu5` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771883321" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

good job following the conventions, but can consider using switch case statements instead of multiple if-else statements.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771895100" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

great use of method to abstract the code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771897624" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

great use of encapsulation: hiding the data (from and to), and providing interface via a public method toString
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#discussion_r2771900330" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Can consider use intelij ide to refactor the code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/31#pullrequestreview-3760315817" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771850344" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Excellent use of exception to catch error 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771867928" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

you had made an extra indentation here. Please remove the indentation in accordance to the coding convention.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771874500" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

redundant semi-colon here, kindly consider to remove 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771878610" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

good job demonstrating the use of encapsulation. startData and endDate are hidden and accessible through the public methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#pullrequestreview-3760269609" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 107. CHOY..HONG `@zhanhong03` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771970525" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like that this is very readable as it avoided long methods and deep nesting.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771976623" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I like how you delegated the messy logic and separated them, which makes the code easy to read.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771980975" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

This comment might be redundant as the code written may be obvious
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#discussion_r2771991164" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

By having the "updateTaskStatus", you managed to avoid writing the same code for both unMarking and Marking, which makes the code clean.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/48#pullrequestreview-3760437346" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2771860360" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like that the comments clearly separate the different things the code does. Makes the code clean and easy to read.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2771869485" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like that you used the "/** and ending **/" for the class header. This is the standard for generating official documentation in Java.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2771874372" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Maybe you can add the comments on the next line if the comment is really necessary. Adding the comments on the same line may make it harder for others to read the code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2771891501" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

This might be too many comments as the code written may be obvious.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#pullrequestreview-3760283427" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 108. YEO ..RYAN `@bryanyeo3125` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#discussion_r2772581725" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Use static final for constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#discussion_r2772589212" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

This loop is nested, like an arrowhead style. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#discussion_r2772591724" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

100 is a magic number because it is not defined why you chose 100
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#discussion_r2772596186" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

For code structure, perhaps you could group functions that work similarly together, such as isDone and setDone. This could help readers associate it more logically.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#pullrequestreview-3761147201" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good implementation!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2772566923" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Remove extra spacing in for loop
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2772568137" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

add spaces between "]" + "[" when concatenating
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2772570416" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

add spaces between index + 1
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2772572004" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Perhaps change the long string to a constant so that you don't have to type out the long line every time
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3761130034" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good implementation!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 109. MARK..IONG `@marken9` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2767394909" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

A named constant can be used instead of having a magic number
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2767409432" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I agree that a switch case statement should be used instead to avoid using so many else ifs.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2767413580" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good naming of variable using camelCase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2767417281" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Correct naming of method using camelCase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#pullrequestreview-3754855129" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/185#discussion_r2767350214" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

No need to capitalise B since goodbye is one word
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/185#discussion_r2767351402" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of named constant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/185#discussion_r2767358790" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Methods are named correctly using camelCase. Keep it up!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/185#discussion_r2767372495" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Putting the main path (marking the task) first is good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/185#pullrequestreview-3754808013" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 110. WANG..AIXI `@WangZX2001` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2772603666" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Maybe you should consider using Camelcase for this method? Perhaps you can also consider coming up  with better naming for this method (handleAction)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2772606605" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Maybe consider adding some spacing inside the for loop condition. for(int i = 0; i &lt; mySize; i++)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2772616939" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good! Declaring the constant using uppercases.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#discussion_r2772626118" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Perhaps you may consider using static in the method declaration. (e.g. public static void printItem(String item))
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/84#pullrequestreview-3761170965" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I think the quality of the code is okay, maybe take note of the spacing inside the condition of the for loop. You can also consider naming the methods clearer and easier to understand.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/193#discussion_r2772564329" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good! All constant names are in all uppercase and underscore is used to separate words
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/193#discussion_r2772571643" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Nice! The methods are in verbs and written in camelCase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/193#discussion_r2772577148" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good! Boolean methods sound like booleans
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/193#discussion_r2772587642" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good! Use of K&R style brackets
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/193#pullrequestreview-3761127347" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I think that the code quality is okay. You are following all the java code quality guidelines.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 111. TAN ..HENG `@WeiHeng2003` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#discussion_r2766905185" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like how you used the prefix is for boolean variables
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#discussion_r2766908475" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I like how the constant here is in capital letters
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#discussion_r2766914684" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Amazing job on following the indentation for nested loops, but I think you can consider using case switch statements or even creating methods and new classes (like Ui focusing on printing statements) to improve the readability of the code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#discussion_r2766921738" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Nice! Imported classes should always be listed explicitly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#pullrequestreview-3754325084" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2766924663" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like how you employed helper functions to make the code more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2766929239" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I think you can consider the use of making class files, rather than putting it all into one long main file
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2766932608" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice use of inheritance and overriding for creating subclasses
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#discussion_r2766938230" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I think that you can consider 'if-else if' statements rather than all 'if's, just in case the code somehow enters 2 if statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/186#pullrequestreview-3754342903" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 112. DING..OWEN `@b0wen120` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2762005202" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Using a "while" loop is smart, allows for clear and smooth code without adding a lot of if-else statements.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2762015961" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

This block of code from 12-15 can be simplified into a "static" line, makes code simplified and smoother.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2762022434" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Both userInput.startsWith for "mark" and "unmark" code seem highly redundant. A helper function can help simplify your code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2762025699" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Very good code quality in general and I see almost no coding standard violations! Nice work!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#pullrequestreview-3748754095" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Looks good! Keep it up!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2762039917" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good use of variable LINE and its .repeat. May want to rename LINE to something else as it may be slightly vague, something like DIVIDER_LINE? 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2762046091" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of while loop and creative responses! while loop and usage of break for "bye" input makes code quite simple instead of multiple if-else statements. Nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2762049622" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Upper and lower limit of taskcount with if-else statement is good! And creative responses as well for a unique chatbot!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#discussion_r2762056739" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Simple and convenient way to echo input. Smart really. But will have to change for subsequent levels.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/149#pullrequestreview-3748790668" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good work. Keep working on it and catch up to this week's iP tasks!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 113. GABR..G YI `@gabri3123` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2777913180" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

cool logo
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2777919629" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Not sure if this is intentional, but methods seem ordered somewhat randomly.
Would grouping them logically (e.g., main → command handling → helpers → printing) improve readability?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2777921993" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Would using an ArrayList&lt;Task> simplify things and remove the need for capacity checks?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2777922641" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good separation, having greeting, command execution, and exit logic in their own methods makes main very clean and easy to read.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#pullrequestreview-3767697635" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2777903847" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

What happens if the user enters something like mark abc or mark -1?
Should we consider handling invalid input more defensively to avoid runtime errors?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2777905206" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like how the main command loop is laid out each command is clearly separated and easy to follow.
It made the flow of supported commands very readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2777905582" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

cool logo :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#discussion_r2777910141" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I noticed Deadline / Event can be created with empty by, from, or to.
Should these classes validate inputs, or is validation intentionally handled in Greg?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/183#pullrequestreview-3767616760" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

gooood
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 114. WESL.. LOW `@Trivorten-wes` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2772582230" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

You should consider renaming booleans to start with 'is', 'has' or 'was' for easier readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2772586257" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Maybe consider using helper functions that you can call within if else statements to reduce the size of the if else blocks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2772596658" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Consider initialise variables that are common between if else blocks outside so you do not have to initialise them in each block
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2772599787" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I think it would be better if the "else if" was on the same line as the closing ``}`` from the previous if statement for easier readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#pullrequestreview-3761147737" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good code, I think that with some slight adjustments your code would be more readable!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772613556" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Consider making each if-else block shorter by adding helper functions that can be called from the if else blocks, this would significantly reduce the length of your main function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772623803" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

consider a helper function for this print line as it is called multiple times
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772633970" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

maybe use a javadoc comment so that the reader has a better understanding of the methods and attributes of this class 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#discussion_r2772634478" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

very good use of a helper function to help readability and neatness
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/184#pullrequestreview-3761182171" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good code, some usage of useful helper functions like printLine, I think that if you used more of these helper functions it would be even better!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 115. SEOW..VIER `@Javierseow` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771911376" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

can split into functions to make main not too long
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771913843" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

use line wrapping, your line over 120 characters long
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771917832" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

follow if else convention, else if should be on previous line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#discussion_r2771920702" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

use a more descriptive name
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/74#pullrequestreview-3760353649" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

overall good job 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2771851061" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

variable userInput should be in camel case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2771857863" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Your line is 121 characters long, should use line wrapping
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2771877608" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Can consider using a constant to represent 100, e.g. MAX_SIZE
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#discussion_r2771893495" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good use of Egyptian style brackets
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/146#pullrequestreview-3760270301" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

General good use of brackets and naming for the most part
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 116. LIM ..RIEL `@gabriel-550` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762000741" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps can replace this magic number
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762008355" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Perhaps can extract a method called printList
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762012526" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Perhaps can separate into different classes, such as Todo, Deadline, Event
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762016233" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Naming is generally good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#pullrequestreview-3748750111" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2762031543" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good readability by avoiding magic numbers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2762036989" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of different methods 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2762041887" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Perhaps can replace the magic number here as well
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2762047786" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Perhaps it would be better to use String description instead of line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#pullrequestreview-3748779616" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 117. WENG..YANG `@WengXianYang` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771843088" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Great work keeping the code easily readable by adding relevant comments to indicate overriding.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771855678" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good practice of coding convention by using full capitalisation for constants.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771860386" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good work replacing magic numbers to make it clearer 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#discussion_r2771868208" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Maybe can try using switch case for cleaner code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/89#pullrequestreview-3760261846" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall great job
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2771881735" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Maybe can try using isBai to follow the naming convention.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2771884303" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Maybe can try using switch case for easier readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2771889898" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Try using a constant to replace magic numbers.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#discussion_r2771898825" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Maybe can try following: ``}`` else ``{`` 
instead of having them on separate lines
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/172#pullrequestreview-3760313304" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall well done.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 118. AIDA..TONG `@aidan17715` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#discussion_r2762317614" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of the override function. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#discussion_r2762322897" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Class is well defined and describes the class well. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#discussion_r2762324674" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good use of if, else if and else loops. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#discussion_r2762328533" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of protected class. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#pullrequestreview-3749130841" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762289518" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good use of Override. Annotating toString() improves readability and maintainability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762297997" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Could avoid unnecessary .toString() calls, as java automatically calls .toString when printing. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762303026" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Line drawn to signal end of programme. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762309062" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Class is clearly defined and properly describes the class. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#pullrequestreview-3749099637" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Week 4 tutorial 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 119. HUAN..HUAN `@Huang-Hau-Shuan` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762027572" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good override
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762028782" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good else-if names for conciseness
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762029213" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good abstraction to prevent duplication
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762030771" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good line to signal end of program
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#pullrequestreview-3748775472" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Review code quality
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762003965" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

All follow basic coding standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762004658" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

All follows basic coding standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762005229" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Follows basic coding standard: indentation and naming
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762007425" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Follows good naming convention 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#pullrequestreview-3748752899" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 120. YEO .. WEI `@ZesterJ` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2771850802" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good job on proper use of REPL-style structure.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2771866100" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

suggestion, good practice to close scanner after loop
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2771873517" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

clear ownership of data and size
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#discussion_r2771878770" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

suggestion to use helper function for printing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/73#pullrequestreview-3760270055" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2771890170" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

good exception handling, keep it up
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2771892388" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

good use of bounds checking
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2771896495" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

try to stay away from usage of magic numbers

perhaps can use String[] parts = line.split(" ", 2);
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2771898832" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

perhaps can consider to use constant for separator instead of hard coding
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#pullrequestreview-3760325225" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 121. KOH ..TIAN `@LiTianKoh` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/10#discussion_r2774379840" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good naming convention for getting the icon to mark/unmark the task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/10#discussion_r2774381223" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Short and neat method



</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/10#discussion_r2774393175" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Neat that you defined LINE instead of using a long string of '-'
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/10#discussion_r2774402381" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good naming for action method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/10#pullrequestreview-3763370655" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good naming conventions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762288438" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I would suggest putting the override section at the bottom to help make it neater
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762290625" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Try putting the override section at the bottom of the class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762298833" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I would recommend adding spaces like this " [" + this.getStatusIcon() + "] " for better readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762305537" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good naming of object, not too long, easy to understand what you're trying to do with this object
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#pullrequestreview-3749098285" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good code overall, minor readability issues
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 122. RYAN..E XI `@ryanzx-zone` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772606494" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like that you made your lines a constant rather than hardcoding them, it makes your code a lot more readable and intuitive
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772612094" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

great usage of inheritance method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772620131" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

creative chatbot name
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#discussion_r2772621291" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

great use of split to separate the dates and event name
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/22#pullrequestreview-3761174138" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2772580561" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

great use of substring to extract the task number after the key word "mark"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2772591975" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

good job for implementing appropriate if else spacing
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2772595323" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like your camel case usage over here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#discussion_r2772599928" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

good and intuitive naming of boolean variable isDone over here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/161#pullrequestreview-3761145880" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 123. SHAH..TESH `@Kushalshah0402` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#discussion_r2766800612" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I feel that the main is quite long and handles multiple responsibilities. Perhaps you could extract command handling logic into helper methods to improve code maintainability and readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#discussion_r2766806694" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

There is use of hardcoded numbers like '5' and even '7' below which others might not understand when they recieve the code to work on it. Consider defining constants for command lengths to improve clarity.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#discussion_r2766817582" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I like that the else if chain is logically ordered and easy to follow. Commands are grouped clearly.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#discussion_r2766825157" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

The mark and unmark commands assume the task index is always valid. U could try checking the bounds (e.g. index &lt; 0 or >= taskCount) before allowing the command to be carried out
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#pullrequestreview-3754223151" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great work! Overall, I found your code easy to read for the most part other than the main which I feel could be shortened to improve code quality
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766920333" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

There are some magic numbers here which another reader might not understand. Perhaps try using named constants?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766932927" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Consider declaring constants as static final and using ALL_CAPS naming (e.g. MARK_INDEX) to better follow Java coding conventions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766940244" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

You may want to add basic validation for user input (e.g. invalid indices, index out of range) to make the program more robust.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#discussion_r2766942090" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Great code readability because you introduced a TaskManager class and delegated logic to it instead of stuffing everything into main
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/177#pullrequestreview-3754338972" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good separation of concerns by using a TaskManager, which keeps main clean and readable. The command flow is clear, and using named constants instead of magic numbers is a nice touch.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 124. AHMA..ADAM `@1cecream03` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762327139" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Short and direct method. Naming done in the write format.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762329787" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Perhaps it's better to use java.util.ArrayList&lt;Task> here. It will handles dynamic resizing automatically, simplifying the add/delete logic and removing the risk of array overflow.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762331945" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Clean indentation, with clean nesting that is not deep.

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762336906" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I agree with the previous commenter. Redundant use of this can be omitted.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#pullrequestreview-3749143274" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

LGTM!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762288742" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I second the point about avoiding deep nesting here. Extracting this logic into a dedicated method (e.g., unmarkTask()) would significantly improve readability and reduce the complexity within the main loop.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762300745" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good job on naming the function in the right format!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762305743" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good job on keeping methods short and direct!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#discussion_r2762311258" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

The number 5 is used here as a 'Magic Number'. It is not immediately clear to a reader what 5 represents without counting the characters in 'mark '. Consider defining a constant like private static final int MARK_COMMAND_LENGTH = 5.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/103#pullrequestreview-3749098766" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

LGTM. Keep it up!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 125. THIA.. HAN `@SheepSweat` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766702969" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of SCREAMING_SNAKE_CASE for constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766710706" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

camelCase could be used for the variable name "INTROS" instead of SCREAMING_SNAKE_CASE.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766799650" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good use of comment to indicate overridden function
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#discussion_r2766805934" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of camelCase for method names.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/4#pullrequestreview-3754128153" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Very good job overall in following the coding standards.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2766679573" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good use of PascalCase for Class names and camelCase for Variable names. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2766684239" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Perhaps a more descriptive name could be used for the remaining string as opposed to "rest". 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2766693565" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

A more descriptive name could be used as opposed to "numStr"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#discussion_r2766708459" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good use of comments to highlight an override
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/181#pullrequestreview-3754105162" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great job overall in following the coding standards
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 126. LOW .. WEI `@zenweilow` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2761749910" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

good job using prefix length constants instead of magic numbers 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2761761845" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

use input instead of in?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2761764338" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

keep the spacing between ``{`` consistent 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#discussion_r2761768842" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

very clear naming, great for readability 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/18#pullrequestreview-3748476731" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761797352" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

good, instead of fixed array, this way is more scalable 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761800748" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

can crash when not valid integer inputted 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761804678" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Everything is in main: UI formatting, parsing, task storage, execution, can extract into classes instead
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761807910" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

good naming, very clear and readable 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#pullrequestreview-3748536978" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 127. KART..RESH `@karthikkathiresh` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/52#discussion_r2766802247" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like the abstraction done in the main function to keep it simple and easy to understand. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/52#discussion_r2766817482" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Perhaps the use of constants for the command phrases? 
(Example: public static final String EXIT_COMMAND = "bye")
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/52#discussion_r2766819215" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I like the use of overrides to reuse functions here. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/52#discussion_r2766827712" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Perhaps the use of if-else to improve the readability of the code? Noticed this usage of ternary operators in few other areas also. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/52#pullrequestreview-3754224763" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, good job! Breaking down the code into multiple classes is a good idea and has made your code more readable. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2772355458" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

The try-catch implementation is missing the catch element. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2772357998" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Perhaps use a constant for this print message? Noticed this issue in few other places also. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2772364183" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

May want to consider case-break format if more conditionals are being added in the future. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#discussion_r2772365072" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good quality code that is readable! Able to understand what this code is doing. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#pullrequestreview-3760870278" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/125#pullrequestreview-3761264818" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall good job! The code is readable and easy to understand.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 128. DINE..AVAN `@dinvsh` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2767641537" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps use tasks (camelCase) here to follow the variable naming convention?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2767644040" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Any reason for the missing spaces? Maybe add a space after while and before the ``{`` to follow the while (condition) ``{`` format?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2767649472" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Would you consider adding a space before the ``{`` to match the Egyptian style mentioned in the guide? I noticed the same formatting in some the following else if blocks below as well.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2767690922" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Any reason for not having a space before to:? I'm worried the output might look a bit squashed, like (from: Monto: Tue).
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#pullrequestreview-3755150560" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

The logic is solid and the code is very well implemented! I just noticed a few minor nits regarding the Java coding standards.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2767764262" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like how you've organized the command logic! Since the main method is handling everything from scanning to string parsing and task creation, do you think we could perhaps extract the command execution into its own method? It would make the high-level logic in main easier to follow.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2767775600" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I noticed the use of names like part, part1, and part2. Any reason for not using more descriptive names like deadlineParts or eventDetails? 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2767790925" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I noticed that any unrecognized input currently creates a generic Task. Would it be useful to use this to catch errors or unknown commands instead?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#discussion_r2767800396" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like the ASCII art! Since this is a constant that doesn't change, should the name be in SCREAMING_SNAKE_CASE (e.g., LOGO) to match the standard for constants?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/166#pullrequestreview-3755323349" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, the code is very well implemented, and I like how you’ve separated the user interface logic into the ConsoleUI class to help with readability. I just suggested some nits to follow the standards.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 129. JOEL..L KU `@joeLku1` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761807868" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good job on commenting what each ```if``` statement does within the loop!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761808819" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

There is no way to set the boolean ```isDone``` to be false, could I suggest a setter method or a ```markAsUndone``` method?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761811914" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good job on using line wrapping for the logo for readability and ensuring that the number of characters do not exceed 120 characters.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#discussion_r2761813814" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Could I suggest that instead of adding a ```\n``` at the back, to use the ```println``` method instead?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/37#pullrequestreview-3748552363" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, great job on the code! Keep it up :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2761740033" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

From the Java guide,
> Plural form should be used on names representing a collection of objects.

Should the variable ```task``` be renamed to ```tasks``` instead?

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2761768501" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like the formatting of this, where the ```case``` statements are in line with the switch statement.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2761773772" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Should there be spaces before and after the operator?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#discussion_r2761779545" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

May I suggest removing the additional blank lines within the functions?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/72#pullrequestreview-3748466147" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job on your code! Looks good overall and coding standards are followed well.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 130. SEAN..LIYU `@SeanTLY23` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/64#discussion_r2761736645" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good job on uppercasing constant names and using underscore to separate words
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/64#discussion_r2761752287" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Note that there is no identation for case clauses. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/64#discussion_r2761756217" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good job on following the rule of always using curly brackets for if else and loops, even for single statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/64#discussion_r2761759917" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

None of your classes and methods have Javadoc comments. Try including some comments in your classes.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/64#pullrequestreview-3748462436" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761792355" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

This method violates SLAP as it mixes high level logic (creating and storing a task) with a low-level string manipulation. Try ensuring that high level and low level functions are separately grouped
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761800144" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Use of magic literals like 1 or 4 which can change if "/by" be changed to "--by" and is not immediately obvious why these exact numbers are added. Try using string.split instead
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761856752" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good job on making the happy path prominent by catching the error immediately instead of wrapping the entire logic in a giant if-else block 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761858213" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good job on avoiding magic numbers by naming the constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#pullrequestreview-3748525626" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 131. CHAN..ERNG `@yihernggggg` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2766798099" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Great use of static strings for tidying up code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2766804674" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I liked the implementation of this function, I could follow through and understand everything with ease.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2766809579" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I like the implementation of this.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#discussion_r2766813839" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Great implementation with proper input handling.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/8#pullrequestreview-3754220687" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job bro.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766817655" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I would use a switch case statement so its neater.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766818651" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Make sure to account for extra spaces in the input using .trim() method. Maybe have a separate input parser function.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766821324" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Make use of static strings for printing messages so the code is neater.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#discussion_r2766821969" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Overall clean implementation of the class.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/179#pullrequestreview-3754239348" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

W cydric bot
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 132. MAHE..URAV `@puma-31` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766820541" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Hard-coded substring indices reduces readability and makes the code fragile if command keywords change. Consider replacing these with named constants or computing indices based on command length.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766826492" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

The code mostly uses consistent 4-space indentation and logical structure for blocks, which lines up with the coding standard recommendations.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766832649" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good job on using SCREAMING_SNAKE_CASE and labeling them as static final for the constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#discussion_r2766835902" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Indentation on soft wrapping reduces readability a little. consider indenting with the line.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/5#pullrequestreview-3754241948" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766911086" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

The boolean field isDone is well-named and clearly indicates a true/false state. This is a good example of using boolean names that read naturally in conditionals.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766913487" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

The long if–else if–else chain makes it slightly harder to follow the command logic. I'd suggest extracting each command into a method to improve readability and reduce nesting.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766919947" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The numbers used in substring(5) and substring(7) rely on knowledge of command lengths. Using named constants (e.g. MARK_COMMAND_LENGTH) would make the intent clearer and avoid “magic numbers”
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#discussion_r2766923025" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

The variable name 'line' is quite generic and doesn’t clearly convey its purpose. Since it represents user input from the CLI, a more descriptive name like userInput or command could improve readability and make the code intent clearer.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/53#pullrequestreview-3754330395" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 133. CHAK..ASTI `@shrabasti-c` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766681408" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

You could consider using the @inheritDoc tag for javadoc comments for overriden methods.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766692691" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Perhaps you could consider renaming the "content" variable to reconcile it as the description of your tasks?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766693997" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Overall javadoc documentation is clean and well-segregated, following coding standards.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766701171" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Great work- all classes follow Pascal Case and have been refactored to show clear segregation of tasks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#pullrequestreview-3754107592" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766708860" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good job avoiding magic numbers by defining constants.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766712902" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

You could consider minimising the code duplication here?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766715093" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice work showing a prominent Happy Path in your main function.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#discussion_r2766735854" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good job- your code is structured logically and you have successfully prevented deep nesting with your conditional statements.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/175#pullrequestreview-3754133969" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 134. YADA..UMAR `@aruyadav13` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772572817" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like how you followed the coding standards and used UPPERCASE letters for constant names. Many people tend to miss that!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772589984" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I noticed you used hardcoded values like 5, 9, and 6 for the substring indices in addTask. According to the 'Avoid Magic Numbers' standard, would it be better to define these as constants (e.g., TODO_PREFIX_LENGTH) so the meaning is clearer?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772597880" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Great job applying a single Level of abstraction to the main method! It reads like a high-level summary because you extracted all the detailed logic into manageTasks and the print methods
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#discussion_r2772599477" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I see the variable name temp used in parseArgs. The coding standard advises avoiding generic names like temp. Would a name like argumentsAfterFirstSlash or remainingArgs be more descriptive of what this string actually contains?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/34#pullrequestreview-3761136302" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2772625349" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I see you used hardcoded numbers 6 for substring indices. The 'Avoid Magic Numbers' guideline suggests replacing these with named constants (e.g., TODO_PREFIX_LENGTH) to make the code more readable and robust against changes.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2772631873" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

According to the SLAP principle (Code Quality guidelines), the main method should act as a high-level summary. Currently, it's doing the low-level work of parsing commands (like split) and managing the task array. Would it be better to extract logic into helper methods like handleAddTodo(), handleAddDeadline(), or printTaskList()
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2772640902" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

The code currently assumes the user always enters perfect input. For example, Integer.parseInt(input.substring(5)) will crash if the user types "mark  two". The guidelines on Error Handling suggest validating input first maybe?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#discussion_r2772652234" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

The code layout is very clean. You consistently used 4 spaces for indentation and K&R style brackets (opening brace on the same line), which makes the code easy to scan and compliant with the standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/75#pullrequestreview-3761194370" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 135. PRER..NKAR `@prerana-r11` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766687682" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

perhaps the method names could use camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766706268" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

the statement under the if -block could be indented as specified in the standards
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766779572" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good job attaching array specifier to the type and not to the variable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#discussion_r2766895612" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

perhaps the method name could be more intuitive
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/28#pullrequestreview-3754113443" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766734294" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Great job defining named constants and avoiding the use of magic numbers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766826094" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

good job with consistent abstraction levels
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766913224" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

the happy path could perhaps be made more prominent by adding a guard clause to handle invalid inputs?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766917958" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

perhaps the magic literal can be avoided here by using a named constant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#pullrequestreview-3754157835" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 136. GABR..BHAN `@GShubhan` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2766669875" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Well done on prefixing "is" before all boolean variables.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2766710901" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I like that you have used the correct coding standard to import the java library!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2766712653" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Well done on using Task [] tasklist instead of Task tasklist []
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#discussion_r2766968540" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Please make variable names more descriptive and in camel case.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/131#pullrequestreview-3754092665" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2766702156" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Is it better to keep the access modifiers as "protected" for these variables?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2766996533" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Can using this type of broad exception hide some other bugs later?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2767004570" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Please close the scanner.
[Scanner.close() is missing.]
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#discussion_r2767025956" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good use of inheritance and polymorphism!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/152#pullrequestreview-3754127379" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 137. TRAN..KHOA `@Michael-coding06` (18 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762005016" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like it when you use switch here instead of if/else to avoid the deep nesting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762029082" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I think you should have declared 40 outside. 
Maybe: LINE_LENGTH = 40;
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762040160" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I think should have protected/private here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#discussion_r2762045763" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Array specifiers must be attached to the type not the variable.
For example: int[] a = new int[20];
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#pullrequestreview-3748753908" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#pullrequestreview-3748776980" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#pullrequestreview-3748791042" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#pullrequestreview-3748797807" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/16#pullrequestreview-3748807436" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

This is my review, Tran Viet Khoa A0310600E
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#discussion_r2762031975" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

I like the way to avoid magic number
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#discussion_r2762048761" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Array specifiers must be attached to the type not the variable.
For example: int[] a = new int[20];
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#discussion_r2762058121" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Good job on following the naming standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#discussion_r2762059435" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

I think you can break lines here to give it better structure
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#pullrequestreview-3748780144" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#pullrequestreview-3748801351" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#pullrequestreview-3748811392" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#pullrequestreview-3748812504" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/57#pullrequestreview-3748815372" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

**Review Status:** COMMENTED

This is my review, Tran Viet Khoa: A0310600E
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 138. GUPT..AMIT `@ShamitGupta` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2766795146" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Use standard camel case for naming. Eg: toDo should be the method name
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2766798384" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good job in ensuring that fixed values have variable names in CAPS
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2766800595" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

can consider replacing multiple if statements with else-if statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#discussion_r2766801567" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of Inheritance to ensure code reusability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/41#pullrequestreview-3754217769" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2766814004" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good use of using camel casing naming style and ensuring that methods are a verb 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2766817166" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good job in ensuring that fixed valued variables are in upper case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2766821029" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good use of inheritance to increase code reusability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#discussion_r2766827391" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Excellent use of spacing for while loops, commands within while loops, if statements and commands within if statements. Spacing is also consistent, and follows the 4 spacing rule
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/139#pullrequestreview-3754236084" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 139. KOTH..ONAK `@SmeetRonak` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762287655" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps a better way would be use the pre-defined repeat() method to print lines:
System.out.println("-".repeat(50));

Bear in mind that the repeat() method takes works on strings only
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762290077" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Clean indentation and if-else blocks!
Very easy to read and follow!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762293560" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Redundant use of "this" keyword.
Can be written simply as:
isDone = false;
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#discussion_r2762300083" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

When creating an fixed-size array, it could be better to define Final Static variable that defines the max capacity of tasks that you can hold instead of hard-coding it while initializing the array 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/101#pullrequestreview-3749097192" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

I like that you have followed the coding standards thoroughly!
Very clean code and easy to read!

Few minor changes can be implemented
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#discussion_r2762315064" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like how you created a static final variable to hold the number of max_tasks you can handle
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#discussion_r2762319359" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like the abstraction of basic UI messages into separate functions for good readabilty!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#discussion_r2762323892" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how you account for different variations of the same word that the user might input, and parse the input accordingly!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#discussion_r2762326357" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like the override annotation to indicate that this method overrides it's parent class method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#pullrequestreview-3749127826" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

I like how you've modularized the code, and abstracted simple tasks into separate functions!

Good coding style overall!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 140. GUO ..HENG `@gzc-ceg` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762279936" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

It may be prone to errors. Ex. the user types extra spaces.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762288630" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

suggestion: use switch instead of if-else
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762296510" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

can return -1
suggestion: add a range check
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#discussion_r2762306691" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good exception handling!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/6#pullrequestreview-3749087846" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

decent code readibility!
some minor errors may need to be handled
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#discussion_r2762069060" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

good job for using all uppercase letters for the constant!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#discussion_r2762080225" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

"taskIdx" is acceptable, but "taskIndex" or simply "index" may be slight more readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#discussion_r2762091918" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

'''suggestion
String input = in.nextLine().trim();
'''

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#discussion_r2762094321" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

can insert a line here: System.out.println("please enter a command.")
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#pullrequestreview-3748822805" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall looks good!
The coding standards are all well met.
Some comments can be added to improve the code readiblity.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 141. CUI ..AHAO `@Overture-2021` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762290178" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

You can consider refactoring these to constants to avoid magic literals.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762291995" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

You can consider more aggressive abstraction as it's recommended to not go over 30 lines or so in a method.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762297070" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I see these lines appearing repetitively across the codebase, you can consider extracting them to a printMsg() method for better organization.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762304047" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

You can consider packing these into methods belonging to the event class. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#pullrequestreview-3749100396" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job implementing complex operations
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2762269246" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

You can consider renaming this to isValidChoice: "_As much as possible, use a prefix such as is, has, was, etc. for boolean variable/method names so that linters can automatically verify that this style rule is being followed._"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2762272480" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

You can consider refactoring these fixed messages as constants instead of variables.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2762279188" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice use of verbs in method names representing actions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#discussion_r2762284137" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

You can consider adding a 'default' case for the switch statement
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#pullrequestreview-3749074555" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/165#pullrequestreview-3749078238" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good Job
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 142. MAO ..OHAN `@nicoleroot` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#discussion_r2772625312" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Would it be better if the updateMarkStatus function also includes the line outputs?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#discussion_r2772629727" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Would it be better if there's a function handling line outputs after adding a task?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#discussion_r2772647587" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Like the way you used switch case and the overall structure
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#discussion_r2772650573" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Maybe can define a variable for this?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#pullrequestreview-3761194335" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772577801" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Like your separation of getIcon and getDetail
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772584895" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Like the use of Todo here instead of abstract Task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772592540" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Would it be better if task and others are put in different java files?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#discussion_r2772594781" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Would it be better if todo/event/deadline are handled in seperated functions?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/138#pullrequestreview-3761142601" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Adheres well to coding standards! Good job
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 143. YANG..YAQI `@Yaqi66` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2774570882" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

NumberFormatException is caught but not handled. Consider printing a helpful error message and exiting the current command, so the user knows what went wrong.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2774574975" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

consider adding a consistent usage format message for each command when user input is invalid
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2774590232" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

may behave unexpectedly with duplicate tasks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#discussion_r2774617723" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

You may consider extracting error message into a small helper method (e.g., printErrorMessage(String action))
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/143#pullrequestreview-3763578839" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2766800415" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Maybe setIsDone() and setIsUndone can be combined into one function?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2766811753" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Should this use camelCase?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2766821410" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how you draw the dashed line elegantly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#discussion_r2766829395" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

I like how clean this bit of code is 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/178#pullrequestreview-3754222948" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 144. ONG ..QIAN `@yqzzy` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766806546" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

method name follows camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766808045" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good use of public static final for constant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2766814178" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

should be addToDoList?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#discussion_r2769212038" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good formate for if-else statement
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/142#pullrequestreview-3754228613" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2766826001" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

printing statement in separate lines makes it readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2766828101" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

can consider adding space after .
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2766831470" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Consider extracting this repeated logic into a helper method like markTask() to reduce duplication and improve readability, also to ensure encapsualtion of protected attribute isDone
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#discussion_r2766833740" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

duplicated line with line above
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/158#pullrequestreview-3754247125" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 145. KEAG..JANA `@keagedw` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772607154" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like the clean headers and proper formatting! Very readable!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772609310" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Nice use of try-catch!!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772615671" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Love the personality!!!!!!!!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#discussion_r2772617704" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Nice usage of if-else if-else to avoid deep nesting!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/59#pullrequestreview-3761174880" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall really good code quality and nice touch or personality!!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772584223" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

cleaner to have the else on the same line as the if end brace
'''suggestion
                ``}`` else ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772590341" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

maybe better to add a space before curly brace?
'''suggestion
    public Task (String description) ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772591847" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

better to add a space before curly brace?
'''suggestion
    public Todo(String description) ``{``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#discussion_r2772600041" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

variable is not used, for future methods?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/91#pullrequestreview-3761150251" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall I like the clean implementation of the code! Logic seems well thought out, just minor coding standard issues here and there. Good Job!!!!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 146. LEE .. NGA `@eugenia-cnl-lee` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2767414016" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Agreed. If this was CS2030 this would have failed. It is good coding practice to remain consistent.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2767423565" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I agree as well.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2767428309" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Nice use of 'protected'
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#discussion_r2767430433" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Neat use of .format() - Makes this line a lot cleaner.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/60#pullrequestreview-3754859508" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

This is a good piece of code. I was struggling to find things to write review comments on because it is so well written.

I wish there was more documentation/comments though.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#discussion_r2767362065" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Well done for spotting the repetition.
This is a smart use of helper function, well done.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#discussion_r2767364879" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

The indentation is incorrect here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#discussion_r2767376307" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

You pay a lot of detail to your code. A lot of effort put into edge cases.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#discussion_r2767380321" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Again, great level of detail for incooporating a wide range of edge cases. Nice defensive programming
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#pullrequestreview-3754820371" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall well done. Especially on your level of detail for edge cases and defensive programming techniques. I know certainly I sometimes am too impatient to code to accomodate for such a wide range of potential edge cases. Kudos!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 147. KIM ..NSUN `@violetsunshades` (12 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/25#discussion_r2777909798" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

maybe you can make multiple functions within this class to simplify the code, since using if/else-if statements put the conditions and actions in the same place, making it hard to read, while using functions can separate the two.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/25#pullrequestreview-3767668137" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I found your code easy to read for the most part except a few places!

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/170#discussion_r2777923919" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Maybe using a switch-case might help in terms of clarity and readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/170#discussion_r2777924811" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

using try-catch seems like a very smart choice here, as it enhances the readability of your overall code!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/170#discussion_r2777925557" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

 using (A : B ? C) format coding is a smart move that improves the clarity of your code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/170#pullrequestreview-3767726605" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I found your code clear and readable, good programming!

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/182#discussion_r2777904322" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

using () marks for each condition in this code line would make it easier for a reader to make a clear interpretation of the multiple conditions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/182#discussion_r2777913825" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

using switch-case seems like a very good choice here, considering there are a variety of conditions and cases.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/182#discussion_r2777916646" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

making different functions for actions such as greetings(), manageList(), and so on to separate the actions really help in the clarity of reading this code, good choice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/182#discussion_r2777918781" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

overall great code, but is adding \n necessary here?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/182#pullrequestreview-3767621899" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED

some pr reviews!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/182#pullrequestreview-3767702655" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, I found your code easy to read for the most part except a few places! Very well organized and almost no violations in the code quality rules we learned in class.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 148. NI T..ANYI `@fromtyn` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762021941" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

It's good to put codes related to handling command into one method to improve readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762025804" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

It's good to create multiple subclasses for different tasks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762028187" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Maybe these lines can be put into one helper method to avoid repeatition.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#discussion_r2762030521" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Maybe it's unnecessary to create such a helper method since the original code only costs one line?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/90#pullrequestreview-3748770072" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/127#discussion_r2761999696" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

It's good that the codes are divided into multiple method "showExit", "showGreeting"......
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/127#discussion_r2762003743" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

It's good to set up a constant rather than magic number.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/127#discussion_r2762010073" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Perhaps we can use "tasks" rather than "items" to make it more descriptive.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/127#discussion_r2762012979" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

It's good to use "isDone" as the name of a boolean.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/127#pullrequestreview-3748748859" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 149. YAO ..MING `@RayminQAQ` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772585586" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I think this line of code shouldn’t be written as a single line under the course guidelines; it’s supposed to be properly indented. However, I don’t think this is a major issue overall. The rest of your code looks good, and your write-up is solid.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772591647" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

It’s a good design choice to use variables to distinguish between different strings.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772601552" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Not sure why lengthOfStringEvent has a number added. Hope you can add a brief comment to clarify.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#discussion_r2772604715" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good use of commands for better code quality.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/58#pullrequestreview-3761151709" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2772649679" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Should the variable names must be in camelCase?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2772653565" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Should “Task``{``” be indented as “Task ``{``” (with a space before the brace)?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2772654194" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Should “Task``{``” be indented as “Task ``{``” (with a space before the brace)?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#discussion_r2772656974" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Would it be better to use constant enum to capsulate all strings?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/115#pullrequestreview-3761224873" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 150. XIAO..JING `@Aurosky` (11 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766707160" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Nice comment, explain what dose the function do.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766709201" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

No nesting loop, happy path prominent, nice work
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766715371" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

May consider put System.out.println(LINE) in main function since each sub function has this, to avoid duplicate.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#discussion_r2766777994" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Split a long block of code into two parts to enhance code readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/27#pullrequestreview-3754132350" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/148#discussion_r2764770564" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Numerous small functions have been implemented to keep the main code concise. It might be worth considering placing repetitive code (such as `System.out.println(SEPARATOR);`) within the main method for greater clarity.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/148#discussion_r2766673286" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

No deep nesting, structure code logically, KISSing; named well, no misleading name, nice work
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/148#discussion_r2766685292" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good SLAP, use function wisely, code is easy to read and understand. Use the proper name for function; comment minimally but sufficiently -- ie. explain what is the getStatusIcon function doing.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/148#discussion_r2766687906" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Clear code, no misleading name, proper use of protected and public.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/148#pullrequestreview-3751897011" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/148#pullrequestreview-3754096930" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 151. HUAN..GRUI `@cigaho` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766821188" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Clear instructions on String dealings
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766823311" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Nice ways of greeting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766824909" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good way of handling tasks object
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766827238" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Easy constructor build for todo
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#pullrequestreview-3754242594" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766802783" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Clear construct function making use of the super constructor
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766805499" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Maybe we can add something to prevent the case that user do not include two '/' which may result in index error
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766808036" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

good standard adding comments
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#discussion_r2766811799" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

good use of switch
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/137#pullrequestreview-3754225227" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 152. WANG..LING `@Michael-wzl` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766830913" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

No JavaDoc for the class. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766834168" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Over-complicated statement. Better to switch to simpler logic. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766836400" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Unclear naming. Better: deadline
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#discussion_r2766857610" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Magic strings. Should use a constant.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/82#pullrequestreview-3754252469" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2766809466" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Complete and informative JavaDocs. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2766815436" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

`list`, `mark`, etc are magic strings. It is better practice to use constants. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2766818750" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good naming of boolean variables. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#discussion_r2766820445" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

All methods are kept short and concise. Met the coding standards well. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/83#pullrequestreview-3754231551" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

PR review on tut. 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 153. PAN ..NGYU `@seeml-mo` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766935136" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

'''suggestion
Maybe you can set them into a constant named GREETING: 
        System.out.println(logo);
        System.out.println(" We record everything you say for quality assurance purposes. Type 'list' to see the stored Herogasm Files, or 'bye' to GTFO.");
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766942599" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

'''suggestion
   Here can be generated into a method to fit in the "abstraction" concept of OOP
            switch (command) 
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766943755" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

'''suggestion
This kind of formatted output can be set in a function/method, because they are repeatedly showing up
                        System.out.println("   [X] " + tasks[index].getDescription());
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#discussion_r2766944680" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

'''suggestion
Good way to avoid segment fault
                        System.out.println(" added: " + command);
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/151#pullrequestreview-3754352752" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766955314" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

'''suggestion
proper spacing should be applied: for(int i = 0; i &lt; counter; i++)
        for(int i = 0; i&lt;counter;i++)
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766959537" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

'''suggestion
It would be better if written as: i += 3;
                    i = i+3;
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766967175" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

'''suggestion
It seems that the "[ ]" bracket to mark isDone is omitted.
        return "[D]" + super.toString() + " (by: " + by + ")";
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#discussion_r2766971980" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

'''suggestion
The format needs to be rewritten after the types are added(as [D][X] is the new standard).
        return "[" + this.getStatusIcon() + "] " + this.description;
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/167#pullrequestreview-3754371894" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 154. YIK ..YUAN `@YWY2002` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2766942480" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

All methods are name in cameCase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2766943455" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Constant variable is in all CAPS.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2766945539" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Variables in for loop is spaced out.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#discussion_r2766946874" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Could use switch case for multiple conditions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/23#pullrequestreview-3754359328" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#discussion_r2766914034" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

All methods names are in camelCase. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#discussion_r2766923702" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Good use of protected keyword for future inheritance classes from this class.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#discussion_r2766925089" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Boolean variable names sound like boolean just be reading it.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#discussion_r2766933039" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Variables names are all in camelCase.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#pullrequestreview-3754333291" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 155. WAN ..YANG `@Bunnyhunch2024` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761913254" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Task management logic is separated into a dedicated class，nice
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761921077" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

markAsNotDone "A" not "a"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761923742" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good method extraction,clean and readable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#discussion_r2761925774" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

avoided magic string, nice
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/50#pullrequestreview-3748659138" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761884254" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

typing an invalid command, the program may add it as a task instead of showing an error.

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761887728" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

if typing "mark abc" or something ,it may crash
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761897058" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

camelCase format used correctly on names,easy to understand
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#discussion_r2761900604" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

resizable array,flexible and scalable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/116#pullrequestreview-3748629085" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 156. SUK-..KORN `@KanakornMek` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762004029" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

In my opinion, I think it's better to assign ____________ as a constant variable, because there are a repetitive uses of System.out.println("______")
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762008060" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

The catch block should not be empty. You should add some error handling code inside of it, such as printing out the error
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762010417" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

This is a good use of getter method for the class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#discussion_r2762013051" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

The nice use of printInformation for printing Task details
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/9#pullrequestreview-3748752947" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2762025385" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Nice job for assigning line as a constant as it is used many time throughout the code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2762028802" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I think making these messages variables is a good coding practices, as they can be easily editted later. However, in my opinion, making a separate class for it might be better.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2762030105" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

This is the same as the last comment on lines R16 to R23. Making a separate class for error might be better.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#discussion_r2762032370" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

NIce use of catch statement for error handling.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/71#pullrequestreview-3748773154" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, the code is very well implemented. I suggested you some alternatives for some parts of the code
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 157. REHA..MOOD `@RehaanMahmood` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/19#discussion_r2762293749" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps using this() would make the constructor code more concise?

'''suggestion
    public Command(CommandType type, String arg1, String arg2, String arg3) ``{``
        this.type = type;
        this.arg1 = arg1;
        this.arg2 = arg2;
        this.arg3 = arg3;
    ``}``
    
    public Command(CommandType type, String arg1, String arg2) ``{``
        this(type, arg1, arg2, "");
    ``}``
    
    // etc.
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/19#discussion_r2762300383" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Should variable printer be made all-uppercase?

'''suggestion
    private static final Printer PRINTER = new Printer();
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/19#discussion_r2762303201" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Should the return statement be placed on the next line?

'''suggestion
        if (s == null || s.isEmpty()) ``{``
            return false;
        ``}``
'''
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/19#discussion_r2762311181" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

If break statements are intentionally not included in case statements, perhaps "Fallthrough" comments should be included?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/19#pullrequestreview-3749105155" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, your code is quite neat and readable. Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762332042" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Perhaps it is better to avoid nested if-statements in general to improve readability, although in this instance it is not much of an issue.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762336662" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I agree, perhaps it is better to program defensively even if the project is small.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#discussion_r2762339278" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

I like how you have done this in a concise way using the ternary operator.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/162#pullrequestreview-3749148123" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, your code's quality is good and it has been written well.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 158. YEO ..HING `@Chingy0404` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2766696008" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

follow PascalCase that's good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2766698365" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

mark() is too short and undescriptive
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2766703722" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

your constructor body is not consistent in spacing (sometimes 3 spaces sometimes 4 spaces)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#discussion_r2766704483" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

same issue as mark(), unmark() is not descriptive enough
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/123#pullrequestreview-3754121176" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766685667" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

array names could be more descriptive e.g taskList
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766689764" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

nice using camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#discussion_r2766690370" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

same for other arrays, should be more descriptive and provide more useful information
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/132#pullrequestreview-3754111578" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 159. DANI.. JIE `@Daniel-czj` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#discussion_r2771880604" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

magic number
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#discussion_r2771892662" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good use of functions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#discussion_r2771893493" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

good use of switch case

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/46#pullrequestreview-3760311477" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job overall, nice use of functions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771916465" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consider adding Class to group these 2 together
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771920347" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Final should only be for constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771921238" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Array should be camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#discussion_r2771922912" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

nice error hanlding
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/69#pullrequestreview-3760360334" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job overall
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 160. DYLA.. LIM `@dylanlimyf` (10 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2772570896" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

should have 4 spaces indentation 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2772578402" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

amazing job on commenting what each chunk of code does and clearly putting blank lines after each specific chunk :D
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2772584845" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

space after the close bracket
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2772594477" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

great job on following convention for the if-else statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2772598663" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

amazing use of camelCase!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2772600963" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

oops my bad it was a ui issue, seemed to me there a line break without 4 space indentation

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#discussion_r2772603094" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

love the comments on what the line of code does when it seems ambiguous

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#pullrequestreview-3761134076" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#pullrequestreview-3761167921" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/128#pullrequestreview-3761170428" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 161. KART..IVEL `@vet3whale` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2761902963" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

maybe can use unmarkDone
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2761903119" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

printing welcome could be done using a printWelcome() for better readability in main
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2761910320" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

maybe can use enums for the method. so enum Commands ``{`` LIST, MARK, UNMARK ``}`` etc
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#discussion_r2761914432" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good use of a line variable as it is repeated often. :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/54#pullrequestreview-3748649192" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

nice
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761876876" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

maybe can use methods to make your main() method to be cleaner? can use printWelcome(), or missingTaskNumber() etc.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761885174" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

maybe can instead say userInput.equals(bye), where bye is a String variable holding "bye"?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#discussion_r2761889378" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

good use of try-catch
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/154#pullrequestreview-3748622208" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

nice
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 162. NEER..SSAN `@neerajehh` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/42#discussion_r2762011127" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Consider extracting 100 to a constant at the top:
private static final int MAX_TASKS = 100;
(Coding standard: constants in SCREAMING_SNAKE_CASE)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/42#discussion_r2762011967" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Love the descriptive variable name `name`! 👍 Much clearer 
than using single letters.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/42#discussion_r2762013034" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Great work overall! ✅ Consistent 4-space indentation, K&R 
brackets, and clear method names. Very clean code! 👍
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/42#pullrequestreview-3748759837" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762038397" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

The method name getIsCompleted() violates the standard Java naming convention for boolean getters. According to the "Use Nouns for Things and Verbs for Actions" guideline, boolean getters should use the is...() pattern, not getIs...().
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762041881" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

The variable name len is unnecessarily abbreviated. According to the "Not Too Long, Not Too Short" guideline, we should avoid abbreviations that don't significantly save typing but reduce clarity.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762046571" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

This line performs two operations simultaneously: array assignment and increment. According to the "Do Not 'Trip Up' Reader" guideline, we should avoid putting multiple statements or operations in the same line as it can confuse readers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#discussion_r2762048546" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

While the constant is properly named (good!), the value 100 appears without any comment explaining why this specific capacity was chosen. According to the "Avoid Magic Numbers" guideline, significant numbers should have context
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/134#pullrequestreview-3748789035" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 163. ROSH..UMAR `@Roshan-Alagar` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2762287507" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Switch case coding standard is followed correctly 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2762302021" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

There is a use K&R style brackets which is good 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2762312302" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Basic indentation of 4 spaces is followed which is good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#discussion_r2762320114" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Constants are written in screaming_snake_case which is good 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/47#pullrequestreview-3749097038" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Comments for Week 4 Tutorial
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762327332" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Added comments which is excellent
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762331568" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Code is simple and easily readable. Good Job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762333044" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

This line is a bit too long, try to see if there is a way to simplify/make it shorter 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#pullrequestreview-3749143487" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 164. JUST..NJIE `@justinpoonjj` (16 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#discussion_r2771867299" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Good use of storing the attributes and keeping track of it when running the main program

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#discussion_r2771869256" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

abit of a nesting maybe wanna abstract the code out for better readability
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#discussion_r2771873102" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good use of methods

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#pullrequestreview-3760292153" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#pullrequestreview-3760295599" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#pullrequestreview-3760300362" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/13#pullrequestreview-3760301068" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Nice coding 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2771877384" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Good use of the switch-case branching
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2771880067" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Good use of inheritance

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2771882798" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

Overall no arrowhead pretty nice!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#discussion_r2771883541" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Nice use of polymorphism
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#pullrequestreview-3760306724" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#pullrequestreview-3760310628" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#pullrequestreview-3760315093" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#pullrequestreview-3760316022" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/26#pullrequestreview-3760317001" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall very good code
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 165. WONG..HAWN `@wongeeshawn` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2771873415" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

large if else chain inside here
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2771876603" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

For booleans, isDone() reads cleaner and follows common Java naming style.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#discussion_r2771887463" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

something like taskCount or nextTaskIndex reads better.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/119#pullrequestreview-3760300949" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771851523" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Nice use of SCREAMING_SNAKE_CASE for constants instead of hardcoded numbers.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771855054" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

From a coding standard/readability perspective, these could be named constants instead of raw strings.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771857370" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

could be wrapped to follow the 110–120 char limit
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#discussion_r2771859982" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

avoids the common single-line loop issue.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/121#pullrequestreview-3760270906" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 166. MANU..AGUR `@manudagur87` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761887037" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like the use of refactoring to method for a simple task like printing. It makes the code much more readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761891706" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Incorrect indentation of case statements.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#discussion_r2761897619" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Consider adding all your classes in a package. 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/100#pullrequestreview-3748631867" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761913869" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consider adding some comments to enhance readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761916986" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Avoid long methods to make the code more readable.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761919582" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Consider using constants rather than magic numbers
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2761924739" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Perhaps you can consider using case statements instead of else if statements
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3748659874" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 167. TAN ..IVAN `@ivan-tan` (8 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/97#discussion_r2762007443" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps you can create another static final variable called INDENTATION for the indentation behind "added: .... " 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/97#discussion_r2762008617" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Good job on extracting out showGreeting
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/97#discussion_r2762017448" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Perhaps you can consider changing markAsDone to isDone to reflect the boolean variable
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/97#pullrequestreview-3748756301" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job on implementing your first chatbot. Perhaps you can try adding other classes in future so that you can abstract out your tasks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762031556" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

perhaps you can consider extracting the handling of user input into another method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762038512" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Perhaps you can extract the welcome message to another method to make things tidier
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762048871" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Perhaps you can change LINE_BREAK to a static final variable 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#pullrequestreview-3748779627" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job on starting you chatbot. I like how you added the class Task.java to abstract out the different tasks. 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 168. AYDE..TTEN `@podledges` (8 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/109#discussion_r2761882143" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

You should try using enums for commands, so it looks alot cleaner imo
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/109#discussion_r2761883736" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good naming convention
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/109#discussion_r2761885510" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

break up the else blocks more cleanly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/109#pullrequestreview-3748627086" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2761896858" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like this syntax/function, I had done it a more complicated way
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2761898474" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Clean breaking up off string to not make lines too long
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2761908106" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

i guess you can delete this comment, especially since you have a different implementation of it below
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#pullrequestreview-3748642408" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 169. TRAN.. LAM `@BaoLam194` (8 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761885332" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

According to coding standard, your class needs to belong to some package.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761889776" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

The variable name should be more meaningful, like taskCount rather than some vague one like counter
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761891103" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Some problem as aboved, the variable name is so vague.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761901043" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

You are creating a new class inside another class, which violates the coding quality for readability and file layout.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761906040" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

This code has a lot of deep nesting, you could try to seperate them into smaller functions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#discussion_r2761915229" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

You should seperate the logic between printing(action) and declaring the variables here to increase it readability instead of mixing the logic together. One suggesstion is to declaring variables first then perform any logical statement/action later.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#pullrequestreview-3748630104" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Looks good.
There are some minor coding standard violation and my suggestion.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/157#pullrequestreview-3748647158" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

Needs improvement. I have some suggestion to improve the code quality as reference.
Generally, You may need more comment to describe your code and structure it more logically.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 170. SEAN.. SHU `@heehaw1234` (8 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761746165" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

no need for extra space after "(", change to public Command(String description)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761753035" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

leave a space after "()", change to public String toString() ``{``
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761754817" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

please leave a space after "=" sign
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#discussion_r2761762874" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

comments for class members should be in the form /** this is a comment */
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/17#pullrequestreview-3748472633" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/164#discussion_r2761797238" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

define 100 at the top of code, currently is just a magic number
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/164#discussion_r2761801354" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

please indicate override at the beginning of this method, might lead to potential bugs
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/164#pullrequestreview-3748536805" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

good job overall, needs more commenting. 
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 171. LEON..YANG `@codefuul` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#discussion_r2762047854" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Nice, u used upper snake case for the constants 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#discussion_r2762051589" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I think that it should be task and not tasks 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#discussion_r2762093742" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

The class names should be in PascalCase 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#pullrequestreview-3748800266" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall looks good 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#pullrequestreview-3748851745" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#discussion_r2762022976" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

I like how you made this private so that it wont be messed up with other parts of your program
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#discussion_r2762026536" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

I like how u made sure the bot work even if the user types "BYE"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#discussion_r2762027552" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Nice, u applied upper snake case for the constants 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/168#pullrequestreview-3748771021" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Looks good overall
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 172. AW S.. JIE `@shuojiee` (8 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#discussion_r2761888858" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Would the method name mislead readers/users into thinking that a boolean value would be returned? Perhaps a more intuitive name here which tells the user that a String will be returned?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#discussion_r2761899061" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Formatting is clear and concise! Good job!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/30#pullrequestreview-3748633673" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job! I couldn't find any major coding violations.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761912031" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I'm wondering if String.format() would be clearer than string concatenation.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761915809" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Not checking if 'to' and 'from' are null may cause the program to not work as intended.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761919366" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Good job catching invalid inputs!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#discussion_r2761922334" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

This method seems really long, would it be possible to break it down into multiple smaller methods?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/56#pullrequestreview-3748657861" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good job overall! Was very reader-friendly apart from that one long method.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 173. CHU ..HUOC `@fuocchu` (8 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2766668416" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I think `String description` -&gt; `String descriptions` because this is pural form so it should be used on names representing a collection of objects.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2766669750" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I think `String description` -&gt; `String descriptions` because this is pural form so it should be used on names representing a collection of objects.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2766682939" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

consider leave a space for each else if conditions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#discussion_r2766684529" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

consider myObj in camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/122#pullrequestreview-3754090693" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

LGTM
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#discussion_r2766699650" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Consider `String descriptions` instead of `String description`. It''s pural form 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#discussion_r2766711089" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

consider `try` or `switch `. I think it more easier to understand code logic
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/173#pullrequestreview-3754124815" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall LGTM
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 174. MICH..UVEL `@michaelshyam1` (6 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/107#discussion_r2767429587" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

The long if–else if–else chain makes it slightly harder to follow the command logic. I'd suggest extracting each command into a method to improve readability and reduce nesting.


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/107#discussion_r2767433619" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I like that uses camelCase, as recommended by the coding standard for variable names.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/107#discussion_r2767436738" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I like how the code is consistently formatted and indented, improves readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/107#discussion_r2767441650" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I like the use of comments to explain your code
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/107#discussion_r2767460291" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

It’s good that you separated each feature into its own file, as this improves code organisation and makes the codebase easier to read and maintain.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/107#pullrequestreview-3754892547" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 175. LABE.. LEE `@lab3ll3` (7 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2762293250" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

can shorten to MAX_TASKS
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2762299013" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Can change numberOfTasks to taskCount
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2762302405" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Can add edge case for when invalid input is given for getEventInstance, getDeadlineInstance
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#discussion_r2762307166" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

good that you separated the class!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/68#pullrequestreview-3749104542" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#discussion_r2762326927" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Can create a separate class for the underscores 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/114#pullrequestreview-3749143079" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 176. YEE .. JIE `@yeejj` (7 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#discussion_r2766677750" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

actual text and expected text not added, runtest.bat wont be useful
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#discussion_r2766683590" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

i like how there is a tutorial in the greeting and that you have comsidered all edge cases for the marks and unmarks
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/106#pullrequestreview-3754102716" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

**Review Status:** COMMENTED

i think its great, keep it up! and stay on task to this week's ip
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#discussion_r2766692650" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

i like how you made response strings in this first block, it makes it easier to make changes to each response and makes the code cleaner
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#discussion_r2766705031" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

what is random for, and the message is not really random
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#discussion_r2766706924" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

whats this for?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/176#pullrequestreview-3754117848" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

i think its great, keep it up! and stay on task to this week's up
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 177. HOWI..O YU `@HowieYHY` (7 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#discussion_r2762017169" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

String line can be declared at the start of main for ease of coding
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#discussion_r2762017752" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Also, it should be named stringLine
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#discussion_r2762022951" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

you can use a helper function for the indentation instead of manually inputting the spaces
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/32#pullrequestreview-3748765628" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762004885" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Name should be stringSeparator
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#discussion_r2762008050" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

No java coding standard violations that I can tell. Well done!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/85#pullrequestreview-3748751394" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 178. ZHAN..YIZE `@ZhangYize2003` (7 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#discussion_r2762025203" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like that your comment follows the standard Javadoc conventions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#discussion_r2762034695" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

For this If-else block, the coding standard is not uniformed. Some of the else-if statement blocks have a empty line preceding the next block while some do not have. Consider removing the empty line for all blocks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/93#pullrequestreview-3748772985" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, good job on maintaining the code standard
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2762059840" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Within the while loop, you can also consider using a switch-case statement improve the readability of your code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2762065346" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

I like that you followed the standard convention and put the features in separate classes.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#discussion_r2762077044" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Consider putting this line of code in a function call instead as it is a simple greeting that does not have other useful functionalities .
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/105#pullrequestreview-3748812898" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

LGTM!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 179. SHYA..AMAN `@ShyamalV18` (6 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#discussion_r2767383570" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Indeed, this would make it more clear that it is a boolean attribute
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#discussion_r2767391827" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Comment style: The header comment is helpful, but since it describes the class purpose, consider converting it to a short Javadoc on the class (e.g., /** ... */) instead of multiple // lines..
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#discussion_r2767395889" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Method naming: isList, isMark, isUnmark is clear and follows lowerCamelCase

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#discussion_r2767403499" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

String command variable appears declared but not used (at least in the diff shown). Coding standards usually prefer removing unused variables to avoid warnings / clutter.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#discussion_r2767408961" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Naming conventions: STANDARD_BAR(), ADD_RESPONSE(...), PRINT_TASK(...) are methods, but they’re named like constants (UPPER_SNAKE_CASE). Most Java standards expect LowerCamelCase for method naming dear sir.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#pullrequestreview-3754842628" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good attempt! Just a few coding standard related issues to fix
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 180. SAMU.. JIN `@dorndorn54` (7 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761771256" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

good use of coding standards to clearly define constants used in java.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761780702" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

this is abit confusing, should not use nested functions.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#discussion_r2761788582" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

print function too long, please shorten it
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/80#pullrequestreview-3748500814" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#discussion_r2761738822" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

follows convention for constants being used in java, goodjob
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#discussion_r2761742556" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

maybe the strings can be declared as variables that are then chosen, not hard coded?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/156#pullrequestreview-3748464991" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 181. TOH .. WEI `@yiweitoh44` (7 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#discussion_r2761997326" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like that you used enum for different namings
Use pascalcase for enum
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#discussion_r2762010266" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

boolean must make it sound like boolean
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#discussion_r2762011480" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

singular for Task
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#discussion_r2762014534" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Looks good
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/43#pullrequestreview-3748745928" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#discussion_r2762039514" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Code is a little long for the whole while loop
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/135#pullrequestreview-3748790268" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 182. WEN ..N YU `@WenJunYu5984` (6 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767358183" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I think method should follow camelCase
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767362273" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Should use Magic numbers instead for the number 100
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767376920" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Should also be of private and not public as leaving it public would allow other classes to modify internal data directly
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767386998" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Can consider overriding toString() method instead of manually managing each type
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#discussion_r2767398761" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Nice! I like that you added colours to your text
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/7#pullrequestreview-3754816185" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 183. MATH.. ION `@SIONMATHEW` (7 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#discussion_r2761890652" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

I like that the Import Classes are explicitly stated
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#discussion_r2761899744" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Maybe keep the print statements on a single line
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#discussion_r2761915480" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Good that all classes follow Pascal Case
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/76#pullrequestreview-3748635731" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall, Good standards follow except few cosmetic changes
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/109#discussion_r2761903787" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Maybe each class should be in a separate file
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/109#discussion_r2761919439" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Could maybe also make a max limit private static variable but good that comment specifies
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/109#pullrequestreview-3748649982" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good Quality except minor changes
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 184. MO H..ANQI `@the-RoaringCat` (9 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2761877791" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Can extract out a method here-printList
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2761884399" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Can extract into a class eg TaskList that has a list of class, and methods to access the List for different purpose
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2761902200" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Extract a class for UI to print 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#discussion_r2761902618" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Magic number
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#pullrequestreview-3748622995" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#pullrequestreview-3748629217" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#pullrequestreview-3748648445" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#pullrequestreview-3748648816" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/79#pullrequestreview-3748650348" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

**Review Status:** COMMENTED

Naming is good, you can consider extract out classes and methods to create layers of abstraction.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 185. CHEN..TONG `@uphyrdia` (5 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761878032" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Can extract UI out into a class
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761880911" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Consider using ArrayList for dynamic array
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761886401" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Can consider using continue instead of nested else if
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#discussion_r2761890098" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

setDone(false) sounds contradictory to me. Maybe considering mark()/unmark()
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/153#pullrequestreview-3748623271" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Overall the code looks functional and easy to read. But can consider extracting an TaskArray class whose methods are those inside each if block, to make the code more OOP
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 186. GOH .. ANN `@shaun-gsa` (5 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762020079" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Remove line 12 so that override refers to the toString method
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762027000" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Can provide comment on how the input is processed for readability.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762042114" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

There is no need to put the conditional statement for "bye" in the if-else loop when it would break out of the while loop when user inputs "bye"
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#discussion_r2762047590" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Good else case to check for invalidity to check for different cases.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/40#pullrequestreview-3748768337" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great work! Can provide comments for better readability and use continue or break instead of else-if in main.
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 187. GOH .. LEE `@leegoang` (6 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766679069" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Perhaps a switch case be more efficient here?
It could be better for adding future commands, making it easier to see, rather than a else if tree.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766687044" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Great use of predefined command variables rather than the direct string. It really helps with making the code neat and easy changes to the command words in the future
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#discussion_r2766693255" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

First 2 commands do not have a space character within the command but subsequent ones do. 
It would be good to keep it consistent for future command references. In the future if you would like to print or use the command in a string, it would be easier to format the variable to what you want the output to be
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/63#pullrequestreview-3754104332" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED

Well done!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#discussion_r2766708919" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Perhaps you could consider a boolean variable naming such as isDone, isMarked, over marked. It could help guide your true or false assignment.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/147#pullrequestreview-3754134031" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good use of Messages class to format your print statements.
Generally straightforward understanding of variables with the naming convention.
Well done!
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 188. RISH..ENOY `@RishabhShenoy03` (5 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2761781478" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

nice use of constants
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2761793730" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

good indentation
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2761798489" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

interesting use of constants for the words typed in but does this make code more readable than just "mark"?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#discussion_r2761801368" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

nice formatting with divider
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/111#pullrequestreview-3748512162" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

fantastic job man
</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 189. PREM..SHAN `@Rosh2403` (6 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2762292177" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

According to the naming convention, this should be defined as a constant using SCREAMING_SNAKE_CASE. This is to reduce the repetitiveness of code.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2762293880" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

The variable is too generic according to the standard, variable names should be descriptive and written in camelCase. Consider renaming it to something more specific like taskCount or numberOfTasks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#discussion_r2762296883" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

While String[] list is correct, the variable name list is not very descriptive. According to the naming convention, names representing collections should clearly indicate what they contain. Consider renaming to tasks.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/15#pullrequestreview-3749103166" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/19#discussion_r2762320361" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Consider renaming to more descriptive names that explain what each argument represents
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/19#pullrequestreview-3749135521" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 190. DOBR..GDAN `@BogdanDobrynin` (5 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762286412" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Maybe use a separate method in a task class to decide what action to take based on the input
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762292982" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Recommended: define the a constant and assign the separator to it, to enhance code readability 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762299182" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Would be wise to implement a multi-argument handling (ex "unmark 1 2 3 etc...") to remove repetitions
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#discussion_r2762308427" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Add separator constant
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/104#pullrequestreview-3749095652" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 191. RAHM..AYAN `@RayanInCode` (6 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#discussion_r2761912409" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

What is the intended use of the bye command in if else and also separately as a case?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#discussion_r2761917817" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

(input.equals("bye")) is not properly closed, and there are case labels inside else if blocks. This code will not compile as written. Perhaps choosing just switch case statements would be better coding style than if statements for this purpose.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#pullrequestreview-3748658251" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/136#pullrequestreview-3748663529" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/164#discussion_r2761877572" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Might be better practice to use a switch case statement instead of if else here.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/164#pullrequestreview-3748622771" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info"  collapsed>
<div slot="header">

### 192. ZHAN..TONG `@Zhang-Zhitong` (0 comments)
</div>

n/a
</panel>

<panel type="info"  collapsed>
<div slot="header">

### 193. PRAN..AMAN `@pranavjana` (0 comments)
</div>

n/a
</panel>

<panel type="info"  collapsed>
<div slot="header">

### 194. KHOO..NHAO `@AK2003x` (8 comments)
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#pullrequestreview-3754892705" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

**Review Status:** COMMENTED

Do we want the comment // mark done task with X to be removed since the code is already self-explanatory, or replaced with a constant name that makes it obvious without needing a comment?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#pullrequestreview-3754903116" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great usage of camelCase throughout the code!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#pullrequestreview-3754906034" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

**Review Status:** COMMENTED

Great usage of inheritance between your parent and child classes!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/51#pullrequestreview-3754909040" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

**Review Status:** COMMENTED

I like how you included a text file of your input and expected output!
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#pullrequestreview-3754860468" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

**Review Status:** COMMENTED

Fantastic Work so far! Would you consider adding some javadoc comments?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#pullrequestreview-3754867930" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

**Review Status:** COMMENTED

Good use of inheritance! Maybe you can change the Integer to Int?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#pullrequestreview-3754873192" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

**Review Status:** COMMENTED

I like that taskList is encapsulated. Would it make sense to declare it as private final ArrayList&lt;Task> taskList; since you only initialise it once and never reassign it?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/ip/pull/187#pullrequestreview-3754876760" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

**Review Status:** COMMENTED

In if (userInput != "bye"), any reason you’re using != for string comparison? Would switching to !userInput.equalsIgnoreCase("bye")  avoid reference-comparison issues in Java?
</panel>

</panel>
