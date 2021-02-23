# Viridithas-Chess

A Python chess engine using opening books, principal variation mull-window search, the python-chess library, and a transposition table for tracking repeated positions across searches. 

The main engine is found within Viridithas.py.

Modes for Antichess, Atomic, and Crazyhouse are implemented via subclasses of the main engine, but Crazyhouse currently possesses suboptimal evaluation.
