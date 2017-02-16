## Autocomplete demo in Haskell
 - Simple project that does dictionary based word-complete via a web interface
 - Mainly an experiment to play around with Haskell

## Tech used
 - Haskell
 - [Orclev](https://github.com/orclev)'s Trie from [https://gist.github.com/orclev/1929451](https://gist.github.com/orclev/1929451)
 - Scotty
 - Aeson

## Work yet to be done
 - code definitely HAS TO BE CLEANED UP! and some more work has to be done
 - React based interface
 - Dockerify the whole thing

## Topics of Research 
 - is my way of serializing the trie completely crap that the serialized way takes way more time than just simply building the trie from ground up :'(
 - parallelizing construction of trie

## License 
 - MIT 
