%%[This page was last updated on May 02 2025]%% [**<span class="text-warning">:octicon-eye:</span> indicates those _watching_ the forum** (kudos :+1:)]


<panel type="info"  collapsed>
<div slot="header">

### 1. KWA ..QUAN `@K-J-Q` (25 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/50" expanded>
<div slot="header">

**1. :fas-info-circle: Request for more exam papers**
</div>

I appreciate the mock exam paper provided. Can I check if there are more exam papers for additional practice?

I am unable to find any on NUS Library portal.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/46" expanded>
<div slot="header">

**2. :fas-info-circle: SD convention**
</div>

![Image](https://github.com/user-attachments/assets/0c906bd0-c41e-4d1c-b5ea-1fcf19b4750f)

In the lecture, an empty dotted line is added if the method has no return value.
May I check if:
1. the dotted arrow is needed for void methods
2. If (1) is yes, am I able to explicitly state `void` as shown in the picture. This void is partially due to Mermaid formatting.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/43" expanded>
<div slot="header">

**3. :fas-info-circle: Mermaid do not support moving the class name downwards (to indicate constructor lifeline)**
</div>

An example is the Score class. Am I able to use a note to indicate instead?

![Image](https://github.com/user-attachments/assets/f8e5d88b-0484-486a-9682-91b8ae3f55b2)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/41" expanded>
<div slot="header">

**4. :fas-info-circle: Mermaid diagram dosent allow the activation bar to be right below the class for constructor.**
</div>

![Image](https://github.com/user-attachments/assets/7b9c6c09-15fb-48c1-b3e4-0c0ec7fccbef)

Is it ok if I explicitly state when the constructor is activated?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/33" expanded>
<div slot="header">

**5. :fas-info-circle: Question on sequence diagram**
</div>

![Image](https://github.com/user-attachments/assets/8a854c00-b5f5-4bfe-bb56-f59afc5c5c53)
I have two questions for the sequence diagram lecture this week.
1. Why do we use items and value as the variable name? Shouldn’t it be empty since it is not explicitly stated but only part of the unwrapping process? (The variable names are also self determined)
2. Why is the return type Item when the return type of Order.getItems() is ArrayList&lt;Item>
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/32" expanded>
<div slot="header">

**6. :fas-info-circle: Clarifying closing date for weekly quiz**
</div>

Could I check if the quiz closing date can be extended to 4 pm (before the lecture) instead of the current 12 pm? I did not manage to attempt it.

![Image](https://github.com/user-attachments/assets/2a2a8ab1-8d41-421a-8dea-b278288c2276)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/25" expanded>
<div slot="header">

**7. :fas-info-circle: tP commit message best practices grading**
</div>

**For tP, I did not follow best practices for the first few commits, as we started in week 7.**
![Image](https://github.com/user-attachments/assets/66acc975-44e1-412e-9718-890974735c9b)

**From week 8 onwards, I started following best practices strictly.**
![Image](https://github.com/user-attachments/assets/bf51148c-dedd-4332-ae02-7ba2efb6945a)

Will this impact the grading?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/23" expanded>
<div slot="header">

**8. :fas-info-circle: Did not receive iP allocation for week 8**
</div>

![Image](https://github.com/user-attachments/assets/8b1e38b8-dd3d-45e8-af28-c6096f37ae2d)

As can be seen from the above screenshot, we are supposed to receive the allocation on Monday. However, I did not receive any. May I check if the allocation has been sent?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/17" expanded>
<div slot="header">

**9. :fas-info-circle: Watch this forum**
</div>

Hi all,

I can't seem to find the "watch" button for this forum. I have attached the screenshot of this page. Appreciate any help!

![Image](https://github.com/user-attachments/assets/53192b25-4546-45cf-b2e6-e6536f81ce59)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/16" expanded>
<div slot="header">

**10. :fas-info-circle: Request to help with smoke testing JAR file**
</div>

* Link to JAR file: https://nusu-my.sharepoint.com/:u:/g/personal/e1355944_u_nus_edu/EaOaDm4kf5ZPhktTIB94vygBuG5tpwC2nJ7BoN-rRX_p9w?e=aIb3Tx
* Which OS'es to test on: Windows, Mac and Linux. I would appreciate if tests can be done on Mac and Linux if possible
* Things to check specifically: Ability to store the tasks (Todo/Deadline/Event) correctly, and message output parsing (especially new line character)


Guide for testers:
* Post screenshots from your smoke tests
* Mention which OS you used for testing


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/14#issuecomment-2677604447" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

All appears to be good! Let's close this issue.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10#issuecomment-2677608458" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

@terryasdf 

This is how I implemented my switch-case:

```
        switch (cmd.command) ``{``
        case BYE:
            return true;
        case LIST_TASK:
            listTask(tasks, minionOut);
            return false;
        case ADD_TODO:
            addTodo(cmd, tasks, minionOut);
            return false;
......
        default:
            throw new MinionException("Keyword not caught!");
        ``}``
```
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/13#issuecomment-2677613410" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

Looks like it is updated! Perhaps there is a delay on the dashboard side. Personally, I found that it tends to reflect the changes within one day.

![Image](https://github.com/user-attachments/assets/bd71a5b2-995d-4fef-93d0-8035c7f62603)

Do close this issue if it is resolved
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/15#issuecomment-2677629402" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Cool! A smart idea to use JSON instead of creating your own standard. 

I feel that profs and TAs might want us to do the latter so that we can practice our string manipulation skills. But let's see if this Request gets approved!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/17#issuecomment-2677680076" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

Thanks! I'm able to watch the forum now 👍 
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/22#issuecomment-2724245615" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

It would have to be within the time window for it to be marked as completed

![Image](https://github.com/user-attachments/assets/99988213-e37c-47ae-97b5-43af5e09bdb7)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/23#issuecomment-2731350158" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

Receieved!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/16#issuecomment-2731352228" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

Thank you all for helping with the smoke tests! I have fixed the issues and really appreciate your time!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/25#issuecomment-2735276278" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

Ok! Have started following the best practices strictly. Thanks
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/33#issuecomment-2750813957" expanded>
<div slot="header">

**20 :fas-comment:**
</div>

Thanks, Professor,

Just so I understand correctly, do we write the following in the diagram?

For return type `ArrayList&lt;Type>`, 
✔ `"plural_variable_name": Type`
❌ `"plural_variable_name": ArrayList&lt;Type>`
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/33#issuecomment-2756702098" expanded>
<div slot="header">

**21 :fas-comment:**
</div>

Thanks for the clarification!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/43#issuecomment-2777416346" expanded>
<div slot="header">

**22 :fas-comment:**
</div>

Here is a simplified mermaid diagram

'''mermaid

sequenceDiagram
    participant A as :Round
    participant B as &lt;&lt;class>> RoundActions
    participant F as :Score

    A->>+B: playCards(state, config, cardIndices)
    activate A
activate B
    B->>+F: new Score(boss)

    note right of F: Constructor activated here
    F-->>-B: handScore:Score
    B-->>A: actionResult:ActionResult
deactivate B
    deactivate A
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/43#issuecomment-2795652344" expanded>
<div slot="header">

**23 :fas-comment:**
</div>

Appreciate your time professor!

I opted instead to use Paint to manually move the `:Score` downwards.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/51#issuecomment-2838477436" expanded>
<div slot="header">

**24 :fas-comment:**
</div>

Same thing happens for me. Windows 10 - Adobe Acrobat installed and antivirus disabled.

For my case, it occurred after I try to search for a keyword
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/51#issuecomment-2841714972" expanded>
<div slot="header">

**25 :fas-comment:**
</div>

Thanks for your suggestion prof! Unfortunately, it still did not work for me - sigh 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 2. ZHAN..ANYI `@terryasdf` (20 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/51" expanded>
<div slot="header">

**1. :fas-info-circle: Examplify does not load PDF pages properly**
</div>

Each time I open the attached textbook, it only loads the first few pages, and then all pages goes blank. Is there anyway to fix that? (I'm using Windows 11 with decent hardware setup)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/47" expanded>
<div slot="header">

**2. :fas-info-circle: Is it ok that the submitted files on canvas has -1 at the end of the name?**
</div>

I've uploaded a file more than one time
![Image](https://github.com/user-attachments/assets/1a1cb027-562f-42d4-8b30-a6f764ab8baa)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/42" expanded>
<div slot="header">

**3. :fas-info-circle: How should I disable logging in built jar files?**
</div>

I'm using `java.util.logging.Logger`. The logging info still exists in jar files created with "shadowJar" option.

![Image](https://github.com/user-attachments/assets/40fea4c1-266d-4061-8aaa-a33503e4b0b7)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/40" expanded>
<div slot="header">

**4. :fas-info-circle: Can I delete the lines related to text-ui-test in github gradle.yml?**
</div>

Since we are using JUnit testing, and the initial output of our program involves a line of absolute file path, which may appear differently in different environments, we are always failing the github gradle test, as shown below.

![Image](https://github.com/user-attachments/assets/e6857d9c-4110-417e-900a-a76ff2a16a30)

If I remove the lines below in `gradle.yml`, I can pass all checks on github.

![Image](https://github.com/user-attachments/assets/dc8af0f9-1140-4408-b67a-3bba5c96e4ca)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/21" expanded>
<div slot="header">

**5. :fas-info-circle: Gradle not checking Lambda-style switch statements indentation correctly**
</div>

Original code
```
String message = switch (keyword) ``{``
    case "tutorial" -&gt; cmdRunner.handleTutorial();
    case "set-budget" -&gt; cmdRunner.handleSetBudget(Integer.parseInt(tokens[1]));
    case "view-budget" -&gt; cmdRunner.handleViewBudget();
    default -&gt; throw new InvalidKeywordException(keyword);
``}``;
```
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/15" expanded>
<div slot="header">

**6. :fas-info-circle: Requesting the use of org.json in iP and tP**
</div>

## Library

[JSON-java](https://github.com/stleary/JSON-java)

## Purpose

To convert objects to JSON and parse JSON strings in iP and tP.

## License

https://github.com/stleary/JSON-java/blob/master/LICENSE
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/7" expanded>
<div slot="header">

**7. :fas-info-circle: [Coursemology W4Q3] Cannot pass test case even the results look the same**
</div>

As the screenshot below shows, I can't pass the test case, either using `System.out.println()` or `System.out.print("\n")`. It might be a similar issue as #6. 
![Image](https://github.com/user-attachments/assets/cf3a3835-b27d-4bd2-bf54-df59dcd5860c)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/7#issuecomment-2634043222" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

Replaced `Circle.java` and `Rectangle.java` with the ones from https://nus-cs2113-ay2425s2.github.io/website/schedule/week4/topics.html#key-exercise-print-shape-area. Somehow passed even though the output still looks the same.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/7#issuecomment-2635589708" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

> [@terryasdf](https://github.com/terryasdf) Hey there! I was told by Prof Akshay that Coursemology uses Java 11, which led to `toList` being an invalid method called on a `Stream`. I instead used `.collect(Collectors.toList())` (don't forget to import `Collectors`) and it now works! Assuming you were using similar logic to me, it should execute correctly. Hope this helps!

Oh I did not use streams and filter for this task. I have no idea what caused this, but I passed the test after replacing the files with the one from the 2113 website. Thank you for your comment tho.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/11#issuecomment-2653935027" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

IMO throw checked exceptions (inherited from Exception class while not RuntimeException) for your case. Exceptions are for cases when something stops your program from acting normally. For example if the user provides a invalid cmd input, your program cannot run that command correctly by any means, and an exception can be thrown.

On the other hand, if you have intended behavior for a invalid input, just use if/else. E.g. If your program replaces all invalid negative input values with zeros, then use if/else, because negative values are not "anomalies" that stop your program in this case.

This is my personal understanding.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10#issuecomment-2668238645" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

Could you pls share how you implemented the switch-case in main.java?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/14#issuecomment-2668990752" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

Well the quiz appears now.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/15#issuecomment-2678086103" expanded>
<div slot="header">

**13 :fas-comment:**
</div>

> Approved 👍 [@terryasdf](https://github.com/terryasdf)
> 
> Let this issue remain open. Once approved for one person/team, it is approved for everyone in the class. No need to ask again!

Thank you very much! I will leave the issue open.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699888179" expanded>
<div slot="header">

**14 :fas-comment:**
</div>

Did you push your tags to origin?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699903317" expanded>
<div slot="header">

**15 :fas-comment:**
</div>

> No. this is a new device that I started using a month ago.

Then I suppose you also cannot push right?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/22#issuecomment-2724412739" expanded>
<div slot="header">

**16 :fas-comment:**
</div>

But the deadline is actually 2025-03-14 as shown in [https://nus-cs2113-ay2425s2.github.io/website/schedule/week7/project.html#4-submit-the-final-version-fri-mar-14th-2359](url) ![Image](https://github.com/user-attachments/assets/2515820a-3bf0-4e58-b99c-5449e954547d)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/40#issuecomment-2776103004" expanded>
<div slot="header">

**17 :fas-comment:**
</div>

OK I see. I'll delete them. Thanks
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/42#issuecomment-2777388121" expanded>
<div slot="header">

**18 :fas-comment:**
</div>

ok i'll try to redirect logging to a file. i thought stderr would not be shown in release.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/47#issuecomment-2785116466" expanded>
<div slot="header">

**19 :fas-comment:**
</div>

oh i just noticed it was mentioned in the website

![Image](https://github.com/user-attachments/assets/01d581d9-f603-48c3-b91b-28ee66272b1a)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/51#issuecomment-2838725811" expanded>
<div slot="header">

**20 :fas-comment:**
</div>

I haven't even tried searching a keyword
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 3. T HA..ARAN `@vegetablestabber` (12 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/6" expanded>
<div slot="header">

**1. :fas-info-circle: Coursemology not passing Q9 and Q10 for Homework 2**
</div>

Hi, Coursemology isn't passing my answers for Q9 and Q10. I'm using streams in both answers so I'm wondering if that's the issue with my code because I'm not aware of any restrictions that we have for Coursemology. Just pasting the relevant parts of each answer:

Question 9:

'''Main.java
public static String[] filterEmails(String[] items) ``{``
    List&lt;String> filteredItems = Arrays.stream(items)
            .filter(str -&gt; str.contains("@"))
            .toList();

    return filteredItems.toArray(new String[0]);
``}``

public static void printItems(String[] items) ``{``
    System.out.println(Arrays.asList(items));
``}``
'''

Question 10:

'''Main.java
public static void main(String[] args) ``{``
    // ...

    line = in.nextLine();

    List&lt;String> amountStrings = Arrays.stream(line.split(" "))
        .filter(str -&gt; str.contains("$"))
        .toList();

    System.out.println("Expenses in overseas currency:" + amountStrings);

    double totalAmount = amountStrings.stream()
        .map(str -&gt; str.replace("$", ""))
        .mapToDouble(str -&gt; Double.parseDouble(str) * 1.70)
        .reduce(0.0, (acc, elem) -&gt; acc + elem);

    System.out.println(String.format("Total in local currency: $%.2f", totalAmount));
    in.close();
``}``
'''

</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/6#issuecomment-2629237125" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

> this could be due to the line ending. cr vs cr + lf try using `print` instead of `println`
> 
> [@vegetablestabber](https://github.com/vegetablestabber)

@okkhoy Hi Prof, swapping the `println` statements with `print` statements has not changed anything unfortunately. I switched `println("Some string")` with `print("Some string\n")`, which resulted in no change. More specifically:

**Q9:**
_Before:_ `System.out.println(Arrays.asList(items))`
_After:_ `System.out.print(Arrays.asList(items) + "\n")`

**Q10:**
_Before:_ `System.out.println(String.format("Total in local currency: $%.2f", totalAmount))`
_After:_ `System.out.print(String.format("Total in local currency: $%.2f", totalAmount))`

I've even used a [text comparison tool](https://text-compare.com/) which tells me that the results are identical for all public test cases for Q9 and Q10.

I'm a little bit more concerned as this is now past the deadline and I'm worried I won't get the marks for Homework 2, haha. Would really appreciate your advice on this, thank you Prof!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/7#issuecomment-2634071929" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

@terryasdf Hey there! I was told by Prof Akshay that Coursemology uses Java 11, which led to `toList` being an invalid method called on a `Stream`. I instead used `.collect(Collectors.toList())` (don't forget to import `Collectors`) and it now works! Assuming you were using similar logic to me, it should execute correctly. Hope this helps!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/6#issuecomment-2634113690" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Fixed this issue by replacing `.toList()` with `.collect(Collectors.toList())` (don't forget to import `Collectors`). Apparently, Coursemology uses Java 11, an earlier version of what this course encourages to use, which resulted in my code being invalid. 
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10#issuecomment-2644493958" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

@juneja999 Hi, can you please share more context? I think I've come across the same issue for another problem, but I'd need to check your working.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/8#issuecomment-2644494326" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

@Travissssz Hi, can you please close the issue if it has been resolved, thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/11#issuecomment-2663122266" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

@Deanson-Choo Please close the issue if the issue is resolved, thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/13#issuecomment-2663129727" expanded>
<div slot="header">

**8 :fas-comment:**
</div>

If you have followed the steps correctly on the CS2113 website, I would suggest emailing or messaging Prof Akshay on Teams since this could possibly be a backend issue. Don't forget to close this issue if resolved, thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10#issuecomment-2663155443" expanded>
<div slot="header">

**9 :fas-comment:**
</div>

Sorry for the late reply, but looking at this now, I'm not sure what seems to be an issue. According to Prof Akshay, Coursemology runs on Java 11 but I don't think there's anything necessarily wrong with your code. I know we're on Week 6 Coursemology practice problems now, but I think you could benefit with a discussion with either your TAs or Prof Akshay.

If you're past this problem, please close this issue, thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/12#issuecomment-2663158143" expanded>
<div slot="header">

**10 :fas-comment:**
</div>

@jessican1212 Please close this issue if resolved, thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/5#issuecomment-2663159165" expanded>
<div slot="header">

**11 :fas-comment:**
</div>

@LEESY02 Please close this issue if resolved, thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/3#issuecomment-2663159725" expanded>
<div slot="header">

**12 :fas-comment:**
</div>

@rozaliesmit Please close this issue if resolved, thanks!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 4. CHOO..NSON `@Deanson-Choo` (7 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/37" expanded>
<div slot="header">

**1. :fas-info-circle: Requesting usage of java.lang.reflect.Field**
</div>

## Library

[java.lang.reflect.Field](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/reflect/Field.html)

## Purpose

``{``Used to access and manipulate private fields within classes during unit testing. This is particularly useful when testing internal state or behavior that is not exposed via public methods. It helps ensure correctness without changing access modifiers purely for testability.``}``

## License

java.lang.reflect.Field is part of the Java Standard Library and is distributed under the GNU General Public License
[](https://openjdk.org/legal/gplv2+ce.html)

</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/26" expanded>
<div slot="header">

**2. :fas-info-circle: Failing gradle runShadow check**
</div>

My team application is failing with the following error after running runShadow:

![Image](https://github.com/user-attachments/assets/42934ce8-fbec-4cf7-8dc7-3845c824dca5)


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/22" expanded>
<div slot="header">

**3. :fas-info-circle: JAR final submission not being detected by script**
</div>

I submitted my JAR under releases with the tag 'A-Release' on Wednesday 430pm, but it has yet to be registered by the grading script. 
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/11" expanded>
<div slot="header">

**4. :fas-info-circle: Error Handling: Throwing an exception**
</div>

What is the difference between throwing an exception and printing an error message with a return statement? When should I throw an exception instead of simply printing an error and returning?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/11#issuecomment-2664650936" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Thank you everyone for the responses!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/26#issuecomment-2734109658" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

Hi Prof, Thanks for the reply. Our team realized that it was due to test-ui-test/EXPECTED.txt and test-ui-test/input.txt that caused us to fail the test since we did not change those initially. 


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/37#issuecomment-2770434641" expanded>
<div slot="header">

**7 :fas-comment:**
</div>

Noted Prof!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 5. TANG.. YAN `@Lyam-T` (6 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/45" expanded>
<div slot="header">

**1. :fas-info-circle: Request usage of org.json**
</div>

## Library

[org.json](https://github.com/stleary/JSON-java)

## Purpose

To export trip planning information to a files for later reload of the data such that user can reuse the previous saved trip planning process

## License

https://github.com/stleary/JSON-java/blob/master/LICENSE
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/13" expanded>
<div slot="header">

**2. :fas-info-circle: iP progress dashboard not updated after enable the issue tracker**
</div>

I have enabled the the issues tracker as reminded by the email a week or more ago, yet it is still not yet updated in the iP dashboard. I am wonder whether I did anything wrong, or it is just that the dashboard not yet being updated. Thank you for the help in advance.

<img width="985" alt="Image" src="https://github.com/user-attachments/assets/c79b7218-12b7-465a-90cf-fce6d0b3af12" />
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/13#issuecomment-2697892669" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

> We check for the issue tracker the first 2 weeks, if it is not updated by then, it remains red.

Thank you for letting me know, then I shall close this issue.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/24#issuecomment-2728411383" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Me and my teams also encountered this, I tried close and reopen a new pull request and it works and allow merge somehow. **However** the CI test after merged failed again.
Can we know what exactly is causing this inconsistency testing and how to fix it properly, Thx!
<img width="697" alt="Image" src="https://github.com/user-attachments/assets/b10fb9d8-7893-4039-a9fc-543479183056"/>


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/24#issuecomment-2729745615" expanded>
<div slot="header">

**5 :fas-comment:**
</div>





> Me and my teams also encountered this, I tried close and reopen a new pull request and it works and allow merge somehow. **However** the CI test after merged failed again. Can we know what exactly is causing this inconsistency testing and how to fix it properly, Thx! <img alt="Image" width="697" src="https://private-user-images.githubusercontent.com/121327285/423351340-b10fb9d8-7893-4039-a9fc-543479183056.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDIyMjIwODksIm5iZiI6MTc0MjIyMTc4OSwicGF0aCI6Ii8xMjEzMjcyODUvNDIzMzUxMzQwLWIxMGZiOWQ4LTc4OTMtNDAzOS1hOWZjLTU0MzQ3OTE4MzA1Ni5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzE3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMxN1QxNDI5NDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lODI2ZTJiNTUyYjBkYjg4NzE4ZDNlZjgzYmNmMzMxMjg2MGNmNzM2MGEwMGZjNmJjNzk5NGFhZmYxZGUyNGFjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.UIEJbxXs1oJXyoiZHINobglYEzO3roV-YSvxRp4TcYo">

Update
I might have fix the issue, I think for my case it might be that my build.gradle mainClass is incorrectly set. Or it is because the task pass by luck... You can validate it by running locally the gradle test under Tasks/application/run. See if this might help!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/45#issuecomment-2781201760" expanded>
<div slot="header">

**6 :fas-comment:**
</div>

thank you!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 6. NGUY.. DAT `@QuyDatNguyen` (5 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/49" expanded>
<div slot="header">

**1. :fas-info-circle: PE Tester Response - what happens if I want to change severity and how my accuracy be affected?**
</div>

I am taking a look at the developer's response and I believe that some of these bugs should be different severity than what me and the developer decided (Eg: I originally sent a "High" severity, the developer changed to "Low" but I want to change to "Medium" after reading extra information given by them).
However, what will happen to both me and the dev's bug accuracy after I state in disagreement that I want to change to "Medium" instead (simply because their error causes misunderstanding in diagram and should be at Medium at least and definitely must make changes)?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/44" expanded>
<div slot="header">

**2. :fas-info-circle: Clarity on severity level for FeatureFlaw and DeveloperGuide**
</div>


I want to ask more on how severity level can be seperated from each other in FeatureFlaw and DeveloperGuide

1. For incorrect notation for Diagram (eg: use of incorrect notation like the one mentioned in the announcement, using some wrong notation for graph such as wrong notation for frame/ mistake return arrow to be straight line like calling arrow), will these issues be considered as MEDIUM or LOW (this can be 1 mistake in a whole diagram, but do you consider them as minor convenience or actually more serious one).
2. Can you explain more on how to differentiate between HIGH, MEDIUM, LOW and VERY LOW severity in Feature Flaw (as the current instructions only say how it creates inconvenience in using, but not much on relevancy for feature flaw). In addition, do you have any tips when looking for feature flaw, as how can quickly indicate feature laws and their severity as well.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/44#issuecomment-2800557405" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

thanks prof
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/49#issuecomment-2808606448" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

For reference, i receive this as issue #12 on my own pe repo
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/49#issuecomment-2812138691" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

> We will still go by:
> 
> ![Image](https://github.com/user-attachments/assets/f99c5674-6a45-4e56-8fb5-49fa4d279317)

Can I check if teacher's decision on bug's severity must be either same as tester/ dev or they can have their own position. And in the case I change my severity at this phase (eg: from High to Medium), will their final position still be based on my initial position anymore (eg: High, given Dev's choice is Low)
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 7. OJAS..RANA `@ojassurana` (5 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/39" expanded>
<div slot="header">

**1. :fas-info-circle: Requesting usage of Atlas library.**
</div>

## Library

[Atlas](https://github.com/bkiers/atlas)

## Purpose

Given a longitude and latitude, this library helps geo code and provide the location of those coordinates (e.g. "Cape Town").

## License

[MIT License](https://github.com/bkiers/atlas/blob/master/LICENSE)

</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/19" expanded>
<div slot="header">

**2. :fas-info-circle: Requesting help with smoke testing my JAR file for non-mac users.**
</div>

**JAR file**: https://github.com/ojassurana/ip/releases/tag/A-Release
**Which OS'es to test on:** Windows or any Linux Distro

_Things to check specifically:_
* See if all the features listed in my UG: ojassurana.github.io/ojassurana/ip work flawlessly


Note for testers:
* I used Mac OS so far

Thanks a lot for the help. Really appreciate it! 
Contact me on Telegram: [@ojasx](t.me/ojasx) if any issues for quicker correspondence!


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/16#issuecomment-2702736957" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

I did the smoke testing on my Macbook and everything seems to work well! I'd also appreciate if you could help smoke test for me on your windows: https://github.com/nus-cs2113-AY2425S2/forum/issues/19

<img width="510" alt="Image" src="https://github.com/user-attachments/assets/0b31ef14-3714-40aa-892d-cfe975b61ccd" />
<img width="481" alt="Image" src="https://github.com/user-attachments/assets/bbb1d9e2-2427-49aa-83e0-c4710e97adaf" />
<img width="566" alt="Image" src="https://github.com/user-attachments/assets/33f7f428-ff5d-451e-a612-6bafc1a7dd25" />
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/20#issuecomment-2705406056" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Hi fellow course mate. I had encountered the same issue as you :c 
What worked for me is that I simply deleted the my previous project (in your case you should delete https://github.com/jing-yen/jing-yen.github.io)

After that I simply hosted the ip on Github pages again and opened the URL on incognito mode (the URL might not work in your main browser as the older website may be cached. Let me know if it works!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/39#issuecomment-2771264819" expanded>
<div slot="header">

**5 :fas-comment:**
</div>

Thanks prof. I will find another library but close this issue for now. 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 8. KHOO..YLAN `@dylankhoo` (4 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/1#issuecomment-2594568775" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Did you try clearing your browser cookies and cache? I had the same issue but resolved it by doing so.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699893968" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Similar to commits, you need to push your tags as well

You can use this to push a single tag:
`git push origin tag &lt;tag_name>`

But for your case you can just push all with:
`git push origin --tags`
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699896082" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

> Yes, but this pops up and stops me from doing so. This also appears whenever I want to push my commits via terminal, so I usually only use the commit tool on the side bar:
> 
> <img alt="Image" width="948" src="https://private-user-images.githubusercontent.com/142810616/419307623-2a21d82c-1773-4872-81cb-588965423620.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDExNTI4NDMsIm5iZiI6MTc0MTE1MjU0MywicGF0aCI6Ii8xNDI4MTA2MTYvNDE5MzA3NjIzLTJhMjFkODJjLTE3NzMtNDg3Mi04MWNiLTU4ODk2NTQyMzYyMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMwNVQwNTI5MDNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zMWE2OTliZWJkZDFkZTcxMjYxNDk4YzUyZWYwMzdiMGJlNTc1NzhjMGQ2MDYxNjgyNTNjMWRmYzEzZWQ3YTdhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.4_JkQ4_7i3PvcxhG-UD1esLxF1h96exCHnfN4Y8yWfI">

This is an authentication issue, did you set up SSH key for your device?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699901584" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

> No. this is a new device that I started using a month ago.

Refer to:
1. [Generate SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agentl)
2. [Adding SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) 

I think this will probably fix your issue. You may need to restart your device after the set up first.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 9. GOVI..KSHA `@roshnidaksha` (4 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/36" expanded>
<div slot="header">

**1. :fas-info-circle: Using draw.io instead of PlantUML**
</div>



In the FAQ regarding alternatives to PlantUML, it is mentioned that we should:

_**"Choose a diagramming tool that has some 'source' format that can be version-controlled using git and updated incrementally"**_

My team is considering using [draw.io](https://app.diagrams.net/) to draw sequence and class diagrams. The tool generates `.drawio` files, which contain 400+ lines per diagram. 

Given this, would it be necessary to commit these files to our project repository?

Could we create a shared drive link instead with all our source files and attach the link in the DG instead of committing them to our project repository?

Thank you
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/30" expanded>
<div slot="header">

**2. :fas-info-circle: Requesting the use of Natty library in tp**
</div>

## Library

[natty](https://github.com/joestelmach/natty/tree/master)

## Purpose

The `natty` library is intended to be used for natural language date parsing. It allows users to input dates in a flexible, human-readable format (e.g., "next Monday" or "two weeks from now") and converts them into structured Date objects. This functionality is useful for our project by enabling users to enter interview dates, and other time-related details in a more intuitive manner.

## License

https://github.com/joestelmach/natty/blob/master/LICENSE

</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/29" expanded>
<div slot="header">

**3. :fas-info-circle: Requesting the use of Prettytime library**
</div>

## Library

[prettytime](https://github.com/ocpsoft/prettytime/tree/master)

## Purpose

The `prettytime` library is intended to be used for formatting and displaying time differences in a human-readable format. It helps to convert timestamps into relative time expressions like "5 minutes ago" or "in 2 hours," making date and time information more user-friendly. 

For our project, this functionality is useful for displaying the interview date and time or other time-related events.

## License

https://github.com/ocpsoft/prettytime/blob/master/LICENSE

</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/36#issuecomment-2764622008" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Yes, it is an online tool. Thank you for clarifying, I'll close this issue now.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 10. JUNE..SHAT `@juneja999` (4 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10" expanded>
<div slot="header">

**1. :fas-info-circle: Coursemology week 4- question 4 test case not passing**
</div>

For question 4, one test case is passing whereas the other is not. There is a subtle difference between the two test cases but I'm yet to figure out the problem point.

![Image](https://github.com/user-attachments/assets/a6a32a92-e815-40f4-9494-7ec7e68d10d5)

 
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10#issuecomment-2647438352" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

@vegetablestabber 

I was using this in my priority.java file 

```
public enum Priority ``{``
2 | HIGH, MEDIUM, LOW;
3 |  
4 | //@Override
5 |     public String toString() ``{``
6 |         return this.name();
7 |   ``}``
8 | ``}``
9 |  
```

and then I was simply calling it in my main code like this 



```
2 |  
3 | // Add your method here
4 | public static void describe(String s, Priority p ) ``{``
5 | System.out.printf("%s indicates %s priority \n", s, p.toString().toLowerCase());
6 | ``}``
7 |  
8 | public static void main(String[] args) ``{``
9 | describe("Red", Priority.HIGH);
10 | describe("Orange", Priority.MEDIUM);
11 | describe("Blue", Priority.MEDIUM);
12 | describe("Green", Priority.LOW);
13 | ``}``
14 | ``}``
15 |  

```

This problem got solved when I removed the toString() method and instead used a switch-case in main.java


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10#issuecomment-2763096878" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

> Could you pls share how you implemented the switch-case in main.java?

Sorry, but I had changed my approach to the question. Hence I didn't save this particular code.

</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/10#issuecomment-2763097624" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Thank you everyone for participating and helping. I will now close the thread. 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 11. CHAN.. KAI `@kevinchangckc` (4 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18" expanded>
<div slot="header">

**1. :fas-info-circle: Tagging appropriately for iP**
</div>

I was checking the iP dashboard and realized that I haven't been creating tags for the commits I made for each week, so it appears that I have not made reasonable progress to the project. I have everything tagged on my local IntelliJ and they all show as normal when I use `git tag`, but I was wondering if there is a standard procedure from there to sync it to my github repo? 

I have read through the instructions on how to do so as well, but could not really understand how. Please let me know how I can be more specific about this, and I really appreciate your help!

<img width="369" alt="Image" src="https://github.com/user-attachments/assets/bcd373ba-fe58-4eba-a56f-6d274e318157" />

<img width="369" alt="Image" src="https://github.com/user-attachments/assets/8fe6c47c-1b56-4bf4-89c2-b1b2ce195102" />
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699893565" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Yes, but this pops up and stops me from doing so. This also appears whenever I want to push my commits via terminal, so I usually only use the commit tool on the side bar:

<img width="948" alt="Image" src="https://github.com/user-attachments/assets/2a21d82c-1773-4872-81cb-588965423620" />
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699895922" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

The same outcome seems to persist:

<img width="949" alt="Image" src="https://github.com/user-attachments/assets/5b91450a-17c6-493f-b450-3242afd68c1e" />
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/18#issuecomment-2699900018" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

No. this is a new device that I started using a month ago.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 12. LEE ..YOON `@LEESY02` (3 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/5" expanded>
<div slot="header">

**1. :fas-info-circle: Grading of ip**
</div>

How will the grading of Individual Project be conducted?

Will forking the directory and pushing commits onto our remote directory (the forked one) suffice?
Is it okay to leave the Duke.java file in the directory (src/main/java) of the remote directory, or will it interfere with the grading algorithm?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/1" expanded>
<div slot="header">

**2. :fas-info-circle: Issues installing Java 17**
</div>

Currently facing problems when installing Java 17 when trying to install through the link present in the course website (https://www.oracle.com/java/technologies/downloads/#java17). I am using Windows, and I had the same error when trying to install for Linux as well.

![Screenshot 2025-01-16 124612](https://github.com/user-attachments/assets/100e9c17-d9a5-41eb-b24e-4b96add8b204)
400 Bad Request 
Request Header Or Cookie Too Large

Is there anyone getting this issue / managed to fix it?

Thank you for the help.


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/27#issuecomment-2736119229" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Hi guys, if you guys have this issue, you can try what I did to solve it (Thank you Mr GPT)

Apparently different OS has different line endings (LR and CRLF, you can search for what it is, idk also)

![Image](https://github.com/user-attachments/assets/345be5df-bbab-4af8-84b1-1cf46313ba01)

So when you try to run the runtest.sh or runtest.bat your test case will fail.

You need to install something via MINGW (I ran this command: pacman -S dos2unix)

![Image](https://github.com/user-attachments/assets/feac17ff-510a-4ced-8900-bcfe36add097)

Then you can either use dos2unix or unix2dos to convert the line endings of EXPECTED.txt or ACTUAL.txt

![Image](https://github.com/user-attachments/assets/0e29b716-b515-4ba3-b995-e983f425e439)

![Image](https://github.com/user-attachments/assets/6284b813-261c-4a8c-96c3-5a37302c483d)

Afterwards it passed my local test and the github check. I hope you guys don't need to go through this

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 13. KAM .. JIE `@ShengJie13245` (2 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/7#issuecomment-2635811276" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

It is due to the coursemology version of the Circle and Rectangle classes not being a subclass of the Shape class
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/8#issuecomment-2636367765" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

It is probably caused by the Circle and Rectangle file in coursemology are not inherited from the shapes class.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 14. LEE ..SHUA `@b1inmeister` (2 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/27" expanded>
<div slot="header">

**1. :fas-info-circle: automated text UI mismatch error**
</div>

Hi all, my team has been experiencing this error for a few days now. When running the checks on Github, this error appears when running runtest.sh on Linux. 

![Image](https://github.com/user-attachments/assets/ec22bd1f-05f7-430c-88c3-f0a4d54051d6)

From the picture, the actual and the expected output are identical. We have also looked at the text files multiple times on IntelliJ and found no leading or trailing spaces present. We also find it very odd that all the lines are failing.

Furthermore, I have run the runtest.sh locally on the Git terminal in Sourcetree. From the picture below, the test passes on my local machine. This makes me even more confusing that it passes locally, but not on the Github checks.

![Image](https://github.com/user-attachments/assets/079fac09-5dd8-4e36-a418-05b4b6675ed6)

Any help will be appreciated. Thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/27#issuecomment-2736244428" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Thanks for your input. After looking through what you mentioned about the different line endings, I did more research and found out that the absence of the dos2unix command in the virtual machine that runs the Github checks is rather significant. That is why the test cannot pass, as the absence of dos2unix command means that the expected text file could not convert to the same format as the actual text file. With the difference between Windows and Linux in how they interpret the end of a line, the two text files will actually be different, despite visually looking the same.

After doing more research, I found a solution to this problem. I edited the runtest.sh file to replace dos2unix with something else that does not require installation. 

![Image](https://github.com/user-attachments/assets/956ef604-6b07-47c2-9d1b-363d14d3dbce)

This helped to convert the EXPECTED-UNIX.TXT and ACTUAL.TXT to the same format for comparison during the automated text UI test. Thus, the test is now satisfactory.

Thanks again for the help! 

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 15. TRAV..ARAN `@Travissssz` (2 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/8" expanded>
<div slot="header">

**1. :fas-info-circle: Week 4, exercise 3 help**
</div>

```
public class Main ``{``
    private static Shape[] shapes = new Shape[100];
    private static int shapeCount = 0;

    public static void addShape(Shape s)``{``
        shapes[shapeCount] = s;
        shapeCount++;
    ``}``

    public static void printAreas() ``{``
        for (int i = 0; i < shapeCount; i++) ``{``
            System.out.println(shapes[i].area());
        ``}``
    ``}``

    public static void main(String[] args) ``{``
        addShape(new Circle(5));
        addShape(new Rectangle(3, 4));
        addShape(new Circle(10));
        printAreas();
        addShape(new Rectangle(4, 4));
        printAreas();
    ``}``
``}``

```
This is my main.java code, and I have the same output as coursemology on my terminal. But I keep failing the public test, why is this? Below is the screenshot of my output

<img width="335" alt="Image" src="https://github.com/user-attachments/assets/a4d1765d-cee7-4bb5-a1c0-93b1180c7177" />
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/8#issuecomment-2637429100" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

damn, yeah thank you
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 16. CHAN.. BIN `@ShengBin-101` (2 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/19#issuecomment-2707891647" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Tested on Linux (Ubuntu 22.04 LTS) and everything seems to work great. 
You can see the text file below for more details.

[log.txt](https://github.com/user-attachments/files/19139967/log.txt)
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/16#issuecomment-2707901141" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Tested on Linux (Ubuntu 22.04 LTS) and identified a few issues:

1. Program crashes if command "mark" is not given a task index, or task index given is not a number (see log.txt and log2.txt)
2. Similar issue as (1) for command "unmark" (see log3.txt)

Other than the mentioned issues, everything else seems to work fine. Good job!

You can see the text files attached to see my smoke tests. Filenames follow order of testing.

[log4.txt](https://github.com/user-attachments/files/19140060/log4.txt)
[log3.txt](https://github.com/user-attachments/files/19140057/log3.txt)
[log2.txt](https://github.com/user-attachments/files/19140058/log2.txt)
[log.txt](https://github.com/user-attachments/files/19140059/log.txt)
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 17. TAN ..NMIN `@xmtan1` (2 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/9" expanded>
<div slot="header">

**1. :fas-info-circle: Unable to push**
</div>

Every time I push from Sourcetree, a "credentialHelperSelector" will pop up, and no matter what I click, the push ends with this error:

git -c diff.mnemonicprefix=false -c core.quotepath=false --no-optional-locks push -v --tags origin master:master
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/xmtan1/ip.git/'

Pushing to https://github.com/xmtan1/ip.git
Completed with errors, see above.

I have tried doing the AppData\Local\Atlassian\Sourcetree method found online to delete the password stored and tried again but to the same result. Just in case, I also resetted my password before doing the above and it still does not work

The committed files do not show up on my Github
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/9#issuecomment-2639454996" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Thank you!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 18. PHUA..HIAN `@Phua-Lock-Hian` (2 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/24" expanded>
<div slot="header">

**1. :fas-info-circle: Cannot validate Gradle wrapper**
</div>

Hi, my tp pull request is running into an issue with validating the Gradle wrapper as shown below, does anyone know how I can solve this? I found a similar issue on previous year forums and have tried the solution of closing the PR and creating a new one but the problem still persists.

![Image](https://github.com/user-attachments/assets/39fa09b1-965c-43aa-8044-ac69640bb5be)

Here is the link to the problematic PR: https://github.com/AY2425S2-CS2113-T12-2/tp/pull/32

Thanks!
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/24#issuecomment-2728171530" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

> I have also encountered this too. I tried to pass all local JUnit tests (make all arrows green locally![Image](https://github.com/user-attachments/assets/218245e8-e020-4e2a-8bb9-3bdf22927c3c)), and then it passed the gradle wrapper. I don't know why this is relevant, and not sure if this also works for your case.

Hi, my tests were passing locally already but I still have this issue. Thanks though.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 19. MARW..KITA `@nmarwah7` (2 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/34" expanded>
<div slot="header">

**1. :fas-info-circle: Requesting the use of ASCIItable library**
</div>

## Library

[asciitable](https://github.com/vdmeer/asciitable)

## Purpose

The asciitable library will be used to update the Ui of our Cli app toorganize data printed out onto the terminal in an intuitive tabular format which is more user-friendly. 

For our project this is useful since we would be printing out the data in a format that the user may use in their resumes or CVs.

## License

https://github.com/vdmeer/asciitable/blob/master/LICENSE

</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/4" expanded>
<div slot="header">

**2. :fas-info-circle: Naming convention for iP increment commit**
</div>

Hi was wondering, apart from Git conventions link (under Other Links on the course website), if there is any other necessary convention we must follow when pushing our weekly increment work to remote repo for subject. Specifically, I named the commit Level_0, instead of Level-0, (underscore vs. dash) and wanted to ensure the semantic difference wouldn't cause any issue in detection by the grading scripts?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 20. TONG.. YEN `@jing-yen` (2 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/20" expanded>
<div slot="header">

**1. :fas-info-circle: Github Pages deployment for multiple sites**
</div>


Hi, I have a Github Pages deployment from my previous project, it catches all URLs going to https://jing-yen.github.io/..., even the IP repo URL. 

May I know what is the best way to make the Github Pages for IP to appear, short of disabling Pages on my previous repo completely? Thanks.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/20#issuecomment-2724950613" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Thanks! I found another way... by going to Github Pages settings and changing the deployment from Github Actions, to select a branch manually. Then I selected None. The old page still loads (due to cache i think), but from incognito mode it shows the IP documentation now.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 21. ZHU ..NGYI `@yangyi-zhu` (2 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/31" expanded>
<div slot="header">

**1. :fas-info-circle: Will there be deductions for this mistake?**
</div>

I forgot to deploy my UG after having submitted everything in my iP (including the updated UG itself) last week. By the time I realized that I had missed that step, it was already a few hours past the deadline.

Since there was no actual content missing from my submission at that point, will I face any deductions for this mistake?
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/31#issuecomment-2742214479" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

Yes I have already deployed it earlier this week. Just wanted to make sure. Thank you prof!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 22. GOTO.. AYU `@sweetFish8` (2 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/28" expanded>
<div slot="header">

**1. :fas-info-circle: Will I Be Able to Submit for Final Grade Evaluation?**
</div>

I have just resolved the Java version error in my project, but it’s almost certain that I won’t be able to meet the peer review deadline. While I may miss the peer review, I wanted to know if there’s still a possibility for my submission to be considered for the final grade evaluation.


</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/28#issuecomment-2740624098" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I did! thank you
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 23. HUNG.. KIN `@randust` (2 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/11#issuecomment-2647604141" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

From my opinion, as we may have more than one exceptions, can be checked or unchecked, we can handle all exceptions by using throw at one place for more organized code. It also works if you print the error message directly.
</panel>

<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/24#issuecomment-2727935421" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I have also encountered this too. I tried to pass all local JUnit tests (make all arrows green locally![Image](https://github.com/user-attachments/assets/218245e8-e020-4e2a-8bb9-3bdf22927c3c)), and then it passed the gradle wrapper. I don't know why this is relevant, and not sure if this also works for your case.


</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 24. BRYA..ALIM `@gavalion` (1 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/38" expanded>
<div slot="header">

**1. :fas-info-circle: Requesting usage of com.drewnoakes:metadata-extractor:2.18.0**
</div>

## Library

[[Metadata Extractor](https://mvnrepository.com/artifact/com.drewnoakes/metadata-extractor)](https://mvnrepository.com/artifact/com.drewnoakes/metadata-extractor/2.18.0) 

## Purpose

``{``use to extract photo metadata to get date, latitude and altitude to get the location of the map which can calculate the distance between places``}``

## License

``{``https://github.com/drewnoakes/metadata-extractor/blob/main/LICENSE``}``

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 25. LIM .. FUN `@ljunfun` (1 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/14" expanded>
<div slot="header">

**1. :fas-info-circle: Week 6 Weekly quiz**
</div>

Hi, would like to ask if the weekly quiz for Week 6 is available for us to do? It has not shown up on canvas/other platforms till now. Thank you!

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 26. TAN ..SHIN `@Yshinprograms` (1 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/2" expanded>
<div slot="header">

**1. :fas-info-circle: Course website key exercises for week 2 does not correspond with coursemology exercises**
</div>

The key exercises on the course website lists Compare Names as the first exercise:
![Image](https://github.com/user-attachments/assets/265d0f7d-433d-4d1a-82f5-9e57062f3ba3)

Whereas Coursemology lists ByeWorld as the first exercise:
![Image](https://github.com/user-attachments/assets/eacf882e-d1b7-4712-9834-73c443f8d502)

Can I check if we should just follow the exercises on Coursemology?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 27. JAHA..DHAN `@mohammedhamdhan` (1 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/35" expanded>
<div slot="header">

**1. :fas-info-circle: Requesting use of XChart library**
</div>

## Library

XChart

https://github.com/knowm/XChart

## Purpose

The XChart library would be used to show the user data visualisation charts, based on their spending for the month, etc. This would make the application more user friendly.

## License

https://github.com/knowm/XChart/blob/develop/LICENSE
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 28. HOE .. HAO `@H-ZhanHao` (1 posts) 
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/48" expanded>
<div slot="header">

**1. :fas-info-circle: PE Bug Validity Inquiry**
</div>

Hello,

The issue at question is: #566

I would like some clarification regarding whether or not this specific bug classifies as a bug, since the input is a Disk Operating System command for the end of input, our program will throw an exception. I believe most, if not all, programs will inherit similar behaviour. 

Some clarification on whether or not this type of exception should have been handled by the developers would be appreciated. Thank you. 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 29. NG J.. LEE `@jessican1212` (1 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/12" expanded>
<div slot="header">

**1. :fas-info-circle: A-Exceptions tag on iP progress dashboard but not in Week 5 tasks**
</div>

Hello! I noticed that I have an uncompleted A-Exceptions tag on the iP progress dashboard. However, the iP tasks for Week 5 only include:
1. Learn from others (optional)
2. Add Increment as a branch: Level-5
3. Add Increment: A-Packages

Should we tag the same Level-5 commit as A-Exceptions? Or was this a mistake on the dashboard?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 30. SMIT..ISEN `@rozaliesmit` (1 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/nus-cs2113-AY2425S2/forum/issues/3" expanded>
<div slot="header">

**1. :fas-info-circle: Accidentally submitted too early**
</div>

I think my touchpad was not working properly or something but I couldn't click on to move on from the first question to the other questions and I accidentally submitted the entire thing while I was trying to get to the other exercises. Now it shows me that I've only done 1 out of 4 questions. Is there a way to reverse this? Or hand in the exercises some other way?

</panel>

</panel>
