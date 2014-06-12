# Collaborative Brain Dump

## Jakarta Functional Programmers

### Haskell weaknesses

*   have to recompile on target machine (can cross-compile?
    I tried compiling on Ubuntu 12, copied the generated program to a machine running Ubuntu 11,
    and executing the program fails with an error message mentioning libc)
*   mobile
*   installation
*   dynamic linking
*   cabal
*   patchy documentation
    *   A possible solution to this is git clone the source,
        document (Haddock) the source, and send the changes as a patch.
        We can start The Haskell Documentation Project like The Linux Documentation Project.
        We pick underdocumented great libraries and improve their Haddock documentation.
        It will help everyone after us.
        It will help us ten years from now.

### What are the advantages of Haskell compared to X?

#### The answer of the synthetic philosopher who happens to be a disciple of Socrates

*   Does Haskell actually _help_ people solve _their_ problems?
    How large is the class of the problems Haskell actually help people solve?
*   Do people ask "What are the advantages of C compared to X?"
    They don't. They simply use C. Why? They have no choice.
    Why don't they have any choice?
    Nobody bothers to make a choice for them.
*   If people do not have any reason left for not using Haskell,
    will they use Haskell?
    Do people even need a reason to do something?
    Are people even rational?
    Are they only following their peers?
    Are they only using what their peers use?
    Do friends let friends use Haskell?
    Do friends let friends use Java?
*   Why do people use a language?
    Because others are using them.
    People use a language because other people are using them.
    Language is a means of communication.
    Communication requires at least two parties.
    Your self in a sufficiently far future counts as one party
    that is distinct from your present self.
    If there is no need to communicate, you don't need a language.
*   Do we need to answer this question?
    Will any answer to this question ever make enough people switch to Haskell?
    If Haskell were widely used, would people still ask this question?
    Do people really care about the answer?
    Why do they ask this question?
    Do they ask this question for the sake of asking,
    that is to avoid switching (or even thinking about switching) to Haskell?
    Will they never switch regardless of the comprehensiveness of the answers we give?
*   Why do they have to be convinced? Because it is not _common_.
    Do you need someone to convince you to breathe?
*   If so, this question is not to be answered.
    Make Haskell common; the question will suddenly disappear.
*   Is programming language a business? Who are the customers?
    The programmers, the managers, the users of the programs written in the language?
    New customer acquisition?
    Customer retention?
*   Is programming language a religion?
    Why do some religions proselytize and others don't?
    If you are the majority, proselytizing does not gain you much.
*   Does language affects how you think?
    If a concept is simpler in a language, will people use it more?

http://en.wikipedia.org/wiki/Socratic_questioning

#### The analytic philosopher's answer

Define that X is an _advantage_ over Y if and only if ...

Define that a language X is _better_ than a language Y if and only if ...

(TODO define the axioms to answer this question)

Define this, define that. Natural deduction says what?

#### The engineer's answer

Let's do some non-trivial stuffs in both Haskell and X and then compare the sources.

Suggestion of things:

*   tower of hanoi (really?)
*   context-free (or even somewhat context-sensitive) parsing;
    monadic parsing such as that enabled by Parsec,
    vs whatever you think best in your language;
    infix arithmetic expression parsing with precedence
*   non-trivial web service
*   non-trivial app that consumes a non-trivial web service
*   desktop application (too broad?)
*   accounting software
*   database management system
*   infrastructure management (like chef, juju, etc.)
*   non-trivial web application
*   non-trivial game
*   error handling?
    errors package (EitherT) vs whatever you have
*   operational package (or free monads?) vs Java interpreter pattern
*   logic programming? promotions in a retail store?
*   window manager? xmonad?

Compare from what angle?

*   readability
*   writability
*   maintainability
*   comprehensibility
*   correctness
*   reusability

#### The salesperson's answer

*This section is just for the lulz. Do not take this seriously.*

Whatever a salesperson says must always be taken with a grain of salt.
All that matters to salespeople is that you buy what they are selling,
and nothing else.

*   Haskell allows you to skip the stuffs that do not matter.
    Haskell frees up your attention so you can fit in your head more things that matter.
    Leave to the machine things that are boring that it is best at doing.
*   The type system helps you; it does not get in your way.
    You can code with more confidence that your code is indeed correct.
    You can write less unit tests.
*   If all you have is a hammer, everything looks like a nail.
    You don't cut a hamburger with a hammer, do you?
    If that hamburger is programming and Java is your Golden Hammer,
    then Haskell will be your knife.
*   Haskell widens your horizon. It shows you that something
    that you have never thought possible is indeed possible.
*   Do you find yourself writing your own DSL?
    Just use Haskell and get a strongly-typed DSL.
*   Haskell is full of beautiful abstractions. The beauty of such abstraction is that
    they pops up at places you did not think before,
    and when they do, they actually help solving the problem at hand.
*   Functions allow more finely grained modularity than objects do.
*   Using objects everywhere is like forcing a square peg into a round hole.
    Functional programming is a rounded rectangle peg so it fits better into a round hole.
    (Ha ha only serious.)
*   You don't want a flaky hardware.
    Why should you settle for less when it comes to software?

http://c2.com/cgi/wiki?GoldenHammer

FP is an application of mathematics to programming.

What is the benefit of mathematics?
Unambiguous. Clear.
We won't have computers otherwise.

### Is functional programming hard?

Is it because math is hard?
Is math hard?
Does programming need math?
Is programming knowledge or skill?

Does physics need math?
What would physics be without math?
How can math help (or not)?

Does designing a processor need math?

Formal systems are also a part of mathematics.

What is to blame, the subject, the teacher, or the students?
The war, the general, or the soldier?

### Does anybody even care?

Users don't care what programming language you use.
Management doesn't care either.
Why should you care?

#### The salesperson's answer

Less stress, shorter time-to-market, less cost, fewer bugs, easier maintenance.

The goal is to make programmers fungible. The parts of a great system are fungible.
A great system does not depend on the people in the system.
If you replace the people with monkeys, the system will just run as well.

#### The philosopher's answer

Is there such system?
Will this ever happen?

Do all questions deserve an answer?
