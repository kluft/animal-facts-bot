## How to contribute (Teach AnimalFactsBot a new animal):

        Due to Hacktoberfests pull requests are coming in fast! Comment on an issue you are going to work on - and also check open pull requests before you do work someone else has already done.

Steps:
* Fork/clone the repo
* Add a tuple of strings of facts (to animalfacts.py) pertaining to a particular animal. Name the tuple variable following the format 'NAMEOFANIMAL_FACTS'. Put the tuple in alphabetical order with the other tuples.
* Add your tuple to the ALL_FACTS tuple.
* Add a line to the check_comment_for_animal() function for your animal following the format.
* Add your animal to the Readme
* Add me on Twitter @joelatwar

Please:
* Don't add a very small set of facts (this will cause the bot to be repetetive regarding your animal).
* Each fact must make sense independent of the other facts in the tuple because users will only get one fact at a time.
* Only add TRUE facts. Please no trolling with 'alternative facts'.
* Don't add 'seal', 'bat' or 'duck' facts unless you've figured out how to not reply to homonyms.
* Don't add 'cat' or 'dog' because they are just too common on reddit.

Please: Don't add a very small set of facts (this will cause the bot to be repetetive regarding your animal).
        Each fact must make sense independent of the other facts in the tuple because users will only get one fact at a time.
        Only add TRUE facts. Please no trolling with 'alternative facts'.
        Don't add 'seal', 'bat' or 'duck' facts unless you've figured out how to not reply to homonyms.
        Don't add 'cat' or 'dog' because they are just too common on reddit.

If you have a question the quickest way to reach is me on twitter @joelatwar


# animal-facts-bot

A Reddit bot that searches for comments on reddit that contain the name of the animal and then replies to the comment with a fact about that animal.

You can see the bot in action at https://www.reddit.com/user/AnimalFactsBot/comments/

### Current supported animals:
* albatross
* alligator
* ant
* badger
* beaver
* camel
* chameleon
* cheetah
* cow
* crab
* crocodile
* cuttlefish
* dolphin
* dragon
* eagle
* echidna
* elephant
* emu
* falcon
* flamingo
* fox
* frog
* giraffe
* grasshopper
* goat
* goose
* gopher
* gorilla
* hamster
* hedgehog
* hippo
* honeybee
* horse
* hummingbird
* husky
* jellyfish
* kangaroo
* koala
* lion
* leopard
* lizard
* llama
* meerkat
* monkey
* narwhal
* newt
* ocelot
* octopus
* orca
* otter
* owl
* panda
* pangolin
* panther
* peacock
* parrot
* penguin
* pig
* pigeon
* platypus
* scorpion
* seagull
* sea cucumber
* shark
* skunk
* sloth
* snail
* snake
* squirrel
* stingray
* tiger
* turtle
* walrus
* wolf
* whale
* wolf
* zebra

### AnimalFactsBot will reply to its replies if they contain the phrases:
* good bot
* bad bot
* thank
* more
* silly
* TIL
* AnimalFactsBot

AnimalFactsBot gets these fairly often.
