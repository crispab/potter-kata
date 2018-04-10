# Harry Potter-Kata

## Problem Description

Once upon a time there was a series of 5 books about a very English hero called Harry. (At least when this Kata was invented, there were only 5. Since then they have multiplied) Children all over the world thought he was fantastic, and, of course, so did the publisher. So in a gesture of immense generosity to mankind, (and to increase sales) they set up the following pricing model to take advantage of Harry’s magical powers.

One copy of any of the five books costs 8 EUR. If, however, you buy two different books from the series, you get a 5% discount on those two books. If you buy 3 different books, you get a 10% discount. With 4 different books, you get a 20% discount. If you go the whole hog, and buy all 5, you get a huge 25% discount.

Note that if you buy, say, four books, of which 3 are different titles, you get a 10% discount on the 3 that form part of a set, but the fourth book still costs 8 EUR.

Potter mania is sweeping the country and parents of teenagers everywhere are queueing up with shopping baskets overflowing with Potter books. Your mission is to write a piece of code to calculate the price of any conceivable shopping basket, giving as big a discount as possible.

For example, how much does this basket of books cost?

- 2 copies of _The Philosopher's Stone_ 
- 2 copies of _The Chamber of Secrets_
- 2 copies of _The Prisoner of Azkaban_
- 1 copy of _The Goblet of Fire_ 
- 1 copy of _The Order of the Phoenix_

The following table lists a few key examples:

|  I  |  II  | III |  IV  |  V  |  Price  |
|-----|------|-----|------|-----|---------|
|  1  |      |     |      |     |  8.00   |
|  1  |  1   |     |      |     |  15.20  |
|  1  |  1   |  1  |  1   |  1  |  30.00  |
|  2  |      |     |      |     |  16.00  |
|  2  |  1   |     |      |     |  23.20  |
|  2  |  1   |  1  |      |     |  29.60  |
|  2  |  2   |  2  |  1   |  1  |  51.20  |
|  5  |  5   |  4  |  5   |  4  |  141.20 |
