%%[This page was last updated on ==2025-05-03 @12:20==]%%


<panel type="info"  collapsed>
<div slot="header">

### 1. NEER..MBAR `@flyingapricot` (**73** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/30#discussion_r1976406572" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of hashmap to store rank
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/30#discussion_r1976406631" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good descriptive comments
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/30#discussion_r1976406672" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good to import hashmap first
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/30#discussion_r1976406721" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of enum to store suits
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976463066" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Instead of using the integer 8, maybe you could consider defining it as a constant?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976463263" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Likewise here, you could consider using a variable for the blind score instead of using a magic number

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976464487" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Likewise here, you could consider using a variable for the expected length of cardIndices instead of using a magic number

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976464554" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Likewise here, you could consider storing the maximum plays in a variable instead of storing in a magic number
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976698043" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

When I checked your workflow on your forked repo, the test step is not running successfully because youre defining objects that do not exist yet (e.g. Deck, UI). It would be better if you commented those out for the workflow to run completely.

![image](https://github.com/user-attachments/assets/71bb9d73-a455-40cb-bcbe-d779c1ee9b11)


Below is the log that shows which parts caused the error:
/home/runner/work/tp/tp/src/main/java/Javatro/Round.java:16: error: cannot find symbol
> Task :compileJava FAILED
    private Deck deck;
            &hat;
  symbol:   class Deck
  location: class Round
/home/runner/work/tp/tp/src/main/java/Javatro/Round.java:18: error: cannot find symbol
    private HoldingHand playerHand;
            &hat;
  symbol:   class HoldingHand
  location: class Round
/home/runner/work/tp/tp/src/main/java/Javatro/Round.java:19: error: cannot find symbol
    private State gameState;
            &hat;
  symbol:   class State
  location: class Round
/home/runner/work/tp/tp/src/main/java/Javatro/Round.java:20: error: cannot find symbol
    private UI ui;
            &hat;
  symbol:   class UI
  location: class Round
/home/runner/work/tp/tp/src/main/java/Javatro/Round.java:[28](https://github.com/K-J-Q/tp/actions/runs/13616603423/job/38060524873#step:6:29): error: cannot find symbol
    public Round(State gameState) ``{``
                 &hat;
  symbol:   class State
  location: class Round
/home/runner/work/tp/tp/src/main/java/Javatro/Round.java:36: error: cannot find symbol
        this.playerHand = new HoldingHand();
                              &hat;
  symbol:   class HoldingHand
  location: class Round
/home/runner/work/tp/tp/src/main/java/Javatro/Round.java:[37](https://github.com/K-J-Q/tp/actions/runs/13616603423/job/38060524873#step:6:38): error: cannot find symbol
        this.ui = new UI();
                      &hat;
  symbol:   class UI
  location: class Round
7 errors


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/30#discussion_r1976706759" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

IllegalArgumentException is not handled
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1979351109" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

alright sure, let us hold off until the remaning classes have been created.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/52#discussion_r1985276401" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great use of javadocs, helps explain the function well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/52#discussion_r1985277078" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Exception is not handled here, try this:
public static PokerHand evaluateHand(List&lt;Card> cards throws IllegalArgumentException
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985297383" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Use the javadocs format to declare javadocs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985304449" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

UI should not be done within the logic, you can consider throwing a custom exception.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985305490" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

UI should not be done within the logic, you can consider throwing a custom exception.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985309142" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

might want to consider making this private, as well as add getters and setters to retreive the hand info
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985313232" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you might want to consider using a stack structure over here since the deck behaves like a stack (eventually)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/52#discussion_r1985316374" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you can just return new PokerHand(HIGH_CARD) instead of putting in the else
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/52#discussion_r1985331524" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Does PokerHand refer to my current hand or the result of poker hand? If it refers to the result of poker hand, what does HandResult do?

Could consider a rename
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/60#discussion_r1990373660" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Yep, I will be working on that part
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/60#discussion_r1990374335" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I will move the instantiation of Ui class to be within the controller instead, since the game logic should not handle the Ui.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/60#discussion_r1990640291" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Use a code block for multiple lines of print output.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/60#discussion_r1990643161" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Use %s as the printf String specifier in the text string being formatted. It prevents multiple strings from being instantiated.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/63#discussion_r1996715164" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

should be done within the UI class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/63#discussion_r1996715339" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great use of javadocs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/63#discussion_r1996716926" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

this exception is not handled
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/68#discussion_r2000877473" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

There has already been a deck class defined
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/68#discussion_r2000892504" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You could move this to the OptionScreen.java where this can be displayed for users on how to play the game.

You could consider building a new HelpScreen.java in a subsequent iteration to provide a detailed help guide.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/75#discussion_r2008684587" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

No star imports should be used
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/79#discussion_r2009143602" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

add the assert
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/86#discussion_r2011178956" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should remove this commented code if it is no longer in use
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/86#discussion_r2011180432" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

does this have to be public
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/86#discussion_r2011181242" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Do not use star imports
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/88#discussion_r2013414973" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Why only 26 cards
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017840323" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you might want to consider splitting this into different functions and calling them inside display screen.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017842153" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You should create the Ante object ( public static Ante ante;)  in JavatroCore instead of inside the manager.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017842753" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You might want to consider defining anteCount as a static.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017843582" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Greate use of copy constructor
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018098396" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Javatro Manager does not handle a complete game - rather it listens to UI events and triggers changes. It should not own any game related logic (including ante)

JavatroCore is the model, it manages game logic and data, including round management and internal game states like the ante. Therfore JavatroCore owns the round logic as well.

Storing ante in JavatroManager breaks the separation of concerns by giving game state responsibility to the manager that is acting as the controller. For that reason, you have to have the ante object within JavatroCore itself.

Additionally, @jwyk and @K-J-Q require JavatroCore to be a centralised place to manage the ante and rounds played.


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018105545" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

To resolve this: 

```
so a new ante will be create each time a new round is created which is not what we need.
```

You can pass the ante into the constructor of JavatroCore, initalise it once when the core is created and persist it as a field inside JavatroCore.

It is true that JavatroCore spins new rounds but with this approach, the rounds can reuse the same ante object or value, thus that way you can initalise the ante once per game inside JavatroCore and reuse it across multiple rounds.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018106020" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I have commented on this in the comment below.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018107282" expanded>
<div slot="header">

**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

```
public static int roundCount = 1;
```
should also be moved to JavatroCore and both of them (ante and roundCount) should be declared as a protected variable.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/102#discussion_r2019681767" expanded>
<div slot="header">

**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will be referencing this to update the deck based on information from the save file
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/102#discussion_r2019683991" expanded>
<div slot="header">

**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would require a function that is able to instantiate a particular Joker based on an enum (similar to what you have done in Deck), probably might need you to create a JokerType Enum (Like what you have done for DeckType).


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/102#discussion_r2019684334" expanded>
<div slot="header">

**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

SaveFile can store string values of the Jokers present with player's hand. When the saved run is loaded, the heldJokers is instantiated with the same set of jokers that was saved, for this might require an enum of Jokers, like something you have done in the Deck Class. 

You can see my [previous comment](https://github.com/AY2425S2-CS2113-W13-1/tp/pull/102/files#r2019687215) where I I made a function to load a deck based on a given string using the Deck Enum.

I want to do something like this for the Jokers as well.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/102#discussion_r2019685975" expanded>
<div slot="header">

**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will only be able to add the Deck Saving/Loading after this is merged

![](https://media.tenor.com/ICPLJ_e8OQcAAAAM/bye-obama.gif)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/102#discussion_r2019686550" expanded>
<div slot="header">

**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

shag

![](https://i.makeagif.com/media/3-09-2021/YYrqBc.gif)

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/102#discussion_r2019687215" expanded>
<div slot="header">

**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Using this, I am able to create a deck based on a string value:

```
    private void Deck createDeckFromString(String deckTypeString) ``{``
        DeckType deckType;
        try ``{``
            // Convert the string to the corresponding DeckType enum
            deckType = DeckType.valueOf(deckTypeString); 
        ``}`` catch (IllegalArgumentException e) ``{``
            // Handle the case where the string doesn't match a valid DeckType
            deckType = DeckType.DEFAULT;  // Defaulting to "DEFAULT" Decktype
        ``}``

        // Return a new Deck initialized with the valid DeckType
        return new Deck(deckType);
    ``}``
    
```
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2019696880" expanded>
<div slot="header">

**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Alright, nice
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020074196" expanded>
<div slot="header">

**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should delete this if it is no longer in use
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/118#discussion_r2020147442" expanded>
<div slot="header">

**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice, great job finding the bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020177467" expanded>
<div slot="header">

**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Exception is not handled here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020184125" expanded>
<div slot="header">

**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Oh, I meant the IllegalArguementException, you throw it here and its not handled, you could either handle it within this function or get the function to throw it (public void setPlayerHandCards(List&lt;Card> playerHandCards throws IllegalArguementException)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/125#discussion_r2020200290" expanded>
<div slot="header">

**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Delete these comments if not needed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/125#discussion_r2020200332" expanded>
<div slot="header">

**56 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Delete these comments if not needed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/126#discussion_r2020204750" expanded>
<div slot="header">

**57 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of constants
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/129#discussion_r2020624591" expanded>
<div slot="header">

**58 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Just need to fill this part too
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/138#discussion_r2024271287" expanded>
<div slot="header">

**59 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good note
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/138#discussion_r2024273370" expanded>
<div slot="header">

**60 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Round, Ante Component should be a subsection under the model component and not their own section, but this one can be done later
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/138#discussion_r2024275214" expanded>
<div slot="header">

**61 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should be a subsection under the model component not its own section but can be handled in the next PR
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024276559" expanded>
<div slot="header">

**62 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Round, Ante Component should be a subsection under the model component and not their own section, but this one can be done later
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024278649" expanded>
<div slot="header">

**63 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Here as well you might want to put the code in the ''' tags
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/139#discussion_r2024800883" expanded>
<div slot="header">

**64 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should move score to a subsection under the model component, it can be done in the next PR.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2025073877" expanded>
<div slot="header">

**65 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Alright nice
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/211#discussion_r2030054016" expanded>
<div slot="header">

**66 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will update the storage
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/211#discussion_r2030054419" expanded>
<div slot="header">

**67 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Table is not aligned here it may not load up on the website

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/211#discussion_r2030054577" expanded>
<div slot="header">

**68 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will adjust this since this has changed in after the storage
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/211#discussion_r2030054681" expanded>
<div slot="header">

**69 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will update this since this has changed after the storage
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/210#discussion_r2030402941" expanded>
<div slot="header">

**70 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Sequence diagram may not work on the website, you need to take a screenshot and upload instead
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/210#discussion_r2030403153" expanded>
<div slot="header">

**71 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this to setup the mermaid?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/217#discussion_r2031010184" expanded>
<div slot="header">

**72 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

ur table might break but you can test and see
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/220#discussion_r2031673519" expanded>
<div slot="header">

**73 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Theres an extra @ here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980701482" expanded>
<div slot="header">

**74 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Yep, need to do for all the methods
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980701865" expanded>
<div slot="header">

**75 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Will create a constant CLEARSCREEN for \033[H\033[2J
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980703250" expanded>
<div slot="header">

**76 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

This number indicates the maximum value of score allowed before it is truncated.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980703481" expanded>
<div slot="header">

**77 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Likewise 10-99999 indicates the range of score allowed before it is truncated.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997958479" expanded>
<div slot="header">

**78 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

@swethacool 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997958701" expanded>
<div slot="header">

**79 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

@swethacool 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997959333" expanded>
<div slot="header">

**80 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Alright sure, will add this in the next PR
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997959670" expanded>
<div slot="header">

**81 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Will add this in the next PR since I'm cleaning up the class in the next PR
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030229462" expanded>
<div slot="header">

**82 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I think we need to just credit the original owners? I will do this also.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030229533" expanded>
<div slot="header">

**83 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Alright, will fix this in next PR.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030229537" expanded>
<div slot="header">

**84 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Alright, will fix this in next PR.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030229615" expanded>
<div slot="header">

**85 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Alright, will fix this in next PR.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/36#issuecomment-2692319125" expanded>
<div slot="header">

**86 :octicon-comment:** %%(other comment)%%
</div>

Failing the test because the script cannot find the forked repo branch, closing this request for now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/37#issuecomment-2692324133" expanded>
<div slot="header">

**87 :octicon-comment:** %%(other comment)%%
</div>

Works now, but the Lint,Test and Build are being run on the master repo, which is not what we want, we want these checks to run on the forked repo and display the outcome here, closing again for now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/38#issuecomment-2692329060" expanded>
<div slot="header">

**88 :octicon-comment:** %%(other comment)%%
</div>

Checks still running within the master repo and the formatter is not working now, closing for now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/39#issuecomment-2692330651" expanded>
<div slot="header">

**89 :octicon-comment:** %%(other comment)%%
</div>

Tests do not run now, closing for now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#issuecomment-2692335042" expanded>
<div slot="header">

**90 :octicon-comment:** %%(other comment)%%
</div>

> > Could you also include some Junit tests for your class? You can follow @Markneoneo’s previous PR for an idea of what tests to include
> 
> For tests, we would have to wait for the classes `Deck` and `Holding Hand` to be created. Should I submit a PR after they have been created instead?

okok nope thats cool, you could make a seperate PR for the tests later on.

Before this gets approved, could you pull in your branch again to update the CI/CD script?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/42#issuecomment-2692343743" expanded>
<div slot="header">

**91 :octicon-comment:** %%(other comment)%%
</div>

Created the CICD setup with automated formatting, linting, testing and building
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/43#issuecomment-2692343858" expanded>
<div slot="header">

**92 :octicon-comment:** %%(other comment)%%
</div>

Added the CI/CD Status on README
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/44#issuecomment-2692344022" expanded>
<div slot="header">

**93 :octicon-comment:** %%(other comment)%%
</div>

Fixed checkout issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/41#issuecomment-2692344122" expanded>
<div slot="header">

**94 :octicon-comment:** %%(other comment)%%
</div>

Feature has been completed, CICD pipeline is now setup and works
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/101#issuecomment-2780141095" expanded>
<div slot="header">

**95 :octicon-comment:** %%(other comment)%%
</div>

This is not being used anymore, moved over to JavatroStorage branch, closing this PR.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#issuecomment-2781559172" expanded>
<div slot="header">

**96 :octicon-comment:** %%(other comment)%%
</div>

Will clarify the sources for the audio
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/104#issuecomment-2781880638" expanded>
<div slot="header">

**97 :octicon-comment:** %%(other comment)%%
</div>

Shifted to a new PR
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 2. JOHN.. KAI `@jwyk` (**55** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/28#discussion_r1975757225" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/29#discussion_r1975783209" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/40#discussion_r1976461404" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good renaming to be more clear
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/40#discussion_r1976461446" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good to indicate that no changes have been made
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976464692" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would be better to change the magic literal 3 to something like playLimit.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/60#discussion_r1989357432" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Change to "Your cards after discard: "
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/60#discussion_r1989360014" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would be better phrased as "Discards Remaining: "
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/60#discussion_r1989367570" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For now it should be okay, but as the number of ui functions increases i think there could be a better way of grouping the ui functions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997942768" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Better to make these a constant so you don't have to constantly refer to them 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997942990" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

See above comment
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997945648" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Might be better to just throw an error here and add the exception to JavatroException
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997946799" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would be much better to have case statements here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/69#discussion_r1997947958" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Better to state out what this color is in a constant.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/71#discussion_r2000295655" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Tests look good and well thought out. We can add Javadocs for future documentation later, but for now the testing looks robust enough.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/68#discussion_r2001036964" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This should be the holdingHand class to just see your current hand. See #46.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/68#discussion_r2001040052" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I'm guessing this is supposed to be the 8 hands held every round? This has been implemented under #46.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/68#discussion_r2001041667" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Wasn't this was already done under #53?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/68#discussion_r2001065729" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For score, you can just pull from @K-J-Q's Round class instead of instantiating it in the Command Class. See #35 for the skeleton code, and #63 for further changes.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/68#discussion_r2001087472" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This is okay. A better way of printing the Card Object out would be to use  `Card.getSimplified()`.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/85#discussion_r2010482536" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of assertion here.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014171455" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

There is a slight chance the cards randomly selected for the test here will pass the blind score
- Consider a Straight Flush of any kind. The minimum score added is 100 x 8 = 800, which will beat the base blind score of 300 for lvl 1 ante and small blind. Also consider high value Flushes like a hand of A, Q, 10, 8 and 7. 35(base) + 46 (card chip value) x 4 = 324 > 300.
- https://efhiii.github.io/balatro-calculator/ can be referenced and used if you need exact scoring logic for score calculations.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014194323" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This is okay for checking if cards played will never reach the score, but you should use high score blinds (like high antes levels, big and boss blinds) to test for round not winning.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014199968" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This should work for now until we eventually get "The Needle" boss blind type.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014200754" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of assertions here.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2016259784" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These 2 should be moved to JavatroCore and managed from there
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2016262490" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Ante Class structure is good.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2016267730" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The testing is good, but I think it would be better if you can test random blinds and their respective scores.

For instance Ante 8, Big Blind should result in a target score of 1.5 x 50,000 == 75,000.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2016284863" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This is okay for a skeleton and testing the blind logic, but later on we need to integrate @swethacool blind logic into this.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2016285498" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

See above comment.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2016290548" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

See above comment about integration.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2019829996" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good testing suite 👍 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020071651" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

👍
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020071869" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

If we are storing planet card displays in txt files, remember to release 2.0 in a zip file with those txt files.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020072014" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Okay with renaming CounterJoker to AbstractJoker. Will take note if ever questioned about the naming convention.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020072380" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should delete commented out code block.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020072579" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Refactoring for DeckSelectOption looks good 👍 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020072673" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020072871" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Remember to fix * import.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/105#discussion_r2020073085" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Fine with moving the Joker to WinRoundScreen.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/107#discussion_r2020073672" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/107#discussion_r2020076771" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For the recent PR, changes were made to the Round class to add them to UI displays.

### Additions
```
    public PokerHand playedHand;
    public List<Card> selectedCards;
```
`List<Card> playedCards` and `PokerHand result` should be updated respectively to store these values.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/107#discussion_r2020076844" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Okay with this.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/107#discussion_r2020076943" expanded>
<div slot="header">

**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020175286" expanded>
<div slot="header">

**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

👍 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020176881" expanded>
<div slot="header">

**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This ensures THE_PSYCHIC will work by forcing 5 cards to be selected? Okay with this implementation of it.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020177156" expanded>
<div slot="header">

**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These conditions LGTM 👍 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020177216" expanded>
<div slot="header">

**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good test suite
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020182889" expanded>
<div slot="header">

**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You should set state.remainingPlays to 1 here, not max hand size.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/133#discussion_r2023054287" expanded>
<div slot="header">

**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the ToC format, looks good to me.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024108982" expanded>
<div slot="header">

**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Code snippets can be enclosed in ''' tags.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024109956" expanded>
<div slot="header">

**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Probably don't need to add `private static final` to the parameters
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030205814" expanded>
<div slot="header">

**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

According to 2113 guidelines, I think it should be okay, don't see anything relating to use of music _so far_. As for copyright reasons, I think it's okay as far as we use this for educational purposes?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030206034" expanded>
<div slot="header">

**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Remove the star imports.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/214#discussion_r2030229539" expanded>
<div slot="header">

**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good fix and catch.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/210#discussion_r2030416479" expanded>
<div slot="header">

**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

He uses svg files to display some of the changes, which can also be displayed on a markdown file.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985336156" expanded>
<div slot="header">

**56 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved in latest commit
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985336489" expanded>
<div slot="header">

**57 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved in latest commit
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985337089" expanded>
<div slot="header">

**58 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved by changing parameter to cardsToDiscard
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985337650" expanded>
<div slot="header">

**59 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved by adding a add() method
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017188569" expanded>
<div slot="header">

**60 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved in latest commit.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017190989" expanded>
<div slot="header">

**61 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Changed implementation in the latest commit to use copy constructor and deep copying.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017199473" expanded>
<div slot="header">

**62 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Moved card variable declaration to `@BeforeAll` in tests in latest commit.

The holdingHand.add() was left intact because the positions of the cards are intentionally placed in that manner, and I need their positions to be exactly there.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017200118" expanded>
<div slot="header">

**63 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved in latest commit.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/209#discussion_r2030095819" expanded>
<div slot="header">

**64 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved in latest commit.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/62#issuecomment-2727230840" expanded>
<div slot="header">

**65 :octicon-comment:** %%(other comment)%%
</div>

Noted, will work on this. This bug also occurs for `discard(cardsToPlay, deck)` function due to the similar logic flow.

```
        for (int discard : cardsToDiscard) ``{``
            Hand.remove(discard);
        ``}``

        // Draw the same number of cards discarded
        for (int i = 0; i < cardsToDiscard.size(); i++) ``{``
            Card tempCard = deck.draw();
            Hand.add(tempCard);
        ``}``
```

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/124#issuecomment-2764613350" expanded>
<div slot="header">

**66 :octicon-comment:** %%(other comment)%%
</div>

The Needle should not allow 1 card only to be played, but rather allow only 1 _hand_ to be played. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/124#issuecomment-2764656961" expanded>
<div slot="header">

**67 :octicon-comment:** %%(other comment)%%
</div>

This bug came from when The Needle was previously using 1 card played only, which caused this to occur. This has been fixed in #119 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/128#issuecomment-2765331085" expanded>
<div slot="header">

**68 :octicon-comment:** %%(other comment)%%
</div>

Noted. 

This error occurs solely for the Abandoned Deck because it has 40 cards versus the standard 52 card deck (missing 12 face cards).
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/136#issuecomment-2769821703" expanded>
<div slot="header">

**69 :octicon-comment:** %%(other comment)%%
</div>

**Intended Behaviour**. The parser automatically picks up any illegal values and discards them using Arrays.stream. This results in only a clean `List<Card>` being returned. For _single entries_ that are illegal values, e.g. `-1`, the inputed parsed will be cleansed to an empty List, causing a `JavtroException` to be thrown later on for empty entries.


``` 
private static List<Integer> parseCardInput(String input, int maxCardsAvailable)
...
        List<Integer> userInput =
                Arrays.stream(input.split(","))
                        .map(String::trim)
                        .filter(s -&gt; !s.isEmpty())
                        .map(
                                numStr -&gt; ``{``
                                    try ``{``
                                        return Integer.parseInt(numStr);
                                    ``}`` catch (NumberFormatException e) ``{``
                                        return null; // Mark invalid entries as null
                                    ``}``
                                ``}``)
                        .filter(Objects::nonNull)
                        .filter(num -&gt; num >= 1 && num <= maxCardsAvailable)
                        .map(num -&gt; num - 1) // Convert to 0-based index
                        .distinct()
                        .collect(Collectors.toList());
...
```
### Many Entries with Illegal Inputs
![Image](https://github.com/user-attachments/assets/7250dd63-0486-499c-97b9-04f70cf0c3d1)

### One Illegal Entry Input
![Image](https://github.com/user-attachments/assets/234fc570-54eb-4146-a23c-836f575f4e26)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/149#issuecomment-2778958743" expanded>
<div slot="header">

**70 :octicon-comment:** %%(other comment)%%
</div>

### Update

![Image](https://github.com/user-attachments/assets/716d7c6f-bd41-4425-8c7e-980f91f5f69e)

This error possibly happens due to _FLUSH_ hands played, but more testing is needed for the root cause.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/149#issuecomment-2778993655" expanded>
<div slot="header">

**71 :octicon-comment:** %%(other comment)%%
</div>

### Update

The cause of the bug is due to `ROYAL_FLUSH` being included inside the `PokerHand`, but not inside `PlanetCard`. 

Consequently when you try to generate a PlanetCard, there is a 1 in 13 chance of getting a `PokerHand` type `ROYAL_FLUSH`, which doesn't exist as a PlanetCard. Thus, you get a `NullPointerException` since `PlanetCard.getForHand()` will return null.

This will be fixed in 2.1.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/177#issuecomment-2781290672" expanded>
<div slot="header">

**72 :octicon-comment:** %%(other comment)%%
</div>

Not really relevant because it's part of a step by step process.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 3. CHAR..NDRA `@Charly2312` (**49** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/26#discussion_r1997500156" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe we can add a goodbye from the bot later, to ensure it really ends
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/26#discussion_r1997500559" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For now, I think this will be sufficient given our error handling cases now. May add assertThrows in the future.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/29#discussion_r1997636055" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

try to be specific in variable naming for a better flow and readability
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/29#discussion_r1997636505" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

maybe can add "_TEMPLATE" also
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/31#discussion_r1997668720" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good use of parameterized test
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/31#discussion_r1997669730" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you can use the helper function instead:

private void somename() ``{``
        List&lt;Expense> expenses = List.of(
            new Expense("eat", 10.0, "food"),
            new Expense("mrt", 2.30, "transport"),
            new Expense("dinner", 15.90, "food")
        );
        expenses.forEach(ExpenseManager::addExpense);
    ``}``
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1998190572" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

can follow our usual style "..._TEMPLATE"
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/58#discussion_r2017855479" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Looks good. Thanks for editing
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/57#discussion_r2017959957" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good use of hashmap
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/57#discussion_r2017960905" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice! very specific error handling
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/57#discussion_r2017962424" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

thanks for making it to be more specific
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/57#discussion_r2017963597" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for refactoring the code!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/63#discussion_r2019744688" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

thanks for making it more specific!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/63#discussion_r2019744966" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

doesnt this also return true for an integer?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2020214493" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good use of Hash map!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2020214693" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good inputs for testing the functions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/71#discussion_r2020215624" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good test cases for testing utils function!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/71#discussion_r2020215763" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

very detailed test cases for add command!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/74#discussion_r2021468303" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

thanks for refactoring the code and making it has less coupling 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/74#discussion_r2021478245" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

thanks for making the condition to check if the date has the same month and day
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/76#discussion_r2021523448" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good job in separating it into another class to make it more readable and neat
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/76#discussion_r2021527014" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice idea for separating our code to execute any command into another class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/76#discussion_r2021529540" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

thank you for remembering to update the test files
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/76#discussion_r2021530582" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

very detailed test cases! Thank you!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/78#discussion_r2022201772" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good exception handling if the date is empty
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/78#discussion_r2022202317" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

i think this will make the "input date" into a category instead. can try to check, thanks
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/78#discussion_r2022203631" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for helping to save the data into a .txt file
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/77#discussion_r2022213800" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

are we changing to [/d DESCRIPTION] or just [DESCRIPTION]? i might be wrong but I thought it was supposed to be /d[DESCRIPTION]
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/77#discussion_r2022215047" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good idea of using boolean variable to differentiate normal and recurring expenses
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/91#discussion_r2024063666" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good job on settling the budget feature!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/91#discussion_r2024064876" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice error handling
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/91#discussion_r2024065382" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

detailed test cases
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/98#discussion_r2026714550" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

looks good but may need to decrease it to 30 lines in the future
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/99#discussion_r2026723129" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good test!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/99#discussion_r2026725879" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good test case!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/100#discussion_r2026875717" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good way to separate them into smaller functions!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/103#discussion_r2027008203" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

what is this for?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/119#discussion_r2028041652" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this a duplicate?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/119#discussion_r2028042737" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Oh for checkstyle error
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/172#discussion_r2029287000" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

overall good test cases! Thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/174#discussion_r2029742510" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

looks good to use HashMap
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/178#discussion_r2029828400" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

yup didnt see this in the ug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/188#discussion_r2029948037" expanded>
<div slot="header">

**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you missed out on "average-recurring"
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/188#discussion_r2029948239" expanded>
<div slot="header">

**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

wait so is it list-sort or list-sorted now?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/188#discussion_r2029948303" expanded>
<div slot="header">

**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

then this should be list-sort?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/202#discussion_r2030216953" expanded>
<div slot="header">

**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good in ensuring that a recurring expense is added monthly
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/202#discussion_r2030217069" expanded>
<div slot="header">

**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job in making sure it follows SRP
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/221#discussion_r2031633312" expanded>
<div slot="header">

**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

maybe you can put a note for the XYZ placeholder
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/221#discussion_r2031634878" expanded>
<div slot="header">

**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice, an extra explanation here helps to reiterate what the placeholder is 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1996982809" expanded>
<div slot="header">

**50 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Has changed it into a helper function called constantExpenses()
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1997509879" expanded>
<div slot="header">

**51 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Has changed it into a helper function called constantExpenses()
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/25#discussion_r1997635475" expanded>
<div slot="header">

**52 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

noted. will improve from here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/25#discussion_r1997635568" expanded>
<div slot="header">

**53 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

okay can, will take  note. thank you
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1997670382" expanded>
<div slot="header">

**54 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

will change the name on the other branch. Thanks for reminding!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/56#discussion_r2016782222" expanded>
<div slot="header">

**55 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

done. Thank you
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019834575" expanded>
<div slot="header">

**56 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

okay I will update them accordingly
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019834853" expanded>
<div slot="header">

**57 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

sure will take note. Thank you
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019835088" expanded>
<div slot="header">

**58 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

sure if time permits
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019835250" expanded>
<div slot="header">

**59 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

i was thinking of insertin a recurring expense into the general expense list and hence, the name. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019835360" expanded>
<div slot="header">

**60 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

is it really necessary though?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2020060205" expanded>
<div slot="header">

**61 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Okay I will update it accordingly 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2020060214" expanded>
<div slot="header">

**62 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Noted. Thank you
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/101#discussion_r2026933498" expanded>
<div slot="header">

**63 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

okay will try it now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/101#discussion_r2026948499" expanded>
<div slot="header">

**64 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

did it in the next PR
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/173#discussion_r2029746642" expanded>
<div slot="header">

**65 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok thats true removing it now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/190#discussion_r2029950146" expanded>
<div slot="header">

**66 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

oh ya will change it now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/196#discussion_r2030163511" expanded>
<div slot="header">

**67 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

it was cos i reverted a PR, but it should be okay now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/207#discussion_r2030663436" expanded>
<div slot="header">

**68 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

yup i have done it. Thanks!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 4. EDWA..KITO `@edwardrl101` (**45** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/19#discussion_r1995747086" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

my bad for the naming, thanks for fixing it
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/19#discussion_r1995777073" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe we can make an ERROR_CALCULATING_MESSAGE_TEMPLATE to be used for multiple methods?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/19#discussion_r1995778015" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Similarly for this one, maybe something DISPLAY_EXPENSE_MESSAGE_TEMPLATE?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/19#discussion_r1995778781" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for fixing this to adhere to the coding standard
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/19#discussion_r1995794120" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Personally I like this new class. It makes it easier to deal with errors and printing error messages this way.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1997640278" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Names of methods should be verbs, and this name is not very intuitive. Perhaps consider something like initializeSampleExpenses1()?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1997640721" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Alternatively maybe you can use the code in the method here to initialize the expenses and perform operations for each of the expenses for your tests.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/31#discussion_r1997669041" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe you can have a method to initialize each sample input, such as initializeSampleExpenses1?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/31#discussion_r1997669258" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice variation of the input string, similarly for the rest below
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/31#discussion_r1997669317" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe you can add 2-3 more sample expenses?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/41#discussion_r2006368060" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice error handling for whitespaces
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/41#discussion_r2006368988" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Yes, I agree that you should change the naming of the constant for line 14 or line 15 for consistency
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/41#discussion_r2006369845" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of ParameterizedTest
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/48#discussion_r2007095837" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good spot. Thanks for the error handling
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/12#discussion_r2008835292" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You're right. We will change it accordingly. Thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/56#discussion_r2016752671" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think there is a typo, should be "would like to".
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/56#discussion_r2016755335" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Okay, I think the user profile is good.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/56#discussion_r2016755809" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Value proposition is also good for now. Thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019831798" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe a more intuitive name would work here? like getRecurringExpenseSize()?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019831950" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Similarly, maybe a better name can be used for this method, such as processRecurringExpense()?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019832787" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should this return an error when `description` is empty?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019832904" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think you might want to use a more informative variable name than `segments`, perhaps `expenseAmountAndDate`?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019833178" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You might want to handle the error if `parts.length &lt; 2`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019833314" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You might want to handle the error if `segments.length &lt; 2`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019833450" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great job for this command, just a few changes to be made. Perhaps in the future we might tweak it such that we can add a recurring expense for each week, instead of just months.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019833760" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

perhaps `insertRecurringExpense` would be a better method name?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019833867" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Might want to extract this out as a constant `SMALLEST_VALID_INDEX`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2019834176" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job for this method!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/100#discussion_r2026976106" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for adding an example!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/173#discussion_r2029717254" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Alright, thanks for deleting the redundant classes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/173#discussion_r2029733107" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe you might want to remove this since this test is a duplicate of the test in lines 64-79?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/173#discussion_r2029733592" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Make sure to give this test a better method name, i.e. `testSortCommandInvalidSortDirection`.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/173#discussion_r2029740940" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job on removing all instances of the deleted class and replacing it with the main DeleteCommand class.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/173#discussion_r2029777877" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think the method name is meant to be

`testSortCommand_emptySortFieldOrDirection_fail`?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/188#discussion_r2030061793" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think it should be list-sort
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/188#discussion_r2030062228" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice addition of example. I think this will be greatly beneficial for the user. Thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/196#discussion_r2030163405" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Looks like it is fixed now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/196#discussion_r2030163803" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Okay, thanks for adding glossary items.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/203#discussion_r2030229290" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good spot on the typo!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/207#discussion_r2030620251" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job on creating this Command Class diagram. However, you might want to remove the attributes like what we agreed on, and to ensure consistency between diagrams?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/207#discussion_r2030669567" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Alright, thanks for rectifying this!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/219#discussion_r2031438259" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for adding this command! I think this would really help users by seeing their current monthly budget and how much they have left.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/224#discussion_r2031895482" expanded>
<div slot="header">

**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great job on adding this explanation for the Command class!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/224#discussion_r2031897073" expanded>
<div slot="header">

**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for adding the UML sequence diagram and execution flows for the rest of the commands!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/231#discussion_r2032274699" expanded>
<div slot="header">

**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good spot on this bug. Thanks for fixing it!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/17#discussion_r1995742440" expanded>
<div slot="header">

**46 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I think you're right, will change that accordingly
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1997933824" expanded>
<div slot="header">

**47 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Will do so, thank you for reminding.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1997933983" expanded>
<div slot="header">

**48 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Not really, I think I should remove it for now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1997940183" expanded>
<div slot="header">

**49 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Thanks for the input, i have changed it accordingly and added 2 more test cases. For now, I also only allow the Expense class to be initialized with positive amounts so 0.0 is not allowed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1998199639" expanded>
<div slot="header">

**50 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Ok, I rectified it
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/58#discussion_r2017856304" expanded>
<div slot="header">

**51 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Okay. Thanks for the input
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/78#discussion_r2022309069" expanded>
<div slot="header">

**52 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Okay, will check on this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/178#discussion_r2029845357" expanded>
<div slot="header">

**53 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Not yet, thanks for reminding me. Will add this to the UG.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/178#discussion_r2029859532" expanded>
<div slot="header">

**54 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Not yet, currently, the user can set the date to any date they want to for the recurring expense.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/221#discussion_r2031672749" expanded>
<div slot="header">

**55 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I was thinking of doing that, but I already put an extra note at the bottom of the diagram. I will think about your suggestion, thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/173#issuecomment-2780228237" expanded>
<div slot="header">

**56 :octicon-comment:** %%(other comment)%%
</div>

> 1. edit sort test to include recurring expenses as well
> 2. edit deleteRecurring tests since deleteRecurring class is removed.
> 3. deleted depreciating deleteRecurring and ListRecurring command classes

Please be consistent in the usage of past and present tense, for commit messages also
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 5. LEE ..SHUA `@b1inmeister` (**44** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/65#discussion_r1993294326" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These initializations are causing the GitHub checks to fail. I would suggest to create dummy .java files for these new classes, so that the checks can pass and we can merge with no issues.  As an alternative, you also can comment out this part instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/65#discussion_r1993309417" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

It will be nice if you can break down the input into the command itself and the other information. If not, I can split it up in the CommandParser class too. Up to you.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/66#discussion_r1993324241" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Gradle does not like this line. I think can just comment it out.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/66#discussion_r1993328633" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Since Product class contains the name already, I think we can try using ArrayList? Just a suggestion for whoever is implementing the InventoryManager class. We can stick to HashMap for now.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/66#discussion_r1993331024" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

What happened to Manager? lol
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/66#discussion_r1993338428" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

We may need to change this, depending on what data type we use for the Product class.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/66#discussion_r1993339823" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I would suggest to refactor this out into a separate method, so that it can be reused in computeTotalRevenue().
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/66#discussion_r1993342920" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Gradle is complaining about this bracket placement lmao. Just put in the line above to solve the issue,
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/66#discussion_r1993346930" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I have no idea how the Set class works, but it looks interesting. Nice work.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/71#discussion_r1997637525" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Gradle is giving a error for these imports, as they are not used within the class. I recommend commenting them out or removing them.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/71#discussion_r1997637635" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Don't forget to include a Javadoc comment for the SalesManager class itself.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/71#discussion_r1997637789" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These indentations are 4 spaces (1 tab) too much. You can delete 4 spaces for both these lines.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/71#discussion_r1997638260" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This indentation is one space too long. Also, when you have the time, do not forget to include the @params for the Javadoc comment.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/71#discussion_r1997639538" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Not a bad way to prevent negative or zero quantities. Nice.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/71#discussion_r1997639653" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Smart way to prevent negative numbers. Nice.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/71#discussion_r1997640045" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These indentations are 4 spaces (1 tab) too much. You can delete 4 spaces for both these lines.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/74#discussion_r1997887667" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These initializations are causing the GitHub checks to fail. I would suggest to create dummy .java files for these new classes, so that the checks can pass and we can merge with no issues.  As an alternative, you also can comment out this part instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/74#discussion_r1997888506" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

It will be nice if you can break down the input into the command itself and the other information. If not, I can split it up in the CommandParser class too. Up to you.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/73#discussion_r1997975635" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

containsKey(id) may conflict with the containsKey(name) in addProduct(), as the key in the HashMap cannot be id and name at the same time. I recommend using either one of them, whichever that will make your life easier. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/73#discussion_r1997994074" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Just curious. What is the purpose of using AtomicInteger?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/73#discussion_r1997995600" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice touch that you kept id as final. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/73#discussion_r1998151878" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

There is a missing extra line at the bottom, and it is causing Gradle to fail. Try to remedy this as soon as possible.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/78#discussion_r2003276886" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Very neat organization of the constants. Nice.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/78#discussion_r2003286609" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

It is possible to combine this together by using a boolean value as a parameter to indicate if it is newline or not.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/120#discussion_r2007027952" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of BeforeEach to setup the InventoryManager before starting all the tests. Nice.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/120#discussion_r2007028651" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe later remove this comment, as I am assuming it is for reference.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/126#discussion_r2009880886" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice use of assertions. Strings can be converted to constants though.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/126#discussion_r2009883447" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Strings can be converted to constants.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/126#discussion_r2009886505" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice tests.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/130#discussion_r2011216177" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Creating getter functions for all member variables will be useful. Nice.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/130#discussion_r2011218283" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Checking for null or empty strings is good defensive code. Nice.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/130#discussion_r2011219484" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I see that you have not integrated the Credentials object into the BusynessManager.java file? I assume it will come in a later implementation.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/131#discussion_r2013814011" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

If we are not using these constants, maybe we can remove them.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/131#discussion_r2013826575" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I am thinking about what happens if the user types in something other than FNB or RETAIL? From what I am seeing, the businessType will become RETAIL, even if the user gives a random input.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/131#discussion_r2013829874" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This may expose the Credentials object to creating errors, if the parts are not split properly.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/131#discussion_r2013837228" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The exception handling for NumberFormatException is lacking, though if it is in the list already, it could mean that the data is acceptable. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/132#discussion_r2013853724" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I assume that this is the design portion? So, after this, I think we need to explain the implementation for each class.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/132#discussion_r2013855556" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The user stories are a bit outdated, as some of the ideas in the user stories have not been implemented.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/132#discussion_r2013857611" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Some of the features here are not implemented, which may mislead readers. I will edit this to showcase what we did feature.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/133#discussion_r2014448300" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You embedded the link into the description. Nice.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/133#discussion_r2014449192" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good and brief explanation of our classes.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/133#discussion_r2014450169" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice that you explained the terms we used in our project.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/134#discussion_r2017818082" expanded>
<div slot="header">

**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice inclusion of how InventoryManager works with other Manager classes.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/134#discussion_r2017818447" expanded>
<div slot="header">

**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe it would be better if the remaining methods in the class can be explained as well, even if you are not the author.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/74#issuecomment-2735693400" expanded>
<div slot="header">

**45 :octicon-comment:** %%(other comment)%%
</div>

This PR has failed the GitHub checks. As a team, we came to the conclusion that it is safe to merge this PR, as the error causing the checks to fail is too trivial. This is because the expected and the actual output are virtually identical.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/149#issuecomment-2780690862" expanded>
<div slot="header">

**46 :octicon-comment:** %%(other comment)%%
</div>

Tasks: 
- Add instruction to answer "yes:" if want to add business
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/151#issuecomment-2780693130" expanded>
<div slot="header">

**47 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Limit value of price (double) to 2 decimal places (only accept 2 d.p.)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/150#issuecomment-2780693484" expanded>
<div slot="header">

**48 :octicon-comment:** %%(other comment)%%
</div>

Bug is repeated. Check #149 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/152#issuecomment-2780697491" expanded>
<div slot="header">

**49 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Add "exit:" command to help command list
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/153#issuecomment-2780698035" expanded>
<div slot="header">

**50 :octicon-comment:** %%(other comment)%%
</div>

Bug has been resolved post-v2.0 but before PE-D.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/154#issuecomment-2780702371" expanded>
<div slot="header">

**51 :octicon-comment:** %%(other comment)%%
</div>

Tasks: 
- make tags (/name & /qty & /price) not case-sensitive
-  justify in UG why there must be spaces before and after tags

Complemented by #158 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/155#issuecomment-2780706710" expanded>
<div slot="header">

**52 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- modify "update" command so can update attributes individually
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/156#issuecomment-2780713906" expanded>
<div slot="header">

**53 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Add better description for sign-in process in UG
- Add ability to add multiple businesses (after inputting invalid business ID)
- Add function to edit Credentials (optional)
- Create welcome message after successful login ("Welcome back `businessName`")
- Fix business data loading successfully when credentials deleted bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/157#issuecomment-2780718397" expanded>
<div slot="header">

**54 :octicon-comment:** %%(other comment)%%
</div>

Similar issue to #151.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/158#issuecomment-2780719979" expanded>
<div slot="header">

**55 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Modify tags to just need value
- Update UG with above feature

Complements #154 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/159#issuecomment-2780720756" expanded>
<div slot="header">

**56 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Create new error message when price is 0.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/160#issuecomment-2780722282" expanded>
<div slot="header">

**57 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Modify output of search to show all attributes of the product
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/161#issuecomment-2780723116" expanded>
<div slot="header">

**58 :octicon-comment:** %%(other comment)%%
</div>

Similar issue to #159.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/162#issuecomment-2780725392" expanded>
<div slot="header">

**59 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Add check to confirm if business ID is digits only
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/163#issuecomment-2780727357" expanded>
<div slot="header">

**60 :octicon-comment:** %%(other comment)%%
</div>

Tasks; 
- Create password recovery (ask if forgot password when invalid credentials -&gt; show password if yes)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/164#issuecomment-2780728532" expanded>
<div slot="header">

**61 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Set maximum qty and price size. (100k?)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/165#issuecomment-2780729410" expanded>
<div slot="header">

**62 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Fix revenue not calculated correctly bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/168#issuecomment-2780729721" expanded>
<div slot="header">

**63 :octicon-comment:** %%(other comment)%%
</div>

Similar to #159.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/169#issuecomment-2780730054" expanded>
<div slot="header">

**64 :octicon-comment:** %%(other comment)%%
</div>

Similar to #164.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/170#issuecomment-2780730398" expanded>
<div slot="header">

**65 :octicon-comment:** %%(other comment)%%
</div>

Similar to #164.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/171#issuecomment-2780731148" expanded>
<div slot="header">

**66 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Replace "print" with "list".
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/172#issuecomment-2780731583" expanded>
<div slot="header">

**67 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Add error message when qty sold is 0 and trying to clear
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/175#issuecomment-2780732390" expanded>
<div slot="header">

**68 :octicon-comment:** %%(other comment)%%
</div>

Similar to #163.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/176#issuecomment-2780732534" expanded>
<div slot="header">

**69 :octicon-comment:** %%(other comment)%%
</div>

Similar to #160.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/177#issuecomment-2780733018" expanded>
<div slot="header">

**70 :octicon-comment:** %%(other comment)%%
</div>

Similar to #155.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/178#issuecomment-2780733190" expanded>
<div slot="header">

**71 :octicon-comment:** %%(other comment)%%
</div>

Bug has been resolved post-v2.0 but before PE-D.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/179#issuecomment-2780733836" expanded>
<div slot="header">

**72 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Add a "see" to the third box
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/180#issuecomment-2780734281" expanded>
<div slot="header">

**73 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Add sample outputs in manual testing
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/173#issuecomment-2780737640" expanded>
<div slot="header">

**74 :octicon-comment:** %%(other comment)%%
</div>

Tasks: 
- Indicate in UG that name can only be one word (if more words -&gt; use _ )
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/166#issuecomment-2780739469" expanded>
<div slot="header">

**75 :octicon-comment:** %%(other comment)%%
</div>

Similar to #173.

Third pic is assumed due to tester error. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/issues/174#issuecomment-2780740659" expanded>
<div slot="header">

**76 :octicon-comment:** %%(other comment)%%
</div>

Tasks:
- Justify in DG why ID cannot be repeated.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/184#issuecomment-2781352672" expanded>
<div slot="header">

**77 :octicon-comment:** %%(other comment)%%
</div>

for the 3rd commit, it is actually #173, not #174.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 6. CHEN..NTUO `@wentuoc` (**42** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/20#discussion_r2002342668" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I find this a bit trippy as we have to re-specify which list we want to add the meal to
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/20#discussion_r2002343542" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

If we split the two mealLists, it could also streamline this process a bit
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/27#discussion_r2002508298" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this supposed to be `InvalidPriceException`?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/27#discussion_r2002516720" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can consider encoding in csv format to simplify the decoding process
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2002553409" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could we do without the `filterOrSelect` parameter in the constructor, and directly initialise it in the constructior? Seems to me that this would incur an extra step when calling FilterChecker (or SelectChecker) in their respective command classes.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2002594894" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These conditonals seem to be checking for what condition we are filtering by (whether Ingredient, Meal Name or Meal Cost). Woud the logic be clearer if the variable was renamed as such? (e.g. `switch (filterCondition)` ...)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2002615892" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

What are the checks here for?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2002627120" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This section seems a bit wordy, is there any way to make the call directly in the subclasses?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2002636175" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Same comment as above - perhaps we can parse the filter condition (ingredients, meal cost, meal name) at the start?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2002643412" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should the meal cost needing to be a valid double and positive be checked in the checker instead?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2002646464" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Same comment as above
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/20#discussion_r2002862495" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would it be better to set `userInputText` into a private variable called `userInput` rather than `validUserInput` using
''' this.userInput = userInputText;'''

This is because at this point, the user input has not been verified as valid yet, which occurs after `checkValidUserInput` in line 29. Actually, our classes don't do error correction, which _could_ be a future feature.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/20#discussion_r2002864772" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

What's the intended use of this method?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/33#discussion_r2004870901" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think this is good, can just call all the other functions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/33#discussion_r2004871707" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

> In user's meal list
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/33#discussion_r2004871928" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

> Select a meal and add it into your meal list
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/37#discussion_r2005616980" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Follow the convention in the other Storage methods with regards to dealing with IO Exceptions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/37#discussion_r2005625605" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will it be better if we only do the storage operations (i.e. saving the meal and user lists) at the very end after bye command? @Cheng-Zhiyuan 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/39#discussion_r2005742112" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Just wondering, will there be cases where this check gets triggered? Since in `parser` we check that the command starts with view
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/39#discussion_r2005745465" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This condition will get triggered in the first check already right
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/39#discussion_r2005750885" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think there is a method in MealList that does this too
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/49#discussion_r2017031079" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

See if it's possible to follow the `unitBeingTested_descriptionOfTestInputs_expectedOutcome` convention for tests
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/53#discussion_r2017872225" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will it work if this is in the class constructor? Then we won't need to keep writing `main(null);`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/53#discussion_r2017879091" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this for debugging?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/53#discussion_r2017881645" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The `Meals` class already has methods to get size so there is no need to get the actual `List&lt;Meal>` itself
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/53#discussion_r2017885806" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Was just thinking about it... (not related to this test, but in general) should we move the `checkDuplicateIngredients` into the Meal class instead of being in the CreateCommand class? Since we shouldn't be able to add duplicate ingredients into meals in general
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/56#discussion_r2017928425" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should the instantiation of ListCommand call a constructor of the class?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/67#discussion_r2020171739" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Appreciate the SLAP
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/67#discussion_r2020172202" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Not sure if it's necessary to add the exceptions. The [website](https://nus-cs2113-ay2425s2.github.io/website/schedule/week10/project.html) advises us to keep the diagrams comprehensible, not necessarily comprehensive.  
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/86#discussion_r2026577992" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This OR condition shouldn't get triggered, because your test input guarantees that you can find the filtered meal?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/87#discussion_r2026670825" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can consider putting `addExtractedToken` after this line to maintain the same level of abstraction in this method
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/87#discussion_r2026715406" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Are we renaming this class?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/96#discussion_r2027188780" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Change to code: `recipes`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/177#discussion_r2029932268" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Actually, why is there a need for `EZMealPlan` here?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/178#discussion_r2030082989" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

See if it's better to have a comment examplifying this format, as it's not immediately obvious what this is
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/180#discussion_r2030438219" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Do we need to follow the wrapping rules in UG and DG?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/180#discussion_r2030439469" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Typo - te
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/185#discussion_r2030775455" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

we have changed `/m` and `/u` to `/r` and `/w`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/185#discussion_r2030780078" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

can consider naming tests based on the `featureUnderTest_testScenario_expectedBehavior()` convention
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2031752728" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

* Dotted return arrow for `RecipesCommand`
* Typo for `getRecipess()`
* `userMealList:List` should be `:WishList` right?
* It looks like `ui` returns the `userInput` to `EZMealPlan`, and then it is sent to the `Parser`
* `RecipesList`'s name is `recipes list`
* `RecipesCommand` should get deleted after the command finishes executing right?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2032119885" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

* The lifeline for `EZMealPlan`
* Same as previous, `ui` should return the `userInput` to `EZMealPlan` first right? The `ui` doesn't call the `Parser`
* Return arrow after constructor for `SelectCommand`
* `checkValidUserInput` can be considered a function within `SelectCommand` since `SelectCommand` extends `FilterSelectCommand`
* The self check should come after `execute`
* `wishList` is not a `List`, it is a `MealList` or `WishList`
* `printAddMealMessage` is not a return statement, it is another function call to `ui`
* `SelectCommand` should get destroyed after the command finishes executing right?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2032121289" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Watch the resolution for this image
* Same as above
* Why is there `printWishlistHelp`?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/33#issuecomment-2739296335" expanded>
<div slot="header">

**43 :octicon-comment:** %%(other comment)%%
</div>

Some of the phrasing in the individual help commands can be edited but generally looks good! Thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/125#issuecomment-2781205651" expanded>
<div slot="header">

**44 :octicon-comment:** %%(other comment)%%
</div>

Same as #122, #132
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/174#issuecomment-2781206962" expanded>
<div slot="header">

**45 :octicon-comment:** %%(other comment)%%
</div>

Same as #173, #171, #165
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/164#issuecomment-2781207752" expanded>
<div slot="header">

**46 :octicon-comment:** %%(other comment)%%
</div>

Same as #153 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/151#issuecomment-2781208249" expanded>
<div slot="header">

**47 :octicon-comment:** %%(other comment)%%
</div>

Same as #152 

Is this an issue with the global logger?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/141#issuecomment-2781209149" expanded>
<div slot="header">

**48 :octicon-comment:** %%(other comment)%%
</div>

Similar to #137 #136 #140 #147 
Update `help` command
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/176#issuecomment-2781209649" expanded>
<div slot="header">

**49 :octicon-comment:** %%(other comment)%%
</div>

Same as #134 

Check for empty list when removing/deleting from wishlist/recipes list
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/175#issuecomment-2781210079" expanded>
<div slot="header">

**50 :octicon-comment:** %%(other comment)%%
</div>

I believe this is a testing error from the tester
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/170#issuecomment-2781211071" expanded>
<div slot="header">

**51 :octicon-comment:** %%(other comment)%%
</div>

Same as #168  
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/161#issuecomment-2781211832" expanded>
<div slot="header">

**52 :octicon-comment:** %%(other comment)%%
</div>

Non-issue, since the search is by "contains" and not by "exactly equals"

Possibly update UG for clearer explanations
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/146#issuecomment-2781212796" expanded>
<div slot="header">

**53 :octicon-comment:** %%(other comment)%%
</div>

Non-issue, since `/           r` is not the same as `/r`
Possibly throw a different exception to make this clearer
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/121#issuecomment-2781213553" expanded>
<div slot="header">

**54 :octicon-comment:** %%(other comment)%%
</div>

Same as #131 #169 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/169#issuecomment-2781213876" expanded>
<div slot="header">

**55 :octicon-comment:** %%(other comment)%%
</div>

Same as #121 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/156#issuecomment-2781214745" expanded>
<div slot="header">

**56 :octicon-comment:** %%(other comment)%%
</div>

This is a problem with using "contains" to filter
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/129#issuecomment-2781215279" expanded>
<div slot="header">

**57 :octicon-comment:** %%(other comment)%%
</div>

Same as #155 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/166#issuecomment-2781225436" expanded>
<div slot="header">

**58 :octicon-comment:** %%(other comment)%%
</div>

Non-issue? Since we specify that data is only saved using the `bye` command
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/167#issuecomment-2781225824" expanded>
<div slot="header">

**59 :octicon-comment:** %%(other comment)%%
</div>

Better exception handling - rather than print stacktrace, can probably re-initialise the list. Or, mark as out of scope.  
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/167#issuecomment-2781226345" expanded>
<div slot="header">

**60 :octicon-comment:** %%(other comment)%%
</div>

Same as #133
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/163#issuecomment-2781226744" expanded>
<div slot="header">

**61 :octicon-comment:** %%(other comment)%%
</div>

Same as #139
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/172#issuecomment-2781227115" expanded>
<div slot="header">

**62 :octicon-comment:** %%(other comment)%%
</div>

Sane as #135
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/149#issuecomment-2781227594" expanded>
<div slot="header">

**63 :octicon-comment:** %%(other comment)%%
</div>

Same as #150
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/144#issuecomment-2781227819" expanded>
<div slot="header">

**64 :octicon-comment:** %%(other comment)%%
</div>

Non-issue, not sure what tester is trying to say
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/127#issuecomment-2781227996" expanded>
<div slot="header">

**65 :octicon-comment:** %%(other comment)%%
</div>

Same as #130
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 7. NEO .. HAO `@Markneoneo` (**40** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976466227" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You forgot to add the individual cards chips value to the score.
Hence, you might need to calculate totalchips for UI to print the output as well.

        for (Card card : playedCards) ``{``
            TotalChips += card.getChips();
        ``}``
        TotalChips += result.chips();

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976466379" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Reminder that the deck used will be the same throughout the game, so you have to "pull" the existing deck from the State Interface.
No need to make a new deck every round.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976467083" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You probably can just call playerHand.draw(8), which will make the HoldingHand draw 8 cards into their list.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976468408" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Same as above, can just call playerHand.draw(5);
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976468684" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This is my mistake, you can actually make the function void, since you do not really need to return anything as all the logic is done within the function.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976468844" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Remember to call a UI function to print the played hand output messages.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976469141" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These should be >0 by default, otherwise how to play? 
We can default at 3 first but ultimately we will pull the totalPlays info from State interface since it might change across rounds.
We rather decrement than increment because we will initialize the number of plays they get at the start, and the rest of the logic doesnt need to change, otherwise we have another variable to check against rather than comparing it to 0.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976469219" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This should be totalPlays--
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976469234" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Same for this should be totalDiscards--
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976469462" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This if check will probably be done in HoldingHand since they need to throw exceptions.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976469745" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Since you have the isWon function you can just use it:
'  return totalPlays == 0 || isWon();
'
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976471527" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This should be a variable pulled from State interface, as every round the Blind Score should increase.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976471649" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

If you decrement totalPlays and check if its 0 it will be less complicated.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976472649" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

If you decrement totalPlays and check if its 0 it will be less complicated.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976602206" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

No worries, I purposely left it out because you would have to print the Cards individual scores for the UI anyway, so it would be double effort if we both looked at the cards values.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976602223" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think you misunderstood, the number of rounds played and the total plays has no relation.
The total plays is the number of times a player can play a poker hand in a single round.
The only way to increase total plays is through upgrades (future feature).
So it doesnt matter what round it is, Round 1,2,3... will all get the same totalPlays (3 default).
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/48#discussion_r1980725700" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Handsome man

![amogus](https://images.steamusercontent.com/ugc/2044109228584895997/90DA92FF1702F60A95BF4AED4DE0FAC7C2A14A50/?imw=512&imh=393&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1984718289" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This one can just delete or move to UI
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1984723133" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps Gameplay Logic fits better as description.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1984724157" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

![91ckLZfJiBL _AC_UF1000,1000_QL80_](https://github.com/user-attachments/assets/f6658165-4953-4610-a173-62c39ed4f4db)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1984739990" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You can use a text block here so that you don't need multiple print statements:
`printf(""" """);`
To make it neater and more coherent. You can refer to my ip for reference. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1985298417" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe throw an exception here for this.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1997641614" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Fix Indentations
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1997641934" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of static strings
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014536350" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe call it ANTE_1, ANTE_2 etc? 
Keep same naming convention.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014540699" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is 4 technically a magic number?
Maybe just include a DEFAULT_PLAYS = 4;
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014607009" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe rename it to "Too many cards selected for discarding"? 
Also for JavatroExceptions try to make custom ones in the class itself and call the exception.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014613016" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Doesn't this mean you can only win when you use all your Plays? 
Which shouldn't be the case, you should automatically win once you beat blind score.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017872404" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nothing. Reset just resets the text formatting. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017872784" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I will remove all the star imports once I'm done.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017873890" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

By the way I am planning to overhaul the GameScreen so don't expect any or all changes here to stay. I am doing it last because I need all the other logic classes to work perfectly so that I can receive and display the data.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017874682" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I advice you static import UI and use the public static strings there, instead of re-initializing here. For example all the border characters and colour strings.
Maybe take a look at the UI class? A lot of methods and functions are already implemented there and repeated here, you can just call the methods from UI class.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017876460" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I have tested MacOS for my ip and it works, albeit some terminals may have issues, you can take a look at my ip user guide for more info. I am most likely going to use it for tp as well.

https://github.com/Markneoneo/ip
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017881720" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Why delete the comment?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017881752" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Why delete the comment?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017885644" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Why delete the comment?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017885775" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Why delete the comment?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2019784288" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thx for changing all the star imports lol
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/130#discussion_r2020544428" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Rmb to author your part once you merge my other PR
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/209#discussion_r2030075577" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think change the text file to planet_planet_x instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/86#discussion_r2011906812" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Yes because I have to actually modify the hand for the card selection input to work properly after sorting, otherwise the sorting is just visual and the card indices do not match.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/25#issuecomment-2706984933" expanded>
<div slot="header">

**42 :octicon-comment:** %%(other comment)%%
</div>

This was done by me.

#3
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/21#issuecomment-2706990143" expanded>
<div slot="header">

**43 :octicon-comment:** %%(other comment)%%
</div>

This is already done by me.

#3
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/191#issuecomment-2780371291" expanded>
<div slot="header">

**44 :octicon-comment:** %%(other comment)%%
</div>

If you press enter multiple times too quick this will occur.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/181#issuecomment-2780372642" expanded>
<div slot="header">

**45 :octicon-comment:** %%(other comment)%%
</div>

Duplicate Issue, I will close this one first
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/169#issuecomment-2780384426" expanded>
<div slot="header">

**46 :octicon-comment:** %%(other comment)%%
</div>

Thank you for the feedback!
I understand the concern about allowing players to backtrack after selecting the "Select Cards" option. However, I'd like to clarify the current design intent.

The "Select Cards" step is the final confirmation in a series of deliberate choices made by the player. To reach this point, the player must navigate through multiple screens—‘Play Game’ → ‘Select Deck’ → ‘Accept Blind’ → ‘Play Cards’ → ‘Select Cards’—each of which allows backtracking. It's only after the player confirms their selection that the action becomes irreversible.

This layered flow is intentional. It provides ample opportunity for the player to reconsider or go back at any point before finalizing. In most cases, an accidental confirmation would likely only occur due to rapid clicking or skipping instructions, rather than a flaw in navigation.

That said, I'm always open to improving the player experience. If there's a recurring pattern of confusion around this step, I’d be happy to explore ways to make the confirmation process even clearer (e.g., an additional prompt or visual cue).

Thanks again for taking the time to share your thoughts!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/163#issuecomment-2780385383" expanded>
<div slot="header">

**47 :octicon-comment:** %%(other comment)%%
</div>

Duplicate Issue, I will close this for now.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/160#issuecomment-2780386182" expanded>
<div slot="header">

**48 :octicon-comment:** %%(other comment)%%
</div>

We will include this in known bugs since we cannot change the terminal behaviour.
We will tell the players to keep the terminal fullscreen and dont change its size
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/158#issuecomment-2780386547" expanded>
<div slot="header">

**49 :octicon-comment:** %%(other comment)%%
</div>

We will add this to known bugs.
This will inevitably occur if the terminal is to small for a full line to be displayed.
We will tell the player to play in fullscreen.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 8. HUNG.. KIN `@randust` (**38** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/8#discussion_r1983739920" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

please avoid magic literals
make them into constant variables in class misc.DisplayMessage
you can also make print functions in misc.DisplayMessage to print the messages
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/8#discussion_r1983740243" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/17#discussion_r1995010613" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should it be printing 0 instead of NaN if there is no item yet? Currently, it will print NaN because it is 0/0.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/18#discussion_r1995375052" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should you split using '$' according to our format?
Format: /add [DESCRIPTION] $[AMOUNT] 
And then handle category separately.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1996979360" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can consider extract them out and use a for loop
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1996979437" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/24#discussion_r1996979978" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/25#discussion_r1997608609" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Try to avoid import *
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/25#discussion_r1997609030" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is there a specific purpose for this test?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/25#discussion_r1997610602" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps defining a constant for 9.40? 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/25#discussion_r1997611926" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Consider adding a new line at the end of the file (to pass the checkstyle test in Java CI)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/29#discussion_r1997630146" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Having too many appends can be pretty clumsy. You may consider list.append(String.format("%n%d. %s", i++, expense)); instead.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/29#discussion_r1997630382" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps using a more readable expense variable name?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/29#discussion_r1997631011" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps following our convention, add "_TEMPLATE" after the name?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/29#discussion_r1997631050" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/30#discussion_r1997665752" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Try to avoid arrowhead code. You may consider using parts[1].matches("\\\d+(\\\\.\\\d+)?") to check if it is a decimal number (refer to delete command below).
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1997885144" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

is there a specific purpose for this test?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1997885163" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Try to avoid import *
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1997889646" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

- Instead of the `try-catch` approach, you can consider `assertThrows` (mentioned in the lecture) for better readability.
```
	public void testInvalidExpensesAmount_returnsError() ``{``
	    IllegalArgumentException exception = assertThrows(
	        IllegalArgumentException.class,
	        () -&gt; new Expense("for testing", -5.0, "uncategorized")
	    );
	    assertEquals(DisplayMessage.INVALID_AMOUNT, exception.getMessage());
	``}``
```
This makes the test cleaner and removes the need for `fail()`.
-  Consider adding some more test cases, e.g. amount = 0.0
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/32#discussion_r1997956051" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Try to avoid redundant/similar code blocks. One way to achieve that is to use `@ParameterizedTest` and `@CsvSource`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/61#discussion_r2018446593" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think unknown command shouldn't be executed successfully? Can consider helping him correct it (in help command).
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/61#discussion_r2018466303" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe can use a helper function to ensure a higher level of abstraction. You can also consider using a for loop (with List) in the helper function, so that you don't need to add expenses one by one (refer to expense manager test).
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/61#discussion_r2018481507" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps adding a message after the assertion to let us know why we fail the test, in case we fail it? Same at other places.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/61#discussion_r2018489994" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you simplify the expression by declaring an additional variable
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/61#discussion_r2019107863" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you create a common helper function, but the `CommandTest` class might imply this is a test class itself (with `@Test`). You can consider renaming it to something like TestUtils and moving the file out of the command package so that you can reuse this helper function for the expense manager test. Perhaps a function should be named as a verb (e.g., addConstantExpenses)?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/71#discussion_r2020046597" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

might want to refer to other commands and follow the same way to handle description
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/71#discussion_r2020047108" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you handle user input, making good use of regex expressions, but you might want to pack all these low-level code into a helper function in utils.InputValidator to obtain a higher level of abstraction
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2020048510" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

this method might be too long, consider shortening it by utilizing helper functions. Try to avoid try-catch blocks if possible. You may consider using regex expressions to handle incorrect input format.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/69#discussion_r2020048522" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2020049566" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

the [COMMAND] is typo?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2020049655" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

consider make use of `InputValidator.isNullOrBlank()`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2020050254" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you might want to differentiate the variable name `message` between error message and success message
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2020051230" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same at other places
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/101#discussion_r2026898786" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you can simply put this line to abstract class command, so you won't need to initialize for every command
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/178#discussion_r2029827492" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

just to confirm, do we limit the user to enter a date on or before today
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/178#discussion_r2029827803" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

have you set the upper limit for add/edit... in the ug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/200#discussion_r2030169506" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you might want to change the `InputValidator` into `&lt;&lt;class>> InputValidator`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/200#discussion_r2030169724" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like your idea to change the name to manager 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/19#discussion_r1995815848" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Yup, I am wondering if I should separate out the templates. I will just leave it for now.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/63#discussion_r2020047887" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

yes, this will be used to validate amount value or so
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/77#discussion_r2022563450" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

'/d' is just used to split. They should be the same
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/issues/123#issuecomment-2778528732" expanded>
<div slot="header">

**42 :octicon-comment:** %%(other comment)%%
</div>

As I was following a similar layout to what was displayed on the course website, can you give some specific directions/improvements that can be made based on this? Your suggestions are appreciated.

![Image](https://github.com/user-attachments/assets/2e5f01d3-cdd6-4c92-8565-baa904349206)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/197#issuecomment-2781450244" expanded>
<div slot="header">

**43 :octicon-comment:** %%(other comment)%%
</div>

Thanks for your revert-revert — appreciate the team spirit
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/200#issuecomment-2781491932" expanded>
<div slot="header">

**44 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 9. TENG..QUAN `@Teng-Yong-Quan` (**36** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/33#discussion_r2004815016" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Try avoid magic literals
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/33#discussion_r2004815807" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For printGeneralHelp(), it is ok to print all the helps instead? (It is optional.)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/33#discussion_r2004817890" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Type "help" as static String help = "help" to avoid magic literals.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/34#discussion_r2004895668" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Replace e with IndexOutOfBoundsException
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/34#discussion_r2004895763" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

avoid magic literals: index -1 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/34#discussion_r2004896172" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

avoid magic literals: [1]
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/34#discussion_r2004897129" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Avoid magic literal: [1]
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/34#discussion_r2004897290" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Replace e with numberFormatException
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/37#discussion_r2005622370" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Change to ioexception.getMessage()
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/37#discussion_r2005634017" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

this one i agree
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/49#discussion_r2017080928" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

change from e to exception
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/65#discussion_r2019794732" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Add logger and use logging
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/65#discussion_r2019795240" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

add tests for "view /u number" as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/65#discussion_r2019795883" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

also test for the number that are out of range for both "view /u number" and "view /m number" and ensure that the branch coverage hit as high as possible
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027985591" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Change Main Meal List to Recipes List
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027986630" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

the typical create command is `create /mname mealName /ing ing1(ing1_cost), ing2(ing2_cost)` and it only adds the newly created meal to the recipes list
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027986855" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

View with: `recipes`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027987119" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Delete from it: `delete INDEX`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027987989" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This one for now I not so sure, i think can just remove for now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027988330" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Change User Meal List to wishlist
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027990045" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Replace this line with "This is a secondary list where you can add and remove the preferred meals you have chosen from the (filtered) recipes list using `select Index [filter method (optional)]` and `remove index` respectively."
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027992855" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Replace with "It's useful for suggesting meal recommendations and to-buy ingredients based on the `recommend` and `buy` commands respectively."
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027993245" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

View with: `wishlist`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027995242" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Since I already give suggestions for the wish list as above, this part will be the `Inventory list`.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027996270" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

"This inventory list is where you store and remove the to-buy ingredients which may or may not be part of the meals in the wishlist."
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027997229" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Add to inventory list using: `buy /ing ing1 (ing1_cost), ing2 (ing2_cost)`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027997845" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

View with: `inventory`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027997994" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

remove this line
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/104#discussion_r2027998808" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Replace `main meal list` with ` recipes list` and `user's wish list` with `user's wishlist`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/185#discussion_r2030932152" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

checkstyle violation, please change
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/185#discussion_r2030933640" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

change exception name from `e` to `ioException`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2031770318" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The line after the new UserInterface(), which is going towards the EZMealPlan should be dotted line.
The line after the new RecipesCommand(), which is going towards the Parser should be dotted line.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2031774026" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The line after the new UserInterface(), which is going towards the EZMealPlan should be dotted line.
Don't need `&lt;&lt;abstract>>`

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2031777399" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The line after the new UserInterface(), which is going towards the EZMealPlan should be dotted line.
The line after the new Wishlist(), which is going towards the Parser should be dotted line.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2032259540" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

isn't it `getWishList()` instead of  `getMainMeals()`?
isnt it `printMealList()` instead of ` printWishlistHelp()`?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/194#discussion_r2032261577" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

isn't it `printMealList(recipesList, "recipes list")` instead of the `printMealListHelp()`?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2003074003" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

checker just checks for input format
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2003077807" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

cos for 'select' command you can type with or without the filter methods, so this checks that if the userInput is a 'select' command and it has no filter method, we can just ignore
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2003079000" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok will do
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2003079950" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

make sense, i will create a method and attributes in the initialisation class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/31#discussion_r2003085043" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

i try ternary operator?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/20#discussion_r2003297519" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok will do
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/20#discussion_r2003297809" expanded>
<div slot="header">

**43 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok i change to class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/67#discussion_r2022354544" expanded>
<div slot="header">

**44 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/176#issuecomment-2781472408" expanded>
<div slot="header">

**45 :octicon-comment:** %%(other comment)%%
</div>

i accounted for this issue already. It should message saying list is empty when instead of out of range. The index has also been adjsuted and corrected.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/174#issuecomment-2781472907" expanded>
<div slot="header">

**46 :octicon-comment:** %%(other comment)%%
</div>

settled as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/172#issuecomment-2781473007" expanded>
<div slot="header">

**47 :octicon-comment:** %%(other comment)%%
</div>

settled 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/167#issuecomment-2781473394" expanded>
<div slot="header">

**48 :octicon-comment:** %%(other comment)%%
</div>

this one i already encapsulated it within try and catch
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/162#issuecomment-2781473795" expanded>
<div slot="header">

**49 :octicon-comment:** %%(other comment)%%
</div>

i standardised all inputs to be excatly 2 decimal place. I think i might to lower the capacity
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/issues/151#issuecomment-2781884525" expanded>
<div slot="header">

**50 :octicon-comment:** %%(other comment)%%
</div>

The warning statement is the logger.
The exception thrown is correct.
If the user don't want the logger statement, then i will remove.

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 10. ASHE..SHIH `@Ashertan256` (**33** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/33#discussion_r2003432063" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good clarification!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/39#discussion_r2005332296" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good edge case
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/39#discussion_r2005336221" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good clarification for the user
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/39#discussion_r2005336936" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good specification of the error!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/39#discussion_r2005339836" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good proper formatting of the test cases
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/38#discussion_r2005345486" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Yup, great that you can catch that edge case!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/38#discussion_r2005346233" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for adding this functionality!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/53#discussion_r2009046216" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good catch for more edge cases!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/56#discussion_r2009129276" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for creating a new function specifically for if the date has issues
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/56#discussion_r2009129781" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice, this will make it more intuitive for the user to see his expenses
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/57#discussion_r2009705421" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good catch, should we also take note of wrong entries that may not trigger this? (e.g 1700, 2060...)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/57#discussion_r2009708178" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should we consider the term "delimiter" instead of "seperator"?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/57#discussion_r2009711206" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job updating the test cases!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/58#discussion_r2010484112" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe we shd put "valid" instead of "real" date
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/58#discussion_r2010487281" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for clarifying, better for future devs!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/60#discussion_r2017332224" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for updating the DG!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/61#discussion_r2017478231" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for trying to solve the merge conflicts Matt!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/61#discussion_r2017478952" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good clarification for the user
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/61#discussion_r2017480922" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this code frm Nandhita? May need to attribute her with the author tag eventually so the code is credited properly
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/63#discussion_r2018676199" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

May be a bit hard for maintainers to understand this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/70#discussion_r2020922263" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good for catching for lower/upper cases!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/70#discussion_r2020923288" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Shd we also allow for "y" and "n" as is common practice for Linux?
![Picture1](https://github.com/user-attachments/assets/868e56ec-877c-4573-b3e5-bde5c1726b05)

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/69#discussion_r2020923841" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for updating the test cases!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/68#discussion_r2020924551" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for organising the stuff neatly into a table
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/68#discussion_r2020924975" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Very comprehensive overview of the BudgetManager class!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/67#discussion_r2020927986" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good for making ti clearer for the user!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/67#discussion_r2020933323" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Detailed assertions, good!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/72#discussion_r2022237003" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good simplification of terms!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/72#discussion_r2022238101" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good housekeeping especially since we're dealing with file IO
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/73#discussion_r2022238714" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good clarification and good that it's case-insensitive as well!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/73#discussion_r2022239095" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good catch for edge case!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/73#discussion_r2022239738" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice, prevents user from entering invalid name
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/101#discussion_r2028376739" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for simplifying it and making it easier to maintain
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/153#issuecomment-2781552637" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

No longer an issue as create-group now prevents members of the same name from being added.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/128#issuecomment-2782143527" expanded>
<div slot="header">

**35 :octicon-comment:** %%(other comment)%%
</div>

This is expected and will be documented in the UserGuide. The user can choose to not have the amount add up to 100%, however, the percentage/absolute amount cannot exceed this 100%.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/120#issuecomment-2782318021" expanded>
<div slot="header">

**36 :octicon-comment:** %%(other comment)%%
</div>

Edited to prevent splitting of the same expense between the same group.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/143#issuecomment-2782320869" expanded>
<div slot="header">

**37 :octicon-comment:** %%(other comment)%%
</div>

Reduced complexity.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/142#issuecomment-2782321412" expanded>
<div slot="header">

**38 :octicon-comment:** %%(other comment)%%
</div>

Fixed and updated.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/126#issuecomment-2782522907" expanded>
<div slot="header">

**39 :octicon-comment:** %%(other comment)%%
</div>

This is expected behavior. Will update in the UG that the names are unique across the entire program (Alice in group A is the same as Alice in group B, as long as the name is the same with no collisions). This is because a single individual can be in different friend groups, therefore the amount should be stacked
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/149#issuecomment-2782528317" expanded>
<div slot="header">

**40 :octicon-comment:** %%(other comment)%%
</div>

Good catch, will update UG to inform the user that him/herself should be added into the group. The split function only splits by the members.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/102#issuecomment-2782892163" expanded>
<div slot="header">

**41 :octicon-comment:** %%(other comment)%%
</div>

Sequence diagram has been updated for easier reading
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 11. KWA ..QUAN `@K-J-Q` (**32** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980541546" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

can you fill in the details in this JavaDoc?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980552824" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

not clear what this is. It would be better if you can put this as a constant, describing what it does
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980554376" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This can be a constant, or perhaps even placed in the UI class?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980555319" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Magic numbers
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/45#discussion_r1980555922" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The printf are quite hard to read as well. would it be better to put it in UI?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1980569400" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

follow naming convention HOLDING_LIMIT
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1980570318" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can be confusing to have the method name same as the variable inside. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1980571473" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can be confusing to have the method name same as the variable inside. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1980573297" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good to add checks to ensure plays is of a certain length
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/46#discussion_r1980575858" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

HoldingHand should handle the drawing of cards from the deck using `draw(int numCards)` method

https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976467083
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/65#discussion_r1997535627" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Might be good to create a method in JavatroException and `throw JavatroException.tooManyCardsPlayed()` instead
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/65#discussion_r1997535909" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Looks good! this should fix the bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/65#discussion_r1997535997" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Same here, could make a method in JavatroException instead
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/73#discussion_r2002187100" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Note spelling issue here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017829472" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

It can be better to use 1.0 and 2.0 to indicate that it is a double
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017830666" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Magic number
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017831628" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I've modified this part in my latest PR (which is pending approval)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017831768" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of javadoc
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017832456" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

What is the colour of reset?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017832606" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Not recommended to use *
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017833342" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

lot's of magic values here. is there a way to name them? If not it's fine.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017833641" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

we would have to check if all OS (not just windows) supports emoji.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017841902" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

might be good to assert false here.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017842696" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good use of constants here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017843252" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can the \u characters be a constant ? It is not clear what it means
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/118#discussion_r2020152683" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good to have one variable for both! 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/133#discussion_r2022995980" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great work on creating the table of contents, makes it more organised
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2023167320" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Actually, you don't need to generate a PNG here. You can use the following method to embed the Mermaid diagram directly, and GitHub will automatically generate it.

https://github.blog/developer-skills/github/include-diagrams-markdown-files-mermaid/

Refer to lines 498 - 515 for an example
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2023194160" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Do remove the unused .png as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030199549" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good choice. Are there any copyright issues related to this? I believe there are some limitations for 2113
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030199722" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

note to not use import * here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/213#discussion_r2030199893" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

preferably not to use * here (following cs2113 guidelines)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976516733" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Right, in that case, the `PlayerHand` class will handle all the drawing and discarding logic.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976517983" expanded>
<div slot="header">

**34 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

> If you decrement totalPlays and check if its 0 it will be less complicated.

I started the count at 0 and incrementing it as it might be clearer. 
- other classes can get the number of rounds played via `getTotalPlays` method.
- easier to read UI. e.g. `Round 1 Complete! Press any button to proceed to Round 2 >`

If we were to use the decrement method instead, there would be additional logic to calculate these values. This depends on whether we will print more of the **current rounds** versus **remaining rounds**.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976518659" expanded>
<div slot="header">

**35 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Right, I will implement this. I assumed `PokerHand.evaluateHand(playedCards)` included the individual cards' values as well.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976519759" expanded>
<div slot="header">

**36 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Right, in this case, it makes sense to set it to 3, since the UI will likely show the amount of discards the play has remaining, instead of the number of discards used.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976656019" expanded>
<div slot="header">

**37 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Latest commit should have resolved this!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#discussion_r1976864149" expanded>
<div slot="header">

**38 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

In this case, nearly all the code will be commented out - since round class is the center of the UML diagram. Should we hold off on this pull request until the remaining classes have been created?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017835154" expanded>
<div slot="header">

**39 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Fixed in latest commit! Misunderstood what @jwyk meant previously.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017835361" expanded>
<div slot="header">

**40 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Fixed in latest commit! Misunderstood what @jwyk  meant previously.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017835459" expanded>
<div slot="header">

**41 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Fixed! See comment above.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017836578" expanded>
<div slot="header">

**42 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Yep. We will use @swethacool implementation once it is merged
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017836933" expanded>
<div slot="header">

**43 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Will implement with your PR once it is merged into the main branch. I created these for ease of testing
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017837068" expanded>
<div slot="header">

**44 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Refer to above.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2019829002" expanded>
<div slot="header">

**45 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Merged with your PR. Please check 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/119#discussion_r2020183390" expanded>
<div slot="header">

**46 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Do you mean JavatroException? This function will only be used for sorting by suit/rank under the CardSelectScreen. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/210#discussion_r2030959610" expanded>
<div slot="header">

**47 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

dg_sources is just for reference. A separate file is created for the website
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/210#discussion_r2030959980" expanded>
<div slot="header">

**48 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

yes. under mermaid live
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/35#issuecomment-2692278836" expanded>
<div slot="header">

**49 :octicon-comment:** %%(other comment)%%
</div>

> Could you also include some Junit tests for your class? You can follow @Markneoneo’s previous PR for an idea of what tests to include

For tests, we would have to wait for the classes `Deck` and `Holding Hand` to be created. Should I submit a PR after they have been created instead?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/23#issuecomment-2726764935" expanded>
<div slot="header">

**50 :octicon-comment:** %%(other comment)%%
</div>

Done in `Round` class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/20#issuecomment-2726765085" expanded>
<div slot="header">

**51 :octicon-comment:** %%(other comment)%%
</div>

Done in `Round` clas
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/26#issuecomment-2727165899" expanded>
<div slot="header">

**52 :octicon-comment:** %%(other comment)%%
</div>

Implemented it in `playCards()` method
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/134#issuecomment-2769830306" expanded>
<div slot="header">

**53 :octicon-comment:** %%(other comment)%%
</div>

We will manually refactor the switch statements before the final submission.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/174#issuecomment-2780632810" expanded>
<div slot="header">

**54 :octicon-comment:** %%(other comment)%%
</div>

This was updated in the latest commit (the document referenced is an old commit)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/175#issuecomment-2780637229" expanded>
<div slot="header">

**55 :octicon-comment:** %%(other comment)%%
</div>

Will clarify

https://github.com/nus-cs2113-AY2425S2/forum/issues/46
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/issues/175#issuecomment-2780826792" expanded>
<div slot="header">

**56 :octicon-comment:** %%(other comment)%%
</div>

https://github.com/nus-cs2113-AY2425S2/forum/issues/46#issuecomment-2780730031
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 12. NGUY.. DAT `@QuyDatNguyen` (**30** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/111#discussion_r2024392146" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

just in case after Command becomes abstract, please change this one
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/111#discussion_r2024396758" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

for static, you can use ``{``static``}`` to create underline
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/111#discussion_r2024406149" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

you can make use of multiple opt boxes for validation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/111#discussion_r2024408805" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

also, to make it abstract more, I think you may want to merge them all in 1 opt box and condition be valid change or something else?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/111#discussion_r2024444676" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

the top still uses validating and it still looks a bit messy to me... To be fair you can also use ref box if you want it to look neater
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/116#discussion_r2024847454" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

for static you may want to use ``{``static``}`` to get underline instead
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/116#discussion_r2024848083" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same issue for static
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/116#discussion_r2024848543" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same issue static
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/118#discussion_r2026357785" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Magic literals
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/119#discussion_r2026895820" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

may use ``{``static``}`` to make underline
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/121#discussion_r2026953009" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

static can use ``{``static``}`` to get underline
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/121#discussion_r2026965099" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

please apply change to the image as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/121#discussion_r2026965970" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

these can also use ``{``static``}`` as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/123#discussion_r2027083204" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

hey, appearently I was trying to resolve merge conflicts but forgot to make change here, can you help to change c to command, tks
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/123#discussion_r2027083671" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/123#discussion_r2027084233" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

for coding standards, please change c into command
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/124#discussion_r2027149328" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can your refactor the testing to be manual testing only and add them in last appendix?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/124#discussion_r2027150016" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can remove this part to reduce length tbh
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/124#discussion_r2027154104" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Also no need to mention automation testing anyways (that part has been generally coverred)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029798467" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The syntax does not consistent with the explanation lines below
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029798600" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

many examples of finding/ filtering incomes are still in wrong syntax, and the output of those examples may also need to be updated to fit with your command's behaviour as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029798785" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

can you check UG for this command and see if anything need to be updated as well?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029799049" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

maybe wrap up the string and move it as constant?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029799222" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

for your new output messages, remember to refactor then as constants and avoid magic literals
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029799265" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same issues for magic literals/ magic strings here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029799332" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same issue for magic string
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029799488" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

can refactor command as a constant
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029799549" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same issue with magic strings
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/193#discussion_r2030041971" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

please update the summary command table as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/193#discussion_r2030042426" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

just to make sure u pull the help command changes from upstream first. Also, you still need to update delete-expense command instructions below (check the ones in unchanged)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/198#discussion_r2030043105" expanded>
<div slot="header">

**31 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I will change level to SEVERE after everyone finishes merging their parts and merge change myself (if thats the only change)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/198#discussion_r2030199890" expanded>
<div slot="header">

**32 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

technically it does not return anything since this is a void function
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/198#discussion_r2030200022" expanded>
<div slot="header">

**33 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I still set output message, but in the code this does not mean returning anything btw
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/178#issuecomment-2779235736" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

This one can also be fixed with UG aside from functionality
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/176#issuecomment-2779241521" expanded>
<div slot="header">

**35 :octicon-comment:** %%(other comment)%%
</div>

Fixing the error to show invalid tag
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 13. LI X..AONA `@samstt` (**30** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/72#discussion_r2018092757" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These lines follow naming conventions and are easy to understand, good job!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/72#discussion_r2018094385" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this single print statement necessary here?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/72#discussion_r2018094907" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Are the single empty print statements necessary?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/72#discussion_r2018096440" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These for loops seem to be repeated for the different task subclasses. Is there a way to abstract them into a new method?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/72#discussion_r2018097209" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Looks good here!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/74#discussion_r2018138704" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Looks good! Follows the general format for explaining the different commands
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/81#discussion_r2020672255" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good use of abstraction!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/81#discussion_r2020673384" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

should the default password be this complicated?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/81#discussion_r2020673949" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of assertions here!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/85#discussion_r2020948509" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think you could be more comprehensive in checking the different command outputs, you could consider adding more assertions to check for correct output.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/85#discussion_r2020950610" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

What about special characters such as @, # and characters from other languages?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/85#discussion_r2020951813" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Since password feature has been removed, is this print statement still necessary?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/86#discussion_r2021094193" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is assignmentName variable case sensitive?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/86#discussion_r2021099427" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job in catching all possible exceptions!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/86#discussion_r2021102901" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The command doesn't seem to follow the standard command format, would you like to change this?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/87#discussion_r2021172746" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

What happens if someone changes the attendance list contents? I think you might be hardcoding the tests and the test will fail the moment the user changes the attendance list contents using our commands.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/97#discussion_r2022839324" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job in noticing this bug, this means multi part names won't be split into extra parts now due to the space!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/104#discussion_r2023237349" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job in making sure that the test tasklist isn't stored in the tasklist data after the test ends!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/104#discussion_r2023242325" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is it possible to abstract setup into a separate class since a lot of your tests use similar setUp code?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/102#discussion_r2024789467" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These test cases look good! Good job!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/118#discussion_r2027211783" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could the formatting be clearer and more user-friendly by giving the commands in a table?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/118#discussion_r2027213327" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Did you forget to capitalise the first word in this command description?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/118#discussion_r2027213863" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Did you forget to capitalise these command descriptions too?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/116#discussion_r2027218208" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Very detailed description of who we are targeting using TASync! Good job!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/115#discussion_r2027238825" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this comprehensive enough?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/194#discussion_r2029853604" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Not necessary to include numbering for sequence diagrams. Let's follow the CS2113 notation!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/194#discussion_r2029853649" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Did you mean to include two users in your sequence diagram?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/212#discussion_r2030831285" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job for adding the missing classes that command handler depends on
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/212#discussion_r2030832852" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These details were previously missing from the class diagram, good job spotting them!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/212#discussion_r2031000059" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Since all the commands implement the same command interface, you could consider representing all the different commands with just a 'task commands' placeholder
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 14. VISW..NKAR `@ravi-viswa105` (**30** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/26#discussion_r2000353872" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the specificity of the output if the assertion fails
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/26#discussion_r2000357785" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the renaming as it makes it more clear
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/29#discussion_r2005433199" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the assertion description, it is is very clear
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/31#discussion_r2005529497" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you split the assertion into two lines
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/33#discussion_r2006714248" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think this comment is not necessary as the code is self-explanatory
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/34#discussion_r2006735355" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps you can remove the try catch block and keep the line in the catch block alone
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/34#discussion_r2006736824" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps you could remove the try catch block and keep the line in the catch block alone
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/36#discussion_r2008809835" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like that the random number generator has been abstracted to a separate class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/40#discussion_r2009433785" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the implementation of the List including all of the valid inputs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/57#discussion_r2022054547" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the format
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/58#discussion_r2022114721" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Does this follow the coding standard?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/60#discussion_r2022296307" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the abstraction to a new class for the difficulties
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/64#discussion_r2023099678" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the clarity of the instructions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/62#discussion_r2023102026" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is the feature not implemented yet?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/58#discussion_r2024466884" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the clarity of the javadoc comments
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/68#discussion_r2026379743" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like that the print uses ui instead of sout
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/71#discussion_r2026775481" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the extra information provided to the user
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/75#discussion_r2027016215" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the additional details which help users understand the highscore more clearly.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/77#discussion_r2027080887" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the negative test's conditions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/80#discussion_r2028103339" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the additional clarifications provided to the user
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/82#discussion_r2028260318" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the description of alternatives
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/83#discussion_r2028357733" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the descriptions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/126#discussion_r2030069904" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the more specific description for the command
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/130#discussion_r2030197281" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how the update logic is handled
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/132#discussion_r2030341022" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like this example, it provides users with a good understanding of the feature.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/133#discussion_r2030912455" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like that this follows the coding standard set
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/134#discussion_r2031503259" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think the case statements makes the code more readable
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/136#discussion_r2031586997" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like the way the error is handled
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/139#discussion_r2031649685" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could this be in the switch statement instead?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/138#discussion_r2031654185" expanded>
<div slot="header">

**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think there should be ":" in front of the class names in the sequence diagram
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 15. ABDU..DEEN `@irfandeen` (**25** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/21#discussion_r1999381537" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of assert statements to check for multiple Arg tokenizations.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/30#discussion_r2003141050" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps, the exceptions could be imported and long-form exceptions can be avoided.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/30#discussion_r2003142797" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

StorageManager should be instantiated and loaded into ApplicationManager for persistence!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/30#discussion_r2003143485" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of SRP!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/32#discussion_r2003259377" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of default statement.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/40#discussion_r2003852745" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Non-static class requires constructor.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/41#discussion_r2003923295" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Replace regex with split.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/41#discussion_r2003929527" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Constant variables should have static modifier.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/41#discussion_r2003935656" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Test needs both happy path and error path.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/41#discussion_r2003936583" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps more than one possible valid add command could be tested.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/41#discussion_r2003937718" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Remove debug prints.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/60#discussion_r2009174423" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of JUnit tests for Tokenizer!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/60#discussion_r2009174513" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good refactor to remove redundant variables
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/67#discussion_r2009466541" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could use more negative testing for single word commands. For instance `exit -1234` should throw an exception.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/82#discussion_r2019731685" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good SLAP
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/91#discussion_r2019831586" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

UI should not be coupled with commands, and should be passed as an object to relevant methods to output successful sorting.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/97#discussion_r2025058255" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great refactor! Decreases coupling between UI and commands!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/97#discussion_r2025060763" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can be replaced with `toString()` method provided by `InternshipApplication` class.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/105#discussion_r2026884022" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2027959186" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

UI is transiently called by Logic rather than Logic getting called by UI. Direction of arrow *may* be wrong.

Perhaps, it is better to replace `Main` with `LogJob`?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2027960866" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Replace descriptions (such as Save to file) with exact method signatures
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2027963764" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

"XYZ" is not the proper way to represent generic classes, but with a type parameter on the top right corner of the box!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2027966376" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Parser is a generic class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2027969174" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good work, rigourously representing all the relationships between in the Parser package.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/119#discussion_r2028054495" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/35#discussion_r2003416766" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Noted, created new issue for minor bug fix #36.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/21#issuecomment-2730494934" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

Fix latest commit message. Latest commit message is erroneous.
> [MFixtokenizer JUnit tformatting o comply with checkstlye�](https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/21/commits/546f71827bb7a18f9fb3aec0c89ec61cd9234613)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/76#issuecomment-2763220571" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

Closed by #78 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/96#issuecomment-2777806773" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

Closed by #97 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/100#issuecomment-2777821770" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

Bug is not an isolated issue. Related to #104 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/122#issuecomment-2777823286" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

Closed by #124 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/127#issuecomment-2777830469" expanded>
<div slot="header">

**32 :octicon-comment:** %%(other comment)%%
</div>

Closed by #128 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/123#issuecomment-2777831669" expanded>
<div slot="header">

**33 :octicon-comment:** %%(other comment)%%
</div>

Closed by #126
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/176#issuecomment-2782085167" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

Fixes #88 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/88#issuecomment-2782095816" expanded>
<div slot="header">

**35 :octicon-comment:** %%(other comment)%%
</div>

Fixed by #176 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/203#issuecomment-2783936601" expanded>
<div slot="header">

**36 :octicon-comment:** %%(other comment)%%
</div>

Closes #89 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/89#issuecomment-2783951520" expanded>
<div slot="header">

**37 :octicon-comment:** %%(other comment)%%
</div>

Closed by #203 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/133#issuecomment-2785055531" expanded>
<div slot="header">

**38 :octicon-comment:** %%(other comment)%%
</div>

Closed by #198 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/191#issuecomment-2785194201" expanded>
<div slot="header">

**39 :octicon-comment:** %%(other comment)%%
</div>

Closed through multiple PRs to UG.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/193#issuecomment-2785285251" expanded>
<div slot="header">

**40 :octicon-comment:** %%(other comment)%%
</div>

Closed by #220 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 16. GOVI..KSHA `@roshnidaksha` (**23** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/14#discussion_r1971268534" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

There is a merge conflict in this line. Please resolve it locally.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/18#discussion_r1979508342" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is it better to move these exception messages into `InterSprintMessages.java` and break down the message into an error message and `MESSAGE_USAGE` so that it syncs with format of other commands and useful while creating `help` command.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/29#discussion_r1990494309" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Instead of copying the message usage, can try using the `MESSAGE_USAGE` string for each `*Command` class?
For example, `COMMAND_HELP_MESSAGES.put("add general", AddGeneralCommand.MESSAGE_USAGE)`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/35#discussion_r1992802450" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These lines create an internship object from a JSONObject. This could be extracted into a separate method for better SLAP.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/35#discussion_r1992807370" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Since `loadInternships()` throws a `RuntimeException`, can we use a try-catch block here?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/37#discussion_r1997476019" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Better to add a space between REQUIRED_PARAMETERS and OPTIONAL_PARAMETERS
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/37#discussion_r1997476192" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Space between `+`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/37#discussion_r1997476234" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Space between `+`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/37#discussion_r1997476272" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Space between `+`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/85#discussion_r2009019656" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This comment is redundant as isValidParameters() is self explanatory.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/85#discussion_r2009019674" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This comment is also redundant
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/85#discussion_r2009019759" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Redundant comment 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/85#discussion_r2009019781" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Redundant comment
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/85#discussion_r2009019963" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This comment is redundant. Same issue is found at several other places. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/79#discussion_r2009167431" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Egyptian Style is preferred for brackets. Same issue was found at one another place too.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/79#discussion_r2009168155" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Does `roundCounter` need to be incremented after adding a new round?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/104#discussion_r2019842089" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Misspelled word "yout". Should be "your".
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/104#discussion_r2020065409" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can use ASCII table library here?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/122#discussion_r2021171879" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think we should stick to using `InternSprintLogger` for logging messages. Can replace this line with,
`private static Logger logger = InternSprintLogger.getLogger();`
in all files where logging is used.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/122#discussion_r2021174016" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think it is better to add a line after the description in Javadoc comments.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/122#discussion_r2021179269" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The same set of lines is found in `InternshipStorageHander.java`. Would you want to find a way to extract it out?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/155#discussion_r2027076246" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

ListCommand is not abstract by itself
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/243#discussion_r2030436524" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this line added by accident?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 17. AMIR..MUSA `@amirhusaini06` (**22** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/67#discussion_r1997559142" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

hese dependencies are commented out for now, which makes sense if they are not yet implemented. However, consider using dependency injection when integrating them in the future for better modularity.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/67#discussion_r1997559293" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The test framework imports are commented out. Once the CommandParser class is implemented, consider enabling these imports and adding test cases to validate basic command parsing.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/67#discussion_r1997559321" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The test class is currently empty. Consider adding a basic test stub to verify that the CommandParser can be instantiated successfully.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997559912" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

 The empty constructor is noted as "temporary for JUnit testing." If additional dependencies are needed later, consider adding a parameterized constructor
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997560028" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Potential Issue: If getCommandSeparatorIndex(input) returns -1, extractCommand() and extractInfo() will throw an exception. Consider handling this case before calling substring().
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997560133" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Improvement: If the input does not contain spaces, this will return -1. Before using this index, ensure that your code checks for valid indices.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997560225" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Edge Case: If commandSeparatorIndex == -1, this will throw StringIndexOutOfBoundsException. Consider returning the entire input string instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997560279" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Edge Case: If commandSeparatorIndex == -1, this will cause an error. Consider returning an empty string ("") in such cases.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997560462" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

 Edge Case Consideration: These tests correctly validate scenarios with spaces and empty strings. However, ensure that parseCommand() can handle cases where getCommandSeparatorIndex() returns -1.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997560531" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Potential Issue: Right now, this test expects an empty string when extracting from an empty input, but later implementations might throw an exception. Update the expected behavior accordingly.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/68#discussion_r1997560590" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

 Potential Issue: Similar to extractCommand(), extracting from an empty string might need explicit exception handling.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/69#discussion_r1997561279" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

parseCommand() assumes the command is always the first 5 characters. This could break if input is too short. Consider checking input.length() before substring() to avoid exceptions.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/69#discussion_r1997561443" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Switch case structure is clear, but adding a default case with logging or an exception would help catch invalid commands instead of silently ignoring them.


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/69#discussion_r1997561563" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Currently, no error handling is in place for invalid input formats. Consider validating the structure of info before extracting array indices.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/69#discussion_r1997561684" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Test cases for splitInfo() cover common scenarios, but an edge case for incorrectly formatted input (e.g., missing values) could be added.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/70#discussion_r1997562357" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Extending Exception makes sense, assuming this is meant to be a checked exception (forcing handling at compile-time). If runtime behavior is preferred, consider extending RuntimeException instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/70#discussion_r1997562457" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The constructor correctly calls super(message) to pass the error message up to Exception. Consider adding a default constructor with a generic message to improve usability
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/70#discussion_r1997562588" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Same structure as InvalidCommand, and consistency is maintained. 

Consider renaming to InvalidStringException for clarity, as it follows Java naming conventions for exceptions.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/70#discussion_r1997562668" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Like InvalidCommand, it correctly propagates the exception message. A default constructor with a general message could improve usability
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/129#discussion_r2014428828" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good validation to prevent null or empty passwords. You might consider adding a loop to prompt the user again instead of throwing an exception immediately.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/129#discussion_r2014431683" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This handles I/O errors well, but consider logging the full stack trace for debugging instead of just printing the message.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/129#discussion_r2014436777" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Efficient approach to reading business data. However, adding a check for invalid parts.length could improve robustness, as corrupted files might not contain all expected fields.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 18. TEH .. XUE `@zexueteh` (**17** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/20#discussion_r1999366934" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Exclude data files from commit. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/20#discussion_r1999368273" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Remove debug prints.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/20#discussion_r1999369836" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can be abstracted out for better SLAP. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/35#discussion_r2003386530" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

bug fixes for #31 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/35#discussion_r2003388578" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Add more positive cases e.g. "002", "-1" 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2007157456" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

EmptyTableException is  UI exception, should not be used in this context
Create a new EmptyListException under Model
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2007159618" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Same as previous comment about EmptyTableException
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2007160665" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of user-defined exception, correctly inheriting from RuntimeException.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2007162338" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This line should be abstracted to the constructor of ApplicationManager
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2007164654" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of Dummy class to test Commands that depend on ApplicationManager
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/55#discussion_r2009120258" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should also print Application Status upon adding
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/55#discussion_r2009122380" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Adding Table headers here breaks abstraction, should be done in UiMain or UiTable
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/55#discussion_r2009135445" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of singleton instantiation.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/55#discussion_r2009135845" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Correct implementation of Singleton pattern.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/59#discussion_r2009171210" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good implementation of Singleton logger.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/75#discussion_r2011678654" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of assert for Defensive programming!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/106#discussion_r2026973384" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

documentations changes should be part of a different PR
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/41#discussion_r2003944746" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

To be addressed in #22 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/1#issuecomment-2670553951" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/36#issuecomment-2746740014" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

DeleteCommandParserTest updated in linked PR. Issue can be closed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/203#issuecomment-2783938346" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/156#issuecomment-2784129351" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

clear command not within feature list
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/164#issuecomment-2784131280" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

refer to user guide, -s and -d are optional flags. They default to APPLIED and current date if not provided.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/131#issuecomment-2784147589" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

command words are specified to be case sensitive in the features. No mention of case insensitivity, not a feature we will explore. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/94#issuecomment-2784149740" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

closed by #165 
character limit set to 50
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/138#issuecomment-2785105672" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

can clarify it to SCREAMING_SNAKE_CASE
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/171#issuecomment-2785262894" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

closed with development in linked PRs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/148#issuecomment-2785263966" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

closed with more appendix explanation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/196#issuecomment-2785280313" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

closed by #220 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/222#issuecomment-2785284688" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

closed by #221 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 19. WONG..WHEE `@ChingWhee` (**16** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/18#discussion_r2002756096" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like that you changed the main file to our project's name
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/18#discussion_r2002767336" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like that you make the Ingredient class with the necessary functions so that other files that depend on Ingredient and set and get the necessary information
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/18#discussion_r2002772955" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you created the base class for testing
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/21#discussion_r2002777903" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you inherited from the Catalogue class for the recipe, since recipe is a catalogue of ingredients
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/21#discussion_r2002786323" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great test for checking the ingredient's constructor method 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/26#discussion_r2002936691" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like your JUnit tests for whether there are sufficient ingredients to cook a recipe
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/26#discussion_r2002937311" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you added the key commands for adding ingredients
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/26#discussion_r2002939052" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You can use the IngredientCatalogue instead of making a new list, as IngredientCatalogue has all the specific features implemented
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/40#discussion_r2004099122" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you abstracted out the loading of the catalogue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/53#discussion_r2019747190" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you handle the storage saving in the ByeCommand
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/53#discussion_r2019747456" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I feel like run should indeed be in the controller package. However, I still think that the higher level methods such as start() and exit() should be in the main class on their own
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/53#discussion_r2019747645" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you use for-each loop, which is cleaner and more readable and generic-safe
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/53#discussion_r2019748053" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you resolve the file paths rather than hardcoding it, as it reduces redundancy and improves maintainability
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/54#discussion_r2020126503" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you renamed the variables, making it less confusing and distinguishing between recipe and recipe book
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/54#discussion_r2020127722" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe instead of allowing all catalogue to be passed as parameters and typecast later, you should only allow IngredientCatalogue to be passed into the function
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/54#discussion_r2020128330" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you added a new screen for cooking
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/20#issuecomment-2721958023" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

close #9 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/21#issuecomment-2724007420" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/26#issuecomment-2726550332" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/39#issuecomment-2736342640" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

LGTM! I like how you add JavaDoc for the methods
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/42#issuecomment-2739212657" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

To modify commit contribution
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/76#issuecomment-2774713542" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/79#issuecomment-2774802494" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/89#issuecomment-2777578891" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/159#issuecomment-2779207155" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/182#issuecomment-2783517187" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/183#issuecomment-2783558500" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/187#issuecomment-2783816089" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/185#issuecomment-2784044669" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/188#issuecomment-2784533510" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/194#issuecomment-2784714425" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/197#issuecomment-2785052543" expanded>
<div slot="header">

**32 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/200#issuecomment-2785174551" expanded>
<div slot="header">

**33 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/206#issuecomment-2785224720" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 20. GOH ..BING `@Yikbing` (**15** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/21#discussion_r1997488695" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Avoid wildcard imports, each class import should be explicit.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/100#discussion_r2019786677" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Consider extracting the regex pattern "[a-zA-Z0-9 ]+" into a named constant for better readability
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/98#discussion_r2020557081" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

would be good to change this and amtPattern as a private static final constant since it is re-used a few times! 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/98#discussion_r2020558287" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

It would increase readability if you make the numbers into constants and describe what they represent to reduce magic numbers in the code!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/98#discussion_r2020562624" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Some error messages are defined as constants, while others are not. For better consistency and maintainability, it would be better to standardize using constants throughout to ensure uniformity and make future updates easier. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/98#discussion_r2020601577" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This Error message can also be extracted to ensure consistency throughout!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/107#discussion_r2022380150" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

can use InvalidDateException instead for consistency!

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/107#discussion_r2022381616" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could use InvalidNumberFormatException OR MissingAmountException instead to maintain consistency

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/107#discussion_r2024397678" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For this Diagram, could be good if you had the activation bars as well as return arrows within the image!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/195#discussion_r2030054012" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

this allows for more than 4 inputs for the number so it might not be what we want? Having exactly 4 digits could be more appropriate for this!

`("d/(\\d``{``2``}``-\\d``{``2``}``-\\d``{``4``}``)")`
could be better without the comma
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/195#discussion_r2030054770" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For this amtPattern, this may not be the best as the Users will be able to update it to a number larger than 7 digits in integers and 2 digits in decimal! We have decided on 7 digits in integers and 2 digits in decimals as the maximum. Hence a better pattern to use could be 
`"\\d``{``1,7``}``(\\.\\d``{``1,2``}``)?"` 
where the maximum number of digits is constrained
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/195#discussion_r2030055201" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For this, delete-income and expense will be updated to be index of their respective entries instead already but I will manage this in my PR, so should be fine if no additional changes is made to it!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/198#discussion_r2030190691" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

the no matching command part doesnt come from anything, might want to check the file again!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/198#discussion_r2030190907" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

return arrow is in the wrong format for the trimmed input.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/198#discussion_r2030191319" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

size != 0 return arrow doesnt come from anything?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/193#discussion_r2030045949" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

should be updated now, just resolved merge conflicts after pull from upstream 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/112#issuecomment-2772258644" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

merged by Yikbing as no major changes were made, only changed puml to show without icons
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 21. SRIN..HREE `@NandhithaShree` (**13** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/34#discussion_r2003420433" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good job following naming conventions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/34#discussion_r2003431473" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good job in taking care of exceptions! :)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/39#discussion_r2004954361" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great Job handling edge cases!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/39#discussion_r2004963211" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great job naming the tests like shown in the lecture
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/38#discussion_r2004966401" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great that you handled the case where the group cannot be found! 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/53#discussion_r2008994639" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice job in the use of OOP, improving code organisation. Well Done! 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/56#discussion_r2009152266" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

 It is very important to ensure the user does not input erroneous dates :)
 So good job checking for the validity of the date!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/60#discussion_r2017862224" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

lovely detailed description added to week 10, keep it up!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/60#discussion_r2017863278" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great that we have multiple options!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/64#discussion_r2020169583" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great to format the different commands so that it's easier to work as a team!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/65#discussion_r2020171186" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great that you split them in a readable manner!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/67#discussion_r2020220274" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I love how keywords automatically categorise expenses. Very impressive!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/68#discussion_r2020220602" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great detailed edit to the UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/136#issuecomment-2780590816" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Should be okay after sort-expenses is merged
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/135#issuecomment-2780598088" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

added format and usage section
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 22. LIU ..ENYI `@lwenyi1` (**11** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/27#discussion_r1994746208" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can change to a const variable called `DELIMITTER`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/48#discussion_r2016898755" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice change
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/51#discussion_r2022074363" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can the delete command handling logic be put into a separate function like `handleDelete()`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/59#discussion_r2026504383" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

No longer have solve in 1 line due to inconsistencies when solving FITB and MCQ (functionally it would just be weird for users)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/59#discussion_r2026506193" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice additions, think it's worth adding another segment for automated testing to talk about the Junit tests and test scripts?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/59#discussion_r2026512264" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Better to have this as 300 by 300 pixels to standardize with the other image files, otherwise fire pic
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/61#discussion_r2027038751" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe we can have two formats, one for FITB and one for MCQ? Think we should assume users are of questionable intellect
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/61#discussion_r2027040017" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice catch 🤣 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/98#discussion_r2029812728" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for highlighting this 😭
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/99#discussion_r2029842364" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Ty for cleaning this up 🙏 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/100#discussion_r2030017960" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice find
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/69#issuecomment-2780662102" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

> Instructions are clear in User Guide, but we can still decide if we want to implement this guidance

Small change, can be added p fast @Flaaaash 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/91#issuecomment-2780663284" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

I already limited it to the main stuff to make it slightly less complex, what do the rest think about simplifying further?

Tempted to ignore this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/91#issuecomment-2781200051" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Team has decided the current level of detail in the diagram is needed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/76#issuecomment-2781736743" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Inputting control signals is now covered in UG. Should we still try and solve this in the program itself?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/76#issuecomment-2782645541" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Fixed with UG.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 23. MATT.. WEN `@matthewyeo1` (**11** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2028031632" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good explanation of parser class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2028033212" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good explanation of logic class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2028033899" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Adding an example is a good idea to illustrate the interactions between the classes

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/118#discussion_r2028036674" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Clear layout of core classes that constituent the app
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/31#discussion_r1995117864" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Will the check for user input for 'yes' and 'no' be case-sensitive?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/31#discussion_r1995123515" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Recommended to place the string literals under Messages.java to adhere to Java Coding Standards better
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/59#discussion_r2010112406" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good call on adding the new feature as a keyword under the Commands.java class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/59#discussion_r2010114737" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Wow...adding this many approved exchange rates adds so much coverage in our app, well done!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/59#discussion_r2010115242" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good usage of JavaDoc comments as well!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/70#discussion_r2020492975" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good idea to prompt the user to confirm expense deletion! Prevents any accidental inputs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/70#discussion_r2020493654" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for updating the text UI tests as well
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 24. PHUA..NICE `@venicephua` (**11** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/30#discussion_r1997667038" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

maybe can call the expense newExpense instead to be clearer?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/41#discussion_r2006331584" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

maybe should rename one of these because they are kind of overlapping
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/41#discussion_r2006348129" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

might be difficult to read this part? could consider extracting out and expressing it as a boolean instead, like isNumeric

`boolean isNumeric = parts[1].matches("\\d+(\\.\\d+)?")`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/74#discussion_r2021443087" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good job returning a copy of the expenses and maintaining the code's defensiveness!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/74#discussion_r2021444224" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

i like that there are separate managers for the regular and recurring expenses
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/75#discussion_r2021605692" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

hm i cant view the diagram so i cannot verify that it will show up properly in the DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/75#discussion_r2021609608" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

perhaps adding an example usage (and the steps involved in adding a recurring expense) would be good?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/98#discussion_r2026720207" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

agreed! can consider moving extracting some code into methods in ExpenseReporter 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/167#discussion_r2029213849" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

looks good!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/167#discussion_r2029214682" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

looks good and clean!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/196#discussion_r2030159752" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

i think you have to change the date flag in AddCommand as well to fix the checkstyle issues!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 25. NAND..HANA `@nandhananm7` (**11** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/53#discussion_r2008808732" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Appropriate use of SLAP here, improving the code readability. Well Done!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/53#discussion_r2008809073" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good Job extracting out all the error messages.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/64#discussion_r2020169636" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job updating and maintaining the user guide
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/64#discussion_r2020169716" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good OOP followed 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/64#discussion_r2020169859" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Useful feature addition
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/65#discussion_r2020171097" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good exception handling!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/65#discussion_r2020171215" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good comments and use of try catch block
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/67#discussion_r2020860579" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job implementing pie charts to improve user experience
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/67#discussion_r2020861317" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Very useful feature for users to improve user-friendliness
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/67#discussion_r2020862124" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job testing for all the new additions and edge cases
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/206#discussion_r2032742691" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thank you for updating the links
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/151#issuecomment-2781419615" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Code changed to not allow duplicate members
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/139#issuecomment-2781424828" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Modified code to not allow duplicate members
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/144#issuecomment-2782499976" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Updated ug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/141#issuecomment-2782502699" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Updated UG to fix this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/134#issuecomment-2782509675" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/132#issuecomment-2782510198" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/126#issuecomment-2782519957" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

View-group now shows only the members,
to view the exact amount transactions for a single member, use view-member
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/122#issuecomment-2782521464" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/issues/106#issuecomment-2782524254" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 26. SARA..ETHA `@swethacool` (**10** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2014595302" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For isWon, the condition to be checked should be (currentScore >= blindScore) but not (currentScore >= blindScore & isRoundOver()) as even though the player beats the blindScore, the player will not be declared as won if the round is not over. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2016964492" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

sortByRank and sortBySuit tests have almost identical logic for adding cards and checking order, perhaps its better to refactor the common setup logic into a helper method to improve readability and avoid duplication?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2016994675" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps you could refer to my PR on the ante system as it handles all the ante counts and it also ensures the ante increments after every Boss blind (after the end of every complete round). 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017002991" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps you could refer to my PR on the Blind system as it handles 3 different Blind types already (small, large, boss) as it would be easier to execute the logic of the boss implementation in the gameplay.  
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017005225" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Check the above comments 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/93#discussion_r2017007159" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Yes the condition is correctly implemented!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017028994" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Do note that method names like getdeckName() should follow camelCase (getDeckName()).
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017039399" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This clone performs a shallow copy instead of a deep copy, meaning that while the cloned deck is a new object, the individual card objects are still shared between the original and the clone. If the cards in the original deck are modified during the game, those modifications will also reflect in the cloned deck. However deep copy ensures that the changes to the original deck’s cards won't affect the cloned deck.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017040763" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM !
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/99#discussion_r2017044173" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could perhaps remove these unnecessary comments if not needed for better readability !
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2016951449" expanded>
<div slot="header">

**11 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I had the ante object in JavatroCore itself, but JavatroCore is responsible to spin a new round, so a new ante will be create each time a new round is created which is not what we need.

JavatroManager handles a complete game, so there will be one new ante object per game, not for each round. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2017212992" expanded>
<div slot="header">

**12 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Fixed it in the latest commits
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018062129" expanded>
<div slot="header">

**13 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed it in the recent commits
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018071397" expanded>
<div slot="header">

**14 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Fixed it in the recent commit
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018079830" expanded>
<div slot="header">

**15 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

it has been addressed in the previous comment :  had the ante object in JavatroCore itself, but JavatroCore is responsible to spin a new round, so a new ante will be create each time a new round is created which is not what we need.

JavatroManager handles a complete game, so there will be one new ante object per game, not for each round.


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018083606" expanded>
<div slot="header">

**16 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I thought its being commented in the javadoc itself so its unnecessary to comment it again? 
if really needed Ill add back ? 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018083719" expanded>
<div slot="header">

**17 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I thought its being commented in the javadoc itself so its unnecessary to comment it again?
if really needed Ill add back ?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018084001" expanded>
<div slot="header">

**18 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I thought its being commented in the javadoc itself so its unnecessary to comment it again?
if really needed Ill add back ?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018084111" expanded>
<div slot="header">

**19 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I thought its being commented in the javadoc itself so its unnecessary to comment it again?
if really needed Ill add back ?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2018110898" expanded>
<div slot="header">

**20 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

noted will look into it and fix it soon 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2019695490" expanded>
<div slot="header">

**21 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed in the lastest commits 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2019695526" expanded>
<div slot="header">

**22 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed in the lastest commits
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/95#discussion_r2019695874" expanded>
<div slot="header">

**23 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed in the lastest commits
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2023191778" expanded>
<div slot="header">

**24 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed in the latest commit 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2023199027" expanded>
<div slot="header">

**25 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

yup i removed it in the latest commit itself : c1fe1c8 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024331187" expanded>
<div slot="header">

**26 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed it in the latest commits.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024331331" expanded>
<div slot="header">

**27 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed it in the latest commits.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024331466" expanded>
<div slot="header">

**28 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed it in the latest commits.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/137#discussion_r2024331563" expanded>
<div slot="header">

**29 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

fixed it in the latest commits.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/141#issuecomment-2776222696" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

LGTM 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-1/tp/pull/144#issuecomment-2776290887" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 27. CAI ..UBIN `@xubin0` (**10** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/87#discussion_r2022112237" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good job handling exception here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/87#discussion_r2022113931" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

i like that you reorder the imports and grouped them
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/95#discussion_r2022713096" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great job noticing this subtle difference
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/95#discussion_r2022713934" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

this format without comma is much clearer, i like it
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/98#discussion_r2022872190" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

this line is too long, will fail check style test
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/99#discussion_r2022898749" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great job adding relevant JUnitTests
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/103#discussion_r2023220751" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great job adding multiple tests 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/103#discussion_r2023221385" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

i like that you are standardising all command format
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/104#discussion_r2023223806" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great job adding missing getters
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/104#discussion_r2023226207" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

greatjob testing the ListTaskCommand
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 28. POH .. WEN `@Betahaxer` (**9** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024516457" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good catch. This is also to prevent the thick jar file from getting too big. Although in this case it is a custom class so that shldn't happen
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024522374" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I have arranged the commands previously according to its functions. May I know if you would prefer to have them arranged otherwise? 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024524173" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Also, the case statements should not be indented under switch.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024525313" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

could you keep the comments in english please so that those reviewing the code can also understand?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024526708" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same for these, keep the comments to english please
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024528472" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

sorry, could you explain the reasoning behind this file? is it a file required for the UI?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024533235" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

May I know if usage of this library is approved?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/140#discussion_r2030411949" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can add data files to .gitignore please
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/140#discussion_r2030412068" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same here, remove data files
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/129#discussion_r2030077151" expanded>
<div slot="header">

**10 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I wanted to prevent the user from inputting any arguments after the "unselect" command. So, I have to pass in the arguments to check for that.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/127#issuecomment-2779301691" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Able to test test case 2 and 3 if you exit the app and start again. Possible to include a command to unselect deck but it is not critical
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/112#issuecomment-2779356652" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

potential duplicate with #117 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/109#issuecomment-2779375048" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

No given steps to reproduce or any description.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/106#issuecomment-2779389133" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Behaviour is intended. However, this could be a possible improvement to be able to unselect a deck.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/104#issuecomment-2779394569" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Intended behaviour, but can consider if flashcards should be duplicated or not.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/99#issuecomment-2779401559" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Intended behaviour. Flashcards should not be saved when the program unexpectedly shuts down
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/94#issuecomment-2779422348" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

duplicate with #77, #99, #92 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/83#issuecomment-2780727252" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

duplicate with #113
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/104#issuecomment-2780734726" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

We will allow flashcards to be duplicated, as it increases the strategies and flexibility for the user. For example, repeating a flashcard can help reinforce a key concept by increasing exposure during review.

The Developer's Guide will be updated to reflect this.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/127#issuecomment-2781189255" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

Added unselect, do also update the developer's guide under the testing part
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/124#issuecomment-2781203998" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

I have included a basic description from our previously written user guide, please update it if its not up to date.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/108#issuecomment-2781389788" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Valid suggestion, but we will not be adding this to v2.1 as it will mess with the UI

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 29. TAN ..SHIN `@Yshinprograms` (**9** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/24#discussion_r2001228780" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would it be possible to add in summary.addSavings(amount) here so that your savings show up in the summary as well?
Do refer to Summary class for implementation if needed, thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/24#discussion_r2001230164" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would it be possible to add in summary.removeSavings(amount) here so that your removals show up in the summary as well?
Do refer to Summary class for implementation if needed, thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/24#discussion_r2001234258" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Do help to check that your all your commands are documented correctly in java/ui/HelpDisplay as well thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/35#discussion_r2009018001" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This substring(17) seems like a magic number, perhaps you could consider using a constant or using a comment to explain the choice for this number?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/35#discussion_r2009018301" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The naming conventions for tests don't seem to follow name_input_expectedOutput, maybe you can refer to the CS2113 dashboard if still unsure?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/45#discussion_r2019103105" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

should 4. showExpenses() point to the top of the activation bar for :ExpenseList?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/45#discussion_r2019105383" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

should 5. addExpense() point to the top of the activation bar for :ExpenseList?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/58#discussion_r2020096560" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should the lifelines(dotted lines) continue after the activation bars for :Duke and :Saving?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/66#discussion_r2022151467" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

As per Prof's comments, can just remove these end-of-line comments
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/16#issuecomment-2730218228" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Not sure if failing Java CI is related to gradle setup, but maybe check the mainClass in build.gradle?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 30. JAHA..DHAN `@mohammedhamdhan` (**9** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/57#discussion_r2011251233" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good check for valid date!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/57#discussion_r2011251481" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of setters!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/59#discussion_r2016043803" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This is a very comprehensive list of currencies!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/59#discussion_r2016045374" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

A suggestion would be to try replacing the nested if statements, so the code would follow SLAP
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/65#discussion_r2020169719" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great that you have used multiple catch exceptions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/73#discussion_r2022557062" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great use of String literals.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/73#discussion_r2022557855" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Assert statement here is very useful!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/73#discussion_r2022558320" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good null check!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/72#discussion_r2022562443" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good dev guide update!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/33#issuecomment-2731556616" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Great that you followed the test naming convention!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/34#issuecomment-2736786112" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Good use of classes. I like that you made a new class and it helps with modularisation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/34#issuecomment-2736790396" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

A suggestion would be to add more comments, maybe some JavaDoc ones, to explain the thought process :)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/38#issuecomment-2739394599" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Great job covering edge cases with your edits!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/53#issuecomment-2746070968" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Good use of SLAP!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/56#issuecomment-2746863344" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Great handling of edge cases!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/61#issuecomment-2760118508" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Great job resolving the merge conflicts!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/63#issuecomment-2763396395" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Thanks for resolving the conflicts!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/68#issuecomment-2764630233" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

Great additions to the User guide! It's much more comprehensive now!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/69#issuecomment-2765242552" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

Great updates to make the UX better!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/178#issuecomment-2783074681" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

Good job Hamdhan!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-2/tp/pull/206#issuecomment-2785746385" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

Amazing job! Let's get it!

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 31. SEAN..POON `@Sean2110` (**9** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/29#discussion_r2005452623" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

These could be placed in Ui instead of the main bobo file
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/29#discussion_r2005461335" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

TimerTest looks good 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/53#discussion_r2020386159" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Looks good! It makes sense for highscore to be calculated in the normal mode only
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/53#discussion_r2020388193" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

it looks neater now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/74#discussion_r2027014160" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job! I like that the warning is clear
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/78#discussion_r2027198169" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

looks good to me
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/78#discussion_r2027199784" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice catch
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/137#discussion_r2031710426" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/137#discussion_r2031712226" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 32. YEE ..LTON `@Carlton369` (**9** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/78#discussion_r2026412349" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good test to ensure that our program is able to handle cases where the save .txt file gets altered or corurpted!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/78#discussion_r2026415099" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Clean documentation to help developers understand the expected behavior of this class!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/27#discussion_r2026421647" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Should this be implemented in the main? Please write any unit tests properly and ensure that this is not released to users
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/27#discussion_r2026424259" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good template methods for superclass, these general operations will help streamline the implementation of child classes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/27#discussion_r2026427094" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Very neat function to help users find possible substitutes if they are missing ingredients
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/31#discussion_r2026444222" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of OOP to abstract the commandResult, this will make it easier for developers to dictate the final state of the program once the command has finished execution
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/81#discussion_r2026446814" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good UI change, thanks for locating where the reported bug was located
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/81#discussion_r2026448606" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good catch! this will make it more user friendly by making the logic not case-sensitive
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/81#discussion_r2026453216" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Have we sufficiently tested for all conditions? Perhaps we should add tests for invalid or unexpected inputs for these commands.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/9#issuecomment-2720134364" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

RecipeList class has single attribute of array of Recipes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/19#issuecomment-2721987921" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/20#issuecomment-2721990618" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/23#issuecomment-2724060047" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/24#issuecomment-2724279912" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/27#issuecomment-2726551884" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/36#issuecomment-2733781397" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Brilliant addition Chuan Hui! This will really help our users understand how our program is run and provide a friendly user experience through the clear messages. The code written is also extremely readable and would be easy to improve on following future updates. Looking forward to future stellar changes made by you!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/60#issuecomment-2768987845" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

thanks for the fixes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/61#issuecomment-2774718656" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

in that case we should make it clear that this is the expected behaviour in the UI
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/78#issuecomment-2774787069" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/61#issuecomment-2775900463" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

have refactored code
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/84#issuecomment-2775924536" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

also updated DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/90#issuecomment-2777637098" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Thanks for updating the UML diagrams!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/91#issuecomment-2777898658" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

for recipe also, bug probably in the ingredient class
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/93#issuecomment-2779008434" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

fix issue #98 and #99
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/93#issuecomment-2779164243" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

for issue #94
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/159#issuecomment-2779168097" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

fix issue #96  and #97 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/93#issuecomment-2779193705" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

fix issue #150 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/159#issuecomment-2779206288" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

issue #147 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/160#issuecomment-2779230560" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

#141 

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/160#issuecomment-2779250315" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

#148 , #121
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/164#issuecomment-2780371106" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/177#issuecomment-2781480113" expanded>
<div slot="header">

**32 :octicon-comment:** %%(other comment)%%
</div>

#161
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/181#issuecomment-2782931747" expanded>
<div slot="header">

**33 :octicon-comment:** %%(other comment)%%
</div>

lgtm

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/184#issuecomment-2783656945" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

lgtm, just a nit, should we make cook reachable from the inventory screen? it might be more user friendly to cook a recipe after seeing cookable recipes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/193#issuecomment-2784715632" expanded>
<div slot="header">

**35 :octicon-comment:** %%(other comment)%%
</div>

lgtm!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/200#issuecomment-2785152776" expanded>
<div slot="header">

**36 :octicon-comment:** %%(other comment)%%
</div>

#191
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 33. LIM ..SAAC `@Isaaclks7` (**8** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/90#discussion_r2014394160" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how simply and concisely this is explained.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/94#discussion_r2016982895" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you organized the different error messages into seperate issues!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/94#discussion_r2016992679" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps you could update the medicine quantity without deleting the medicine.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/96#discussion_r2017864908" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you split and named the respective attributes to make it readable
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/96#discussion_r2017866993" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

There is a missing space after 'try', it should be "try (Filewriter...)".
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/120#discussion_r2020593708" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You may consider printing the shift which was marked for the user to see, similar to the logger you have done.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/120#discussion_r2020594119" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

There should be consistent spacing between "try ``{``" and "``}`` catch".
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/120#discussion_r2020596334" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I like how you had a different parser method for each shift command!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/176#issuecomment-2780205519" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/178#issuecomment-2780210430" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/180#issuecomment-2780220463" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/181#issuecomment-2780303788" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out! Issue resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/182#issuecomment-2780335339" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/183#issuecomment-2780341513" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Thanks for your suggestion, UI has been updated to make it much more readable!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/179#issuecomment-2780372238" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/187#issuecomment-2780711088" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, we have standardized the error message to give users a clearer idea of what went wrong!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 34. TAN .. HUI `@ae-24` (**8** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/54#discussion_r2023197495" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps can consider adding an example output
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/54#discussion_r2023198701" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good that clear instructions on how to run the file was included
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/120#discussion_r2029169765" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job including exception handling for overflow conditions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/120#discussion_r2029171458" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good to include an FAQ. Perhaps can direct users to FAQ in quick start.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/120#discussion_r2029172384" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great idea including a table of contents for easier navigation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/128#discussion_r2030102648" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great job accounting for cases of displaying overall summary or for individual categories
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/128#discussion_r2030102704" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps can consider adding file as gitignore
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/128#discussion_r2030102875" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good exception handling for invalid inputs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/134#issuecomment-2783219334" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Great job adding tests for command subclasses
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/147#issuecomment-2784235329" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Great job updating information in the UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/149#issuecomment-2784512770" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Great job fixing the bugs and improving output messages.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/160#issuecomment-2785172877" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Great job adding manual testing instructions and fixing bugs in the diagrams
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 35. LI M..GYAN `@kmnyn` (**8** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/85#discussion_r2020932374" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The test for CommandListPrinter is well-structured. It helps to validate multiple expected command descriptions in the output.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/85#discussion_r2020935692" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Glad that you have keep the format more consistent by changing the hh:mm to HH:mm.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/86#discussion_r2021078472" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe it's better to check validation before retrieving the student
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/86#discussion_r2021082611" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Glad that you have done null checks.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/86#discussion_r2021084771" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Overall it is good that it throws meaningful exceptions.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/103#discussion_r2023217968" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good to see that the tests cover a variety of possible scenarios, including valid input, student not found, tutorial class not found, and invalid input format.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/103#discussion_r2023219805" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good use of methods like initializeTutorialClasses(), createTutorial(), and captureSystemOut() which make test setup clean and reusable.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/117#discussion_r2027212214" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job in being detailed and clear in explaining the tutorial commands implementation!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/194#discussion_r2029855841" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

There should be only one user. Thank you for pointing out. Resolved this error.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/60#issuecomment-2776207836" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

This issue is no longer relevant for v2.0.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/167#issuecomment-2779042751" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Tester forgot to put blank space in between "from"/"to" and datetime which is not following the instruction given.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/169#issuecomment-2779091700" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Tester forgot to put blank space between "from"/"to" and the datetime which is not following the given instruction.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/148#issuecomment-2780698911" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Missing deadline means missing deadline task name but not meaning that the user has missed deadline of the task. Edited the error description to resolve this confusion.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/153#issuecomment-2780700398" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Resolved this issue by clarifying the error message.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/165#issuecomment-2781815054" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

This message is from NumberFormatException, the number input by user is too large thus it throws an exception which categorizes it as not an integer. In practice, it is very unusual for one user to have such a huge number of tasks.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/159#issuecomment-2781818137" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

We have intentionally designed the logic such that valid input parts should be taken in before user can move on. We will take note of this inconvenience in future design. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/224#issuecomment-2783671784" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Good job in providing detailed class diagrams for data management and command handling.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 36. LEE ..YOON `@LEESY02` (**7** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/125#discussion_r2009143959" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Makes it very clear for user, nice implementation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/125#discussion_r2009144760" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for adding authors
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/125#discussion_r2009145469" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This whole stretch of code is quite lengthy with multiple try-catch segments. Maybe it will improve readability if you throw all of these into once try block and catch multiple errors in one catch clause
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/123#discussion_r2009146713" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps refactoring these boolean equations into a simple boolean method that sorts it into case segment may help in terms of readability and future expansion
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/123#discussion_r2009147075" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could remove the Math.max method since we are checking qtySold > currentQty in the if else statement
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/123#discussion_r2009147552" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Could print this message in recordSale() method in SalesManager for same level of Abstraction
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-1/tp/pull/123#discussion_r2009147725" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice additions in general :D
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 37. SHAN.. HUI `@shanicetanhui` (**6** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/27#discussion_r2001919196" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

'''suggestion
        this.file = new File(filePath);
'''
'File file' creates a local variable
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/27#discussion_r2001921387" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Might want to consider handling empty files.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/27#discussion_r2001934794" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

If you wish to return the file contents 'file.toString()' might not be the solution as it returns the pathname. 
'Scanner scanner = new Scanner(file);' might be what you are looking for?


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/131#discussion_r2030239729" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Very clear and straightforward. Diagram is a good value-add.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/135#discussion_r2031628494" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good consideration of the aspect.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/144#discussion_r2032272557" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good catch of exception!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/43#issuecomment-2750428231" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/46#issuecomment-2755432195" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Good and clear renaming of classes.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/45#issuecomment-2755474378" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Good improvement in simplifying the logic.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/48#issuecomment-2758859637" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/56#issuecomment-2767009300" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Nice usage of OOP with good code quality.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/63#issuecomment-2769836866" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Nice and clear formatting.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/65#issuecomment-2769927588" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

LGTM 😄 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/70#issuecomment-2775259038" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/73#issuecomment-2775464048" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/82#issuecomment-2777719211" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Good improvements in the clarity of the sequence diagrams!

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/129#issuecomment-2781433380" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Good job on clear and straightforward sequence diagrams.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/131#issuecomment-2781600409" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

Using a general representative class diagram helped to omit repetitive details. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/144#issuecomment-2785062909" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

Good job in fixing all ui inconsistencies.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 38. TANG.. YAN `@Lyam-T` (**6** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/21#discussion_r1997604531" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

why you need to change this? 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/21#discussion_r1997604582" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

why you need to add this? 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/69#discussion_r2005843311" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Why is this .> instead of ..>?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/69#discussion_r2005862626" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Understood! Thx
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/77#discussion_r2009002289" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

please use a different pull request to handle different issues
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/77#discussion_r2009002344" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

same as above, for the listing methods changes please start a new pull request thx!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/7#issuecomment-2724211095" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

This is the updated UML, see if anything incorrect. If no problems, I will later start a pull request to put this under docs as well. 
![Image](https://github.com/user-attachments/assets/e14d2c4f-1fd5-4363-b419-69a00a27fcd1)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/35#issuecomment-2728399075" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

close to try fix the wrapper-verification problem according to forum
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/45#issuecomment-2733390785" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

error review required approved yet cannot merge
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/10#issuecomment-2733774500" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Duplicated
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/60#issuecomment-2742297636" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

This pull request is fetched, updated and then open as a new pull request
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/89#issuecomment-2753540413" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Incorrect style of testing
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/92#issuecomment-2765449874" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

closed to start a new pull request, the merging has been resolved locally instead
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/16#issuecomment-2774407389" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

closed as move to developer guide 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/31#issuecomment-2774407755" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

closed as move to developer guide
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/138#issuecomment-2777586422" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

branch name incorrect, another pull request is opened instead
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/97#issuecomment-2781195246" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

close as will not be implemented
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/193#issuecomment-2781202971" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

After testing, it can take two commands with delay of output. 

<img width="712" alt="Image" src="https://github.com/user-attachments/assets/31646817-1c8a-4504-a839-456b8bb992f6" />

The exception message has been updated to

<img width="805" alt="Image" src="https://github.com/user-attachments/assets/2493e82f-47aa-4cbc-a47b-f91d628ac92c" />
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/192#issuecomment-2781209928" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

Updated to be within 366 days
<img width="432" alt="Image" src="https://github.com/user-attachments/assets/609472a4-2cce-4315-bea8-a7d01f05da10" />
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/191#issuecomment-2781210642" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

Note that in this command line application, there will be no self-evaluation of the user input happened as in website. hence there is no need to do input validation 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/214#issuecomment-2781310993" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

wrapper class is already used, and the exception is properly caught already
no need to handle
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/187#issuecomment-2785011090" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

due to time limit, currently will not implemented
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/189#issuecomment-2785286682" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

User don't really need to know the exact calculation for the percentage
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 39. FELI..N QI `@felfelyuen` (**5** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024276286" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Do you still want to keep this code? If not, can delete out the commented out code
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024278392" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

change import into single use imports instead, or else the github gradle checks won't pass through

**in the intellij ide, you can click on this line, and hover on the import word, and a lightbulb should appear. Click the lightbulb and it should give u the option to replace line 4 with single use imports
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024279770" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

line 22 already has import ui.Ui, so this line not needed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024280478" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Use single use imports instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/58#discussion_r2024284385" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Why is this test is commented out? If the new code added makes this test unworkable, sure but let me know, ill change the test function then.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/11#issuecomment-2724987036" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Looks good to me!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/16#issuecomment-2733453144" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Looks good to me!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/100#issuecomment-2780611930" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Closed issue, as bug is similar to #105, will be resolved with #105.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/117#issuecomment-2781219473" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Closed, duplicate issue, similar to #112 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/105#issuecomment-2784114207" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Closed with PR #139 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/82#issuecomment-2784114777" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Closed with PR #139
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/110#issuecomment-2784116733" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Closed with PR #139
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/111#issuecomment-2784117093" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Closed with PR #139
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/91#issuecomment-2784119289" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Closed, duplicate of issue #88 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 40. JAME.. JIE `@James17042002` (**5** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/2#discussion_r1976401931" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

add defend function? increase defense value by 100 for the next attack taken.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/2#discussion_r1976402906" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Add To String method for enemy? After each round of attacking display the enemy name, health, attack, defence, and maybe ASCII ART for the enemyeg 
-------------------------
Hydra
-------------------------
Health: [90, 45, 90]  Attack: 100  Defence: 25
-> insert hydra ASCII art here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/2#discussion_r1976403648" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

To do: add equipment class, player should have an array of equipment, maybe MAX_EQUIPMENT = 2 by default, increasing this through upgrades purchased. equipments grant attack and defence bonuses
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/2#discussion_r1976403732" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

To do: add gold. in game currency owned by the player
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/2#discussion_r1976403866" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Instead of printing enemy and player health bars, just print the enemy and player "toString" methods
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 41. WONG.. HAO `@wongyihao02` (**5** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/83#discussion_r2020764399" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good to abstract out repeating code
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/86#discussion_r2021141142" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

what if the MaxMark of a Mark object is set to 0?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/117#discussion_r2027210072" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice caps
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/117#discussion_r2027211079" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

nice highlight
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/187#discussion_r2029688240" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

seems to still be DELETETUT in the user guide
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/87#discussion_r2021186126" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

this one is not testing the commands,its supposed to check that the attendancelist functions for marking attendance and getting and giving comments work
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/118#discussion_r2027273393" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

yeah
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/118#discussion_r2027273505" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

yeah
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/118#discussion_r2027273944" expanded>
<div slot="header">

**9 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/15#issuecomment-2736183427" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

added list future tutorials and list all tutorial students
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/11#issuecomment-2736943490" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

closed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/60#issuecomment-2765432869" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

finished
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/77#issuecomment-2765459350" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

good job noticing the format issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/77#issuecomment-2765479595" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

nice change
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/82#issuecomment-2765735170" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

looks good,like the max attempts feature
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/139#issuecomment-2778990237" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

looking at this,it seems that all the documentation supports DELETETUT being the correct form when command factory only has delete -t
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/issues/125#issuecomment-2779009738" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

i think these are the emoji
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 42. LIU ..UYAN `@Flaaaash` (**5** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/19#discussion_r1994162087" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Remove the println for debugging.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/46#discussion_r2020080789" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

A null pointer reference violates OOP. Objects should always be in a valid state. Using null contradicts encapsulation by requiring external checks before usage. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/99#discussion_r2029881648" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job defining clearer error message displayed for the users.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/103#discussion_r2030111645" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Since almost all of our Command sub-classes use questionBank, we may as well just make it an attribute of Command super-class.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/116#discussion_r2031047943" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job clarifying this behaviour. Maybe can add a few more lines to explain the user can still delete 2 on the last shown list.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/90#issuecomment-2781034048" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

From the console output, on the line [Command you entered: add ], there is one extra space after "add". The output should be [Command you entered: add] regardless of the number of trailing spaces in the input. The issue is likely produced by the extra space captured in the [Command you entered: add ] but the method to produce it is unknown.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/79#issuecomment-2781036351" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

considering the impact on the app’s performance and functionality, I think we do not to implement an exhaustive input validation feature at this time.

Validating every possible input would require extensive checks, potentially leading to resource consumption that could slow down the app. Given that the user is in control of entering the question and answer content, I believe it is ultimately the user’s responsibility to ensure they input the correct data.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/78#issuecomment-2781037599" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

We now define the behaviour of the app in our user guide to allow the command input to be case-insensitive for ease of use, i.e. Help/help/HELP to provide more flexibility and improving ease of use based on users’ preferences for entering commands.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/72#issuecomment-2781358432" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Duplication of questions are handled now.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/106#issuecomment-2781530762" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Currently the easiest fix is to remove solve attempt logger.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/90#issuecomment-2782817525" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Input is now trimmed at every stage when input is read/split.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 43. TEO ..AVIN `@tzqgav10` (**5** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/91#discussion_r2015617529" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Code is well-structured and easy to read overall
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/94#discussion_r2017956003" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I see that in the Medicine class, there are checks for if quantity is negative or equal to 0. Double check if the code reaches there to display more accurate error messages.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/94#discussion_r2017960079" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great error handling overall.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/102#discussion_r2020048768" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice error handling, good to consider different inputs and display the relevant error message.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/149#discussion_r2026882882" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Are all the details important to include? Can consider splitting into different sequence diagrams if possible.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/132#issuecomment-2771806803" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Everything looks good.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/196#issuecomment-2781179572" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, it is now fixed!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/197#issuecomment-2781179926" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

It was intended to be this way, but I have now added a custom message if notes are empty, thanks for the feedback!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/202#issuecomment-2781180167" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Thanks for the feedback, I have removed the extra "P".
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/210#issuecomment-2781180381" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Fixed the bug, thanks for pointing this out!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/211#issuecomment-2781180767" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Now, contact will only take in 8 digits. Thanks for pointing this out!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/213#issuecomment-2781180892" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Fixed, age can only be within a certain range now. Thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/216#issuecomment-2781181126" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Contact will now only take in 8 digits. Thanks!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 44. CHOI..LONG `@choiak` (**5** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/21#discussion_r1995688869" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think there is unnecessary to store this Since ArrayList already can provide the number of item in the list.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/35#discussion_r1997499676" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think it may be better to check for CommandTarget first with one exception of the exit command. This way it is possible to pass the casted Command object into the action handler instead of casting in every execution method, reducing the amount of casting.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/68#discussion_r2006703624" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The test fail maybe because of it is creating a new local variable trip instead of initializing the trip attribute here.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/68#discussion_r2006704723" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The intention here is to perform assertion on the mode attribute but getter getName is used instead of getMode.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/68#discussion_r2006708197" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

The intention here is to assert there are no item, but why is 1 is used instead of 0?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/69#discussion_r2005845964" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

To make the arrow points horizontally.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 45. T HA..ARAN `@vegetablestabber` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#discussion_r2007870456" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

So I'm thinking we should abstract out each command into a separate file (sorry, Luke). The reason for this is because we want to decouple as much explicit logic from this file so it's better for testability.

Plus, I think the responsibility of 'CommandCenter' would be to house these 'Command's, not the logic for them. If the scope for this project was much smaller, this would have been perfectly fine but our scope keeps changing, so it'll also be better if we keep this logic immutable in a file and just add new 'Command's to this file when they come along.

I did something similar for my iP, but I think we should call the others to help out with this because there's a lot to deal with here.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#discussion_r2007870822" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

@AY2425S2-CS2113-W12-1/developers What do you guys think?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#discussion_r2007874185" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This is a good start, but we definitely need to push all UI code out of Main as well. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#discussion_r2007876786" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

@AY2425S2-CS2113-W12-1/developers Can someone assign themselves to #51? Thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/87#discussion_r2024012858" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Thanks Copilot!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/10#issuecomment-2699798186" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

i hate you
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/10#issuecomment-2699801923" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

> i hate you

i've changed my mind, i no longer hate you
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/28#issuecomment-2740944485" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Did a lot of refactoring for better cohesion
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/41#issuecomment-2741374884" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Also, I feel like adding a newline character at the start of the string is a bit cumbersome, when we can just add this as functionality to `Log::saveLog`, keeping this out of sight and out of mind.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/32#issuecomment-2741417441" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

> major major change but im sure the team will adapt eventually 🙏

the project will never be the same after this 😔✊
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#issuecomment-2743837992" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Changed the PR to a draft PR because there's a lot of changes that need to be made before we can merge
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/50#issuecomment-2744688039" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

> @vegetablestabber This is functionaly speaking complete, however it is VERY messy.
> 
> I'm going to be pretty busy over the next week, but if i find time I will do my best to clean it up as right now it is for lack of a better term shameful 😭

Honestly, don't stress over this too much because we're supposed to work as a team and you don't have to write this code all by yourself. Let's try to delegate amongst ourselves so it's easier on you. You're doing great, man. 🫡🤙🦅
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/50#issuecomment-2744706393" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

> But basically I wanted to say that if you need it to develop other features then you could always PR it, and it can be cleaned up at a later date? Like I said, it does work, so 🤷‍♂️

If I'm not mistaken about how merge conflicts work, I believe that our current approach could lead to really massive merge conflicts down the line because that one file could look completely different after such PRs. We're not supposed to prioritise functionality over the scalability of the code because it depends on the latter.

That being said, you can't always have perfect code before merging a PR, but closing a PR should really signal finishing an issue or we risk adding more issues to clean up code, thereby keeping our milestone progress stagnant.

This really only hinges on the fact that some of our code is exclusively in one file, so from now on, we should avoid coupling together a lot of methods in one file because they seem somewhat related.

For example, If there are helper methods that aren't strongly related with a given class, I suggest creating a utility class that supports the class previously referred to and houses these helper methods. Our code needs to be modular, which means having smaller methods.

But in conclusion, I completely agree what you said and I'll review and merge it soon, but we have to rethink our current workflow from now on to avoid cleaning the PR code up after merging, because we've been doing this a lot lately. Our thought process should be more of, "We've implemented this feature with scalable code" and less of, "The user can do this now and that's all that matters."
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#issuecomment-2744721302" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

> Each command into its own FILE holy moly
> 
> I mean I don't mind if you wanna then I'm down, thats another level tho haha

The reason why it feels like a lot of work is because you completed a lot of the features in the beginning, which is good. However, when it comes to refactoring the code to, let's say, share the NUSMods link, then we're going to be adding on to that massive switch statement in CommandCenter and then create a method, which I'm assuming is not going to be simple and therefore long, making the file huge.

At this point, CommandCenter just becomes this massive dumping ground for functionality, which makes it difficult for us developers because debugging is not going to be as easy because we have to scour through all those lines of code.

This is why I've been promoting modular code because it reduces the chances of errors happening as well as makes it easier to understand the code for others, because too much code in one file can be overwhelming and thereby difficult to understand for the average reader.

So I would go as far as to say that completing the issues early without thinking about scalability will make work more tedious (if it isn't already). As I mentioned in #50, we cannot prioritise functionality over maintainable code, because if we can't understand our code as developers, then there might be bad UX.

In terms of responsibility, I did something similar for my iP so I can take over this if needed, but I'd like someone else from @AY2425S2-CS2113-W12-1/developers to also volunteer. But in conclusion, let's refrain from pushing out code that's not very scalable anymore because this will come back to bite us later for sure.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#issuecomment-2745230895" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

> I'm totally cool with this approach, it makes sense, however Im just curious, How do you go about debugging? You've mentioned a few times that we would have to scour through alot of code but the stack trace tells you exactly where the error occurs and where it comes from no? no shade, just curious if you could elaborate 😅

Nah, you're good, man. Explanation's going to be a bit longer than it needs to be because I'm thinking conversationally, so I'm sorry for the long read, haha. Thanks for sticking through with this convo though.

So I use the IDE's debugger to debug code, which is available in IntelliJ as well (I use VS Code for reference). I can set breakpoints at specific lines in the program, which indicate to the IDE that the program needs to be paused at these lines and I can proceed line-by-line to see how variables are affected at a manageable pace.

Right now, error messages are not being printed to the console but to log/log.txt instead. This is subjective and while I understand that we aren't displaying error messages to the user yet, I would prefer knowing upfront in the console if an error was thrown as opposed to switching to another file and then looking the stack trace for the error.

The reason why is that I can run all commands without running into an error, which could make me think that the code is working as  intended, unless I knew what kind of output I was expecting beforehand, which is hit-or-miss especially if we're dealing with API data. Therefore, while logging is great, but I feel that it's complementary and insufficient to handle errors.

An example of this was the issue where the condensed module data was not being downloaded because we didn't include code to create parent directories for the JSON file if they didn't exist. The stack trace did give me some information that was pertinent to this issue, but in conjunction to the debugger, I was able to evaluate that the HashMap being returned had no elements and confirmed what the cause of the issue was with certainty.

Not to mention, by the end of v2.0, we'll have logging statements in the necessary parts of our program, but we're currently nowhere near completing it and thereby we don't have logging statements everywhere where errors might be thrown.

Therefore, I may not always be able to pinpoint why something's not working as intended, unless I refer to log/log.txt and which may or may not give the stack trace for a runtime error and also doesn't account for incorrect logic with valid syntax.

Hope that clarifies the debugging bit! However, the main point was scouring through all those lines of code, which I don't want to always deal with by using a debugger or a logger. I don't want to always run code to understand how it works, especially if it's code that I'm working on with a team.

I also need to be familiar with this code and I have to read through it without much friction to do so (ironically, you mentioned you not understanding my code so it does apply to me too), hence the promotion for modularity, which is always a good practice, not just for maintainability and scalability, but also readability. Hope this makes sense!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#issuecomment-2745950830" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

> If it is someone else's draft PR, is there a way for another person to work on it? Or is it just we need to approve and close this PR before we continue on :( ?

Yea, you can! You need to checkout the PR to your IDE, although I'm not sure how to do with IntelliJ.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/40#issuecomment-2745955947" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Still think this needs work, so I'm reopening it for now.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/65#issuecomment-2748821585" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

Merging this in as it passes the Java CI checks; the stray Telegram GitHub workflow is causing us issues so hopefully it doesn't appear in future PRs.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/62#issuecomment-2753041864" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

Yeah, I can't find what's going on either. Had a look at the error for the Java CI workflow but can't really ascertain the cause of this issue. I also checked out the PR to my local device and it passed the Gradle checks, so I don't think there's another issue. Could it be that ACTUAL.txt doesn't match EXPECTED.txt?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/62#issuecomment-2760319184" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

@kagiura You didn't update EXPECTED.txt to match ACTUAL.txt, hence the failed checks. All good now!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/76#issuecomment-2763103655" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

Removed unused Telegram workflows
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/96#issuecomment-2774452147" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Initiating the PPP process - everyone just needs to modify their content below:
'''yml
---
title: ...
---
'''
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/180#issuecomment-2781330847" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

Still working on this - please only merge it when it's ready for review, thanks!

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/180#issuecomment-2781333647" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

@shuu4 Had to refactor variablenames in `ScheduleTest` as it was confusing (`Schedule timetable` was one example) and some of the tests were failing so I updated the expected values to match the actual values.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/185#issuecomment-2781683956" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

Guys, so I can't pass all the checks because the following Commands marked in red are failing:

![image](https://github.com/user-attachments/assets/03ba8f06-1850-4a2e-b682-50fed26ff87b)

I've finally implemented our `CommandParser`, which I had to modify `Command` to become an abstract class which was previously an interface and `CommandParser` also takes advantage of `Input`, another new class. Please read through `Input` because it significantly simplifies things.

But the brief rundown is you can write commands in the following format:

`&lt;command> &lt;argument, which can contain whitespace> --&lt;flag1, no whitespace> &lt;argument for flag 1, which can contain whitespace --&lt;flag2, no whitespace> &lt;argument for flag 2, which can contain whitespace> &lt;...more flags if needed>`

Example commands would be:

1. `searchmod --faculty Computing`
2. `searchmod Software Engineering --faculty Computing --units 4`
3. `searchmod Magic --semesters 1 2 --units 4`

As there was a demand for a command parser from others, I went ahead and implemented one.

However, the drawback is that some of you have to conform to this new change, but it should be much easier for you now, given that the usage of `Input` is extremely straightforward.

I still have to finish my PPP and UML diagrams tomorrow so I can assist if needed, but to reiterate, changes will be minimal and I tried to ensure that the program workflow is similar to the previous iteration.

Please also don't forget to update your respective documentation as well, thanks guys!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 46. TONG..KIAT `@tongkiankiat` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/28#discussion_r2004679663" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Great job considering multiple test cases and also edge cases!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/33#discussion_r2005530286" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe we don't have to track this?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/61#discussion_r2026968343" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Nice check to ensure that user's input must be valid for multistep commands
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/62#discussion_r2027161218" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think we can add this user story for edit then merge
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/pull/46#discussion_r2020084168" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Resolved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/91#issuecomment-2780665692" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

I think its already very simplified, should be okay to ignore this
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 47. YEW ..IANG `@kaixiangg` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/pull/24#discussion_r2005660293" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would it be better to use the FinTrackException class here?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/pull/24#discussion_r2005682355" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Perhaps could check for data.length != 4 instead and throw an exception if its not so as to ensure the correct number of fields are saved and there won't be corrupted saved files.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/pull/42#discussion_r2022775435" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would having the link in the developer User Guide be more intuitive for users who wants to download it immediately?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/pull/105#discussion_r2030390998" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Might want to use the individual imports to fixcheckstyle
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/pull/30#issuecomment-2744134057" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Edited the with Parser Class and changed Commands Class to receive worded inputs, need to refactor if required for the storage logic and the corresponding features.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/issues/97#issuecomment-2780656703" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

#98 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 48. BRAN..KANG `@brand0nnn` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/154#discussion_r2028960221" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for helping to add the Javadoc
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/154#discussion_r2028961743" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good spot on the grammatical error!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/181#discussion_r2029876701" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Thanks for adding this in. Maybe you can state it above under the "Notes on general command format:" section instead? Then we just specify there that all the commands under the Group Selection Menu should only be used there, and all the commands inside a group should only be used there.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/181#discussion_r2029876913" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Can I check are the other commands also case-insensitive?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/146#issuecomment-2780225001" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Not a valid bug as tester did not read the UG. The `exit` command is under the commands *after* selecting a group, whereas the tester executed the exit command while still in the group selection stage.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/162#issuecomment-2780283840" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

This bug is not valid as the tester did not read the UG that which already specified that for paid commands, the identifiers are with respect to a person's individual list and not the full list.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/168#issuecomment-2780307212" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

This bug is not a valid bug as tester did not follow instructions. If the tester has entered "delete" exactly when there are no groups, the output would have been
```
> delete
There are no groups to delete.
Would you like to delete or select a group?
____________________________________________________________
```
Tester probably entered "delete " with a spacing which is not a valid command since it has stated to enter either "select" or "delete" exactly.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/169#issuecomment-2780327761" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

This is not a valid bug as you cannot owe $0.005 since money with 3 decimal places does not exist.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/159#issuecomment-2780552668" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

This is not a valid bug as the tester did not read the UG. `paid` command uses identifiers that is with respect to the payer.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/160#issuecomment-2783906881" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

We feel that a sequence diagram is better suited to show how the different methods are being called and used
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/167#issuecomment-2783990919" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

It is a feature that we are using numbers for users to select groups, thus the groups should not be able to be named using numbers.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 49. DARI.. LUN `@dariusyawningwhiz` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/196#discussion_r2030195095" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

can declare error message at the start of the class. 
private static final String ...
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/196#discussion_r2030195124" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

maybe declare all the magic literals
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/208#discussion_r2030456324" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

i think there should be return arrows and activation blocks right?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/208#discussion_r2030457223" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

May I check what is the changes here? Is it ok to remove CommandType?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/123#discussion_r2027110575" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

I realised that too. I have changed it 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/195#discussion_r2030066836" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

i did without the comma previously, still can accept input with 5 digits year

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/162#issuecomment-2780428207" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Can update description, will update user guide for clarity

![Image](https://github.com/user-attachments/assets/6cfd9e3d-c30f-49c9-826c-e77eefd279ee)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/143#issuecomment-2780627280" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

edited UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/152#issuecomment-2780631455" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

added to UG

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/132#issuecomment-2780633309" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

removed line
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/142#issuecomment-2780633423" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

added to UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/191#issuecomment-2780633820" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Updated UG for add income, update expense, update income and code summary.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/181#issuecomment-2781137041" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

![Image](https://github.com/user-attachments/assets/85a905f7-0ecd-48e7-9dcc-4c0b6141ccec)
updated UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/160#issuecomment-2781160001" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

able to take up to 7 digits and 2 dp now.

![Image](https://github.com/user-attachments/assets/028ec87b-8599-453f-9bb9-c223e4f76167)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/163#issuecomment-2781162082" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

updated UG 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/146#issuecomment-2781163778" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Updated
can take up to 7 digits only and it wont round up now.

![Image](https://github.com/user-attachments/assets/7657670f-9707-4d71-9feb-def34e65b24d)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/179#issuecomment-2781425491" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

![Image](https://github.com/user-attachments/assets/7cbb8f46-6d05-4ae7-9d52-514df7bb7428)
change to delete-expense &lt;index>
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 50. RODE..HANG `@rodi-314` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/28#discussion_r2005372122" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think logging statements can be used more effectively in the actual classes being used in the main code to inform developers of what is happening i.e., State.java and Storage.java!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/28#discussion_r2005384863" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think you need to add a few assert statements here (not just the JUnit asserts) to complete the tasks for Week 9!
e.g.
'''suggestion
assert highscore >= 0.0 : "highscore must be a positive number";
'''

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/28#discussion_r2005389486" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job implementing JUnit tests to check if the score is being saved and read to the file correctly!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/28#discussion_r2005392444" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job implementing JUnit tests to check if high scores are being updated and retrieved correctly!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 51. MARW..KITA `@nmarwah7` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/11#discussion_r1971212891" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Hi!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/12#discussion_r1971215501" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Hi
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/13#discussion_r1971247980" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This has a merge conflict
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/63#discussion_r2005484343" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Maybe we could think about leaving this line in, since if the user disables logging they would not be able to see the correct message usage format?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 52. TIAN..YONG `@TiangSoonYong` (**4** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/20#discussion_r1999087675" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Where will hasWon be set?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/59#discussion_r2027334277" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think we have to remove the class icons as well as represent the correct visibility icons as per the instructions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/59#discussion_r2027336159" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I have actually done up my Storage class diagram in PR #56, maybe we can discuss to see which to use 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/59#discussion_r2027345336" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

It is quite difficult to follow the sequence of the program and there are some errors, for example Parser return inputString to PlayerTurn but PlayerTurn did not call Parser, which should not happen. 

Perhaps we should remove the footboxes and the labelling for the classes should reflect that it is an object. I think the current interpretation in the diagram implies that all the methods are static.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/17#issuecomment-2729953893" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

It's just two lines, so i'll approve this myself

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/22#issuecomment-2734172139" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Current state: runnable
Only HelpAction, StartAction and DefendAction are not coded
- HelpAction should call ui to print help for all commands, better if only show commands that are currently available for that event
- StartAction should construct new game. Currently the game is created upon running main but should only be created upon "start". Additionally, it can be used during Death event
- DefendAction...I have no clue what it does, maybe it blocks more damage? Fully relies on implementation in Character class

Note: Another Battle subclass of Event was created instead of using the Battle within the Battle Package
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/56#issuecomment-2773702062" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

I have only added my sequence diagram! I still need to add in details for Storage in DG, so please do not merge this PR yet
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/62#issuecomment-2776705562" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Updated Storage Class to support new Event subclasses and Player attributes. However, I am unsure whether we should proceed with the current structure of the Event Generation within Game.java as Shop event will never be saved. So if the player exits during a shop event, it would likely skip to the next event and lose all equipments as it were not saved beforehand.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 53. LEE ..YING `@szeyingg` (**3** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2019988687" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

might be helpful to store string formats in separate variables to avoid magic literals and improve clarity
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/70#discussion_r2019988814" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

good use of logging and assertions!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-1/tp/pull/190#discussion_r2029948588" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

would regular be better to be consistent with that was explained above?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 54. SITT..PARN `@kagiura` (**3** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/6#discussion_r1980669020" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great photo
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/8#discussion_r1980671276" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

dont forget to replace your image later haha
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/9#discussion_r1980671599" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

dont forget to replace your photo later onn
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/1#issuecomment-2676132004" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

seems to be this error.... whatever it is? 
![2025-02-22-18 09 37@2x](https://github.com/user-attachments/assets/872dd0b7-4b9c-4022-8926-e86142c344dc)
do all the files have newlines at the end of them 🤔 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/23#issuecomment-2732271811" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

whoops ok sorry fixed, can you check again? @gitHST 

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/62#issuecomment-2747604705" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

i have no idea what chain of tests i just broke someone lmk if this isnt supposed to be done LMAO
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/62#issuecomment-2750141953" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

@gitHST hello good sir would you happen to be able to check which test case i failed 😭 looks like theres just one that just inputs "Hello" and expects nothing out ?????
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/54#issuecomment-2750156092" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

in case anyones backreading / it hasnt been made clear yet
- 1, 2 are lectures
- 01, 02, ..., 09, 10 are tutorials
- the rest are labs

is this an issue to be closed though im not sure what this issue is exactly asking
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/85#issuecomment-2770513016" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

put in very rudimentary stuff, ill continue updating this tmr. or i might just push this and call it a day
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/136#issuecomment-2781338536" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

course isnt offered this year is probably why; should add to UG that the courses that can be search are only ones that are offered in the current AY
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/151#issuecomment-2781338925" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

dont think this one makes much sense, you dont need to 'create'a module to bookmark it; any module can be bookmarked
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/132#issuecomment-2781339545" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

i think clashes should be allowed but should at least be noted down somewhere; will fix
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/161#issuecomment-2781340528" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

did we ever say our program did this? im not sure if it was ever included in the scope of our program to save user data
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/182#issuecomment-2781389710" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

i accidentally pushed the other changes to the wrong branch so im just gonna merge this with #183 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/193#issuecomment-2785152054" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

merging because with luke's new pr SHOULDDD fix everything
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/121#issuecomment-2785242210" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/148#issuecomment-2785254468" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

will not be fixed in v2.1
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/issues/171#issuecomment-2785255322" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

not fixed in v2.1
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/202#issuecomment-2785257366" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

wait i already fixed this 😭  ill close this
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 55. HENG..G YI `@HTY2003` (**3** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/22#discussion_r2005767561" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Not sure why this file is here, I think it's not supposed to be
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/22#discussion_r2005769126" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Setting file path like this may be a problem, try "./data/coinflip.csv"
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/98#discussion_r2029266220" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Name could use work; WinsAchievement suggests that it represents 1 achievement, possibly inheriting from Achievement class, but this represents a collection of Achievement objects
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/6#issuecomment-2720245427" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Added in #11 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/8#issuecomment-2723520721" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Added in #12 .
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/9#issuecomment-2736296903" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Added in #14 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/10#issuecomment-2736707068" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Added in #15 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/17#issuecomment-2739921315" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Fixed CI checks in the process
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/16#issuecomment-2740957891" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Added in #22 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/7#issuecomment-2740958379" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Added in #16 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/28#issuecomment-2741270150" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Added in #27 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/29#issuecomment-2741494571" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

added in #31 , improved upon in #32 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/34#issuecomment-2742315492" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Resolved in #33 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/24#issuecomment-2745377623" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Added in #37
Although @CRL006 the PR title could be more specific, thanks!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/25#issuecomment-2755756668" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

added in #39 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/47#issuecomment-2759379989" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

* Added underscore lines before and after all program output for clarity
* Printed User Guide URL in help command output
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/49#issuecomment-2760322169" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Could the check command for wins/losses/total won/total lost be combined into a single command? I think it makes the most sense to view all of those stats at one go
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/49#issuecomment-2760325435" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

As for naming....maybe check flips or check games
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/49#issuecomment-2760351324" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

LGTM, one last thing: could you update the user guide?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/45#issuecomment-2764100610" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

Added in #51 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/44#issuecomment-2764105047" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

Added in #47 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/46#issuecomment-2764107204" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Added in #49 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/26#issuecomment-2776489275" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

Added in #56 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/98#issuecomment-2779488549" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

Merging, but will make effort to reduce redundant code in the future

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/64#issuecomment-2779739580" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/66#issuecomment-2779739953" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/78#issuecomment-2779740429" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/74#issuecomment-2779740798" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/59#issuecomment-2779741346" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

added
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/68#issuecomment-2779741767" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/95#issuecomment-2779742121" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/65#issuecomment-2779742873" expanded>
<div slot="header">

**32 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/72#issuecomment-2779743256" expanded>
<div slot="header">

**33 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/76#issuecomment-2779743655" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/77#issuecomment-2779743979" expanded>
<div slot="header">

**35 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/71#issuecomment-2779744206" expanded>
<div slot="header">

**36 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/89#issuecomment-2779744518" expanded>
<div slot="header">

**37 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/70#issuecomment-2779747037" expanded>
<div slot="header">

**38 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/80#issuecomment-2781164626" expanded>
<div slot="header">

**39 :octicon-comment:** %%(other comment)%%
</div>

Rejected, because the severity level is definitely not High. However, I will open a new issue to improve the specificity of the target user motivation.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/67#issuecomment-2781192244" expanded>
<div slot="header">

**40 :octicon-comment:** %%(other comment)%%
</div>

Added
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/69#issuecomment-2781192462" expanded>
<div slot="header">

**41 :octicon-comment:** %%(other comment)%%
</div>

Added reset balance feature, documented that betting with 0 coins is allowed and is part of expected app behaviour.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/96#issuecomment-2781192726" expanded>
<div slot="header">

**42 :octicon-comment:** %%(other comment)%%
</div>

Fixed in documentation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/93#issuecomment-2781192894" expanded>
<div slot="header">

**43 :octicon-comment:** %%(other comment)%%
</div>

Documented that this is allowed and expected behaviour
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/75#issuecomment-2781193146" expanded>
<div slot="header">

**44 :octicon-comment:** %%(other comment)%%
</div>

Reset command added, guide on resetting file no longer needed, although I added more details as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/79#issuecomment-2783837337" expanded>
<div slot="header">

**45 :octicon-comment:** %%(other comment)%%
</div>

Added
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/86#issuecomment-2783837798" expanded>
<div slot="header">

**46 :octicon-comment:** %%(other comment)%%
</div>

Added
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/82#issuecomment-2783838445" expanded>
<div slot="header">

**47 :octicon-comment:** %%(other comment)%%
</div>

Added
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/73#issuecomment-2783839691" expanded>
<div slot="header">

**48 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/101#issuecomment-2783841157" expanded>
<div slot="header">

**49 :octicon-comment:** %%(other comment)%%
</div>

Added
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/issues/104#issuecomment-2783841625" expanded>
<div slot="header">

**50 :octicon-comment:** %%(other comment)%%
</div>

Added
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 56. ZHAN..ANYI `@terryasdf` (**3** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/15#discussion_r2000280052" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

may assert here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/15#discussion_r2000280410" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

may check and throw exception here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/47#discussion_r2025453947" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Avoid catching `Exception` since it would cover up all potential problems. Directly throw `DateTimeParseException` here and catch it in `Parser.java`.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/119#discussion_r2030077967" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Messages must be printed during loading process, e.g. when one of the expense is invalid and has to be skipped. Unless we append all the exception messages till the end of loading, and return all of them back, we can't avoid using Ui here.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/119#discussion_r2030078082" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Sure no problem I'll change that
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/73#issuecomment-2778754520" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Haven't been able to reproduce. I guess JSON file is corrupt. Need handling JSONException when reading.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/74#issuecomment-2778758615" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Add a min value in UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/75#issuecomment-2778768206" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Throw `InvalidArgumentException` if name exists
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/76#issuecomment-2778771131" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Modify output message and/or add explanation to UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/78#issuecomment-2778783165" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Add java version and download link in UG and DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/81#issuecomment-2778816275" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Either implement the `AMOUNT [CURRENCY]` correctly or just totally remove `[CURRENCY]` and use base currency for calculation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/91#issuecomment-2778891376" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

I suppose it's list-expense
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/107#issuecomment-2779551303" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

work as intended
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/issues/87#issuecomment-2779614617" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

The correct format is written in UG and `tutorial` command
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 57. WANG..MING `@Alaneel` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/26#discussion_r1993758116" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Delete one line XD
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/30#discussion_r1994014566" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This file no need to add to git, should exclude
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/94#issuecomment-2764431242" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

<img width="683" alt="image" src="https://github.com/user-attachments/assets/1033ea8d-5d9f-4846-8cdd-fa5ddd488d6e" />

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/119#issuecomment-2779257316" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/120#issuecomment-2779267526" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/121#issuecomment-2779272804" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/123#issuecomment-2779318458" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/125#issuecomment-2779349358" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/126#issuecomment-2779350040" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/130#issuecomment-2779365674" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/129#issuecomment-2779367254" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/131#issuecomment-2779371755" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/132#issuecomment-2779374255" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/133#issuecomment-2779375214" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/135#issuecomment-2779377481" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/136#issuecomment-2779381376" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/139#issuecomment-2779385235" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/140#issuecomment-2779385746" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/168#issuecomment-2779388070" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/146#issuecomment-2779391734" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/144#issuecomment-2780697297" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/161#issuecomment-2780707791" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Already solved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/149#issuecomment-2780732919" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/issues/143#issuecomment-2780733055" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 58. LIM .. FUN `@ljunfun` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/110#discussion_r2024118394" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job on packaging out all the mermaid diagrams
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/110#discussion_r2024119331" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great job adding examples to all the commands
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/26#discussion_r1993784583" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Deleted said line
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/23#issuecomment-2714497704" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 59. RAMD..YANT `@OmJRamdas` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/49#discussion_r2020055632" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is this file supposed to be git ignored
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/49#discussion_r2020056057" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Question cause im not sure, is it better to pass by reference the ui object from the main program rather than create a new one 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/48#issuecomment-2763349305" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Resolves #42 

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/49#issuecomment-2764368547" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

To Resolve #37 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/51#issuecomment-2764446740" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

DG command update
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/81#issuecomment-2774629565" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Closes #81 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 60. SU M..CENT `@vincesum` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/89#discussion_r2030441613" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

What is the SCANNER.nextLine here for?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/89#discussion_r2030442855" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Possible to abstract this part out with a save file method to make it look cleaner.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 61. CHAN.. BIN `@ShengBin-101` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/pull/67#discussion_r2009520223" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Formatter.printSimpleMessage() adds an indent of 5 spaces for every line
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/pull/67#discussion_r2009525881" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

![image](https://github.com/user-attachments/assets/0a49a424-586b-439c-8c42-9240cf756f4f)

It seems that the indents added within the input for Formatter.printSimpleMessage() is adding in additional indent on top of the indent() used in the implementation of Formatter.printSimpleMessage().
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/pull/67#issuecomment-2746987493" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Could you show me the output in ACTUAL.TXT? 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/85#issuecomment-2756977741" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

This ordering issue applies to 

- add-book
- update-book
- add-loan
- edit-loan
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/85#issuecomment-2765211363" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Update: Option 2 was chosen and now application supports for different order of arguments 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/198#issuecomment-2780185072" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

This can be fixed with using Enums for category. #69 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/69#issuecomment-2780186106" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Remember to handle case-sensitivity. We want to allow users to enter in a mix of lowercase and uppercase for category.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/200#issuecomment-2780188247" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

For this, we specify in our User Guide that the Location is meant to be a label to indicate where to store the book in the Library. Hence, it is not required to update location to borrower's location. 

Close this issue after updating UG/DG. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/195#issuecomment-2780190230" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Related to #179 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 62. ARAV..RTHA `@theertha120` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/9#discussion_r1971207743" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good description!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-3/tp/pull/10#discussion_r1971209581" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Hi! Good description!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 63. LI S..YANG `@lishunyang12` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/129#discussion_r2030066801" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

For unselect method, I don't why there is a need to input a parameter after we are sure that the user is already in a deck. Therefore, why not just assign the current deck to null before which we take the name of the deck for the success message?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/129#discussion_r2030067007" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

may be you need to adjust test case accordingly.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/pull/67#issuecomment-2776545816" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

LGTM. I think it is good to go. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/127#issuecomment-2781184211" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

roger that. Will take your advice. 

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/126#issuecomment-2781195182" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

thanks for catching this issue. will edit it.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 64. DAZA..NORA `@noradazaperez` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/119#discussion_r2030075809" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

i don't think this should bee here to be honest. I wouldn't mix ui stuff with loading Data 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/119#discussion_r2030077054" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Here, maybe we could have Ui as an attribute. So that tripBuddy just accesses this.ui.printMessage(), instead of passing it on as an input
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 65. LEE ..YING `@yyingg-243` (**2** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/61#discussion_r2027949812" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

printCharacterInfo is in UI not BattleUI so ill keep it as UI
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/61#discussion_r2027954782" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

In my latest pr, i have removed this part cause i was thinking that showing attack sequence itself doesn't have to include starting the game and initializing the battle, it should just start by receiving commands directly from the player. (tht's what i think but can discuss)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/59#discussion_r2027965479" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

just have a quick check on both, I think yours is better cause mine was just a draft version (hvt really deal with the details)so ill remove mine on my side.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/59#discussion_r2027998646" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

done removing footbox and updated the diagram to let player turn class parser before parser returning input string to it .

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/63#issuecomment-2777567657" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

![Image](https://github.com/user-attachments/assets/c03ba623-81bb-40d0-8bf7-1000b41dfc13)

edit the naming of package to start with lower case (eg: game instead of Game)
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 66. TAN ..YONG `@whalesyong` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/6#discussion_r1975436461" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

To clarify, this subclass will be moved to another file in a later iteration?

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/68#issuecomment-2764448674" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Will resolve CI issues immediately 

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/141#issuecomment-2781856893" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Storage persistence added in the attached commit. Closing this issue.


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/137#issuecomment-2781858048" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Instructions for basic manual testing and automation testing has been added in the attached PR. Closing this issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/161#issuecomment-2781891766" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Issue resolved in the attached commit. Closing this issue.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/160#issuecomment-2781931481" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

closing this issue as no further action is needed.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/153#issuecomment-2781932571" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

This is the intended behaviour of our application as of v2.1. Further changes will be reconsidered in later versions. 
Closing this issue as no further action is needed.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/209#issuecomment-2785171967" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

YAYYYYYYYYYYYY IT FINALLY PASSSED 

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 67. SER ..SLEY `@sjwking` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/pull/45#discussion_r2024154420" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

LGTM!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 68. TAI ..OUIS `@louistaii` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/168#discussion_r2028048985" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

This test is possibly failing because the index field should be id/ instead of sn/
 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/96#discussion_r2017881601" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Fixed. Thanks for catching that!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/203#issuecomment-2780359450" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/207#issuecomment-2780359561" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/209#issuecomment-2780359639" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/221#issuecomment-2780359800" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/222#issuecomment-2780359948" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/225#issuecomment-2780360074" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/219#issuecomment-2780632821" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/206#issuecomment-2780633142" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out. The error occurs when the integer value the user input is extremely large.  Code has been refactored to handle this edge case.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/200#issuecomment-2780633205" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out, issue has been resolved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/192#issuecomment-2780676705" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out. The user and developer guide has been updated to clearly state that the patient must exist before an appointment can be added.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/205#issuecomment-2781376493" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out. The ID in appointment list referred to the index of the appointment when you do `appt list` and not the patient's ID. The command fields have been updated to be less confusing.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/204#issuecomment-2781376792" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out. The find feature now supports both searching by patient name and ID for less confusion.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 69. SEAN.. JUN `@SeanTerrr` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/113#discussion_r2023019489" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Would there be any difference removing the dp vs with the dp?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/100#issuecomment-2758635165" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

well done! clean code and a great improvement to our tp!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/150#issuecomment-2780647469" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Added a check to throw an exception if no payer was found
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/155#issuecomment-2780652755" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

made all commands case insensitive 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/147#issuecomment-2780656811" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

added a note in the UG to make it clearer
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/172#issuecomment-2780662682" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

zuckerberg is gone
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 70. NICH..N HE `@nicholascxh` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/pull/82#discussion_r2022661308" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

great to have :)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/pull/76#issuecomment-2760227176" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Approve on behalf of George
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/pull/79#issuecomment-2765038320" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

looks great! nice!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/pull/83#issuecomment-2769030396" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

i think the code looks great!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/pull/80#issuecomment-2769036359" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

changes are fantastic :)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/138#issuecomment-2781229834" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

updated already
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/140#issuecomment-2781230240" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Already implemented, not sure why it is still requested.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/145#issuecomment-2781230579" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Already updated
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/117#issuecomment-2781231674" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Updated with separate log file for SOC
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/119#issuecomment-2781342884" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

done for expense and income, waiting for loan
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/156#issuecomment-2782142805" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Updated flaw in UG, can be implemented for future references
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/160#issuecomment-2783961903" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Done intentionally since that is the syntax for each command. &lt;command> is used since there is no need to use / 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 71. WONG.. HUI `@xhuinn` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/140#discussion_r2024977535" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

You may consider using NurseSchedException instead
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/230#issuecomment-2780221590" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out! I have made the changes to the medicine delete command in the command summary.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/220#issuecomment-2780227374" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Thanks for pointing this out! I have added the exit command to both the error message and the user guide.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/212#issuecomment-2780231286" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Thank you for your feedback! 

However, I believe that the medicine with quantity 0 should still be able to exist in the list as some medicines might still be relevant and the users might want to keep track and restock them. This is so that when the users carry out the `medicine restock` command, the medicine name and its quantity will still appear in the list.

I will be making this clearer in the user guide to prevent confusion!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/issues/201#issuecomment-2780629324" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Thank you for pointing this out! I have made changes to output a warning when the input date is before the current date.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 72. TAN ..NMIN `@xmtan1` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/29#discussion_r2005815637" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Is there no catch for the second try``{````}`` (the one within the first try)?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/103#issuecomment-2777550798" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/105#issuecomment-2777559745" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/110#issuecomment-2777589853" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

nice
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/150#issuecomment-2783154663" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

same as issue #168. Fixed
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 73. PYDI..NAVI `@pjahn31` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#discussion_r2008758125" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

I think we could abstract each command out. Although might be a lot of work, it will make our code look cleaner as well.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#issuecomment-2745241168" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

If it is someone else's draft PR, is there a way for another person to work on it? Or is it just we need to approve and close this PR before we continue on :( ?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/50#issuecomment-2745952537" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Read through the summary of your commits, this looks good!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/77#issuecomment-2765794519" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

please do check to see whether everything looks alright! right now on my end the removemod and addbreaks are having some problems which i am trying to resolve
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 74. ASTH..HAAN `@vihaan27` (**1** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-3/tp/pull/97#discussion_r2022843061" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)
</div>

Good job in fixing all occurrences of the bug.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 75. KOH ..ELON `@ElonKoh` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/124#issuecomment-2781231925" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

I must have forgotten to merge my documentation before. Added now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/107#issuecomment-2781232557" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Duplicate Bug, already handled by another issue (Tester E)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/85#issuecomment-2781232963" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Duplicate bug, already handled in another issue (Tester E)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-4/tp/issues/93#issuecomment-2781263291" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Solved this issue with the attached pull request
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 76. BRYA..ALIM `@gavalion` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/136#issuecomment-2784410757" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Fix the code for trip, need to update UG and DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/136#issuecomment-2784411894" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Need to add for photos inside one trip, no duplicate name or file
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/136#issuecomment-2784472610" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

fix the code for photo duplicated filepath and name, need to update the UG and DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/116#issuecomment-2784495629" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

need to update UG 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/138#issuecomment-2784514128" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Done with code, need to fix UG and DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/141#issuecomment-2785166889" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Coding done, need to update DG or UG
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 77. ASHL.. YEE `@ashleyang2001` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/pull/164#issuecomment-2785262045" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

****
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 78. CHEN..UOYI `@gu0y1` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/139#issuecomment-2781148897" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Solved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/115#issuecomment-2781149415" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Case sensitive removed, y & Y both ok now @yangyi-zhu 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/143#issuecomment-2781150542" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

You are correct, now the transaction IDs are unique and cannot be changed by user.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/132#issuecomment-2781153021" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Will change visual format @yangyi-zhu 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/135#issuecomment-2781162179" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Solved accordingly
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/152#issuecomment-2781164024" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Decide to remove this feature? @AnotherSACE @AnotherSACE @gu0y1 @HalFentise @Lukapeng77 ???
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/151#issuecomment-2781165005" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Also confused by me, will edit a little for better understanding by audience. @yangyi-zhu 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/146#issuecomment-2781173976" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

I will do this feature @yangyi-zhu 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/173#issuecomment-2781713981" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

We will use edit wizard to edit any transactions. Issue solved, no need PR.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/195#issuecomment-2785057347" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Sorry, please update your code based on the latest version #196 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/195#issuecomment-2785088139" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Code cannot run, please revert this PR. Update code based on #196 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 79. CHEN..SIYU `@syCHEN1645` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/177#issuecomment-2780727419" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/176#issuecomment-2780727506" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/154#issuecomment-2780729427" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/150#issuecomment-2780730758" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Duplicate bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/148#issuecomment-2780731580" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/144#issuecomment-2780732263" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/136#issuecomment-2780733070" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/135#issuecomment-2780733432" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Out of project scope
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/135#issuecomment-2780734287" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

output message is wrong
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/128#issuecomment-2780737639" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/110#issuecomment-2781047060" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Nice catch , thanks for the feedback!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/131#issuecomment-2782000304" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Not a bug confirmed by prof
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 80. CHEN..YANG `@yiyang74` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/117#issuecomment-2779462509" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

User might want to include numbers in description and location.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/118#issuecomment-2779467435" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

You've entered canteen as your name.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/136#issuecomment-2779487794" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

"-1000" is a negative number, "/-1000" is not a number
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/134#issuecomment-2779493121" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Don't see how this is an issue but will be clarified in UG/DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/145#issuecomment-2779507206" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

I believe this result can be intended. @lakshm1i up to you if you want to document this or throw an exception.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/146#issuecomment-2779509566" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

If you do not enter 'exit' the program doesn't exit and stays in the loop as documented in the sequence diagram.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/147#issuecomment-2779513274" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

@KeerthanaBanukumar is this intended?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/152#issuecomment-2779520198" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

@KeerthanaBanukumar is this intended?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/156#issuecomment-2779523432" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

@KeerthanaBanukumar not sure what's going on here
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/170#issuecomment-2779534091" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Muslim-owned stalls aren't halal certified, thus, requiring the distinction for people with strict restrictions. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/171#issuecomment-2779535820" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

When asked "What's your name?", enter your name into your terminal.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/issues/184#issuecomment-2779550638" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

This is supposed to be continuation from the user story above but page break will be added
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 81. JOEL..NWEI `@HightechTR` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/pull/31#issuecomment-2739858669" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Create PR from your branch, not master
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/pull/55#issuecomment-2763222474" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Merging, but please please check your spelling before you commit
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/57#issuecomment-2768392215" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Note: Storage is already abstracted, left Parser and UI

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/pull/65#issuecomment-2769312238" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

@Rishi7830 all images need to be in the docs folder, will have to remove the ones here rn
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/70#issuecomment-2774516833" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Merged already
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/157#issuecomment-2780823766" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

@SahejAgarwal05 use the isValidYear and isValidSem methods in Utils
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/139#issuecomment-2780836032" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Fixed in latest DG update
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/174#issuecomment-2780841518" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

AddCommand diagram fixed in latest update
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/121#issuecomment-2780847396" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/120#issuecomment-2780860839" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

If it is a CEG course, it will display the error due to the file missing, but with all parameters included it will still succeed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/141#issuecomment-2780866978" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Detecting repeated courses should fix this issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/162#issuecomment-2780870080" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/163#issuecomment-2780870232" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/164#issuecomment-2780870649" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/165#issuecomment-2780870731" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/166#issuecomment-2780870845" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/167#issuecomment-2780870901" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/168#issuecomment-2780870968" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/169#issuecomment-2780871011" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/171#issuecomment-2780871422" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/172#issuecomment-2780871495" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

mistake issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/109#issuecomment-2780875236" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Google doc version to be depreciated, web version fixed already
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/issues/161#issuecomment-2780886077" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

@Rishi7830 can use isValidSem isValidYear and isValidMc methods in Utils
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/pull/179#issuecomment-2781414029" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

Bug already fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-2/tp/pull/210#issuecomment-2784041524" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

@JinbaoAlex the emoji will not display correctly in the jar, please amend
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 82. TONG.. JUN `@jiajun2002` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-2/tp/pull/30#issuecomment-2757515709" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Great additions to our current features!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-2/tp/pull/112#issuecomment-2785039409" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Looking dashing!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 83. ROYC..RONG `@Roycecodes` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/29#issuecomment-2735318466" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Did not merge because checkstyles failed

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/30#issuecomment-2735406491" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

great ready to merge

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/140#issuecomment-2780202467" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

In the user guide it states that if nothing is input in it will show the current month
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/133#issuecomment-2780204172" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

This is the intended purpose of our program. Imagine wanting to cook the same meal twice in a week because that is all the ingredients you have
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/116#issuecomment-2780205898" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

This is a feature we added so that if users forgot to add their dishes before cooking they would be able to after to ensure ingredient consistency
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/139#issuecomment-2780700405" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Do you mind sharing with me how you achieved this bug? 
what are the dishes in your dish list and what terminal are you using thanks!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 84. CHOO..NSON `@Deanson-Choo` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-3/tp/issues/11#issuecomment-2728762372" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Enhances user story #27 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 85. CHUA..YUAN `@srfl0` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/177#issuecomment-2781600940" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

make sure `Ui.showMessage()` is used for printing to console for this for all `System.out.println()` that separates into the next command
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 86. LI J..XIAN `@Li-JunXian` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/71#issuecomment-2763212144" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

All's good with Merge pull request #71 ;D
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 87. KASH..AIN `@KashfyZul` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/issues/39#issuecomment-2748223553" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

UI alert - can output diff colour text based on how much stock is remaining
Count stock based on instrument classes (e.g. no. of guitars remaining, no. of flutes remaining)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/issues/44#issuecomment-2771561707" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Extension of "list" - allow user to view different lists (e.g. "list -s" will list stocks)
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 88. AKAA..ALAN `@akaash02` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/pull/22#issuecomment-2742785938" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Closing this as Java CI failed. Might want to check JUnit tests. 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 89. LIAN..MING `@fivenames` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/153#issuecomment-2778891861" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Duplicated Issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/162#issuecomment-2779055586" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

The ID should indicate the ID of the application in the application list, not a mere numbering in the printed list
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/163#issuecomment-2779263125" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Duplicated PR
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 90. XAVI..GRUI `@Xavierleejrui` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-3/tp/pull/34#issuecomment-2729011768" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

LGTM carry on wayne 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-3/tp/pull/95#issuecomment-2735935830" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 91. ZHON..IANG `@siqiangz` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/130#issuecomment-2781490549" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

removed `clear` command suggestion from help table
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/152#issuecomment-2781541741" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Registration of patients with the same name has been made impossible, so this update issue should be fixed. @RaidaNUS you could test your update and see if it works.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 92. IRWI.. KAI `@zavsky` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/50#issuecomment-2773148592" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

#51 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/44#issuecomment-2776312104" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

More bugs as of release v2.0

<img width="743" alt="Image" src="https://github.com/user-attachments/assets/3eda3f13-818a-408f-a071-08bc15ae2b78" />

Upon completion of one play-through and returning to the menu, if the user selects to play a new game, the new game crashes when the `attack` option is selected. All other options seem fine. Above is the stacktrace result.

The shop does not parse inputs properly and player cannot purchase anything. Same for selling since the player has nothing to sell. Leave command exits the game.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/60#issuecomment-2776316609" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

#44 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/85#issuecomment-2780769560" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

## Short DG to Quick Start
### Other stuff to add
- [ ] Connecting story
- [ ] Exit from game
- [ ] Fleeing from battle
- [ ] Dropping loot and gold
- [ ] Shop with buy and sell mechanics
- [ ] Expand Armor, Weapon passive abilities
- [ ] Expand Abilities special effects
- [ ] Add character classes (warrior, wizard...)
- [ ] Add shop
- [ ] Add random events (dropping weapon due to injury)

### Glossary
#### Term -&gt; Meaning
Wave -&gt; Enemy encounter
Round -&gt; Bout number during battles

#### Damage Calculation:
[(dice roll result) + (num of dice) * (weapon bonus)] * [(power) / (max power) * 0.5 * (weapon damage multiplier)] - (opponent armor defense)
### Ability class
Instantiate using: `new Ability(AbilityType, abilityName, additionalInfo, emojiIcon, cooldownRequired, damageMultiplier, powerCost)`

`isReady()` - return true if CD period over and sufficient power available
`isCDReady()` - return true if CD period over
`resetCooldown()` - set CD to zero (after a battle completes, or when special effect used)
`startCooldown()` - start CD (ability was just used)
`tickCooldown()` - decrement CD timer at end of each round
`additionalFeatures(Player)` - special effects that can be applied to either player character when invoked
### Armor class
`new Armor(nameOfArmor, defenseValue)`
TODO: create more defense effects of Armor items, refer Abilities.Heal for an example
### Weapon class
`new Weapon(nameOfWeapon, bonusAttackPerDice)`
TODO: create more offense effects of Weapon items, refer Abilities.Heal for an example
### Player class
`new Player(name, maxHp, `
`baseAttack, ` - base damage value before multiplier
`numDice, ` - number of dice to roll
`Weapon, Armor, isHuman)` - distinguish between player and AI (technically two human players can play against each other, maybe another game mode for fun?)

`getDiceRolls()` - reroll the Player's dice
`computeDamageTo(Player)` - calculate the damage dealt to other player
`applyDamage(damage, Player, text)`
`heal(amount)`
`chooseAbility()` -&gt; `showUserMenu()` or `chooseAIAction()` - get choices of ability to use this round
`isAlive()`
`updateAbilityCooldown()`
`hasAbility(name)` - returns true if the ability is already learnt by player
`applyAbilityAdditionalFeatures()` - apply special effects of Ability used this round
`updatePower()` - increment power after each round
### TerminalClear pkg
`clearAndWrite(contentToWriteAfterClearingScreen)`
### TypewriterEffect pkg
`print(text)` or `print(text, withDelayAfterwards)`
### DiceBattleAnimation pkg
`animateBattle(int[] player1rolls, int[]player2rolls` - draw dice rolling animation for both players, side-by-side
### BattleDisplay pkg
`showPlayerStatus(Player)` - draw Player stats at the start of each round
### HpBar
`animate(Player1, Player2, prevHP1, prevHP2, diceDisplay)` - HP bar animation
### Narrator
`commentOnHealth(Player)`
`commentOnMomentum(Player1, Player2, damageDealt, p2PrevHp)`
### Rolladie
`GenerateNewEnemy(wave)` - generate harder enemies progressively (may need to manually stop at certain round for testability)
`StartBattle(Player1, Player2)` - begin battle sequence for a wave
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/pull/85#issuecomment-2781372522" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

### Main game loop
Rolladie -&gt; main
-> mainMenu
-> (if new game) create new character
-> (if load game) load from save file
@ -&gt; start game loop
-> create wave enemy
-> start battle
-> (if survived) save game
-> return to @

### Battle
@ -&gt; BattleDisplay.showPlayerStatus()
-> player.chooseAbility()
-> animate dice
-> compute damage
-> apply damage
--> update ability cooldown
--> update power stat
--> apply ability special effects
-> animate HP bar
-> narrator commentary
-> (if battle not over) return to @, (else) reset all ability cooldowns, increase HP and power


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/68#issuecomment-2781965437" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Appreciate the report and apologies for the issue, we have fixed crashes faced when running in Windows terminals and will be publishing a new version soon!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/67#issuecomment-2781965696" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Appreciate the report and apologies for the issue, we have fixed crashes faced when running in Windows terminals and will be publishing a new version soon!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/69#issuecomment-2781966131" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Appreciate the report and apologies for the issue, we have fixed crashes faced when running in Windows terminals and will be publishing a new version soon!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/70#issuecomment-2781966460" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Appreciate the report and apologies for the issue, we have fixed crashes faced when running in Windows terminals and will be publishing a new version soon!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/72#issuecomment-2781967568" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Thanks for the report! We have looked into it and will be correcting it for the upcoming release :)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/74#issuecomment-2781968641" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Thanks for the report! We are tracking this issue internally and should be removed in the next release
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/73#issuecomment-2781969680" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

We are able to reproduce the same error and it is being corrected in the next release. Stay tuned

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/76#issuecomment-2781971079" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

We noticed that there was insufficient context given to the player here and it has since been rectified in the new version
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/77#issuecomment-2781971723" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Thanks for the report!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/78#issuecomment-2782006498" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Thanks for the bug, we are tracking it and should be resolved in the next release
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/80#issuecomment-2782007784" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Something to note for the next release. The scoring system is still not clear and should be explained to the player
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/81#issuecomment-2782008446" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

We note that the gold system was non-functional and is targeted to be fixed in the next release
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/44#issuecomment-2782009874" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

I think we can close this now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/100#issuecomment-2782226873" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

#97 First update
#98 Second update
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-4/tp/issues/101#issuecomment-2784406915" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

Thank you for the report, we have resolved this in the latest version
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 93. PIRA..NDER `@thezerohour` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/60#issuecomment-2765384257" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

closed by PR #70 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/73#issuecomment-2771969836" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

closed by #75 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/164#issuecomment-2782707070" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

should be resolved with user initialization prompt and documentation update
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/210#issuecomment-2783509562" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 94. KHOO..YLAN `@dylankhoo` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/174#issuecomment-2780701332" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Fix in UG by explaining constraints to User
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/170#issuecomment-2780701888" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Fix in User Guide by explaining constraints to User.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/168#issuecomment-2780702385" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Fix in User Guide by explaining constraints to User.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/167#issuecomment-2780702541" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Fix in User Guide by explaining constraints to User.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/202#issuecomment-2780711031" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

1. Change printBorderedMessages to print Exception Message
2. Refactor make a setAll() function
3. Change to "User Input" (follow other sequence diagrams)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/169#issuecomment-2780712408" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

1. Use opt blocks
2. Change user input
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/202#issuecomment-2782930529" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Looks Good!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 95. NEO .. KIN `@kinneo` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-4/tp/pull/18#issuecomment-2723570893" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-4/tp/pull/21#issuecomment-2727217782" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-4/tp/issues/98#issuecomment-2765308719" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

read the code cause it overlaps
rmb to update find/view part in userGuide
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-4/tp/issues/163#issuecomment-2781288122" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

@keanneeee split ViewGoalParser to logic (ViewGoalCommand) and parsing (ViewGoalParser). then edit the ParserManager

also specify in UG that view is for goals, and search/list is for logs or smthing like that
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-4/tp/issues/194#issuecomment-2781315035" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

i will do this at the end when most of the code part is done
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 96. TAY ..HENG `@TayGuangSheng` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/52#issuecomment-2764565333" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Great job on improving the error handling for the Edit Expense function and adding detailed JavaDocs! It really enhances the readability and reliability of the code. If possible, consider adding more unit tests to validate the new error handling logic and ensure it behaves as expected.


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/65#issuecomment-2775317582" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Looks good to me. Good that the class diagram do not have common mistakes such as the round circle symbol at the top.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/127#issuecomment-2781323508" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

The new DG format and outline make it clearer to the people reading our document.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/129#issuecomment-2781488271" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

LGFM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/issues/100#issuecomment-2781526304" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Resolved by modifying busy student to budget conscious student. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/issues/114#issuecomment-2781526814" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Added in the userguide on how to set budget category with the set-budget function.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/issues/106#issuecomment-2781531005" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Add a max limit of $10000 to the add function 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/130#issuecomment-2781579553" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Checkstyle is consistent 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/133#issuecomment-2783072244" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Good to add more JUnit Test
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/135#issuecomment-2783423491" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Goodjob for adding more JUnit tests to enhance the test coverage and ensure the reliability of the application.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/150#issuecomment-2784498108" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Good job for fixing the diagrams for DG. Most of the diagrams are correct, but I think there are still a few more diagrams that need to be fixed. 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 97. EDWI.. TUN `@EdwinTun98` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/104#issuecomment-2781388905" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Cannot replicate mistakes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/105#issuecomment-2782336575" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Not a bug. Budget is saved in budget.txt. to see budget save is different command
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 98. HANS..KIEW `@Hansel-K` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/150#issuecomment-2780894007" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Fixed this issue back in PR #92, but the updated JAR file was not uploaded in time for PE dry run
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/153#issuecomment-2780913548" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Was not able to reproduce the error as of [PR #92], which was merged before the PE dry run, but not uploaded in time for it.

![Image](https://github.com/user-attachments/assets/557993c2-4db3-4174-aedf-6a54f09d8cde)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/152#issuecomment-2780914815" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Issue was fixed before the PE dry run in [PR #92], but the updated code was not uploaded for use in the PE dry run.

Duplicate issue along with other commands utilizing `startswith("string")` method in Parser.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/141#issuecomment-2780959850" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

"Check" command was added into the UG before the PE dry run in PR #92, but was not uploaded as part of the files used for the PE dry run.

Follow up actions:
- Add "Check" command into DG
- Change "Total" to "Overall" for clarity of reference across commands
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/156#issuecomment-2780991838" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Updated error message to reflect "No matching entries found for keyword: &lt;keyword>".
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/109#issuecomment-2781030954" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Couldn't replicate error when trying to debug.

![Image](https://github.com/user-attachments/assets/eef9f0f5-9318-43b0-aff5-e6d4a47befd1)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/124#issuecomment-2781462893" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

We intentionally formatted to automatically cut off at 2 d.p. no matter how many decimal places are input. Will reflect it in the DG and UG instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/140#issuecomment-2781479935" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Fixed addExp to require input in the specific order.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/121#issuecomment-2781488621" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

We intentionally formatted to automatically cut off at 2 d.p. no matter how many decimal places are input. Reflected it in the DG and UG instead.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/116#issuecomment-2782028826" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Bug resolved in PR #166 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-4/tp/issues/119#issuecomment-2782033104" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Couldn't reproduce bug.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 99. HOE .. HAO `@H-ZhanHao` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/269#issuecomment-2782553999" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Parser issue is fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/262#issuecomment-2782682333" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Changed to "must be greater than 0"
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/261#issuecomment-2782710271" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Added the message
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/260#issuecomment-2782725997" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

It should work now. Findforplan has been renamed to findplan for simplicity 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/257#issuecomment-2782733766" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Fixed! Added bounds checking.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 100. CHAN..THAN `@ecxm02` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2008788713" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Wait but for this one I need to create an arraylist for the storageManager to copy the files into though, its not just made only for ApplicationManager
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2008983371" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

It throws it because it uses the UI method, which throws it. Not exactly because I want to reuse the same exception

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/pull/50#discussion_r2008983374" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Same as above
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/92#issuecomment-2775005676" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

No issues found, but adjusted table date format to align with input for better intiuitive inputs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/138#issuecomment-2785120657" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Improved help clarity
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-2/tp/issues/161#issuecomment-2785125985" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Improved help message
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 101. BUI ..MINH `@minhbgn` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/195#issuecomment-2781229880" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Please use ```viewRecipeList```, as specified in the User Guide, or specified when clicking ```help```.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/190#issuecomment-2781231902" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Please use '''viewRecipeList''', as specified in the User Guide, and in the app when using command '''help'''
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/259#issuecomment-2781988629" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

This might be the issue running with Gradle. I tried running it normally and running it on JAR file it worked as expected.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/173#issuecomment-2783334124" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

It has been updated and fixed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/167#issuecomment-2783352188" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

I have noted that the line should be added line by line. Copy-pasting is inconsistent across computers which should not be used. Reopen this issue if you think we should make our program robust to copy-pasting unexpected values
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 102. WANG..NJIE `@olsonwangyj` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-4/tp/pull/56#discussion_r2017956466" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

it doesn't have a constructor, only contain an execute function
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 103. CHOW..RNAZ `@RaidaNUS` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/5#issuecomment-2737121087" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

DONE!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/3#issuecomment-2737123545" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

DONE!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/170#issuecomment-2783110838" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Solved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/171#issuecomment-2783112397" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Solved
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 104. HU H..HENG `@Hudou0420` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/159#issuecomment-2781450355" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Yep I have modified it to generate a shorter summary
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/158#issuecomment-2781450637" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Now it should have a detailed error, giving you more information
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/155#issuecomment-2781451226" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Its fixed now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/152#issuecomment-2781451507" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Now its fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/153#issuecomment-2781453581" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Now users can safely navigate between sub components
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/149#issuecomment-2781454451" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Now the program gives detailed errors.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/146#issuecomment-2781454666" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Now its fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/144#issuecomment-2781455274" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Now its fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/151#issuecomment-2781456659" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/136#issuecomment-2781456870" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/125#issuecomment-2781457344" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/124#issuecomment-2781457519" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/123#issuecomment-2781457723" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/122#issuecomment-2781458058" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-2/tp/issues/121#issuecomment-2781458335" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

The budget component currently do not have a delete command. We will include it in our future versions
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 105. LOKE..NZEL `@denzelloke` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/110#issuecomment-2771414864" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

✅ General Impressions

Awesome job on this PR! 🎉
The updates to both the README and the logging configuration show clear attention to detail and user experience. I can tell a lot of thought went into making FinBro both more user-friendly and robust under the hood. Nicely done 👏
📘 README.md

👍 What I Like:

    You’ve made the CLI examples interactive, which better reflects how FinBro actually works. This makes onboarding much easier for new users.

    Addition of budget and savings goal features to the feature list is helpful and accurate.

    I appreciate the visual consistency you’ve maintained even while extending the examples.

💡 Suggestions:

    Consider using consistent formatting for commands (some are prefixed with > while others are inside code blocks). Maybe wrap the entire flow in triple backticks for clarity.

    Adding a short table of contents at the top of the README could improve navigation, now that the feature list has grown.

🧠 LoggingConfig.java

👍 What I Like:

    Clear improvements to log rotation—moving from a static log file to a rotating log system is a solid upgrade.

    Great use of standard log levels across different packages—this will help a lot with debugging.

    Smart use of a Filter to suppress sensitive info from console output 💯

💡 Suggestions:

    The Copilot suggestion to use Instant.ofEpochMilli() instead of LocalDate.ofEpochDay(...) for timestamps is a good call—more accurate and safer. Consider applying it if time permits.

    Minor: you might want to extract the formatter and filter logic into private methods just to clean up configureLogging() a bit—it’s getting a tad long.

🧪 Testing Changes (EXPECTED.txt)

👍 What I Like:

    Great attention to detail in updating test expectations to match new logic and output (especially the date changes).

    Including real dates like 2025-04-02 makes the output predictable for automated UI testing.

💡 Suggestions:

    If these date shifts are due to today's system date changing, and not hardcoded in the test setup, consider mocking the system clock for consistency across test runs.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/118#issuecomment-2775940511" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Alan, this is a finely crafted pull request.
I thank you once more for your bountiful contributions.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/118#issuecomment-2775954696" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Local Gradle Build Tested.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-3/tp/pull/171#issuecomment-2780355019" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Great work on this PR! The introduction of the CurrencyFormatter utility is a solid improvement that centralizes and standardizes currency formatting across the app. This not only improves consistency but also simplifies future maintenance.

Clear separation of concerns with the new utility class.

Logical updates across commands and UI to use the formatter.

Robust input validation enhancements.

Test coverage has been thoughtfully updated to reflect the new formatting rules.

No major issues spotted. Everything looks clean and well-structured.

LGTM

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 106. NEO ..N QI `@icknee` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/106#issuecomment-2760419187" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

The use of the counter is a smart way to handle that exception, nice!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/109#issuecomment-2765455967" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Good work, exception handling for the group files is much more robust now. Great spot on the invalid file names!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/127#issuecomment-2772055050" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Good work on solving the bugs!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/132#issuecomment-2773180379" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Good spot on the bug, code also looks more readable now!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/137#issuecomment-2775088500" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Good work on the PPP!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/166#issuecomment-2780861431" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

User story 1 assumes everyone pays the same portion, so the expense is split evenly. User story 2 is split based on consumption, so custom amounts are to be paid per person.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/165#issuecomment-2780863080" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Since the terms payer and friend are used heavily in the project, we felt it was important to define each term clearly.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/190#issuecomment-2782089311" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Looks good!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/193#issuecomment-2783522250" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

![Image](https://github.com/user-attachments/assets/65b33e19-78ec-4125-8fbf-ea053382c9b1)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/193#issuecomment-2783527086" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

To state in UG that parameters must not contain `/`
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/195#issuecomment-2783867411" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Looks good!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 107. KEAN..IONG `@keanneeee` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-4/tp/pull/13#issuecomment-2720777338" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 108. QUAN.. WAI `@adoorknob` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/49#discussion_r2020056901" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

sounds about right thanks
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/issues/36#issuecomment-2763486892" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Better to use individual classes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/201#issuecomment-2785272348" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

fixing the styling messes up gradle
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 109. CHEL..SHMI `@lakshm1i` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-2/tp/pull/34#issuecomment-2733338564" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 110. JENS..HOCK `@Jensenkuok` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/89#issuecomment-2779166186" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

class/method names are consistently formatted and capitalised according to Java naming conventions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/90#issuecomment-2779181673" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Tested out, this is likely due to trailing space behind mcq command (ie: "mcq ") which is an invalid input, consider trimming inputs
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/87#issuecomment-2779184138" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Maybe we should just trim everything?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/69#issuecomment-2779207534" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Instructions are clear in User Guide, but we can still decide if we want to implement this guidance
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/84#issuecomment-2779219778" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

It is unlikely that a user woulf edit the question if he doesnt want to edit the questions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/74#issuecomment-2779227240" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Team, we can decide if we want to add in this guidance, or just refer to UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/82#issuecomment-2779246672" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

the command is `ist answer` as mentioned in the user guide
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/80#issuecomment-2779257571" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Edit 2 q should prompt user to update question, logic is fine in app. This is a UG documentation bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-3/tp/issues/81#issuecomment-2779260755" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Editting specific option might be tedious because of the random shuffling of options, maybe can ignore this improvement.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 111. NG W..IANG `@weiliangng` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/56#issuecomment-2764572227" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Thanks for the fix! 

Changing getName() to getType() in saveToFile() makes a lot more sense given the current class implementations.

Clean and concise update – great job!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/136#issuecomment-2779373387" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

This program assumes end user is savvy enough to directly edit the file, hence the user is well aware of the changes made to the file and does not need to be informed, corruption due to external forces cannot be differentiated from end-user changes without another file that is strictly only accessible by program or encrypted which is out of scope of this project
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/138#issuecomment-2779502985" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Bug has been fixed!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/120#issuecomment-2779515709" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Issue has been solved with improved input sanitization handling
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/127#issuecomment-2780280783" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

0 quantities should be automatically removed now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/114#issuecomment-2780549977" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/129#issuecomment-2780552630" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Enter command: list
This recipe requires the following ingredients:
1. 2x g_g
2. 2x g_r
3. 1x g

Fixed with the above presentation
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/128#issuecomment-2780554117" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

added check disallowing control and escape characters
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/126#issuecomment-2780556720" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

users are allowed to name their items with quotes or not, users are well aware of their actions, hence confusion is presumed impossible
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/124#issuecomment-2780558066" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/113#issuecomment-2780560368" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/104#issuecomment-2780564379" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

<img width="351" alt="Image" src="https://github.com/user-attachments/assets/1209df2e-5c45-448c-a193-1bc87963ffd8" />

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/108#issuecomment-2780567542" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

<img width="365" alt="Image" src="https://github.com/user-attachments/assets/c433f15d-d856-4c79-91cf-152b84bb1da8" />

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/115#issuecomment-2780570999" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

This is expected as a primitive "autocomplete/suggestion" feature planned ahead, when reactive GUI is implemented
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/110#issuecomment-2780572753" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

<img width="366" alt="Image" src="https://github.com/user-attachments/assets/559f1d0d-d731-43d5-886c-106291934ec6" />

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/107#issuecomment-2780575868" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

<img width="396" alt="Image" src="https://github.com/user-attachments/assets/a274ca0d-a86b-48e2-a6ab-d87958db7181" />

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/116#issuecomment-2780576986" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

<img width="396" alt="Image" src="https://github.com/user-attachments/assets/62e1aa4b-1d27-463e-8b78-1bfbf0836459" />

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/130#issuecomment-2780580315" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

numbers with +8 are naturally interpreted as positive 8 -&gt; 8, following the natural law and order of mathematics, although the sign is not required for positive numbers
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/132#issuecomment-2780581816" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

<img width="374" alt="Image" src="https://github.com/user-attachments/assets/0ee9cc66-d962-48c0-80f0-f9c22ce65f8b" />

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/133#issuecomment-2780582224" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

<img width="370" alt="Image" src="https://github.com/user-attachments/assets/a42b94bc-adbb-41f0-939f-39efdbc5b08f" />

immediate matches do not prompt seperate entries anymore fixed.

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/171#issuecomment-2780632481" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

Rudimentary Unit testing for refactored classes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/170#issuecomment-2780632632" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/155#issuecomment-2780872909" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/106#issuecomment-2780875352" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

Integer and name limits have been added
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/112#issuecomment-2780876593" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

Completed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/118#issuecomment-2780877954" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

Completed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/91#issuecomment-2780880984" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/125#issuecomment-2780885238" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

Add UG to say use _ delimiter for ingredient names 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/146#issuecomment-2781047664" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

these characters are allowed, only special control, + characters not allowed now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/135#issuecomment-2781048236" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

github/catcher integration is out of scope in the context of functionality for user
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/102#issuecomment-2781048594" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

file is only read on startup, contents are imported, modifications while program is running is ignored as file is overwritten on saving
file is only saved on bye command
user may update file only while program is not running
This functions as a speed editor/importing, or ways for text file to be programmatically generated using scripts in the following format:
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/142#issuecomment-2781050806" expanded>
<div slot="header">

**32 :octicon-comment:** %%(other comment)%%
</div>

file is only read on startup, contents are imported, modifications while program is running is ignored as file is overwritten on saving
file is only saved on bye command
user may update file only while program is not running
This functions as a speed editor/importing, or ways for text file to be programmatically generated using scripts in the following format:

crashes have been addressed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/101#issuecomment-2783658357" expanded>
<div slot="header">

**33 :octicon-comment:** %%(other comment)%%
</div>

please use:

 add 2 grams of sugar now
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/199#issuecomment-2785107852" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

Nice addition of the upper limit check and informative message when skipping excess ingredients—this improves robustness and user transparency. Consider making the max count (100) a named constant for easier maintenance and reuse.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 112. JOEL.. JUN `@itsjoelha` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/33#issuecomment-2743256835" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

As a student, I want to add a module to a specific semester so that I can organize my academic plan.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/32#issuecomment-2743258175" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

As a student, I want to view my module workload for a specific semester so that I can manage my study schedule effectively.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/53#issuecomment-2758239285" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

LGTM! Nice job with the cases intead of if-else :)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/56#issuecomment-2763147715" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/172#issuecomment-2780122574" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Fixed - only allow 1 argument max and must be an integer between 1 and 8.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/171#issuecomment-2780123645" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Fixed - any custom mods the user adds that has the substring "GEC" or "GEN" will now clear the grad requirements.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/162#issuecomment-2780126728" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Fixed - /workload only allows 1 argument max and must be an integer between 1 and 8
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/160#issuecomment-2780127425" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Fixed - /view only allows 1 argument maximum & must be an integer between 1 and 8.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/157#issuecomment-2780127740" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/155#issuecomment-2780128915" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Fixed - whenever a custom module is added to user's database that contains the substrings "GEC" or "GEN", the respective module is removed from the graduation list.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/154#issuecomment-2780131770" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/139#issuecomment-2780139245" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Fixed - if CommandParser detects no input, returns true and continues looking for new input
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/126#issuecomment-2780140031" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/125#issuecomment-2780140349" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/123#issuecomment-2780140550" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/120#issuecomment-2780140736" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/147#issuecomment-2780600050" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/130#issuecomment-2780624232" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/170#issuecomment-2782313973" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

Unable to replicate, fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/153#issuecomment-2782400586" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

Working on this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/153#issuecomment-2782529266" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/152#issuecomment-2782530760" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/149#issuecomment-2782544733" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

unable to replicate as well
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/141#issuecomment-2782560553" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

Fixed?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/133#issuecomment-2782629858" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/131#issuecomment-2782674072" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/143#issuecomment-2782677910" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

fixed
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 113. WONG.. HAO `@wongyihao0506` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/23#issuecomment-2740944827" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Added in #23
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 114. ROMA..OSHI `@Roma637` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/82#issuecomment-2768610075" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

lmao failing CI
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 115. ZHAN..OHAN `@xiaohan28` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/107#issuecomment-2760952414" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/110#issuecomment-2765707270" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/134#issuecomment-2773185182" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Thanks for upating the DG!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/130#issuecomment-2773186937" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Comprehensive delete function
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/135#issuecomment-2774250244" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/issues/152#issuecomment-2780600821" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

![Image](https://github.com/user-attachments/assets/95eef3cf-a167-4a6f-9ae3-7a976899210c)

Help command displays the format for user input and for this case, the user input format for net balance is present in the screenshot of the issue as shown above, hence there is no bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/171#issuecomment-2780628981" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

LGTM - great work cleaning up edge cases! 
Everything looks well-tested and aligned with the issues raised during PE-D. 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 116. LEE ..AIRE `@clj55` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/70#issuecomment-2765380636" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/75#issuecomment-2767955924" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/77#issuecomment-2769719588" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/82#issuecomment-2772681679" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

setup page lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/85#issuecomment-2775613769" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/89#issuecomment-2775935473" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

lgt
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/104#issuecomment-2777552187" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/170#issuecomment-2781201755" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Same I cannot replicate it 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/166#issuecomment-2781203332" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Thats because CS2040C needs the prerequisite CS1010

![Image](https://github.com/user-attachments/assets/232fd295-7e90-4fcc-81c4-5357148b0e4d)

Will add a print prerequisites after the missing prerequisites to make it clearer for the user
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/167#issuecomment-2781204189" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Add a /waivePrereq function that toggles on and off whether prereq is checked?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/158#issuecomment-2781211173" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Will manually add Su-able field to moddata file
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/149#issuecomment-2781230009" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

cannot replicate error
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/167#issuecomment-2783853593" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

am working on it rn 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/224#issuecomment-2784280951" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

lgtm 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/227#issuecomment-2785112120" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

lgtm 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/244#issuecomment-2785255691" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 117. CHUA..A EN `@cj143n` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/140#issuecomment-2781540497" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

I have made registering multiple patients of the same name impossible. @jhu0748 u can close it once u think its good to go.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 118. WONG.. HUI `@chuanhuiw` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/12#issuecomment-2726554088" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Done.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/35#issuecomment-2733794641" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Hi Good job refactoring the code to suit addressbook2 as given in lecture. This will really help us in structuring our codebase so that future feature additions can be done much more efficiently!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/44#issuecomment-2742550297" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Good job avoiding checkstyle errors as well as adding assertions in your test cases! LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/45#issuecomment-2747940424" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Amazing work with the cleanup and refactoring our code such that we have 3 different interfaces for Inventory, Recipe and Shopping. Great job with the javaDoc as well.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/50#issuecomment-2758202646" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Good job updating shopping list as discussed as well as improving our test cases such that UI and Parser have 100% branch coverage!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/67#issuecomment-2769326894" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

good job adding user stories to the DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/80#issuecomment-2775659007" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Good work restructuring the UI UML diagram to the standards we have learnt in lecture
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/86#issuecomment-2776258424" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/93#issuecomment-2777929621" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

I see you have found the bug that causes your code to crash when user runs cook [name] function. However, should add exception handling for this feature such as null cases (ex: user inputs "cook").
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/92#issuecomment-2778142914" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/186#issuecomment-2783725853" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/195#issuecomment-2784982802" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/196#issuecomment-2785051236" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/198#issuecomment-2785072006" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/201#issuecomment-2785175191" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 119. LIU ..SHAN `@lys2333` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-3/tp/pull/140#discussion_r2025088533" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok fixed
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 120. AHMI..NAIR `@Ahmish15` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W13-4/tp/pull/54#issuecomment-2741046906" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 121. JONA.. JOE `@Jonathan2745` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/81#issuecomment-2772448607" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/64#issuecomment-2775451703" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Acknoledgements, Setting up Getting started complete
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/91#issuecomment-2775991879" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

LGTM

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/90#issuecomment-2776000220" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/93#issuecomment-2776102321" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/92#issuecomment-2776126914" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/96#issuecomment-2776210086" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

LGTM! 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/105#issuecomment-2777559971" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/177#issuecomment-2780133916" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/169#issuecomment-2780182797" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Fixed bug with error using totalMcs instead of only graded mcs

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/133#issuecomment-2780185944" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

unable to replicate

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/170#issuecomment-2780186724" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

unable to replicate - fixed ?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/163#issuecomment-2780188024" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

# noted

#### planned revision is to add said variables with modify feature

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/156#issuecomment-2780198446" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

fixed

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/136#issuecomment-2781308120" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

will add check for MC for custom

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/151#issuecomment-2781446848" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

will add to UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/167#issuecomment-2783149232" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

I think can define as out of scope ?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/128#issuecomment-2783180003" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

will fix by preventing special characters from allowed as input for /add
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/140#issuecomment-2784031868" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

added to UG, thanks for pointing that out
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/145#issuecomment-2784159427" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

double checking in abit

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/216#issuecomment-2784200050" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/142#issuecomment-2784200848" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Out of scope, mentioned in new UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/221#issuecomment-2784220208" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/146#issuecomment-2784222580" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

closed, out of scope, refer to revised UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/222#issuecomment-2784239520" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

LGTM!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/142#issuecomment-2784248260" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

### 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/138#issuecomment-2784250510" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

out of scope, added to UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/223#issuecomment-2784269458" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/pull/225#issuecomment-2784944252" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/127#issuecomment-2785277061" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

Intended feature
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-2/tp/issues/41#issuecomment-2785282407" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

out of scope
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 122. TAN ..ROMY `@jxromy` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/6#discussion_r1975638591" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Yes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/5#issuecomment-2685131366" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

As a user who made an erroneous input, I can delete my entries
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/22#issuecomment-2731477462" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Minor refactoring done to StorageTests which now passes checkstyle
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/45#issuecomment-2740900217" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

There are 2 failing test cases to be fixed in our code:
1. execute_addInvalidDishName_returnsInvalidDishNameMessage - to fix by handling empty string inputs for dish name
2. execute_addDishWithInvalidDate_returnsInvalidDateMessage - to fix by handling  dates added in formats other than "YYYY-MM-DD"
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/90#issuecomment-2772459732" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

DG has also been updated with commands package and errors corrected in the UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/160#issuecomment-2779351100" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

this is the intended behaviour of our application, "list -ingredient" shows the list of ingredients that the user has
"list -recipe" is the correct command to view the required ingredients of the newly created recipe
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/128#issuecomment-2779403495" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

User guide needs to properly document how "list -shopping" works and perhaps example manual testing to be shown in DG's appendix.

Below is an example of proper usage of the command, where "garlic_bread" is a known recipe, has been scheduled with "add -dish=garlic_bread" and the user only has 1 garlic, 0 bread and 0 butter in his available ingredients:

<img width="949" alt="Image" src="https://github.com/user-attachments/assets/7f1d65a8-95c8-47d6-819a-0e9207a7dcd8" />
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/155#issuecomment-2781485911" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Bug resolved after changing input for delete -recipe to take in recipe name instead of recipe index.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/129#issuecomment-2781487763" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

<img width="623" alt="Image" src="https://github.com/user-attachments/assets/b3fd0dba-abf6-45ee-87f7-96583c2e3adb" />
Issue fixed in v2.1, deletion of duplicate recipes are now handled similar to removal of dishes with the same name from calendar
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/issues/130#issuecomment-2781488550" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

This is an expected behaviour of our application
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 123. STEV..N XU `@Stevexchia` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-2/tp/issues/57#issuecomment-2783957024" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Not possible to resolve on CLI Terminal.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-2/tp/issues/79#issuecomment-2784098254" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Format is serializable, not in json or human readable format
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 124. TAN .. XIN `@yx-tzzz` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-3/tp/issues/104#issuecomment-2783399127" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Closed as completed
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 125. XIE ..NJUN `@xyanjun02` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F12-2/tp/pull/14#issuecomment-2733647278" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Code is now much cleaner and concise, thanks!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 126. PHUA..HIAN `@Phua-Lock-Hian` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/pull/67#discussion_r2009544794" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

thanks!

> Formatter.printSimpleMessage() adds an indent of 5 spaces for every line


</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/pull/63#issuecomment-2745013016" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

to add what are the allowed categories and conditions in future if restricted
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/pull/67#issuecomment-2745276994" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

the i/o redirection test is failing due to difference in indentation i think but i can't figure out how much it wants
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/142#issuecomment-2774535383" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

solved in PR #146 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/202#issuecomment-2781359448" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

check if can close after PR #225
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-2/tp/issues/169#issuecomment-2781359661" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

closed with #225 
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 127. NICH..ONG) `@nictzl` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-1/tp/pull/185#issuecomment-2781461175" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

sozz checkstyle fail, will fix it tmr
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 128. OJAS..RANA `@ojassurana` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/116#issuecomment-2782083046" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Solved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/101#issuecomment-2782099800" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Solved!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/98#issuecomment-2782115354" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Fixed! Now it just shows no photos in trip. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/91#issuecomment-2782127625" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

It's already mentioned in our UG:
```
Trip date ranges are automatically determined based on the dates of photos added to the trip. The earliest photo date becomes the trip start date, and the latest photo date becomes the trip end date. You cannot manually set these dates when creating a trip.
```
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/88#issuecomment-2782138681" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

This is not true. Kindly please check it again. What's happening is that even if you switch the orders, the name and description is correct in it's own order.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/105#issuecomment-2782140248" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Thanks for your info! We will work on this if time permits.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/93#issuecomment-2782317935" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

It's not an issue. The image you provided does not have meta data. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/95#issuecomment-2782422199" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Only .jpg images with GPS data can be added. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/94#issuecomment-2782707776" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Hard to replicate error
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/111#issuecomment-2782729624" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

DONE
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/120#issuecomment-2782748426" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

The UG states you need to indicate the image directory which you did not. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/113#issuecomment-2782761540" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 129. KIM ..URIM `@yok2086` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/235#issuecomment-2781256015" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

will fix soon
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/261#issuecomment-2781998138" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

<img width="247" alt="Image" src="https://github.com/user-attachments/assets/6f20093c-2fd6-4688-bc9e-58fe93262050" />

also similarly, for the removeRecipeFromPlan also could add message when its successfully removed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/203#issuecomment-2782841845" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

repeat of other issue
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 130. PENG..ZIYI `@Lukapeng77` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/137#issuecomment-2780222012" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

For setbudget command you should follow the format as "setbudget a/AMOUNT" as described in the UG. 

![Image](https://github.com/user-attachments/assets/5bfc43e5-f088-40f0-88ab-2b872b5e1711)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/111#issuecomment-2780224149" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Added the help command and some Junit tests
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/133#issuecomment-2781186700" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Now the priority is added to the list command functionality. 

![Image](https://github.com/user-attachments/assets/fae284ce-73c8-4eaa-8bbb-8efc0fa8b65f)

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/129#issuecomment-2781189331" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Fix the UI displays for notify command.

![Image](https://github.com/user-attachments/assets/81240772-03d8-4dcd-ba55-340d3987f60d)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/149#issuecomment-2781189947" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Fix the UI display for the notify command. 

![Image](https://github.com/user-attachments/assets/aa00c091-f625-4cd1-8b70-668e4d6aa54c)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/128#issuecomment-2781195266" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Check the input date invaild or not, like set the date cannot before 2020.

![Image](https://github.com/user-attachments/assets/0c91e620-1b1d-40ff-a2f8-0d9f7caf9fc3)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/95#issuecomment-2781309056" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Now the budget can be set to 0, and the difference between current transactions and budget will be reflected. 

![Image](https://github.com/user-attachments/assets/fe68a43d-8bc0-411f-8ac5-fce5e1c11b3f)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/100#issuecomment-2781313740" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Handle the case of large input amount of budget.

![Image](https://github.com/user-attachments/assets/80cc7954-3695-4887-8c7d-ba6d4a8f9640)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/96#issuecomment-2781314658" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Handle the case for negative input budget amount

![Image](https://github.com/user-attachments/assets/35badf7d-2f52-470b-8d84-2690968b71fd)
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 131. JIAN..KUAN `@jyukuan` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/125#issuecomment-2781210322" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Thanks for debuging! That the real bug and already solved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/123#issuecomment-2781211009" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Thanks for debuging! That the real bug and already solved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/113#issuecomment-2781211470" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Thanks for debuging! That the real bug and already solved.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 132. KIM ..NJIN `@hyunjinkim1112` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/62#discussion_r2023113088" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

i edited accordingly. Thanks for spotting that out!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/41#issuecomment-2747096794" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

looks good to me.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/51#issuecomment-2764902313" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

looks good to me!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/54#issuecomment-2765100027" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

looks good. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/59#issuecomment-2768111405" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/61#issuecomment-2769591899" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/67#issuecomment-2774723512" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Looks valid to me.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-2/tp/pull/69#issuecomment-2775198565" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

looks good!
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 133. XIAO..ELEI `@xiaojielei` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/pull/58#discussion_r2020939360" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Updated. I added dotted lines for :Duke and :Saving
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11A-4/tp/issues/19#issuecomment-2730138281" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

 Lists all savings records.

</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 134. LE T..MINH `@LeThiHongMinh` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/62#issuecomment-2776152415" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Solved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/121#issuecomment-2780723013" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Solved in new commit for UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/96#issuecomment-2781487615" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

solved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/118#issuecomment-2781999819" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

remove the tips
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/117#issuecomment-2782005188" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Solved by change the description to required
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/89#issuecomment-2782006383" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

solved by change description of add_trip in help function to "required"
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/90#issuecomment-2782008562" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Solved by make changes to UG "trip -&gt; list"
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/92#issuecomment-2782009143" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

solved by make changes to UD "trip [ID] -&gt; select [ID]" in trip
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/99#issuecomment-2782009981" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

solved by pushing the images
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/112#issuecomment-2782559536" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Reorganized DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/114#issuecomment-2782562064" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Add manual testing in DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/108#issuecomment-2782567920" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Reorganized DG accordingly
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/103#issuecomment-2782569648" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

Add user stories in DG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/104#issuecomment-2782573533" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Fix
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/106#issuecomment-2782599128" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

Added manual testing
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/107#issuecomment-2782604889" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Added non functional requirements and manual testing
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-3/tp/issues/109#issuecomment-2782629102" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

They are automatically added, we specify in UG
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 135. CHAN.. YEE `@chwenyee` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/18#issuecomment-2736974255" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Added Exception and JUnit Test
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/16#issuecomment-2736975831" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Added Exception and JUnit Test
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/111#issuecomment-2780717004" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Updated the UG where the part states that the order of parameters matters.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 136. JUNE..SHAT `@juneja999` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/42#issuecomment-2763093220" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

The packages are relevant and complement the workflow well.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/39#issuecomment-2763095988" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Yes, that would be ideal.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-4/tp/pull/157#issuecomment-2785155459" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Thanks for adding the error message for edge case.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 137. TRAN.. KIM `@thienkimtranhoang` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/26#issuecomment-2732992101" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Done. Store to data/budgetflow.txt
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/31#issuecomment-2732998664" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/185#issuecomment-2780139107" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Suggestion: Add notes in UG that users need to have a space between each parameter
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/183#issuecomment-2780142152" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Add notes in UG, simply tell users not to do this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/151#issuecomment-2780146675" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Add note in UG saying that this chatbot is only for English characters
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/147#issuecomment-2780165412" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Update so that Income and Expenmse amount must be >0
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/165#issuecomment-2780169219" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

edit regex 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/187#issuecomment-2781212980" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Don't really understand this bug. Do they mean they changed the content in datatxt and then the actual data are not updated?
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 138. CHAK..UDEB `@Basudeb2005` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/pull/135#issuecomment-2781133684" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Which bug are you trying to fix in this pull request??

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/110#issuecomment-2784499827" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Thanks a lot have fixed this issue in our version 2.1
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11b-4/tp/issues/115#issuecomment-2784598234" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

<img width="454" alt="Image" src="https://github.com/user-attachments/assets/7d37ece2-2bf0-4476-be7d-c6f2aad6914d" />
<p> Thanks, have made the formatting better for v2.1</p>
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 139. PANG..ZIXI `@HalFentise` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/2#issuecomment-2705638963" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

must add comment then can merge
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/3#issuecomment-2705702559" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

approve
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/10#issuecomment-2717779997" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

So can constantly remind myself not to spend too much.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/118#issuecomment-2781187344" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

ill fix this

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/110#issuecomment-2781187985" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

we will delete tag
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/110#issuecomment-2781188138" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

i can change it to optional date
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/123#issuecomment-2781188426" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

we need to add maunal testing instruction
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/103#issuecomment-2781188779" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

ill fix this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/91#issuecomment-2781189152" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

ill fix this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/90#issuecomment-2781189283" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

ill fix this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/85#issuecomment-2781189435" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

ill fix this
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/93#issuecomment-2781293579" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

this is not caused by our product, this may caused by turn on two jar file
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/175#issuecomment-2781888371" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

need to solve conflict first
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/175#issuecomment-2781928124" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

need to delete all chinese comment, alse nedd to delete emoji in ui output, im afraid cmd cannot display emoji
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 140. TONG.. YEN `@jing-yen` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/179#issuecomment-2780604603" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Lgtm
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-2/tp/pull/183#issuecomment-2780951874" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

LGTM
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 141. ZHU ..NGYI `@yangyi-zhu` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/132#issuecomment-2780439854" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

I think this is because CMD can't display the checkmark unicode character ✓ similar to how it deals with Chinese characters. Maybe it could be replaced with another character which displays correctly.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/130#issuecomment-2780475170" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Missing +1 in ID
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/128#issuecomment-2780531189" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Use the isBefore method
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/127#issuecomment-2780541593" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Add a condition for empty searchTransaction
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/151#issuecomment-2780542916" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Filter out complete transactions
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/146#issuecomment-2780543420" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

File exists but message wrong
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/145#issuecomment-2780543687" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Incorrectly added instead of subtract
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/140#issuecomment-2780547518" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Error with documentation in UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/131#issuecomment-2780548268" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

Wrong prefix in UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/115#issuecomment-2780553217" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Case sensitivity, use toUpperCase
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/113#issuecomment-2780555876" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

Not bug
Input should be goal desc
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/112#issuecomment-2780557087" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

Likely case sensitivity problems
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/102#issuecomment-2780565875" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

toUpperCase
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/101#issuecomment-2780567022" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

UG documentation error
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/99#issuecomment-2780568444" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

UG problem
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/98#issuecomment-2780575101" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

Wrong error message for failed parseInt
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/97#issuecomment-2780576550" expanded>
<div slot="header">

**17 :octicon-comment:** %%(other comment)%%
</div>

Documentation error (should be setbudget)
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/91#issuecomment-2780592920" expanded>
<div slot="header">

**18 :octicon-comment:** %%(other comment)%%
</div>

add if id = 0 throw InvalidCommand("Invalid id") or something else along these lines
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/91#issuecomment-2780593392" expanded>
<div slot="header">

**19 :octicon-comment:** %%(other comment)%%
</div>

&hat;&hat; to searchTransaction
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/89#issuecomment-2780596748" expanded>
<div slot="header">

**20 :octicon-comment:** %%(other comment)%%
</div>

CMD doesn't support Chinese characters, not bug
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/88#issuecomment-2780597889" expanded>
<div slot="header">

**21 :octicon-comment:** %%(other comment)%%
</div>

Forgot to add hyperlink
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/81#issuecomment-2780600633" expanded>
<div slot="header">

**22 :octicon-comment:** %%(other comment)%%
</div>

Duplicate issue, closed to ease debugging
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/83#issuecomment-2780600695" expanded>
<div slot="header">

**23 :octicon-comment:** %%(other comment)%%
</div>

Duplicate issue, closed to ease debugging
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/84#issuecomment-2780600780" expanded>
<div slot="header">

**24 :octicon-comment:** %%(other comment)%%
</div>

Duplicate issue, closed to ease debugging
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/131#issuecomment-2780601903" expanded>
<div slot="header">

**25 :octicon-comment:** %%(other comment)%%
</div>

Duplicate issue, closed to ease debugging
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/101#issuecomment-2780601965" expanded>
<div slot="header">

**26 :octicon-comment:** %%(other comment)%%
</div>

Duplicate issue, closed to ease debugging
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/99#issuecomment-2780602028" expanded>
<div slot="header">

**27 :octicon-comment:** %%(other comment)%%
</div>

Duplicate issue, closed to ease debugging
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/98#issuecomment-2780959038" expanded>
<div slot="header">

**28 :octicon-comment:** %%(other comment)%%
</div>

Problem identified was due to this feature relying on another method that threw an unanticipated NullPointerException. Fixed by decoupling. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/145#issuecomment-2780962102" expanded>
<div slot="header">

**29 :octicon-comment:** %%(other comment)%%
</div>

Original code accidentally subtracted the other way, fixed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/108#issuecomment-2780971202" expanded>
<div slot="header">

**30 :octicon-comment:** %%(other comment)%%
</div>

The current implementation uses parseInt, and since Java integers are 32 bits signed, they only go up to 2147483647.
We are reworking the system to use double instead, which should have a greater limit. If any problem persists, the physical limit will be mentioned in the docs.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/80#issuecomment-2780992442" expanded>
<div slot="header">

**31 :octicon-comment:** %%(other comment)%%
</div>

Was not implemented, incorrectly documented in UG
Will add towards the end
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/151#issuecomment-2781548012" expanded>
<div slot="header">

**32 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/105#issuecomment-2781603995" expanded>
<div slot="header">

**33 :octicon-comment:** %%(other comment)%%
</div>

Problems with id range condition and case-sensitivity
Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/130#issuecomment-2781606377" expanded>
<div slot="header">

**34 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/87#issuecomment-2781606917" expanded>
<div slot="header">

**35 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/107#issuecomment-2781606949" expanded>
<div slot="header">

**36 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/issues/82#issuecomment-2781607001" expanded>
<div slot="header">

**37 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/173#issuecomment-2781811158" expanded>
<div slot="header">

**38 :octicon-comment:** %%(other comment)%%
</div>

PR includes other bug fixes
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-1/tp/pull/173#issuecomment-2781887216" expanded>
<div slot="header">

**39 :octicon-comment:** %%(other comment)%%
</div>

For UI changes with edit wizard it can simply take inputs and create string that resembles what the current edit command format looks like. This PR mostly has to do with the logic of the edit feature.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 142. CAI ..IALI `@kemilii` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/268#issuecomment-2782282092" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Shopping list is generated based on the inventory where ingredients with quantities under threshold will be added in the list. Can I check if you have such ingredients?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F11-3/tp/issues/280#issuecomment-2783664423" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

same for viewIngredientsByCategory command

<img width="430" alt="Image" src="https://github.com/user-attachments/assets/0de80b49-6dee-4339-9bc8-2800179eaa7e" />
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 143. WILL..STIE `@gitHST` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/203#discussion_r2032400381" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

😭 exposed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/1#issuecomment-2671135285" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

It fails the IO tests, as of right now im not sure how to fix but I dont think its an issue yet
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/21#issuecomment-2727337505" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

![giphy](https://github.com/user-attachments/assets/53c306d2-8707-48e0-be32-d1e7f68e1e77)

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/23#issuecomment-2729180175" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Hi dude any chance you could lint this and re-push?
`.\gradlew check`
ty bro 🙏


![tenor](https://github.com/user-attachments/assets/94d49914-251d-44b5-a658-632441b75416)

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/25#issuecomment-2733486043" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Going to approve this myself as v1.0 is due soon
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#issuecomment-2744266994" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

Each command into its own FILE holy moly
I mean I don't mind if you wanna then I'm down, thats another level tho haha
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/50#issuecomment-2744270428" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

@vegetablestabber This is functionaly speaking complete, however it is VERY messy.
I'm going to be pretty busy over the next week, but if i find time I will do my best to clean it up as right now it is for lack of a better term shameful 😭
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/50#issuecomment-2744272276" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

But basically I wanted to say that if you need it to develop other features then you could always PR it, and it can be cleaned up at a later date? Like I said, it does work, so 🤷‍♂️
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/50#issuecomment-2745030079" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

@vegetablestabber I think it should be fine, as long as we keep the same method constructors. Ie if we have method foo that takes in int bar and outputs result, as long as the input and output stay the same, we can change the internals however we want.
So like as long as we decide now on the correct method headers and the format of the response, then we can completely change the internals without issue. Anyway idm tho either way 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W12-1/tp/pull/49#issuecomment-2745031385" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

I'm totally cool with this approach, it makes sense, however Im just curious, How do you go about debugging? You've mentioned a few times that we would have to scour through alot of code but the stack trace tells you exactly where the error occurs and where it comes from no? no shade, just curious if you could elaborate 😅
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 144. CHON..OLIN `@CRL006` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/49#issuecomment-2760346672" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Hmm makes sense, is this ok?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F13-1/tp/pull/49#issuecomment-2760353247" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

yep ok done
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 145. HU J..XUAN `@jhu0748` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/146#issuecomment-2784595796" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

Fixed in taskManager parsing of user input
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T12-1/tp/issues/137#issuecomment-2784615421" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Added a note in UserGuide under 'update' command that when updating patient's doctor info, user must also update doctor's patient info and vice versa.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 146. CHIU..LONG `@paklongchiu` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/182#issuecomment-2781493841" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

None of this is found in the User Guide.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/186#issuecomment-2781494796" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Both example usages contain budget, just in different orders. 
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/180#issuecomment-2781496070" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

This allows maximum flexibility for users to enter the commands, if they want, they can always stick to a format they like/are used to for entering all commands.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/162#issuecomment-2781497322" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Logging info leakage has been solved.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/146#issuecomment-2783291007" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Resolved
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/147#issuecomment-2783300116" expanded>
<div slot="header">

**6 :octicon-comment:** %%(other comment)%%
</div>

It's a user-end issue, works fine for normal users.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/153#issuecomment-2785179477" expanded>
<div slot="header">

**7 :octicon-comment:** %%(other comment)%%
</div>

Considered as user-end issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/184#issuecomment-2785182269" expanded>
<div slot="header">

**8 :octicon-comment:** %%(other comment)%%
</div>

Amended
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/217#issuecomment-2785182825" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

All fixed
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/148#issuecomment-2785184035" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

Fixed
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 147. LEE ..LISA `@melee01` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/47#discussion_r2025454569" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

ok

</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-4/tp/pull/22#issuecomment-2757084237" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Ok
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 148. CHEN..I YU `@J030104` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/47#issuecomment-2748983406" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

NOICE JOB
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/pull/52#issuecomment-2758595115" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

The naming feels much better
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T13-1/tp/issues/61#issuecomment-2771241963" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

This is what I did on purpose. In fact, I think this is quite useful in daily life when you are lazy and don't want to check the number of a specific ingredient. All you want is that "This ingredient should be n". Isn't it fast to just update the quantity? However, I should've written this in user/developer guide.
In short, this should be taken care of but might not be treated as a bug.
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 149. TAN ..ENNY `@je-nnyt` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/pull/21#discussion_r1997518493" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Good point! I will remove it!
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-F14-3/tp/issues/164#issuecomment-2781252434" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Tester potentially used wrong index to delete transportation. Should be delete transportation --i 1
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 150. HO S..ASON `@Jason-Hp` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/14#issuecomment-2689800700" expanded>
<div slot="header">

**1 :octicon-comment:** %%(other comment)%%
</div>

 Variable 'dukeBox' should be in ALL_CAPS (if it is a constant) or be private (otherwise). [ConstantName]
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/pull/55#issuecomment-2766061776" expanded>
<div slot="header">

**2 :octicon-comment:** %%(other comment)%%
</div>

Might need to force merge with master branch to overcome checks failing?
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/issues/115#issuecomment-2781035638" expanded>
<div slot="header">

**3 :octicon-comment:** %%(other comment)%%
</div>

Further discussion may be needed? But icons are just another variant of + - ~ #, but are still correct.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/issues/101#issuecomment-2781035936" expanded>
<div slot="header">

**4 :octicon-comment:** %%(other comment)%%
</div>

Resolved in another issue
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-W11-1/tp/issues/104#issuecomment-2781036249" expanded>
<div slot="header">

**5 :octicon-comment:** %%(other comment)%%
</div>

Resolved in another issue already
</panel>

</panel>


<panel type="info"  collapsed>
<div slot="header">

### 151. ANAK..MANA `@IgoyAI` (**0** comments)
</div>


<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/116#discussion_r2024866381" expanded>
<div slot="header">

**1 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/116#discussion_r2024866581" expanded>
<div slot="header">

**2 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/116#discussion_r2024866745" expanded>
<div slot="header">

**3 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/124#discussion_r2027198402" expanded>
<div slot="header">

**4 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029829568" expanded>
<div slot="header">

**5 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

it is wrong in the UserGuide.md since the beginning, my bad. Will fix it.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/188#discussion_r2029829637" expanded>
<div slot="header">

**6 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

okay
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/208#discussion_r2030462946" expanded>
<div slot="header">

**7 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

Just making it less details as per the review by the TA. Ok CommandType removed.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/208#discussion_r2030463138" expanded>
<div slot="header">

**8 :octicon-git-pull-request::octicon-comment:** %%(commented on own PR)%%
</div>

oh yea, activation blocks added now.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/186#issuecomment-2780125489" expanded>
<div slot="header">

**9 :octicon-comment:** %%(other comment)%%
</div>

There is some mistakes in the UG command. Fixed already.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/154#issuecomment-2780125785" expanded>
<div slot="header">

**10 :octicon-comment:** %%(other comment)%%
</div>

There is some bug in the documentation. Fixed already.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/159#issuecomment-2780126002" expanded>
<div slot="header">

**11 :octicon-comment:** %%(other comment)%%
</div>

There is mistake in the documentation. Fixed already.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/172#issuecomment-2781151728" expanded>
<div slot="header">

**12 :octicon-comment:** %%(other comment)%%
</div>

success.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/145#issuecomment-2781182821" expanded>
<div slot="header">

**13 :octicon-comment:** %%(other comment)%%
</div>

done
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/issues/135#issuecomment-2781211719" expanded>
<div slot="header">

**14 :octicon-comment:** %%(other comment)%%
</div>

Fixed in UG
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/198#issuecomment-2781893771" expanded>
<div slot="header">

**15 :octicon-comment:** %%(other comment)%%
</div>

hi, there is some conflicts needed to be resolved. Thanks.
</panel>

<panel  popup-url="https://github.com/AY2425S2-CS2113-T11a-1/tp/pull/209#issuecomment-2782253819" expanded>
<div slot="header">

**16 :octicon-comment:** %%(other comment)%%
</div>

hi, please check DG.
</panel>

</panel>
