# battleships
Programming

- BattleShips
  - Board
    - size
      - has a set size
      - colabs with maybe ships?
    - state_of_game
      - show ships and shots
      - colabs with ships and player
  - Ship
    - place
      - put ship on board where player chooses
      - colabs with board and player
    - location
      - set where on board the ship is
      - colabs with board
    - size
      - each ships can be of a set size
      - colabs with board
    - damage
      - records number of times a ship has been shot.
      - size == damage means ship is dead
      - colabs with ship and shot
  - Player
    - number_of_ships_per_size
      - number of ships to place at setup
      - colab with ships
    - place
      - player can choose location and direction of ships
      - colabs with ships and board
    - view_board
      - visually displays the state of the board
      - colabs with board.state
    - shoot
      - choose a square to shoot at and damage any ships there
      - colabs with board and ships if hit
