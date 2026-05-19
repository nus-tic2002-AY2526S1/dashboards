%%[This page was last updated on May 07 2026]%% [**<span class="text-warning">:octicon-eye:</span> indicates those _watching_ the forum** (kudos :+1:)]


<panel type="info"  collapsed>
<div slot="header">

### 1. KOTH..ONAK `@SmeetRonak` (5 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/9" expanded>
<div slot="header">

**1. :fas-info-circle: unable to build a shadowJar in gradle**
</div>

# Error faced
I am trying to build a shadowJar using gradle, however, i keep getting errors. 

The main error that I think is that my system is not able to detect/install the plugin correctly, hence it keeps crashing my build. 

---

## My development environment
``` 
1. Java version: java 17.0.18 2026-01-20 LTS
2. Gradle language used: Kotlin
3. Gradle version: Gradle 9.0.0; kotlin: 2.2.0; groovy: 4.0.27
```

---

## My build.gradle.kts (current version)
```
import com.github.johnrengelman.gradle.plugins.shadow.tasks.ShadowJar

plugins ``{``
    java
    application
    id("com.github.johnrengelman.shadow") version "7.1.2"
``}``

group = "io.nus.chatbot"

java ``{``
    sourceCompatibility = JavaVersion.VERSION_17
    targetCompatibility = JavaVersion.VERSION_17
``}``

repositories ``{``
    mavenCentral()
``}``

dependencies ``{``
    testImplementation("org.junit.jupiter:junit-jupiter-api:5.10.1")
    testRuntimeOnly("org.junit.jupiter:junit-jupiter-engine:5.10.1")
    testImplementation("org.junit.platform:junit-platform-launcher:1.14.2")
``}``

application ``{``
    mainClass.set("chatbot.Friday")
``}``

tasks.test ``{``
    useJUnitPlatform()
``}``

tasks.named<JavaExec>("run") ``{``
    standardInput = System.`in`
``}``

tasks.named<ShadowJar>("shadowJar") ``{``
    archiveBaseName.set("friday")
    archiveClassifier.set("")
    archiveVersion.set("")

    manifest ``{``
        attributes("Main-Class" to "chatbot.Friday")
    ``}``
``}``
```

---

## Current errors
```
Unresolved reference 'johnrengelman'.
No type arguments expected for fun named(name: String!, configurationAction: Action<in Task!>!): TaskProvider<Task!>!.
Unresolved reference 'ShadowJar'.
Unresolved reference 'archiveBaseName'.
Unresolved reference 'archiveClassifier'.
Unresolved reference 'archiveVersion'.
Unresolved reference 'manifest'.
<html>None of the following candidates is applicable:<br/>fun Manifest.attributes(vararg attributes: Pair&lt;String, Any&gt;): Manifest:<br/>Unresolved reference. None of the following candidates is applicable because of a receiver type mismatch:<br/>fun Manifest.attributes(vararg attributes: Pair&lt;String, Any&gt;): Manifest<br/>fun Manifest.attributes(sectionName: String, vararg attributes: Pair&lt;String, Any&gt;): Manifest:<br/>Unresolved reference. None of the following candidates is applicable because of a receiver type mismatch:<br/>fun Manifest.attributes(sectionName: String, vararg attributes: Pair&lt;String, Any&gt;): Manifest
Typo: In word 'johnrengelman'
```
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/5" expanded>
<div slot="header">

**2. :fas-info-circle: query on branch deletion**
</div>


Do I delete branches on github after merging it into master? 

Context:
Github provides an option to delete branches after merging them into other branches. Normally, I would imagine that in such cases, only production branches would be kept open, and that all other minor branches are deleted after merging into one of the production branches.

<img width="1304" height="713" alt="Image" src="https://github.com/user-attachments/assets/59751576-babb-4355-a94f-9de5c5b59f7a" />
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/1#issuecomment-3798351977" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

> Hi would like to check. For the configuration of VScode code style advanced, it mentions: setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_switch" value="false" setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_cases" value="true"
> 
> Can I confirm that the first line means that my "case: " should not line up with my "switch" ? which is not the same standard as the one we are following?

Hi, if i am not mistaken, the first line means that the "case: " statements will not be indented relative to the switch statement (setting id="org.eclipse.jdt.core.formatter.indent_**switchstatements_compare_to_switch" value="false"**). The second line means that the line after the case statements will be indented with respect to the case statement (setting id="org.eclipse.jdt.core.formatter.indent_**switchstatements_compare_to_cases" value="true"**).

so the format should turn up something like the following:

```
switch (month) ``{``
case "Jan":
    System.out.println("January");
    break;
default:
``}``
```

This would be keeping in line with the coding standard that we are supposed to follow.
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/5#issuecomment-3909779242" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

Ok, thank you for pointing that out!
I missed that line on the page :)
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/9#issuecomment-4030163095" expanded>
<div slot="header">

**5 :fas-comment:**
</div>


This is for my iP. I tried building the shadowJar with gradle, but it is not able to recognize the plugin for some reason

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 2. MEHT..YESH `@veermehta270` (4 posts) 
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/4" expanded>
<div slot="header">

**1. :fas-info-circle: JavaDoc Comments**
</div>

For making JavaDoc Comments in my code, should I be commenting all the methods using the JavaDoc format or only the complicated methods ? 

Personally I think that simple methods like getters and setters do not require JavaDoc comments and we should only use JavaDoc comments for specifically complicated methods which the user may not understand by just looking at its name.

However the course website does say the 50% of the methods should have JavaDoc comments. So then should I just use JavaDoc comments for even simple methods?

<img width="1061" height="496" alt="Image" src="https://github.com/user-attachments/assets/10098db1-9f14-47d3-8aa3-97921644475e" />
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/3" expanded>
<div slot="header">

**2. :fas-info-circle: google-java-format plugin**
</div>

## Library

google-java-format 

## Purpose

Configure intellij idea to use google java coding standards automatically.

Gemini suggested this : 


Option 1: Using the google-java-format Plugin (Best)
This is the most authentic way to follow Google's standards. It replaces IntelliJ’s default formatter with the exact logic Google uses internally.

Press Ctrl + Alt + S (Windows/Linux) or Cmd + , (macOS) to open Settings.

Navigate to Plugins, search for "google-java-format" in the Marketplace, and install it.

Restart IntelliJ.

Go back to Settings > Editor > google-java-format Settings.

Check the box Enable google-java-format.

(Optional) Choose the "AOSP" style if you prefer 4-space indents (Android style) instead of the standard 2-space.

[!TIP] This plugin ignores many of IntelliJ's manual wrapping checkboxes because it uses a deterministic algorithm. If you want "Format on Save," go to Settings > Tools > Actions on Save and check Reformat code.

Option 2: Importing the Official XML Scheme
If you want to keep using IntelliJ's built-in formatter but with Google’s rules:

Download the XML: Get the [intellij-java-google-style.xml](https://www.google.com/search?q=%5Bhttps://github.com/google/styleguide/blob/gh-pages/intellij-java-google-style.xml%5D(https://github.com/google/styleguide/blob/gh-pages/intellij-java-google-style.xml)) from Google’s GitHub repository.

Import to IntelliJ:

Go to Settings > Editor > Code Style > Java.

Click the Gear icon (⚙️) next to the "Scheme" dropdown.

Select Import Scheme > IntelliJ IDEA code style XML.

Select the file you just downloaded and name it "GoogleStyle".
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/2" expanded>
<div slot="header">

**3. :fas-info-circle: Using ArrayList**
</div>

## Library

ArrayList

## Purpose

To store data, arrayList is more flexible that the basic array functionality.
## License
It is a basic java library

</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/5#issuecomment-3895305168" expanded>
<div slot="header">

**4 :fas-comment:**
</div>

I think normally when building projects we should delete branches which are already merged and we are sure that we will not be needing them. However for the course I think they are tracking our branch names and the tags in order to check that we are accurately following the instructions given on the course website, so I think we need to keep the branches which are specifically mentioned about in the course website and choose to keep or delete the other ones. 

<img width="1280" height="403" alt="Image" src="https://github.com/user-attachments/assets/1c8b551c-209b-4161-bb91-f0c2698009e0" />
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 3. TAN ..IVAN `@ivan-tan` (3 posts) 
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/12" expanded>
<div slot="header">

**1. :fas-info-circle: [PE] Unable to submit qn 8 due to empty student field**
</div>



Hi Prof, for question 8 (the functional code contributed by the person is...) on TEAMMATES, I am unable to submit my response as the question prompts to review 6 students while the group i am reviewing only has 5 students. do i just put a random student's name for the 6th student and answer as unable to judge? Thanks 

<img width="1226" height="251" alt="Image" src="https://github.com/user-attachments/assets/c988d158-7ae3-4f11-846c-536ddcdc3edb" />
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/12#issuecomment-4270095693" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

I am unable to find the option. Attached is a screenshot of my teammate page with the names omitted,

<img width="742" height="926" alt="Image" src="https://github.com/user-attachments/assets/7cfd37ce-2c22-4965-8fea-5d26dff5da12" />
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/12#issuecomment-4270296721" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

resolved- I didnt uncheck the judge options and it didnt let me submit. this is actually a ui test for teammates 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 4. LIM ..THAN `@Kailer811` (3 posts) 
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/1#issuecomment-3798234395" expanded>
<div slot="header">

**1 :fas-comment:**
</div>

Hi would like to check. For the configuration of VScode code style advanced, it mentions:
 setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_switch" value="false"
 setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_cases" value="true"

Can I confirm that the first line means that my "case: " should not line up with my "switch" ?
which is not the same standard as the one we are following? 
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/1#issuecomment-3798590889" expanded>
<div slot="header">

**2 :fas-comment:**
</div>

> > Hi would like to check. For the configuration of VScode code style advanced, it mentions: setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_switch" value="false" setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_cases" value="true"
> > Can I confirm that the first line means that my "case: " should not line up with my "switch" ? which is not the same standard as the one we are following?
> 
> Hi, if i am not mistaken, the first line means that the "case: " statements will not be indented relative to the switch statement (setting id="org.eclipse.jdt.core.formatter.indent_**switchstatements_compare_to_switch" value="false"**). The second line means that the line after the case statements will be indented with respect to the case statement (setting id="org.eclipse.jdt.core.formatter.indent_**switchstatements_compare_to_cases" value="true"**).
> 
> so the format should turn up something like the following:
> 
> '''
> switch (month) ``{``
> case "Jan":
>     System.out.println("January");
>     break;
> default:
> ``}``
> '''
> 
> This would be keeping in line with the coding standard that we are supposed to follow.

I cant format the code here...but basically my cases and defaults are in line w each other but not with switch.
I know the script is working cause when I save my file, it formats everything, with most appearing to be following the coding standard except for the switch cases.


</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/1#issuecomment-3799108615" expanded>
<div slot="header">

**3 :fas-comment:**
</div>

Hi, have solved the issue. VSCode was not actually using the eclipse.xml as applying it thru settings points it at the wrong directory.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 5. LEE .. NGA `@eugenia-cnl-lee` (2 posts) 
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/11" expanded>
<div slot="header">

**1. :fas-info-circle: Tutorial on 2nd April NUS WellBeing Day?**
</div>

If our tutorial is on the 2nd April NUS Wellbeing Day, is it still ongoing or will it be cancelled?
</panel>

<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/10" expanded>
<div slot="header">

**2. :fas-info-circle: Dashboard for tutorial participation/attendance mark?**
</div>

Is there somewhere where we can view our Tutorial participation and/or attendance mark?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 6. CHUA..IANG `@chuayongliang6` (1 posts) <span class=text-warning>:octicon-eye:</span>
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/7" expanded>
<div slot="header">

**1. :fas-info-circle: Missing Git Standard tag in iP dashboard**
</div>

In the iP instructions for week 7, it is mentioned that there is a Git Standard tag on the iP dashboard and check that we fulfill the tag before finalising, as per the screenshot. 

![Image](https://github.com/user-attachments/assets/76289f7d-93d6-4364-ac6e-a4deaa630f5c)

However I am unable to find it on the dashboard. May I check if there is supposed to be a Git Standard tag? Thank you!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 7. TAN ..YUAN `@Yengfuan` (1 posts) 
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/8" expanded>
<div slot="header">

**1. :fas-info-circle: Request to help with smoke testing JAR file**
</div>

* Link to JAR file: https://github.com/Yengfuan/ip/releases/tag/A-Release
* Which OS'es to test on: Mac | Linux
* Things to check specifically: Mainly cross-platform compatibility and Java version compatibility. Feel free to play around with the JAR too!


Guide for testers:
* Post screenshots from your smoke tests
* Mention which OS you used for testing


</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 8. HUAN..GRUI `@cigaho` (1 posts) 
</div>


<panel  popup-url="https://github.com/NUS-CS2113-AY2526-S2/forum/issues/6" expanded>
<div slot="header">

**1. :fas-info-circle: Using GSON for storing data in json**
</div>

## Library

[Gson]
(com.google.code.gson:gson)

## Purpose

To implement the data persistence layer (Storageclass) for our FlashCLI application. It will be used to serialize our core data objects (DeckManager, Deck, Card) into JSON format for saving to a file, and to deserialize the JSON data back into objects when the application loads. This provides a clean, reliable, and human-readable way to save the user's flashcard decks

## License

Gson is released under the Apache License 2.0, a permissive open-source license compatible with this academic project.

</panel>

</panel>
