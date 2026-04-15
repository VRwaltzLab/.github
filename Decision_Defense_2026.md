# Focused Step toward addressing lag problems
Before a social haptics solution will be enjoyable, players need to be able to wrap their head around how much lag a system currently has.
In a dance context, I propose addressing this by merging the solutions:
1. VR kareoke ( where the music is lined up with the singer by buffering)
2. NINJAM (where one musician is aligned with others by buffering to the next chord loop)
This merged solution will make it so that any two paths with the same endpoints
in the reaction graph of players differs by a musically comprehendable quantity of time.
## Test Pieces
In order to test the idea of that equation, we will need to build 3 pieces:
1. A modified NINJAM Server which uses more complex equations to generate the buffer sizes.
2. An acoustic lag utility which estimates the system lag from the computer trying to play a sound to the computer hearing that same sound.
3. An digital lag utility which might already exist because of rhythm games.
## Stretch goal:
If the testing goes well, we might want to try to build a VR world where someone can perform using the server:
1. In VRChat.
2. In Overte.
3. Somewhere else.
