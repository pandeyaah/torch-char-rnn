# Torch Character-Level RNN

This repo contains code based on Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn) with applications to some homemade datasets.


### Data:
- Trump: A collection of Trump speeches and tweets

- Ruby: A bunch of ruby (programming language) source code collected together as raw text

- Rap: A collection of rap lyrics from a variety of artists cleaned and aggregated as raw text


### Usage:
See Andrej Karpathy's repo for more details, but basically to train you use `th train.lua` and to sample you use `th sample.lua cv/your_checkpoint.t7`.


### Collecting more data:
Within the `data` directory, I've included a few notebooks demonstrating how to collect more training data. Warning: much profanity included in `rap` dataset & notebooks. 

### Samples:

- Trump: primetext="crooked hill"
```
crooked hillary is not so politically correct. That's why I don't want to fight for it. 
He wants to get rid of ISIS. He loves Trump. I will tell you, I love you. I love you. I love you. 
But the Art of the Deal, I'm going to say it and I love China. I love America. And I think we're going to do very well. 
I want to just say "Nobody really can do what's right for the country because they're becoming a whole life in the arena. 
The manufacturing better in this country." But I will tell you, we have another one. I can tell you. Right? 
And then you have Senators, who is not nice people who can do this and I sai
```

- Ruby: primetext="def char_rnn"
``` 
def char_rnn
    2.times do |i|
        WIX3PROCS.write(INFO_ARGUMENT)
        chunking_to(Null)
    end
end
```

- Rap: primetext="yo let's get" (censored)
```
 yo let's get it in
 There ain't no bull**** that I am and blowin wit cha mind
 This is what I do this the thing I am, this is the day I be with the game
 Got the truth on the real man I been ready to burn it out
 I'm the biggest style on the line and I can get buck buck
 Man I gotta take my death out, and I'm a stop the change
 I see the love that I take is the sun and my slugs are back
 The streets is startin to go from the back and the track to the shy
 It's the God, I know you missed the sound of the facts
 You that assassin, ****az in the game ain't no stash in this **tch
 And then you ain't gotta take it out of here with the grand life
 I'm just tryna get my gun and the block is playin with my homies
 And I ke
```

