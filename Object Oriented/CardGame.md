# Card Game

Your goal is to develop an algorithm capable of returning a randomized hand from a 52 card deck. The following calls to the same method should return a different set of cards, up to the point where the 52 cards have been taken (so the last hand drawn from the deck might not have the correct amount of cards).

For example (the result's display is simplified): 
```csharp
Deck deck = new Deck();
IEnumerable<Card> hand = deck.GetHand(3);
hand == ["2 of spades", "5 of diamonds", "King of hearts"];
```
You will have to take multiple steps:
* Initialize the deck with every card that can be in it
* Select a given amount randomly (you can use [RNGCryptoServiceProvider](https://msdn.microsoft.com/en-us/library/system.security.cryptography.rngcryptoserviceprovider(v=vs.110).aspx) to get better random numbers)
* Don't forget to remove them from the deck, so that the next draws are realistic.