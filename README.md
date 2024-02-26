# Battleship
🎮 Battleship is a strategy type guessing game for two players. It is played on ruled grids (paper or board) on which each player's fleet of warships are marked. The locations of the fleets are concealed from the other player. Players alternate turns calling "shots" at the other player's ships, and the objective of the game is to destroy the opposing player's fleet.

# Types of games:
1. Single Player: 
  - Computer randomly places 5 ships, player can try to guess 10 times
    
2. Advanced with computer
  - player and computer place 5 single ships, both guess
  - take turns guessing, whichever one sinks all five first wins
    
3. 5 ship types
  - 5 different ship types - 2, 3, 3, 4, 5 and play with computer
    
4. Future algorithm considerations
  - tell user when ship is sunk
  - Computer Placement 
    - Place ships in center and not edges,
    - cluster some ships, possibly in bottom right corner
  - Computer Guess 
    - Picker center, then checkerboard guess strategy
    - If hit, computer plays adjacent to ship

Legend:
  " " available to guess
  X is hit ship
  "-" is miss
