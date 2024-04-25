# t3a2-a-full-stack-app-part-a

Ideas for web app:
### 1st idea: Website to play pazzak (stretch - sabacc) games from star wars
- include login/registration of user
- win/loss record
- chat function with other players
- forum posting
- user settings
- create player deck for use in game (side deck)
    - Side deck is made up of 10 cards exactly
    - Can have multiple copies of the same card

- how to play guide embedded
- (stretch - embedded streaming?)
- Friend list
- Buy cards? (loot box?) (fake currency from gameplay only)
- Actual game?
    - Play against Human or AI
    - create main deck (numbers 1-10 x4 randomised)
    - draw 4 random cards from player side deck
    - Each player draws card from main deck - highest goes first (these cards are discarded)
    - Draw card from main deck face up
        - Pass
        - Add 1 side card
        - Stand
    - Action then passes to player 2
    - Play continues until both players stand or 1 goes bust (exceeds 20)
    - How to win:
        - On reaching exactly 20 player will automatically stand
        - On filling the table (all 9 card spots) filled without a bust
        - The highest score if both players stand
        - The player who used the tiebreaker card and both players have the same value and stood
        - Have not exceeded 20 while the other player has exceeded 20 and bust
        - ELSE: a Tie occurs and no winner for this round
    - 3 wins are required to win a match (stretch, create a setting to allow best of, or increase number or rounds required)