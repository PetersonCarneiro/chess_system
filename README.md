# Chess System
# First class: Position
Checklist:
  - Class Position [public]
  - OOP Topics:
  - Encapsulation
  - Constructors
  - ToString (Object / overriding)

#  Starting to implement Board and Piece
Checklist:
  - Classes Piece, Board [public]
  - OOP Topics:
  - Associations
  - Encapsulation / Access Modifiers
  - Data Structures Topics:
  - Matrix
  - 
# Chess layer and printing the board

Checklist: 

  - Methods: Board.Piece(row, column) and Board.Piece(position)
  - Enum Chess.Color
  - Class Chess.ChessPiece [public]
  - Class Chess.ChessMatch [public]
  - Class ChessConsole.UI
  - OOP Topics:
  - Enumerations
  - Encapsulation / Access Modifiers
  - Inheritance
  - Downcasting
  - Static members
  - Layers pattern
  - Data Structures Topics:
  - Matrix

# Placing pieces on the board

 Checklist:

  - Method: Board.PlacePiece(piece, position)
  - Classes: Rook, King [public]
  - Method: ChessMatch.InitialSetup
  - OOP Topics:
  - Inheritance
  - Overriding
  - Polymorphism (ToString)
  - 
# BoardException and defensive programming

Checklist:

  - Class BoardException [public]
  - Methods: Board.PositionExists, Board.ThereIsAPiece
  - Implement defensive programming in Board methods
  - OOP Topics:
  - Exceptions
  - o Constructors (a string must be informed to the exception)