# Observed behavior

In a conversation, a player can explicitly ask an NPC to come along. The NPC
may answer as if following has started, while the game does not enter follower
state because no valid Follow action was emitted or completed.

The benchmark asks the developer to reproduce this mismatch, determine why
spoken state and game state diverge, and correct it without breaking valid
actions or ordinary dialogue.
