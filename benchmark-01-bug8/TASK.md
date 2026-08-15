# Mantella action/dialogue consistency

Mantella NPC dialogue can verbally claim or strongly imply that an NPC has
begun following the player even when the required Follow action command was
never emitted and/or successfully executed. For example, after the player
asks an NPC to come along, the NPC may respond with language such as “I’m with
you” or “Lead on,” while Skyrim never actually enters follower state because
no valid Follow action occurred.

Investigate the defect, identify its root cause, implement a robust fix, add
appropriate regression/unit tests, and run the relevant test suite. Avoid
regressions to other Mantella actions.

Do not assume the affected parser, prompt, action, or conversation component;
trace the production path and preserve unrelated behavior.
