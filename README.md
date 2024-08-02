# RANDALL
RANDALL: Randomizor Assistant for Narrowing Down All Ludicrous Lists

## Dependencies
- Pandas
- An Excel sheet filled with a ludicrously long list of something

## Backstory
It's the summer break, and I am bored, wanting to play games. I open Steam, I see I have purchased about 16 games; then I open Epic Games, and see I have managed to get my hands on about 70 giveaway games over the last 2 years. Analysis-paralysis strikes! So many good games, so little time, what should one do? I open YouTube, and find a video called [A Misguided Guide To Finishing Your Gaming Backlog](https://www.youtube.com/watch?v=nkgAlnDIPMU) by [DarylTalksGames](https://www.youtube.com/@DarylTalksGames). But the engineer in me is not satisfied by just cataloging and sorting the games, he needs more! Thus RANDALL.

## What Does RANDALL do?
RANDALL takes my list (`GamesBacklog.xlsx`) of video games that I've sorted for 2 criteria: 
- Is the game chill to play or not? The rationale is sometimes I'd prefer not to play a serious/mentally taxing game.
- How excited I am to start the game? (on the 4 point scale from low to peak)
- Am I playing a particular game right now? We don't want RANDALL to recommend an ongoing game, so it removes that subset of games from the list.
Then RANDALL applies a weighted randomness to the list to recommend 1 chill and 1 serious game, which I can start.

### Learnings
- A hands-on use of the [Pandas](https://pandas.pydata.org/) library
- Debugging

### Can this be applied to any other lists
Yeabsolutely! The List just has to be Ludicrously Long.

### Stuff that didn't work
I wanted to implement a "quality per unit time", which gives a greater understanding of how good a game is over its length. The rationale is to compare the quality of games of different lengths (eg. comparing **The Witcher 3** to **A Plague Tale: Innocence**.

#### Was this project necessary?
Not really, but neither is continuous learning daily. I just felt like messing around.

#### Will I ever finish my backlog?
Maybe, maybe not. Idk.


