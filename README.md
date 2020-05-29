# cpp-training-project

Problem Statement:
Build a cricket game application using the C++ programming language.

Algorithm:
1. Create three classes namely Player, Team, and Game.
  Create 3 header files (.h) and the corresponding source files (.cpp) for the three
  classes.
  Declare Player class attributes to store information such as name, unique id, runs
  scored, balls played, balls bowled, runs given, and wickets taken in the match.
  Declare Team class attributes to store information such as team name, total runs
  scored by the team, total wickets lost, total balls bowled, and list of team players.
  Declare Game class attributes to store information such as team A and team B
  details, players per team, maximum deliveries allowed in each innings, names of
  all the 11 given players, and a variable to check which innings is going on.
   Additionally, in the Game class, declare two pointers of type class Team to point
  to the batting team and bowling team in each innings and two pointers of type
  class Player to point to the current batsman and the bowler.
2. Welcome users and show a few basic game instructions.
3. Display all the 11 players with the array index so that the user can select the players
  using that index for each team.
4. Select 4 players for each team one by one in an alternative way.
  Write a utility function to take only integer user input.
  Write a validation function to allow a player to be added to a team only once.
5. Display selected players from each team.
6. Add toss functionality.
  Allow the toss winning team to choose either to bat or bowl first.
  Initialize the batting team and the bowling team.
7. Start the first innings.
  Initialize the batsman and the bowler.
8. Start playing the first innings.
  After each delivery, update batsman score, bowler score, and both teams score.
  If in a delivery runs scored is 0 then the batsman will be OUT and the next player
  in sequence from the batting team will start batting.
  If in a delivery runs scored is 1 to 6, just update data and continue the innings.
  After each delivery, validate the innings score to check if the innings is over.
9. After each delivery, show the game scorecard.
10. When the first innings ends, start the second innings.
  Initialize the batting team and the bowling team.
  Initialize the batsman and the bowler.
11. Start playing the second innings.
  Reuse the same code written to play first innings.
  After each delivery, validate both innings’ scores to decide the winner.
12. Display match summary in the end.
