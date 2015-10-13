# cryptobot
Not an IRC bot, but rather a library for the creation of cryptographically secure enigmatic IRC bots.

# Dependencies
Python 2, pycrypto, SimpleAES

# Usage
Run cryptobot.py to create a codes database.

Import cryptobot.py (and the pickle module) into another module to use the file with an IRC bot.

# Using your codes database

Import it as a variable using pickle.

You will have a list of custom objects.

Each object represents one input phrase (and potential response). Use the functions of each object isTriggered(message) to see if the encoded message matches the input one, and decrypt(message) to get the matching output phrase.
