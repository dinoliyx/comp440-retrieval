# COMP 440: Representing and Retrieving Knowledge

Claude writes your answers here as you say them. A sentence or two is enough for each. Your
Part 0 predictions stay as you first wrote them; Part 5 asks what you would change.

**Name:** Dino
**Date:** October 20, 2026

## Part 0: Predictions

### Questions that name a character, place or thing: which method will do better, and why?

TF-IDF should do better for these questions because normally the names of character or place are unique so I would think keyword search can easily spot the words since it weigh this kind of uniqueness for words.

### Vague descriptions: which method will do better, and why?

Embedding search because it compares the question with overviews and ranks them. I think in this way it understand the context better than TF-IDF

## Part 1: Build the TF-IDF model

### The settings you chose, and why

- `REMOVE_STOP_WORDS = True`: because common words can dillute the information density from the questions.
- `MIN_MOVIES = 3`: because I think the strongest words that representes the movies accuratly.
- `REPEATS_COUNT_LESS = True`: because it still captures the words weight but it won't makes too much of difference between words.

## Part 2: Top terms

### Your movies: what do the top terms get right and wrong about what makes each one distinctive?

For Sing, I think it does a good job listing the words singing, theater, and hosting but I'm surprised that animal is not on the top of the list because I think that would makes it distinctive. For Kill Bill: Vol. 1, it gets right with the general plot of the movie but I expected to see Bill there too, and that's what would've made it distinctive.

## Part 3: Your own searches

### Your questions, as you typed them

1. The movie that's like  a group of car fighting against another a group of cars, they are all aliens.
2. They are huge robots that can convert to cars and vice vera
3. A lot of specail effects and visual appealling

### Did the movies you meant come up? What did TF-IDF get right and wrong?

NO it doesn't appear

## Part 4: The question bank

### Which kind of question did TF-IDF handle best, and which worst? By how much?

XXXX

### The misses you looked at: what do they have in common?

XXXX

## Part 5: Embeddings

### What is a sentence embedding, in your own words?

XXXX

### Where does each method do better, and why?

XXXX

### Your Part 0 predictions: which held, and which would you change?

XXXX

### How might you combine the two methods?

XXXX
