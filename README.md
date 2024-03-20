Kaothar Reda 

**Event Flow Graph (EFG) for Calculator App:**

Nodes:
N1: Open App
N2: Enter first number
N3: Press '+' button
N4: Enter second number
N5: Press '=' button
N6: Display result

Edges:
E1: N1 -> N2
E2: N2 -> N3
E3: N3 -> N4
E4: N4 -> N5
E5: N5 -> N6

Edge-Pairs:
EP1: E1 -> E2
EP2: E2 -> E3
EP3: E3 -> E4
EP4: E4 -> E5

Test Paths for Node Coverage:
- TP1: N1 -> N2 -> N3 -> N4 -> N5 -> N6

Test Paths for Edge Coverage:
- TP2: E1 -> E2
- TP3: E2 -> E3
- TP4: E3 -> E4
- TP5: E4 -> E5
... (one for each edge) ...

Test Paths for Edge-Pair Coverage:
- TP6: EP1 -> EP2
- TP7: EP2 -> EP3
- TP8: EP3 -> EP4
... (one for each edge-pair) ...

**Event Flow Graph (EFG) for Runnerup App:**

Nodes:
N1: Running Mode
N2: Biking Mode
N3: Other Mode
N4: Orienteering Mode
N5: Walking Mode
N6: Audio cue settings 
N7: Manage audio cues




