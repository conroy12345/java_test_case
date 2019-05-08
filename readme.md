The Java coding challenge
-------------------------

We would like you to develop a “guess a word” game, also known as Hangman game (info).
Requirements

Rules
-----

1. The application must be capable of handling multiple game sessions at the same time.
2. In the context of a single game session the player can see how many characters the word
has and can guess up to 9 times if a letter appears in the secret word.
If the letter is in the word, then the place of the character is shown to the player and the
guess count stays unchanged.
Over the span of the game the incomplete word will appear to the player.
3. At any stage the player can propose a word. Each proposal reduces the number of attempts
by one.
4. The player wins if he can find the secret word within the guess limit. Otherwise the game is
lost.
5. Where the initial word comes from is up to you.

Ideally the application will be written in Java and will be using the Spring Boot Framework to expose
REST endpoints to interact with the game engine.

Make sure that the code is production ready (leaving to the reader the interpretation of this point).

Time
----

We haven’t set a time limit for completing this challenge however we would like you not to spend
more than 2 hour in total on it, as this would be the average time that our internal developers
would spend to get the job done cleanly.

Submitting
----------
Please create a private GIT repository with your code and share with
carlo.carbone@theexchangelab.com, so we can review ahead of the final interview.
