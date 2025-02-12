# koi-koi-esc
Test program for the EctaraScript interpreter implementing the card game Koi-Koi (https://en.wikipedia.org/wiki/Koi-Koi)

This is a text-only implementation of the Japanese card game Koi-Koi, which is played with a hanafuda deck. Only hard koi-koi rules are implemented, and a small amount of variations are implemented, mostly those featured in the Yakuza (Like a Dragon) franchise. A bot player implementation is provided, which will take various factors into account to attack when advantageous and defend to impede your progress, but isn't currently designed to trick the player. Notably, the bot doesn't cheat, and can be beaten by skilled players. The game can be configured to have one or both players be human- or computer-controlled, mostly for testing purposes; humans would see each other's hands, but it is entertaining to see bots face off.

It's not the prettiest implementation, and neither is the current grammar for EctaraScript, but it serves as a proof-of-concept.
