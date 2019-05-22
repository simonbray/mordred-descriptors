# mordred-descriptors

This is a list of all descriptors calculated by [Mordred](https://github.com/mordred-descriptor/mordred). The original source is found [here](https://static-content.springer.com/esm/art%3A10.1186%2Fs13321-018-0258-y/MediaObjects/13321_2018_258_MOESM3_ESM.xlsx).

## Citation
Moriwaki H, Tian Y-S, Kawashita N, Takagi T (2018) Mordred: a molecular descriptor calculator. Journal of Cheminformatics 10:4 . doi: [10.1186/s13321-018-0258-y](https://doi.org/10.1186/s13321-018-0258-y)

## List of descriptors

index | module | name | constructor | dimention | description
--- | --- | --- | --- | --- | ---
1 | ABCIndex | ABC | ABCIndex() | 2D | atom-bond connectivity index
2 |  | ABCGG | ABCGGIndex() | 2D | Graovac-Ghorbani atom-bond connectivity index
3 | AcidBase | nAcid | AcidicGroupCount() | 2D | acidic group count
4 |  | nBase | BasicGroupCount() | 2D | basic group count
5 | AdjacencyMatrix | SpAbs_A | AdjacencyMatrix('SpAbs') | 2D | SpAbs of adjacency matrix
6 |  | SpMax_A | AdjacencyMatrix('SpMax') | 2D | SpMax of adjacency matrix
7 |  | SpDiam_A | AdjacencyMatrix('SpDiam') | 2D | SpDiam of adjacency matrix
8 |  | SpAD_A | AdjacencyMatrix('SpAD') | 2D | SpAD of adjacency matrix
9 |  | SpMAD_A | AdjacencyMatrix('SpMAD') | 2D | SpMAD of adjacency matrix
10 |  | LogEE_A | AdjacencyMatrix('LogEE') | 2D | LogEE of adjacency matrix
11 |  | SM1_A | AdjacencyMatrix('SM1') | 2D | SM1 of adjacency matrix
12 |  | VE1_A | AdjacencyMatrix('VE1') | 2D | VE1 of adjacency matrix
13 |  | VE2_A | AdjacencyMatrix('VE2') | 2D | VE2 of adjacency matrix
14 |  | VE3_A | AdjacencyMatrix('VE3') | 2D | VE3 of adjacency matrix
15 |  | VR1_A | AdjacencyMatrix('VR1') | 2D | VR1 of adjacency matrix
16 |  | VR2_A | AdjacencyMatrix('VR2') | 2D | VR2 of adjacency matrix
17 |  | VR3_A | AdjacencyMatrix('VR3') | 2D | VR3 of adjacency matrix
18 | Aromatic | nAromAtom | AromaticAtomsCount() | 2D | aromatic atoms count
19 |  | nAromBond | AromaticBondsCount() | 2D | aromatic bonds count
20 | AtomCount | nAtom | AtomCount('Atom') | 2D | number of all atoms
21 |  | nHeavyAtom | AtomCount('HeavyAtom') | 2D | number of heavy atoms
22 |  | nSpiro | AtomCount('Spiro') | 2D | number of spiro atoms
23 |  | nBridgehead | AtomCount('Bridgehead') | 2D | number of bridgehead atoms
24 |  | nH | AtomCount('H') | 2D | number of H atoms
25 |  | nB | AtomCount('B') | 2D | number of B atoms
26 |  | nC | AtomCount('C') | 2D | number of C atoms
27 |  | nN | AtomCount('N') | 2D | number of N atoms
28 |  | nO | AtomCount('O') | 2D | number of O atoms
29 |  | nS | AtomCount('S') | 2D | number of S atoms
30 |  | nP | AtomCount('P') | 2D | number of P atoms
31 |  | nF | AtomCount('F') | 2D | number of F atoms
32 |  | nCl | AtomCount('Cl') | 2D | number of Cl atoms
33 |  | nBr | AtomCount('Br') | 2D | number of Br atoms
34 |  | nI | AtomCount('I') | 2D | number of I atoms
35 |  | nX | AtomCount('X') | 2D | number of halogen atoms
36 | Autocorrelation | ATS0dv | ATS(0, 'dv') | 2D | moreau-broto autocorrelation of lag 0 weighted by valence electrons
37 |  | ATS1dv | ATS(1, 'dv') | 2D | moreau-broto autocorrelation of lag 1 weighted by valence electrons
38 |  | ATS2dv | ATS(2, 'dv') | 2D | moreau-broto autocorrelation of lag 2 weighted by valence electrons
39 |  | ATS3dv | ATS(3, 'dv') | 2D | moreau-broto autocorrelation of lag 3 weighted by valence electrons
40 |  | ATS4dv | ATS(4, 'dv') | 2D | moreau-broto autocorrelation of lag 4 weighted by valence electrons
41 |  | ATS5dv | ATS(5, 'dv') | 2D | moreau-broto autocorrelation of lag 5 weighted by valence electrons
42 |  | ATS6dv | ATS(6, 'dv') | 2D | moreau-broto autocorrelation of lag 6 weighted by valence electrons
43 |  | ATS7dv | ATS(7, 'dv') | 2D | moreau-broto autocorrelation of lag 7 weighted by valence electrons
44 |  | ATS8dv | ATS(8, 'dv') | 2D | moreau-broto autocorrelation of lag 8 weighted by valence electrons
45 |  | ATS0d | ATS(0, 'd') | 2D | moreau-broto autocorrelation of lag 0 weighted by sigma electrons
46 |  | ATS1d | ATS(1, 'd') | 2D | moreau-broto autocorrelation of lag 1 weighted by sigma electrons
47 |  | ATS2d | ATS(2, 'd') | 2D | moreau-broto autocorrelation of lag 2 weighted by sigma electrons
48 |  | ATS3d | ATS(3, 'd') | 2D | moreau-broto autocorrelation of lag 3 weighted by sigma electrons
49 |  | ATS4d | ATS(4, 'd') | 2D | moreau-broto autocorrelation of lag 4 weighted by sigma electrons
50 |  | ATS5d | ATS(5, 'd') | 2D | moreau-broto autocorrelation of lag 5 weighted by sigma electrons
51 |  | ATS6d | ATS(6, 'd') | 2D | moreau-broto autocorrelation of lag 6 weighted by sigma electrons
52 |  | ATS7d | ATS(7, 'd') | 2D | moreau-broto autocorrelation of lag 7 weighted by sigma electrons
53 |  | ATS8d | ATS(8, 'd') | 2D | moreau-broto autocorrelation of lag 8 weighted by sigma electrons
54 |  | ATS0s | ATS(0, 's') | 2D | moreau-broto autocorrelation of lag 0 weighted by intrinsic state
55 |  | ATS1s | ATS(1, 's') | 2D | moreau-broto autocorrelation of lag 1 weighted by intrinsic state
56 |  | ATS2s | ATS(2, 's') | 2D | moreau-broto autocorrelation of lag 2 weighted by intrinsic state
57 |  | ATS3s | ATS(3, 's') | 2D | moreau-broto autocorrelation of lag 3 weighted by intrinsic state
58 |  | ATS4s | ATS(4, 's') | 2D | moreau-broto autocorrelation of lag 4 weighted by intrinsic state
59 |  | ATS5s | ATS(5, 's') | 2D | moreau-broto autocorrelation of lag 5 weighted by intrinsic state
60 |  | ATS6s | ATS(6, 's') | 2D | moreau-broto autocorrelation of lag 6 weighted by intrinsic state
61 |  | ATS7s | ATS(7, 's') | 2D | moreau-broto autocorrelation of lag 7 weighted by intrinsic state
62 |  | ATS8s | ATS(8, 's') | 2D | moreau-broto autocorrelation of lag 8 weighted by intrinsic state
63 |  | ATS0Z | ATS(0, 'Z') | 2D | moreau-broto autocorrelation of lag 0 weighted by atomic number
64 |  | ATS1Z | ATS(1, 'Z') | 2D | moreau-broto autocorrelation of lag 1 weighted by atomic number
65 |  | ATS2Z | ATS(2, 'Z') | 2D | moreau-broto autocorrelation of lag 2 weighted by atomic number
66 |  | ATS3Z | ATS(3, 'Z') | 2D | moreau-broto autocorrelation of lag 3 weighted by atomic number
67 |  | ATS4Z | ATS(4, 'Z') | 2D | moreau-broto autocorrelation of lag 4 weighted by atomic number
68 |  | ATS5Z | ATS(5, 'Z') | 2D | moreau-broto autocorrelation of lag 5 weighted by atomic number
69 |  | ATS6Z | ATS(6, 'Z') | 2D | moreau-broto autocorrelation of lag 6 weighted by atomic number
70 |  | ATS7Z | ATS(7, 'Z') | 2D | moreau-broto autocorrelation of lag 7 weighted by atomic number
71 |  | ATS8Z | ATS(8, 'Z') | 2D | moreau-broto autocorrelation of lag 8 weighted by atomic number
72 |  | ATS0m | ATS(0, 'm') | 2D | moreau-broto autocorrelation of lag 0 weighted by mass
73 |  | ATS1m | ATS(1, 'm') | 2D | moreau-broto autocorrelation of lag 1 weighted by mass
74 |  | ATS2m | ATS(2, 'm') | 2D | moreau-broto autocorrelation of lag 2 weighted by mass
75 |  | ATS3m | ATS(3, 'm') | 2D | moreau-broto autocorrelation of lag 3 weighted by mass
76 |  | ATS4m | ATS(4, 'm') | 2D | moreau-broto autocorrelation of lag 4 weighted by mass
77 |  | ATS5m | ATS(5, 'm') | 2D | moreau-broto autocorrelation of lag 5 weighted by mass
78 |  | ATS6m | ATS(6, 'm') | 2D | moreau-broto autocorrelation of lag 6 weighted by mass
79 |  | ATS7m | ATS(7, 'm') | 2D | moreau-broto autocorrelation of lag 7 weighted by mass
80 |  | ATS8m | ATS(8, 'm') | 2D | moreau-broto autocorrelation of lag 8 weighted by mass
81 |  | ATS0v | ATS(0, 'v') | 2D | moreau-broto autocorrelation of lag 0 weighted by vdw volume
82 |  | ATS1v | ATS(1, 'v') | 2D | moreau-broto autocorrelation of lag 1 weighted by vdw volume
83 |  | ATS2v | ATS(2, 'v') | 2D | moreau-broto autocorrelation of lag 2 weighted by vdw volume
84 |  | ATS3v | ATS(3, 'v') | 2D | moreau-broto autocorrelation of lag 3 weighted by vdw volume
85 |  | ATS4v | ATS(4, 'v') | 2D | moreau-broto autocorrelation of lag 4 weighted by vdw volume
86 |  | ATS5v | ATS(5, 'v') | 2D | moreau-broto autocorrelation of lag 5 weighted by vdw volume
87 |  | ATS6v | ATS(6, 'v') | 2D | moreau-broto autocorrelation of lag 6 weighted by vdw volume
88 |  | ATS7v | ATS(7, 'v') | 2D | moreau-broto autocorrelation of lag 7 weighted by vdw volume
89 |  | ATS8v | ATS(8, 'v') | 2D | moreau-broto autocorrelation of lag 8 weighted by vdw volume
90 |  | ATS0se | ATS(0, 'se') | 2D | moreau-broto autocorrelation of lag 0 weighted by sanderson EN
91 |  | ATS1se | ATS(1, 'se') | 2D | moreau-broto autocorrelation of lag 1 weighted by sanderson EN
92 |  | ATS2se | ATS(2, 'se') | 2D | moreau-broto autocorrelation of lag 2 weighted by sanderson EN
93 |  | ATS3se | ATS(3, 'se') | 2D | moreau-broto autocorrelation of lag 3 weighted by sanderson EN
94 |  | ATS4se | ATS(4, 'se') | 2D | moreau-broto autocorrelation of lag 4 weighted by sanderson EN
95 |  | ATS5se | ATS(5, 'se') | 2D | moreau-broto autocorrelation of lag 5 weighted by sanderson EN
96 |  | ATS6se | ATS(6, 'se') | 2D | moreau-broto autocorrelation of lag 6 weighted by sanderson EN
97 |  | ATS7se | ATS(7, 'se') | 2D | moreau-broto autocorrelation of lag 7 weighted by sanderson EN
98 |  | ATS8se | ATS(8, 'se') | 2D | moreau-broto autocorrelation of lag 8 weighted by sanderson EN
99 |  | ATS0pe | ATS(0, 'pe') | 2D | moreau-broto autocorrelation of lag 0 weighted by pauling EN
100 |  | ATS1pe | ATS(1, 'pe') | 2D | moreau-broto autocorrelation of lag 1 weighted by pauling EN
101 |  | ATS2pe | ATS(2, 'pe') | 2D | moreau-broto autocorrelation of lag 2 weighted by pauling EN
102 |  | ATS3pe | ATS(3, 'pe') | 2D | moreau-broto autocorrelation of lag 3 weighted by pauling EN
103 |  | ATS4pe | ATS(4, 'pe') | 2D | moreau-broto autocorrelation of lag 4 weighted by pauling EN
104 |  | ATS5pe | ATS(5, 'pe') | 2D | moreau-broto autocorrelation of lag 5 weighted by pauling EN
105 |  | ATS6pe | ATS(6, 'pe') | 2D | moreau-broto autocorrelation of lag 6 weighted by pauling EN
106 |  | ATS7pe | ATS(7, 'pe') | 2D | moreau-broto autocorrelation of lag 7 weighted by pauling EN
107 |  | ATS8pe | ATS(8, 'pe') | 2D | moreau-broto autocorrelation of lag 8 weighted by pauling EN
108 |  | ATS0are | ATS(0, 'are') | 2D | moreau-broto autocorrelation of lag 0 weighted by allred-rocow EN
109 |  | ATS1are | ATS(1, 'are') | 2D | moreau-broto autocorrelation of lag 1 weighted by allred-rocow EN
110 |  | ATS2are | ATS(2, 'are') | 2D | moreau-broto autocorrelation of lag 2 weighted by allred-rocow EN
111 |  | ATS3are | ATS(3, 'are') | 2D | moreau-broto autocorrelation of lag 3 weighted by allred-rocow EN
112 |  | ATS4are | ATS(4, 'are') | 2D | moreau-broto autocorrelation of lag 4 weighted by allred-rocow EN
113 |  | ATS5are | ATS(5, 'are') | 2D | moreau-broto autocorrelation of lag 5 weighted by allred-rocow EN
114 |  | ATS6are | ATS(6, 'are') | 2D | moreau-broto autocorrelation of lag 6 weighted by allred-rocow EN
115 |  | ATS7are | ATS(7, 'are') | 2D | moreau-broto autocorrelation of lag 7 weighted by allred-rocow EN
116 |  | ATS8are | ATS(8, 'are') | 2D | moreau-broto autocorrelation of lag 8 weighted by allred-rocow EN
117 |  | ATS0p | ATS(0, 'p') | 2D | moreau-broto autocorrelation of lag 0 weighted by polarizability
118 |  | ATS1p | ATS(1, 'p') | 2D | moreau-broto autocorrelation of lag 1 weighted by polarizability
119 |  | ATS2p | ATS(2, 'p') | 2D | moreau-broto autocorrelation of lag 2 weighted by polarizability
120 |  | ATS3p | ATS(3, 'p') | 2D | moreau-broto autocorrelation of lag 3 weighted by polarizability
121 |  | ATS4p | ATS(4, 'p') | 2D | moreau-broto autocorrelation of lag 4 weighted by polarizability
122 |  | ATS5p | ATS(5, 'p') | 2D | moreau-broto autocorrelation of lag 5 weighted by polarizability
123 |  | ATS6p | ATS(6, 'p') | 2D | moreau-broto autocorrelation of lag 6 weighted by polarizability
124 |  | ATS7p | ATS(7, 'p') | 2D | moreau-broto autocorrelation of lag 7 weighted by polarizability
125 |  | ATS8p | ATS(8, 'p') | 2D | moreau-broto autocorrelation of lag 8 weighted by polarizability
126 |  | ATS0i | ATS(0, 'i') | 2D | moreau-broto autocorrelation of lag 0 weighted by ionization potential
127 |  | ATS1i | ATS(1, 'i') | 2D | moreau-broto autocorrelation of lag 1 weighted by ionization potential
128 |  | ATS2i | ATS(2, 'i') | 2D | moreau-broto autocorrelation of lag 2 weighted by ionization potential
129 |  | ATS3i | ATS(3, 'i') | 2D | moreau-broto autocorrelation of lag 3 weighted by ionization potential
130 |  | ATS4i | ATS(4, 'i') | 2D | moreau-broto autocorrelation of lag 4 weighted by ionization potential
131 |  | ATS5i | ATS(5, 'i') | 2D | moreau-broto autocorrelation of lag 5 weighted by ionization potential
132 |  | ATS6i | ATS(6, 'i') | 2D | moreau-broto autocorrelation of lag 6 weighted by ionization potential
133 |  | ATS7i | ATS(7, 'i') | 2D | moreau-broto autocorrelation of lag 7 weighted by ionization potential
134 |  | ATS8i | ATS(8, 'i') | 2D | moreau-broto autocorrelation of lag 8 weighted by ionization potential
135 |  | AATS0dv | AATS(0, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by valence electrons
136 |  | AATS1dv | AATS(1, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by valence electrons
137 |  | AATS2dv | AATS(2, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by valence electrons
138 |  | AATS3dv | AATS(3, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by valence electrons
139 |  | AATS4dv | AATS(4, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by valence electrons
140 |  | AATS5dv | AATS(5, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by valence electrons
141 |  | AATS6dv | AATS(6, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by valence electrons
142 |  | AATS7dv | AATS(7, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by valence electrons
143 |  | AATS8dv | AATS(8, 'dv') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by valence electrons
144 |  | AATS0d | AATS(0, 'd') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by sigma electrons
145 |  | AATS1d | AATS(1, 'd') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by sigma electrons
146 |  | AATS2d | AATS(2, 'd') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by sigma electrons
147 |  | AATS3d | AATS(3, 'd') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by sigma electrons
148 |  | AATS4d | AATS(4, 'd') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by sigma electrons
149 |  | AATS5d | AATS(5, 'd') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by sigma electrons
150 |  | AATS6d | AATS(6, 'd') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by sigma electrons
151 |  | AATS7d | AATS(7, 'd') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by sigma electrons
152 |  | AATS8d | AATS(8, 'd') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by sigma electrons
153 |  | AATS0s | AATS(0, 's') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by intrinsic state
154 |  | AATS1s | AATS(1, 's') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by intrinsic state
155 |  | AATS2s | AATS(2, 's') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by intrinsic state
156 |  | AATS3s | AATS(3, 's') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by intrinsic state
157 |  | AATS4s | AATS(4, 's') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by intrinsic state
158 |  | AATS5s | AATS(5, 's') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by intrinsic state
159 |  | AATS6s | AATS(6, 's') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by intrinsic state
160 |  | AATS7s | AATS(7, 's') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by intrinsic state
161 |  | AATS8s | AATS(8, 's') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by intrinsic state
162 |  | AATS0Z | AATS(0, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by atomic number
163 |  | AATS1Z | AATS(1, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by atomic number
164 |  | AATS2Z | AATS(2, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by atomic number
165 |  | AATS3Z | AATS(3, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by atomic number
166 |  | AATS4Z | AATS(4, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by atomic number
167 |  | AATS5Z | AATS(5, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by atomic number
168 |  | AATS6Z | AATS(6, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by atomic number
169 |  | AATS7Z | AATS(7, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by atomic number
170 |  | AATS8Z | AATS(8, 'Z') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by atomic number
171 |  | AATS0m | AATS(0, 'm') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by mass
172 |  | AATS1m | AATS(1, 'm') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by mass
173 |  | AATS2m | AATS(2, 'm') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by mass
174 |  | AATS3m | AATS(3, 'm') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by mass
175 |  | AATS4m | AATS(4, 'm') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by mass
176 |  | AATS5m | AATS(5, 'm') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by mass
177 |  | AATS6m | AATS(6, 'm') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by mass
178 |  | AATS7m | AATS(7, 'm') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by mass
179 |  | AATS8m | AATS(8, 'm') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by mass
180 |  | AATS0v | AATS(0, 'v') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by vdw volume
181 |  | AATS1v | AATS(1, 'v') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by vdw volume
182 |  | AATS2v | AATS(2, 'v') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by vdw volume
183 |  | AATS3v | AATS(3, 'v') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by vdw volume
184 |  | AATS4v | AATS(4, 'v') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by vdw volume
185 |  | AATS5v | AATS(5, 'v') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by vdw volume
186 |  | AATS6v | AATS(6, 'v') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by vdw volume
187 |  | AATS7v | AATS(7, 'v') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by vdw volume
188 |  | AATS8v | AATS(8, 'v') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by vdw volume
189 |  | AATS0se | AATS(0, 'se') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by sanderson EN
190 |  | AATS1se | AATS(1, 'se') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by sanderson EN
191 |  | AATS2se | AATS(2, 'se') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by sanderson EN
192 |  | AATS3se | AATS(3, 'se') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by sanderson EN
193 |  | AATS4se | AATS(4, 'se') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by sanderson EN
194 |  | AATS5se | AATS(5, 'se') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by sanderson EN
195 |  | AATS6se | AATS(6, 'se') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by sanderson EN
196 |  | AATS7se | AATS(7, 'se') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by sanderson EN
197 |  | AATS8se | AATS(8, 'se') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by sanderson EN
198 |  | AATS0pe | AATS(0, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by pauling EN
199 |  | AATS1pe | AATS(1, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by pauling EN
200 |  | AATS2pe | AATS(2, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by pauling EN
201 |  | AATS3pe | AATS(3, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by pauling EN
202 |  | AATS4pe | AATS(4, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by pauling EN
203 |  | AATS5pe | AATS(5, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by pauling EN
204 |  | AATS6pe | AATS(6, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by pauling EN
205 |  | AATS7pe | AATS(7, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by pauling EN
206 |  | AATS8pe | AATS(8, 'pe') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by pauling EN
207 |  | AATS0are | AATS(0, 'are') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by allred-rocow EN
208 |  | AATS1are | AATS(1, 'are') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by allred-rocow EN
209 |  | AATS2are | AATS(2, 'are') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by allred-rocow EN
210 |  | AATS3are | AATS(3, 'are') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by allred-rocow EN
211 |  | AATS4are | AATS(4, 'are') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by allred-rocow EN
212 |  | AATS5are | AATS(5, 'are') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by allred-rocow EN
213 |  | AATS6are | AATS(6, 'are') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by allred-rocow EN
214 |  | AATS7are | AATS(7, 'are') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by allred-rocow EN
215 |  | AATS8are | AATS(8, 'are') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by allred-rocow EN
216 |  | AATS0p | AATS(0, 'p') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by polarizability
217 |  | AATS1p | AATS(1, 'p') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by polarizability
218 |  | AATS2p | AATS(2, 'p') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by polarizability
219 |  | AATS3p | AATS(3, 'p') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by polarizability
220 |  | AATS4p | AATS(4, 'p') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by polarizability
221 |  | AATS5p | AATS(5, 'p') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by polarizability
222 |  | AATS6p | AATS(6, 'p') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by polarizability
223 |  | AATS7p | AATS(7, 'p') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by polarizability
224 |  | AATS8p | AATS(8, 'p') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by polarizability
225 |  | AATS0i | AATS(0, 'i') | 2D | averaged moreau-broto autocorrelation of lag 0 weighted by ionization potential
226 |  | AATS1i | AATS(1, 'i') | 2D | averaged moreau-broto autocorrelation of lag 1 weighted by ionization potential
227 |  | AATS2i | AATS(2, 'i') | 2D | averaged moreau-broto autocorrelation of lag 2 weighted by ionization potential
228 |  | AATS3i | AATS(3, 'i') | 2D | averaged moreau-broto autocorrelation of lag 3 weighted by ionization potential
229 |  | AATS4i | AATS(4, 'i') | 2D | averaged moreau-broto autocorrelation of lag 4 weighted by ionization potential
230 |  | AATS5i | AATS(5, 'i') | 2D | averaged moreau-broto autocorrelation of lag 5 weighted by ionization potential
231 |  | AATS6i | AATS(6, 'i') | 2D | averaged moreau-broto autocorrelation of lag 6 weighted by ionization potential
232 |  | AATS7i | AATS(7, 'i') | 2D | averaged moreau-broto autocorrelation of lag 7 weighted by ionization potential
233 |  | AATS8i | AATS(8, 'i') | 2D | averaged moreau-broto autocorrelation of lag 8 weighted by ionization potential
234 |  | ATSC0c | ATSC(0, 'c') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by gasteiger charge
235 |  | ATSC1c | ATSC(1, 'c') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by gasteiger charge
236 |  | ATSC2c | ATSC(2, 'c') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by gasteiger charge
237 |  | ATSC3c | ATSC(3, 'c') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by gasteiger charge
238 |  | ATSC4c | ATSC(4, 'c') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by gasteiger charge
239 |  | ATSC5c | ATSC(5, 'c') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by gasteiger charge
240 |  | ATSC6c | ATSC(6, 'c') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by gasteiger charge
241 |  | ATSC7c | ATSC(7, 'c') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by gasteiger charge
242 |  | ATSC8c | ATSC(8, 'c') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by gasteiger charge
243 |  | ATSC0dv | ATSC(0, 'dv') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by valence electrons
244 |  | ATSC1dv | ATSC(1, 'dv') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by valence electrons
245 |  | ATSC2dv | ATSC(2, 'dv') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by valence electrons
246 |  | ATSC3dv | ATSC(3, 'dv') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by valence electrons
247 |  | ATSC4dv | ATSC(4, 'dv') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by valence electrons
248 |  | ATSC5dv | ATSC(5, 'dv') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by valence electrons
249 |  | ATSC6dv | ATSC(6, 'dv') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by valence electrons
250 |  | ATSC7dv | ATSC(7, 'dv') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by valence electrons
251 |  | ATSC8dv | ATSC(8, 'dv') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by valence electrons
252 |  | ATSC0d | ATSC(0, 'd') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by sigma electrons
253 |  | ATSC1d | ATSC(1, 'd') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by sigma electrons
254 |  | ATSC2d | ATSC(2, 'd') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by sigma electrons
255 |  | ATSC3d | ATSC(3, 'd') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by sigma electrons
256 |  | ATSC4d | ATSC(4, 'd') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by sigma electrons
257 |  | ATSC5d | ATSC(5, 'd') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by sigma electrons
258 |  | ATSC6d | ATSC(6, 'd') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by sigma electrons
259 |  | ATSC7d | ATSC(7, 'd') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by sigma electrons
260 |  | ATSC8d | ATSC(8, 'd') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by sigma electrons
261 |  | ATSC0s | ATSC(0, 's') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by intrinsic state
262 |  | ATSC1s | ATSC(1, 's') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by intrinsic state
263 |  | ATSC2s | ATSC(2, 's') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by intrinsic state
264 |  | ATSC3s | ATSC(3, 's') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by intrinsic state
265 |  | ATSC4s | ATSC(4, 's') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by intrinsic state
266 |  | ATSC5s | ATSC(5, 's') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by intrinsic state
267 |  | ATSC6s | ATSC(6, 's') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by intrinsic state
268 |  | ATSC7s | ATSC(7, 's') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by intrinsic state
269 |  | ATSC8s | ATSC(8, 's') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by intrinsic state
270 |  | ATSC0Z | ATSC(0, 'Z') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by atomic number
271 |  | ATSC1Z | ATSC(1, 'Z') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by atomic number
272 |  | ATSC2Z | ATSC(2, 'Z') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by atomic number
273 |  | ATSC3Z | ATSC(3, 'Z') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by atomic number
274 |  | ATSC4Z | ATSC(4, 'Z') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by atomic number
275 |  | ATSC5Z | ATSC(5, 'Z') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by atomic number
276 |  | ATSC6Z | ATSC(6, 'Z') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by atomic number
277 |  | ATSC7Z | ATSC(7, 'Z') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by atomic number
278 |  | ATSC8Z | ATSC(8, 'Z') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by atomic number
279 |  | ATSC0m | ATSC(0, 'm') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by mass
280 |  | ATSC1m | ATSC(1, 'm') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by mass
281 |  | ATSC2m | ATSC(2, 'm') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by mass
282 |  | ATSC3m | ATSC(3, 'm') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by mass
283 |  | ATSC4m | ATSC(4, 'm') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by mass
284 |  | ATSC5m | ATSC(5, 'm') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by mass
285 |  | ATSC6m | ATSC(6, 'm') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by mass
286 |  | ATSC7m | ATSC(7, 'm') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by mass
287 |  | ATSC8m | ATSC(8, 'm') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by mass
288 |  | ATSC0v | ATSC(0, 'v') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by vdw volume
289 |  | ATSC1v | ATSC(1, 'v') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by vdw volume
290 |  | ATSC2v | ATSC(2, 'v') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by vdw volume
291 |  | ATSC3v | ATSC(3, 'v') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by vdw volume
292 |  | ATSC4v | ATSC(4, 'v') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by vdw volume
293 |  | ATSC5v | ATSC(5, 'v') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by vdw volume
294 |  | ATSC6v | ATSC(6, 'v') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by vdw volume
295 |  | ATSC7v | ATSC(7, 'v') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by vdw volume
296 |  | ATSC8v | ATSC(8, 'v') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by vdw volume
297 |  | ATSC0se | ATSC(0, 'se') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by sanderson EN
298 |  | ATSC1se | ATSC(1, 'se') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by sanderson EN
299 |  | ATSC2se | ATSC(2, 'se') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by sanderson EN
300 |  | ATSC3se | ATSC(3, 'se') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by sanderson EN
301 |  | ATSC4se | ATSC(4, 'se') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by sanderson EN
302 |  | ATSC5se | ATSC(5, 'se') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by sanderson EN
303 |  | ATSC6se | ATSC(6, 'se') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by sanderson EN
304 |  | ATSC7se | ATSC(7, 'se') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by sanderson EN
305 |  | ATSC8se | ATSC(8, 'se') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by sanderson EN
306 |  | ATSC0pe | ATSC(0, 'pe') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by pauling EN
307 |  | ATSC1pe | ATSC(1, 'pe') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by pauling EN
308 |  | ATSC2pe | ATSC(2, 'pe') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by pauling EN
309 |  | ATSC3pe | ATSC(3, 'pe') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by pauling EN
310 |  | ATSC4pe | ATSC(4, 'pe') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by pauling EN
311 |  | ATSC5pe | ATSC(5, 'pe') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by pauling EN
312 |  | ATSC6pe | ATSC(6, 'pe') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by pauling EN
313 |  | ATSC7pe | ATSC(7, 'pe') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by pauling EN
314 |  | ATSC8pe | ATSC(8, 'pe') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by pauling EN
315 |  | ATSC0are | ATSC(0, 'are') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by allred-rocow EN
316 |  | ATSC1are | ATSC(1, 'are') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by allred-rocow EN
317 |  | ATSC2are | ATSC(2, 'are') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by allred-rocow EN
318 |  | ATSC3are | ATSC(3, 'are') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by allred-rocow EN
319 |  | ATSC4are | ATSC(4, 'are') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by allred-rocow EN
320 |  | ATSC5are | ATSC(5, 'are') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by allred-rocow EN
321 |  | ATSC6are | ATSC(6, 'are') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by allred-rocow EN
322 |  | ATSC7are | ATSC(7, 'are') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by allred-rocow EN
323 |  | ATSC8are | ATSC(8, 'are') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by allred-rocow EN
324 |  | ATSC0p | ATSC(0, 'p') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by polarizability
325 |  | ATSC1p | ATSC(1, 'p') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by polarizability
326 |  | ATSC2p | ATSC(2, 'p') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by polarizability
327 |  | ATSC3p | ATSC(3, 'p') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by polarizability
328 |  | ATSC4p | ATSC(4, 'p') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by polarizability
329 |  | ATSC5p | ATSC(5, 'p') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by polarizability
330 |  | ATSC6p | ATSC(6, 'p') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by polarizability
331 |  | ATSC7p | ATSC(7, 'p') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by polarizability
332 |  | ATSC8p | ATSC(8, 'p') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by polarizability
333 |  | ATSC0i | ATSC(0, 'i') | 2D | centered moreau-broto autocorrelation of lag 0 weighted by ionization potential
334 |  | ATSC1i | ATSC(1, 'i') | 2D | centered moreau-broto autocorrelation of lag 1 weighted by ionization potential
335 |  | ATSC2i | ATSC(2, 'i') | 2D | centered moreau-broto autocorrelation of lag 2 weighted by ionization potential
336 |  | ATSC3i | ATSC(3, 'i') | 2D | centered moreau-broto autocorrelation of lag 3 weighted by ionization potential
337 |  | ATSC4i | ATSC(4, 'i') | 2D | centered moreau-broto autocorrelation of lag 4 weighted by ionization potential
338 |  | ATSC5i | ATSC(5, 'i') | 2D | centered moreau-broto autocorrelation of lag 5 weighted by ionization potential
339 |  | ATSC6i | ATSC(6, 'i') | 2D | centered moreau-broto autocorrelation of lag 6 weighted by ionization potential
340 |  | ATSC7i | ATSC(7, 'i') | 2D | centered moreau-broto autocorrelation of lag 7 weighted by ionization potential
341 |  | ATSC8i | ATSC(8, 'i') | 2D | centered moreau-broto autocorrelation of lag 8 weighted by ionization potential
342 |  | AATSC0c | AATSC(0, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by gasteiger charge
343 |  | AATSC1c | AATSC(1, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by gasteiger charge
344 |  | AATSC2c | AATSC(2, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by gasteiger charge
345 |  | AATSC3c | AATSC(3, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by gasteiger charge
346 |  | AATSC4c | AATSC(4, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by gasteiger charge
347 |  | AATSC5c | AATSC(5, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by gasteiger charge
348 |  | AATSC6c | AATSC(6, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by gasteiger charge
349 |  | AATSC7c | AATSC(7, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by gasteiger charge
350 |  | AATSC8c | AATSC(8, 'c') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by gasteiger charge
351 |  | AATSC0dv | AATSC(0, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by valence electrons
352 |  | AATSC1dv | AATSC(1, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by valence electrons
353 |  | AATSC2dv | AATSC(2, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by valence electrons
354 |  | AATSC3dv | AATSC(3, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by valence electrons
355 |  | AATSC4dv | AATSC(4, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by valence electrons
356 |  | AATSC5dv | AATSC(5, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by valence electrons
357 |  | AATSC6dv | AATSC(6, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by valence electrons
358 |  | AATSC7dv | AATSC(7, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by valence electrons
359 |  | AATSC8dv | AATSC(8, 'dv') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by valence electrons
360 |  | AATSC0d | AATSC(0, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by sigma electrons
361 |  | AATSC1d | AATSC(1, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by sigma electrons
362 |  | AATSC2d | AATSC(2, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by sigma electrons
363 |  | AATSC3d | AATSC(3, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by sigma electrons
364 |  | AATSC4d | AATSC(4, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by sigma electrons
365 |  | AATSC5d | AATSC(5, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by sigma electrons
366 |  | AATSC6d | AATSC(6, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by sigma electrons
367 |  | AATSC7d | AATSC(7, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by sigma electrons
368 |  | AATSC8d | AATSC(8, 'd') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by sigma electrons
369 |  | AATSC0s | AATSC(0, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by intrinsic state
370 |  | AATSC1s | AATSC(1, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by intrinsic state
371 |  | AATSC2s | AATSC(2, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by intrinsic state
372 |  | AATSC3s | AATSC(3, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by intrinsic state
373 |  | AATSC4s | AATSC(4, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by intrinsic state
374 |  | AATSC5s | AATSC(5, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by intrinsic state
375 |  | AATSC6s | AATSC(6, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by intrinsic state
376 |  | AATSC7s | AATSC(7, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by intrinsic state
377 |  | AATSC8s | AATSC(8, 's') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by intrinsic state
378 |  | AATSC0Z | AATSC(0, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by atomic number
379 |  | AATSC1Z | AATSC(1, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by atomic number
380 |  | AATSC2Z | AATSC(2, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by atomic number
381 |  | AATSC3Z | AATSC(3, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by atomic number
382 |  | AATSC4Z | AATSC(4, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by atomic number
383 |  | AATSC5Z | AATSC(5, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by atomic number
384 |  | AATSC6Z | AATSC(6, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by atomic number
385 |  | AATSC7Z | AATSC(7, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by atomic number
386 |  | AATSC8Z | AATSC(8, 'Z') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by atomic number
387 |  | AATSC0m | AATSC(0, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by mass
388 |  | AATSC1m | AATSC(1, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by mass
389 |  | AATSC2m | AATSC(2, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by mass
390 |  | AATSC3m | AATSC(3, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by mass
391 |  | AATSC4m | AATSC(4, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by mass
392 |  | AATSC5m | AATSC(5, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by mass
393 |  | AATSC6m | AATSC(6, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by mass
394 |  | AATSC7m | AATSC(7, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by mass
395 |  | AATSC8m | AATSC(8, 'm') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by mass
396 |  | AATSC0v | AATSC(0, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by vdw volume
397 |  | AATSC1v | AATSC(1, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by vdw volume
398 |  | AATSC2v | AATSC(2, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by vdw volume
399 |  | AATSC3v | AATSC(3, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by vdw volume
400 |  | AATSC4v | AATSC(4, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by vdw volume
401 |  | AATSC5v | AATSC(5, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by vdw volume
402 |  | AATSC6v | AATSC(6, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by vdw volume
403 |  | AATSC7v | AATSC(7, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by vdw volume
404 |  | AATSC8v | AATSC(8, 'v') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by vdw volume
405 |  | AATSC0se | AATSC(0, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by sanderson EN
406 |  | AATSC1se | AATSC(1, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by sanderson EN
407 |  | AATSC2se | AATSC(2, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by sanderson EN
408 |  | AATSC3se | AATSC(3, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by sanderson EN
409 |  | AATSC4se | AATSC(4, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by sanderson EN
410 |  | AATSC5se | AATSC(5, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by sanderson EN
411 |  | AATSC6se | AATSC(6, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by sanderson EN
412 |  | AATSC7se | AATSC(7, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by sanderson EN
413 |  | AATSC8se | AATSC(8, 'se') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by sanderson EN
414 |  | AATSC0pe | AATSC(0, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by pauling EN
415 |  | AATSC1pe | AATSC(1, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by pauling EN
416 |  | AATSC2pe | AATSC(2, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by pauling EN
417 |  | AATSC3pe | AATSC(3, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by pauling EN
418 |  | AATSC4pe | AATSC(4, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by pauling EN
419 |  | AATSC5pe | AATSC(5, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by pauling EN
420 |  | AATSC6pe | AATSC(6, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by pauling EN
421 |  | AATSC7pe | AATSC(7, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by pauling EN
422 |  | AATSC8pe | AATSC(8, 'pe') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by pauling EN
423 |  | AATSC0are | AATSC(0, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by allred-rocow EN
424 |  | AATSC1are | AATSC(1, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by allred-rocow EN
425 |  | AATSC2are | AATSC(2, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by allred-rocow EN
426 |  | AATSC3are | AATSC(3, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by allred-rocow EN
427 |  | AATSC4are | AATSC(4, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by allred-rocow EN
428 |  | AATSC5are | AATSC(5, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by allred-rocow EN
429 |  | AATSC6are | AATSC(6, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by allred-rocow EN
430 |  | AATSC7are | AATSC(7, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by allred-rocow EN
431 |  | AATSC8are | AATSC(8, 'are') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by allred-rocow EN
432 |  | AATSC0p | AATSC(0, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by polarizability
433 |  | AATSC1p | AATSC(1, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by polarizability
434 |  | AATSC2p | AATSC(2, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by polarizability
435 |  | AATSC3p | AATSC(3, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by polarizability
436 |  | AATSC4p | AATSC(4, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by polarizability
437 |  | AATSC5p | AATSC(5, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by polarizability
438 |  | AATSC6p | AATSC(6, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by polarizability
439 |  | AATSC7p | AATSC(7, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by polarizability
440 |  | AATSC8p | AATSC(8, 'p') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by polarizability
441 |  | AATSC0i | AATSC(0, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 0 weighted by ionization potential
442 |  | AATSC1i | AATSC(1, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 1 weighted by ionization potential
443 |  | AATSC2i | AATSC(2, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 2 weighted by ionization potential
444 |  | AATSC3i | AATSC(3, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 3 weighted by ionization potential
445 |  | AATSC4i | AATSC(4, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 4 weighted by ionization potential
446 |  | AATSC5i | AATSC(5, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 5 weighted by ionization potential
447 |  | AATSC6i | AATSC(6, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 6 weighted by ionization potential
448 |  | AATSC7i | AATSC(7, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 7 weighted by ionization potential
449 |  | AATSC8i | AATSC(8, 'i') | 2D | averaged and centered moreau-broto autocorrelation of lag 8 weighted by ionization potential
450 |  | MATS1c | MATS(1, 'c') | 2D | moran coefficient of lag 1 weighted by gasteiger charge
451 |  | MATS2c | MATS(2, 'c') | 2D | moran coefficient of lag 2 weighted by gasteiger charge
452 |  | MATS3c | MATS(3, 'c') | 2D | moran coefficient of lag 3 weighted by gasteiger charge
453 |  | MATS4c | MATS(4, 'c') | 2D | moran coefficient of lag 4 weighted by gasteiger charge
454 |  | MATS5c | MATS(5, 'c') | 2D | moran coefficient of lag 5 weighted by gasteiger charge
455 |  | MATS6c | MATS(6, 'c') | 2D | moran coefficient of lag 6 weighted by gasteiger charge
456 |  | MATS7c | MATS(7, 'c') | 2D | moran coefficient of lag 7 weighted by gasteiger charge
457 |  | MATS8c | MATS(8, 'c') | 2D | moran coefficient of lag 8 weighted by gasteiger charge
458 |  | MATS1dv | MATS(1, 'dv') | 2D | moran coefficient of lag 1 weighted by valence electrons
459 |  | MATS2dv | MATS(2, 'dv') | 2D | moran coefficient of lag 2 weighted by valence electrons
460 |  | MATS3dv | MATS(3, 'dv') | 2D | moran coefficient of lag 3 weighted by valence electrons
461 |  | MATS4dv | MATS(4, 'dv') | 2D | moran coefficient of lag 4 weighted by valence electrons
462 |  | MATS5dv | MATS(5, 'dv') | 2D | moran coefficient of lag 5 weighted by valence electrons
463 |  | MATS6dv | MATS(6, 'dv') | 2D | moran coefficient of lag 6 weighted by valence electrons
464 |  | MATS7dv | MATS(7, 'dv') | 2D | moran coefficient of lag 7 weighted by valence electrons
465 |  | MATS8dv | MATS(8, 'dv') | 2D | moran coefficient of lag 8 weighted by valence electrons
466 |  | MATS1d | MATS(1, 'd') | 2D | moran coefficient of lag 1 weighted by sigma electrons
467 |  | MATS2d | MATS(2, 'd') | 2D | moran coefficient of lag 2 weighted by sigma electrons
468 |  | MATS3d | MATS(3, 'd') | 2D | moran coefficient of lag 3 weighted by sigma electrons
469 |  | MATS4d | MATS(4, 'd') | 2D | moran coefficient of lag 4 weighted by sigma electrons
470 |  | MATS5d | MATS(5, 'd') | 2D | moran coefficient of lag 5 weighted by sigma electrons
471 |  | MATS6d | MATS(6, 'd') | 2D | moran coefficient of lag 6 weighted by sigma electrons
472 |  | MATS7d | MATS(7, 'd') | 2D | moran coefficient of lag 7 weighted by sigma electrons
473 |  | MATS8d | MATS(8, 'd') | 2D | moran coefficient of lag 8 weighted by sigma electrons
474 |  | MATS1s | MATS(1, 's') | 2D | moran coefficient of lag 1 weighted by intrinsic state
475 |  | MATS2s | MATS(2, 's') | 2D | moran coefficient of lag 2 weighted by intrinsic state
476 |  | MATS3s | MATS(3, 's') | 2D | moran coefficient of lag 3 weighted by intrinsic state
477 |  | MATS4s | MATS(4, 's') | 2D | moran coefficient of lag 4 weighted by intrinsic state
478 |  | MATS5s | MATS(5, 's') | 2D | moran coefficient of lag 5 weighted by intrinsic state
479 |  | MATS6s | MATS(6, 's') | 2D | moran coefficient of lag 6 weighted by intrinsic state
480 |  | MATS7s | MATS(7, 's') | 2D | moran coefficient of lag 7 weighted by intrinsic state
481 |  | MATS8s | MATS(8, 's') | 2D | moran coefficient of lag 8 weighted by intrinsic state
482 |  | MATS1Z | MATS(1, 'Z') | 2D | moran coefficient of lag 1 weighted by atomic number
483 |  | MATS2Z | MATS(2, 'Z') | 2D | moran coefficient of lag 2 weighted by atomic number
484 |  | MATS3Z | MATS(3, 'Z') | 2D | moran coefficient of lag 3 weighted by atomic number
485 |  | MATS4Z | MATS(4, 'Z') | 2D | moran coefficient of lag 4 weighted by atomic number
486 |  | MATS5Z | MATS(5, 'Z') | 2D | moran coefficient of lag 5 weighted by atomic number
487 |  | MATS6Z | MATS(6, 'Z') | 2D | moran coefficient of lag 6 weighted by atomic number
488 |  | MATS7Z | MATS(7, 'Z') | 2D | moran coefficient of lag 7 weighted by atomic number
489 |  | MATS8Z | MATS(8, 'Z') | 2D | moran coefficient of lag 8 weighted by atomic number
490 |  | MATS1m | MATS(1, 'm') | 2D | moran coefficient of lag 1 weighted by mass
491 |  | MATS2m | MATS(2, 'm') | 2D | moran coefficient of lag 2 weighted by mass
492 |  | MATS3m | MATS(3, 'm') | 2D | moran coefficient of lag 3 weighted by mass
493 |  | MATS4m | MATS(4, 'm') | 2D | moran coefficient of lag 4 weighted by mass
494 |  | MATS5m | MATS(5, 'm') | 2D | moran coefficient of lag 5 weighted by mass
495 |  | MATS6m | MATS(6, 'm') | 2D | moran coefficient of lag 6 weighted by mass
496 |  | MATS7m | MATS(7, 'm') | 2D | moran coefficient of lag 7 weighted by mass
497 |  | MATS8m | MATS(8, 'm') | 2D | moran coefficient of lag 8 weighted by mass
498 |  | MATS1v | MATS(1, 'v') | 2D | moran coefficient of lag 1 weighted by vdw volume
499 |  | MATS2v | MATS(2, 'v') | 2D | moran coefficient of lag 2 weighted by vdw volume
500 |  | MATS3v | MATS(3, 'v') | 2D | moran coefficient of lag 3 weighted by vdw volume
501 |  | MATS4v | MATS(4, 'v') | 2D | moran coefficient of lag 4 weighted by vdw volume
502 |  | MATS5v | MATS(5, 'v') | 2D | moran coefficient of lag 5 weighted by vdw volume
503 |  | MATS6v | MATS(6, 'v') | 2D | moran coefficient of lag 6 weighted by vdw volume
504 |  | MATS7v | MATS(7, 'v') | 2D | moran coefficient of lag 7 weighted by vdw volume
505 |  | MATS8v | MATS(8, 'v') | 2D | moran coefficient of lag 8 weighted by vdw volume
506 |  | MATS1se | MATS(1, 'se') | 2D | moran coefficient of lag 1 weighted by sanderson EN
507 |  | MATS2se | MATS(2, 'se') | 2D | moran coefficient of lag 2 weighted by sanderson EN
508 |  | MATS3se | MATS(3, 'se') | 2D | moran coefficient of lag 3 weighted by sanderson EN
509 |  | MATS4se | MATS(4, 'se') | 2D | moran coefficient of lag 4 weighted by sanderson EN
510 |  | MATS5se | MATS(5, 'se') | 2D | moran coefficient of lag 5 weighted by sanderson EN
511 |  | MATS6se | MATS(6, 'se') | 2D | moran coefficient of lag 6 weighted by sanderson EN
512 |  | MATS7se | MATS(7, 'se') | 2D | moran coefficient of lag 7 weighted by sanderson EN
513 |  | MATS8se | MATS(8, 'se') | 2D | moran coefficient of lag 8 weighted by sanderson EN
514 |  | MATS1pe | MATS(1, 'pe') | 2D | moran coefficient of lag 1 weighted by pauling EN
515 |  | MATS2pe | MATS(2, 'pe') | 2D | moran coefficient of lag 2 weighted by pauling EN
516 |  | MATS3pe | MATS(3, 'pe') | 2D | moran coefficient of lag 3 weighted by pauling EN
517 |  | MATS4pe | MATS(4, 'pe') | 2D | moran coefficient of lag 4 weighted by pauling EN
518 |  | MATS5pe | MATS(5, 'pe') | 2D | moran coefficient of lag 5 weighted by pauling EN
519 |  | MATS6pe | MATS(6, 'pe') | 2D | moran coefficient of lag 6 weighted by pauling EN
520 |  | MATS7pe | MATS(7, 'pe') | 2D | moran coefficient of lag 7 weighted by pauling EN
521 |  | MATS8pe | MATS(8, 'pe') | 2D | moran coefficient of lag 8 weighted by pauling EN
522 |  | MATS1are | MATS(1, 'are') | 2D | moran coefficient of lag 1 weighted by allred-rocow EN
523 |  | MATS2are | MATS(2, 'are') | 2D | moran coefficient of lag 2 weighted by allred-rocow EN
524 |  | MATS3are | MATS(3, 'are') | 2D | moran coefficient of lag 3 weighted by allred-rocow EN
525 |  | MATS4are | MATS(4, 'are') | 2D | moran coefficient of lag 4 weighted by allred-rocow EN
526 |  | MATS5are | MATS(5, 'are') | 2D | moran coefficient of lag 5 weighted by allred-rocow EN
527 |  | MATS6are | MATS(6, 'are') | 2D | moran coefficient of lag 6 weighted by allred-rocow EN
528 |  | MATS7are | MATS(7, 'are') | 2D | moran coefficient of lag 7 weighted by allred-rocow EN
529 |  | MATS8are | MATS(8, 'are') | 2D | moran coefficient of lag 8 weighted by allred-rocow EN
530 |  | MATS1p | MATS(1, 'p') | 2D | moran coefficient of lag 1 weighted by polarizability
531 |  | MATS2p | MATS(2, 'p') | 2D | moran coefficient of lag 2 weighted by polarizability
532 |  | MATS3p | MATS(3, 'p') | 2D | moran coefficient of lag 3 weighted by polarizability
533 |  | MATS4p | MATS(4, 'p') | 2D | moran coefficient of lag 4 weighted by polarizability
534 |  | MATS5p | MATS(5, 'p') | 2D | moran coefficient of lag 5 weighted by polarizability
535 |  | MATS6p | MATS(6, 'p') | 2D | moran coefficient of lag 6 weighted by polarizability
536 |  | MATS7p | MATS(7, 'p') | 2D | moran coefficient of lag 7 weighted by polarizability
537 |  | MATS8p | MATS(8, 'p') | 2D | moran coefficient of lag 8 weighted by polarizability
538 |  | MATS1i | MATS(1, 'i') | 2D | moran coefficient of lag 1 weighted by ionization potential
539 |  | MATS2i | MATS(2, 'i') | 2D | moran coefficient of lag 2 weighted by ionization potential
540 |  | MATS3i | MATS(3, 'i') | 2D | moran coefficient of lag 3 weighted by ionization potential
541 |  | MATS4i | MATS(4, 'i') | 2D | moran coefficient of lag 4 weighted by ionization potential
542 |  | MATS5i | MATS(5, 'i') | 2D | moran coefficient of lag 5 weighted by ionization potential
543 |  | MATS6i | MATS(6, 'i') | 2D | moran coefficient of lag 6 weighted by ionization potential
544 |  | MATS7i | MATS(7, 'i') | 2D | moran coefficient of lag 7 weighted by ionization potential
545 |  | MATS8i | MATS(8, 'i') | 2D | moran coefficient of lag 8 weighted by ionization potential
546 |  | GATS1c | GATS(1, 'c') | 2D | geary coefficient of lag 1 weighted by gasteiger charge
547 |  | GATS2c | GATS(2, 'c') | 2D | geary coefficient of lag 2 weighted by gasteiger charge
548 |  | GATS3c | GATS(3, 'c') | 2D | geary coefficient of lag 3 weighted by gasteiger charge
549 |  | GATS4c | GATS(4, 'c') | 2D | geary coefficient of lag 4 weighted by gasteiger charge
550 |  | GATS5c | GATS(5, 'c') | 2D | geary coefficient of lag 5 weighted by gasteiger charge
551 |  | GATS6c | GATS(6, 'c') | 2D | geary coefficient of lag 6 weighted by gasteiger charge
552 |  | GATS7c | GATS(7, 'c') | 2D | geary coefficient of lag 7 weighted by gasteiger charge
553 |  | GATS8c | GATS(8, 'c') | 2D | geary coefficient of lag 8 weighted by gasteiger charge
554 |  | GATS1dv | GATS(1, 'dv') | 2D | geary coefficient of lag 1 weighted by valence electrons
555 |  | GATS2dv | GATS(2, 'dv') | 2D | geary coefficient of lag 2 weighted by valence electrons
556 |  | GATS3dv | GATS(3, 'dv') | 2D | geary coefficient of lag 3 weighted by valence electrons
557 |  | GATS4dv | GATS(4, 'dv') | 2D | geary coefficient of lag 4 weighted by valence electrons
558 |  | GATS5dv | GATS(5, 'dv') | 2D | geary coefficient of lag 5 weighted by valence electrons
559 |  | GATS6dv | GATS(6, 'dv') | 2D | geary coefficient of lag 6 weighted by valence electrons
560 |  | GATS7dv | GATS(7, 'dv') | 2D | geary coefficient of lag 7 weighted by valence electrons
561 |  | GATS8dv | GATS(8, 'dv') | 2D | geary coefficient of lag 8 weighted by valence electrons
562 |  | GATS1d | GATS(1, 'd') | 2D | geary coefficient of lag 1 weighted by sigma electrons
563 |  | GATS2d | GATS(2, 'd') | 2D | geary coefficient of lag 2 weighted by sigma electrons
564 |  | GATS3d | GATS(3, 'd') | 2D | geary coefficient of lag 3 weighted by sigma electrons
565 |  | GATS4d | GATS(4, 'd') | 2D | geary coefficient of lag 4 weighted by sigma electrons
566 |  | GATS5d | GATS(5, 'd') | 2D | geary coefficient of lag 5 weighted by sigma electrons
567 |  | GATS6d | GATS(6, 'd') | 2D | geary coefficient of lag 6 weighted by sigma electrons
568 |  | GATS7d | GATS(7, 'd') | 2D | geary coefficient of lag 7 weighted by sigma electrons
569 |  | GATS8d | GATS(8, 'd') | 2D | geary coefficient of lag 8 weighted by sigma electrons
570 |  | GATS1s | GATS(1, 's') | 2D | geary coefficient of lag 1 weighted by intrinsic state
571 |  | GATS2s | GATS(2, 's') | 2D | geary coefficient of lag 2 weighted by intrinsic state
572 |  | GATS3s | GATS(3, 's') | 2D | geary coefficient of lag 3 weighted by intrinsic state
573 |  | GATS4s | GATS(4, 's') | 2D | geary coefficient of lag 4 weighted by intrinsic state
574 |  | GATS5s | GATS(5, 's') | 2D | geary coefficient of lag 5 weighted by intrinsic state
575 |  | GATS6s | GATS(6, 's') | 2D | geary coefficient of lag 6 weighted by intrinsic state
576 |  | GATS7s | GATS(7, 's') | 2D | geary coefficient of lag 7 weighted by intrinsic state
577 |  | GATS8s | GATS(8, 's') | 2D | geary coefficient of lag 8 weighted by intrinsic state
578 |  | GATS1Z | GATS(1, 'Z') | 2D | geary coefficient of lag 1 weighted by atomic number
579 |  | GATS2Z | GATS(2, 'Z') | 2D | geary coefficient of lag 2 weighted by atomic number
580 |  | GATS3Z | GATS(3, 'Z') | 2D | geary coefficient of lag 3 weighted by atomic number
581 |  | GATS4Z | GATS(4, 'Z') | 2D | geary coefficient of lag 4 weighted by atomic number
582 |  | GATS5Z | GATS(5, 'Z') | 2D | geary coefficient of lag 5 weighted by atomic number
583 |  | GATS6Z | GATS(6, 'Z') | 2D | geary coefficient of lag 6 weighted by atomic number
584 |  | GATS7Z | GATS(7, 'Z') | 2D | geary coefficient of lag 7 weighted by atomic number
585 |  | GATS8Z | GATS(8, 'Z') | 2D | geary coefficient of lag 8 weighted by atomic number
586 |  | GATS1m | GATS(1, 'm') | 2D | geary coefficient of lag 1 weighted by mass
587 |  | GATS2m | GATS(2, 'm') | 2D | geary coefficient of lag 2 weighted by mass
588 |  | GATS3m | GATS(3, 'm') | 2D | geary coefficient of lag 3 weighted by mass
589 |  | GATS4m | GATS(4, 'm') | 2D | geary coefficient of lag 4 weighted by mass
590 |  | GATS5m | GATS(5, 'm') | 2D | geary coefficient of lag 5 weighted by mass
591 |  | GATS6m | GATS(6, 'm') | 2D | geary coefficient of lag 6 weighted by mass
592 |  | GATS7m | GATS(7, 'm') | 2D | geary coefficient of lag 7 weighted by mass
593 |  | GATS8m | GATS(8, 'm') | 2D | geary coefficient of lag 8 weighted by mass
594 |  | GATS1v | GATS(1, 'v') | 2D | geary coefficient of lag 1 weighted by vdw volume
595 |  | GATS2v | GATS(2, 'v') | 2D | geary coefficient of lag 2 weighted by vdw volume
596 |  | GATS3v | GATS(3, 'v') | 2D | geary coefficient of lag 3 weighted by vdw volume
597 |  | GATS4v | GATS(4, 'v') | 2D | geary coefficient of lag 4 weighted by vdw volume
598 |  | GATS5v | GATS(5, 'v') | 2D | geary coefficient of lag 5 weighted by vdw volume
599 |  | GATS6v | GATS(6, 'v') | 2D | geary coefficient of lag 6 weighted by vdw volume
600 |  | GATS7v | GATS(7, 'v') | 2D | geary coefficient of lag 7 weighted by vdw volume
601 |  | GATS8v | GATS(8, 'v') | 2D | geary coefficient of lag 8 weighted by vdw volume
602 |  | GATS1se | GATS(1, 'se') | 2D | geary coefficient of lag 1 weighted by sanderson EN
603 |  | GATS2se | GATS(2, 'se') | 2D | geary coefficient of lag 2 weighted by sanderson EN
604 |  | GATS3se | GATS(3, 'se') | 2D | geary coefficient of lag 3 weighted by sanderson EN
605 |  | GATS4se | GATS(4, 'se') | 2D | geary coefficient of lag 4 weighted by sanderson EN
606 |  | GATS5se | GATS(5, 'se') | 2D | geary coefficient of lag 5 weighted by sanderson EN
607 |  | GATS6se | GATS(6, 'se') | 2D | geary coefficient of lag 6 weighted by sanderson EN
608 |  | GATS7se | GATS(7, 'se') | 2D | geary coefficient of lag 7 weighted by sanderson EN
609 |  | GATS8se | GATS(8, 'se') | 2D | geary coefficient of lag 8 weighted by sanderson EN
610 |  | GATS1pe | GATS(1, 'pe') | 2D | geary coefficient of lag 1 weighted by pauling EN
611 |  | GATS2pe | GATS(2, 'pe') | 2D | geary coefficient of lag 2 weighted by pauling EN
612 |  | GATS3pe | GATS(3, 'pe') | 2D | geary coefficient of lag 3 weighted by pauling EN
613 |  | GATS4pe | GATS(4, 'pe') | 2D | geary coefficient of lag 4 weighted by pauling EN
614 |  | GATS5pe | GATS(5, 'pe') | 2D | geary coefficient of lag 5 weighted by pauling EN
615 |  | GATS6pe | GATS(6, 'pe') | 2D | geary coefficient of lag 6 weighted by pauling EN
616 |  | GATS7pe | GATS(7, 'pe') | 2D | geary coefficient of lag 7 weighted by pauling EN
617 |  | GATS8pe | GATS(8, 'pe') | 2D | geary coefficient of lag 8 weighted by pauling EN
618 |  | GATS1are | GATS(1, 'are') | 2D | geary coefficient of lag 1 weighted by allred-rocow EN
619 |  | GATS2are | GATS(2, 'are') | 2D | geary coefficient of lag 2 weighted by allred-rocow EN
620 |  | GATS3are | GATS(3, 'are') | 2D | geary coefficient of lag 3 weighted by allred-rocow EN
621 |  | GATS4are | GATS(4, 'are') | 2D | geary coefficient of lag 4 weighted by allred-rocow EN
622 |  | GATS5are | GATS(5, 'are') | 2D | geary coefficient of lag 5 weighted by allred-rocow EN
623 |  | GATS6are | GATS(6, 'are') | 2D | geary coefficient of lag 6 weighted by allred-rocow EN
624 |  | GATS7are | GATS(7, 'are') | 2D | geary coefficient of lag 7 weighted by allred-rocow EN
625 |  | GATS8are | GATS(8, 'are') | 2D | geary coefficient of lag 8 weighted by allred-rocow EN
626 |  | GATS1p | GATS(1, 'p') | 2D | geary coefficient of lag 1 weighted by polarizability
627 |  | GATS2p | GATS(2, 'p') | 2D | geary coefficient of lag 2 weighted by polarizability
628 |  | GATS3p | GATS(3, 'p') | 2D | geary coefficient of lag 3 weighted by polarizability
629 |  | GATS4p | GATS(4, 'p') | 2D | geary coefficient of lag 4 weighted by polarizability
630 |  | GATS5p | GATS(5, 'p') | 2D | geary coefficient of lag 5 weighted by polarizability
631 |  | GATS6p | GATS(6, 'p') | 2D | geary coefficient of lag 6 weighted by polarizability
632 |  | GATS7p | GATS(7, 'p') | 2D | geary coefficient of lag 7 weighted by polarizability
633 |  | GATS8p | GATS(8, 'p') | 2D | geary coefficient of lag 8 weighted by polarizability
634 |  | GATS1i | GATS(1, 'i') | 2D | geary coefficient of lag 1 weighted by ionization potential
635 |  | GATS2i | GATS(2, 'i') | 2D | geary coefficient of lag 2 weighted by ionization potential
636 |  | GATS3i | GATS(3, 'i') | 2D | geary coefficient of lag 3 weighted by ionization potential
637 |  | GATS4i | GATS(4, 'i') | 2D | geary coefficient of lag 4 weighted by ionization potential
638 |  | GATS5i | GATS(5, 'i') | 2D | geary coefficient of lag 5 weighted by ionization potential
639 |  | GATS6i | GATS(6, 'i') | 2D | geary coefficient of lag 6 weighted by ionization potential
640 |  | GATS7i | GATS(7, 'i') | 2D | geary coefficient of lag 7 weighted by ionization potential
641 |  | GATS8i | GATS(8, 'i') | 2D | geary coefficient of lag 8 weighted by ionization potential
642 | BalabanJ | BalabanJ | BalabanJ() | 2D | Balaban's J index
643 | BaryszMatrix | SpAbs_DzZ | BaryszMatrix('Z', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by atomic number
644 |  | SpMax_DzZ | BaryszMatrix('Z', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by atomic number
645 |  | SpDiam_DzZ | BaryszMatrix('Z', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by atomic number
646 |  | SpAD_DzZ | BaryszMatrix('Z', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by atomic number
647 |  | SpMAD_DzZ | BaryszMatrix('Z', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by atomic number
648 |  | LogEE_DzZ | BaryszMatrix('Z', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by atomic number
649 |  | SM1_DzZ | BaryszMatrix('Z', 'SM1') | 2D | spectral moment from Barysz matrix weighted by atomic number
650 |  | VE1_DzZ | BaryszMatrix('Z', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by atomic number
651 |  | VE2_DzZ | BaryszMatrix('Z', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by atomic number
652 |  | VE3_DzZ | BaryszMatrix('Z', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by atomic number
653 |  | VR1_DzZ | BaryszMatrix('Z', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by atomic number
654 |  | VR2_DzZ | BaryszMatrix('Z', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by atomic number
655 |  | VR3_DzZ | BaryszMatrix('Z', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by atomic number
656 |  | SpAbs_Dzm | BaryszMatrix('m', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by mass
657 |  | SpMax_Dzm | BaryszMatrix('m', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by mass
658 |  | SpDiam_Dzm | BaryszMatrix('m', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by mass
659 |  | SpAD_Dzm | BaryszMatrix('m', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by mass
660 |  | SpMAD_Dzm | BaryszMatrix('m', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by mass
661 |  | LogEE_Dzm | BaryszMatrix('m', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by mass
662 |  | SM1_Dzm | BaryszMatrix('m', 'SM1') | 2D | spectral moment from Barysz matrix weighted by mass
663 |  | VE1_Dzm | BaryszMatrix('m', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by mass
664 |  | VE2_Dzm | BaryszMatrix('m', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by mass
665 |  | VE3_Dzm | BaryszMatrix('m', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by mass
666 |  | VR1_Dzm | BaryszMatrix('m', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by mass
667 |  | VR2_Dzm | BaryszMatrix('m', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by mass
668 |  | VR3_Dzm | BaryszMatrix('m', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by mass
669 |  | SpAbs_Dzv | BaryszMatrix('v', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by vdw volume
670 |  | SpMax_Dzv | BaryszMatrix('v', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by vdw volume
671 |  | SpDiam_Dzv | BaryszMatrix('v', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by vdw volume
672 |  | SpAD_Dzv | BaryszMatrix('v', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by vdw volume
673 |  | SpMAD_Dzv | BaryszMatrix('v', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by vdw volume
674 |  | LogEE_Dzv | BaryszMatrix('v', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by vdw volume
675 |  | SM1_Dzv | BaryszMatrix('v', 'SM1') | 2D | spectral moment from Barysz matrix weighted by vdw volume
676 |  | VE1_Dzv | BaryszMatrix('v', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by vdw volume
677 |  | VE2_Dzv | BaryszMatrix('v', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by vdw volume
678 |  | VE3_Dzv | BaryszMatrix('v', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by vdw volume
679 |  | VR1_Dzv | BaryszMatrix('v', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by vdw volume
680 |  | VR2_Dzv | BaryszMatrix('v', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by vdw volume
681 |  | VR3_Dzv | BaryszMatrix('v', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by vdw volume
682 |  | SpAbs_Dzse | BaryszMatrix('se', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by sanderson EN
683 |  | SpMax_Dzse | BaryszMatrix('se', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by sanderson EN
684 |  | SpDiam_Dzse | BaryszMatrix('se', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by sanderson EN
685 |  | SpAD_Dzse | BaryszMatrix('se', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by sanderson EN
686 |  | SpMAD_Dzse | BaryszMatrix('se', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by sanderson EN
687 |  | LogEE_Dzse | BaryszMatrix('se', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by sanderson EN
688 |  | SM1_Dzse | BaryszMatrix('se', 'SM1') | 2D | spectral moment from Barysz matrix weighted by sanderson EN
689 |  | VE1_Dzse | BaryszMatrix('se', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by sanderson EN
690 |  | VE2_Dzse | BaryszMatrix('se', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by sanderson EN
691 |  | VE3_Dzse | BaryszMatrix('se', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by sanderson EN
692 |  | VR1_Dzse | BaryszMatrix('se', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by sanderson EN
693 |  | VR2_Dzse | BaryszMatrix('se', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by sanderson EN
694 |  | VR3_Dzse | BaryszMatrix('se', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by sanderson EN
695 |  | SpAbs_Dzpe | BaryszMatrix('pe', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by pauling EN
696 |  | SpMax_Dzpe | BaryszMatrix('pe', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by pauling EN
697 |  | SpDiam_Dzpe | BaryszMatrix('pe', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by pauling EN
698 |  | SpAD_Dzpe | BaryszMatrix('pe', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by pauling EN
699 |  | SpMAD_Dzpe | BaryszMatrix('pe', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by pauling EN
700 |  | LogEE_Dzpe | BaryszMatrix('pe', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by pauling EN
701 |  | SM1_Dzpe | BaryszMatrix('pe', 'SM1') | 2D | spectral moment from Barysz matrix weighted by pauling EN
702 |  | VE1_Dzpe | BaryszMatrix('pe', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by pauling EN
703 |  | VE2_Dzpe | BaryszMatrix('pe', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by pauling EN
704 |  | VE3_Dzpe | BaryszMatrix('pe', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by pauling EN
705 |  | VR1_Dzpe | BaryszMatrix('pe', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by pauling EN
706 |  | VR2_Dzpe | BaryszMatrix('pe', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by pauling EN
707 |  | VR3_Dzpe | BaryszMatrix('pe', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by pauling EN
708 |  | SpAbs_Dzare | BaryszMatrix('are', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by allred-rocow EN
709 |  | SpMax_Dzare | BaryszMatrix('are', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by allred-rocow EN
710 |  | SpDiam_Dzare | BaryszMatrix('are', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by allred-rocow EN
711 |  | SpAD_Dzare | BaryszMatrix('are', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by allred-rocow EN
712 |  | SpMAD_Dzare | BaryszMatrix('are', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by allred-rocow EN
713 |  | LogEE_Dzare | BaryszMatrix('are', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by allred-rocow EN
714 |  | SM1_Dzare | BaryszMatrix('are', 'SM1') | 2D | spectral moment from Barysz matrix weighted by allred-rocow EN
715 |  | VE1_Dzare | BaryszMatrix('are', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by allred-rocow EN
716 |  | VE2_Dzare | BaryszMatrix('are', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by allred-rocow EN
717 |  | VE3_Dzare | BaryszMatrix('are', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by allred-rocow EN
718 |  | VR1_Dzare | BaryszMatrix('are', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by allred-rocow EN
719 |  | VR2_Dzare | BaryszMatrix('are', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by allred-rocow EN
720 |  | VR3_Dzare | BaryszMatrix('are', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by allred-rocow EN
721 |  | SpAbs_Dzp | BaryszMatrix('p', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by polarizability
722 |  | SpMax_Dzp | BaryszMatrix('p', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by polarizability
723 |  | SpDiam_Dzp | BaryszMatrix('p', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by polarizability
724 |  | SpAD_Dzp | BaryszMatrix('p', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by polarizability
725 |  | SpMAD_Dzp | BaryszMatrix('p', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by polarizability
726 |  | LogEE_Dzp | BaryszMatrix('p', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by polarizability
727 |  | SM1_Dzp | BaryszMatrix('p', 'SM1') | 2D | spectral moment from Barysz matrix weighted by polarizability
728 |  | VE1_Dzp | BaryszMatrix('p', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by polarizability
729 |  | VE2_Dzp | BaryszMatrix('p', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by polarizability
730 |  | VE3_Dzp | BaryszMatrix('p', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by polarizability
731 |  | VR1_Dzp | BaryszMatrix('p', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by polarizability
732 |  | VR2_Dzp | BaryszMatrix('p', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by polarizability
733 |  | VR3_Dzp | BaryszMatrix('p', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by polarizability
734 |  | SpAbs_Dzi | BaryszMatrix('i', 'SpAbs') | 2D | graph energy from Barysz matrix weighted by ionization potential
735 |  | SpMax_Dzi | BaryszMatrix('i', 'SpMax') | 2D | leading eigenvalue from Barysz matrix weighted by ionization potential
736 |  | SpDiam_Dzi | BaryszMatrix('i', 'SpDiam') | 2D | spectral diamiter from Barysz matrix weighted by ionization potential
737 |  | SpAD_Dzi | BaryszMatrix('i', 'SpAD') | 2D | spectral absolute diviation from Barysz matrix weighted by ionization potential
738 |  | SpMAD_Dzi | BaryszMatrix('i', 'SpMAD') | 2D | spectral mean absolute diviation from Barysz matrix weighted by ionization potential
739 |  | LogEE_Dzi | BaryszMatrix('i', 'LogEE') | 2D | Estrada-like index from Barysz matrix weighted by ionization potential
740 |  | SM1_Dzi | BaryszMatrix('i', 'SM1') | 2D | spectral moment from Barysz matrix weighted by ionization potential
741 |  | VE1_Dzi | BaryszMatrix('i', 'VE1') | 2D | coefficient sum of the last eigenvector from Barysz matrix weighted by ionization potential
742 |  | VE2_Dzi | BaryszMatrix('i', 'VE2') | 2D | average coefficient of the last eigenvector from Barysz matrix weighted by ionization potential
743 |  | VE3_Dzi | BaryszMatrix('i', 'VE3') | 2D | logarithmic coefficient sum of the last eigenvector from Barysz matrix weighted by ionization potential
744 |  | VR1_Dzi | BaryszMatrix('i', 'VR1') | 2D | Randic-like eigenvector-based index from Barysz matrix weighted by ionization potential
745 |  | VR2_Dzi | BaryszMatrix('i', 'VR2') | 2D | normalized Randic-like eigenvector-based index from Barysz matrix weighted by ionization potential
746 |  | VR3_Dzi | BaryszMatrix('i', 'VR3') | 2D | logarithmic Randic-like eigenvector-based index from Barysz matrix weighted by ionization potential
747 | BCUT | BCUTc-1h | BCUT('c', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by gasteiger charge
748 |  | BCUTc-1l | BCUT('c', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by gasteiger charge
749 |  | BCUTdv-1h | BCUT('dv', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by valence electrons
750 |  | BCUTdv-1l | BCUT('dv', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by valence electrons
751 |  | BCUTd-1h | BCUT('d', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by sigma electrons
752 |  | BCUTd-1l | BCUT('d', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by sigma electrons
753 |  | BCUTs-1h | BCUT('s', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by intrinsic state
754 |  | BCUTs-1l | BCUT('s', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by intrinsic state
755 |  | BCUTZ-1h | BCUT('Z', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by atomic number
756 |  | BCUTZ-1l | BCUT('Z', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by atomic number
757 |  | BCUTm-1h | BCUT('m', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by mass
758 |  | BCUTm-1l | BCUT('m', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by mass
759 |  | BCUTv-1h | BCUT('v', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by vdw volume
760 |  | BCUTv-1l | BCUT('v', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by vdw volume
761 |  | BCUTse-1h | BCUT('se', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by sanderson EN
762 |  | BCUTse-1l | BCUT('se', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by sanderson EN
763 |  | BCUTpe-1h | BCUT('pe', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by pauling EN
764 |  | BCUTpe-1l | BCUT('pe', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by pauling EN
765 |  | BCUTare-1h | BCUT('are', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by allred-rocow EN
766 |  | BCUTare-1l | BCUT('are', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by allred-rocow EN
767 |  | BCUTp-1h | BCUT('p', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by polarizability
768 |  | BCUTp-1l | BCUT('p', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by polarizability
769 |  | BCUTi-1h | BCUT('i', 0) | 2D | first heighest eigenvalue of Burden matrix weighted by ionization potential
770 |  | BCUTi-1l | BCUT('i', -1) | 2D | first lowest eigenvalue of Burden matrix weighted by ionization potential
771 | BertzCT | BertzCT | BertzCT() | 2D | Bertz CT
772 | BondCount | nBonds | BondCount('any', False) | 2D | number of all bonds in non-kekulized structure
773 |  | nBondsO | BondCount('heavy', False) | 2D | number of bonds connecting to heavy atom in non-kekulized structure
774 |  | nBondsS | BondCount('single', False) | 2D | number of single bonds in non-kekulized structure
775 |  | nBondsD | BondCount('double', False) | 2D | number of double bonds in non-kekulized structure
776 |  | nBondsT | BondCount('triple', False) | 2D | number of triple bonds in non-kekulized structure
777 |  | nBondsA | BondCount('aromatic', False) | 2D | number of aromatic bonds in non-kekulized structure
778 |  | nBondsM | BondCount('multiple', False) | 2D | number of multiple bonds in non-kekulized structure
779 |  | nBondsKS | BondCount('single', True) | 2D | number of single bonds in kekulized structure
780 |  | nBondsKD | BondCount('double', True) | 2D | number of double bonds in kekulized structure
781 | CarbonTypes | C1SP1 | CarbonTypes(1, 1) | 2D | SP carbon bound to 1 other carbon
782 |  | C2SP1 | CarbonTypes(2, 1) | 2D | SP carbon bound to 2 other carbons
783 |  | C1SP2 | CarbonTypes(1, 2) | 2D | SP2 carbon bound to 1 other carbon
784 |  | C2SP2 | CarbonTypes(2, 2) | 2D | SP2 carbon bound to 2 other carbons
785 |  | C3SP2 | CarbonTypes(3, 2) | 2D | SP2 carbon bound to 3 other carbons
786 |  | C1SP3 | CarbonTypes(1, 3) | 2D | SP3 carbon bound to 1 other carbon
787 |  | C2SP3 | CarbonTypes(2, 3) | 2D | SP3 carbon bound to 2 other carbons
788 |  | C3SP3 | CarbonTypes(3, 3) | 2D | SP3 carbon bound to 3 other carbons
789 |  | C4SP3 | CarbonTypes(4, 3) | 2D | SP3 carbon bound to 4 other carbons
790 |  | HybRatio | HybridizationRatio() | 2D | hybridization ratio
791 | Chi | Xch-3d | Chi('chain', 3, 'd', False) | 2D | 3-ordered Chi chain weighted by sigma electrons
792 |  | Xch-4d | Chi('chain', 4, 'd', False) | 2D | 4-ordered Chi chain weighted by sigma electrons
793 |  | Xch-5d | Chi('chain', 5, 'd', False) | 2D | 5-ordered Chi chain weighted by sigma electrons
794 |  | Xch-6d | Chi('chain', 6, 'd', False) | 2D | 6-ordered Chi chain weighted by sigma electrons
795 |  | Xch-7d | Chi('chain', 7, 'd', False) | 2D | 7-ordered Chi chain weighted by sigma electrons
796 |  | Xch-3dv | Chi('chain', 3, 'dv', False) | 2D | 3-ordered Chi chain weighted by valence electrons
797 |  | Xch-4dv | Chi('chain', 4, 'dv', False) | 2D | 4-ordered Chi chain weighted by valence electrons
798 |  | Xch-5dv | Chi('chain', 5, 'dv', False) | 2D | 5-ordered Chi chain weighted by valence electrons
799 |  | Xch-6dv | Chi('chain', 6, 'dv', False) | 2D | 6-ordered Chi chain weighted by valence electrons
800 |  | Xch-7dv | Chi('chain', 7, 'dv', False) | 2D | 7-ordered Chi chain weighted by valence electrons
801 |  | Xc-3d | Chi('cluster', 3, 'd', False) | 2D | 3-ordered Chi cluster weighted by sigma electrons
802 |  | Xc-4d | Chi('cluster', 4, 'd', False) | 2D | 4-ordered Chi cluster weighted by sigma electrons
803 |  | Xc-5d | Chi('cluster', 5, 'd', False) | 2D | 5-ordered Chi cluster weighted by sigma electrons
804 |  | Xc-6d | Chi('cluster', 6, 'd', False) | 2D | 6-ordered Chi cluster weighted by sigma electrons
805 |  | Xc-3dv | Chi('cluster', 3, 'dv', False) | 2D | 3-ordered Chi cluster weighted by valence electrons
806 |  | Xc-4dv | Chi('cluster', 4, 'dv', False) | 2D | 4-ordered Chi cluster weighted by valence electrons
807 |  | Xc-5dv | Chi('cluster', 5, 'dv', False) | 2D | 5-ordered Chi cluster weighted by valence electrons
808 |  | Xc-6dv | Chi('cluster', 6, 'dv', False) | 2D | 6-ordered Chi cluster weighted by valence electrons
809 |  | Xpc-4d | Chi('path_cluster', 4, 'd', False) | 2D | 4-ordered Chi path-cluster weighted by sigma electrons
810 |  | Xpc-5d | Chi('path_cluster', 5, 'd', False) | 2D | 5-ordered Chi path-cluster weighted by sigma electrons
811 |  | Xpc-6d | Chi('path_cluster', 6, 'd', False) | 2D | 6-ordered Chi path-cluster weighted by sigma electrons
812 |  | Xpc-4dv | Chi('path_cluster', 4, 'dv', False) | 2D | 4-ordered Chi path-cluster weighted by valence electrons
813 |  | Xpc-5dv | Chi('path_cluster', 5, 'dv', False) | 2D | 5-ordered Chi path-cluster weighted by valence electrons
814 |  | Xpc-6dv | Chi('path_cluster', 6, 'dv', False) | 2D | 6-ordered Chi path-cluster weighted by valence electrons
815 |  | Xp-0d | Chi('path', 0, 'd', False) | 2D | 0-ordered Chi path weighted by sigma electrons
816 |  | Xp-1d | Chi('path', 1, 'd', False) | 2D | 1-ordered Chi path weighted by sigma electrons
817 |  | Xp-2d | Chi('path', 2, 'd', False) | 2D | 2-ordered Chi path weighted by sigma electrons
818 |  | Xp-3d | Chi('path', 3, 'd', False) | 2D | 3-ordered Chi path weighted by sigma electrons
819 |  | Xp-4d | Chi('path', 4, 'd', False) | 2D | 4-ordered Chi path weighted by sigma electrons
820 |  | Xp-5d | Chi('path', 5, 'd', False) | 2D | 5-ordered Chi path weighted by sigma electrons
821 |  | Xp-6d | Chi('path', 6, 'd', False) | 2D | 6-ordered Chi path weighted by sigma electrons
822 |  | Xp-7d | Chi('path', 7, 'd', False) | 2D | 7-ordered Chi path weighted by sigma electrons
823 |  | AXp-0d | Chi('path', 0, 'd', True) | 2D | 0-ordered averaged Chi path weighted by sigma electrons
824 |  | AXp-1d | Chi('path', 1, 'd', True) | 2D | 1-ordered averaged Chi path weighted by sigma electrons
825 |  | AXp-2d | Chi('path', 2, 'd', True) | 2D | 2-ordered averaged Chi path weighted by sigma electrons
826 |  | AXp-3d | Chi('path', 3, 'd', True) | 2D | 3-ordered averaged Chi path weighted by sigma electrons
827 |  | AXp-4d | Chi('path', 4, 'd', True) | 2D | 4-ordered averaged Chi path weighted by sigma electrons
828 |  | AXp-5d | Chi('path', 5, 'd', True) | 2D | 5-ordered averaged Chi path weighted by sigma electrons
829 |  | AXp-6d | Chi('path', 6, 'd', True) | 2D | 6-ordered averaged Chi path weighted by sigma electrons
830 |  | AXp-7d | Chi('path', 7, 'd', True) | 2D | 7-ordered averaged Chi path weighted by sigma electrons
831 |  | Xp-0dv | Chi('path', 0, 'dv', False) | 2D | 0-ordered Chi path weighted by valence electrons
832 |  | Xp-1dv | Chi('path', 1, 'dv', False) | 2D | 1-ordered Chi path weighted by valence electrons
833 |  | Xp-2dv | Chi('path', 2, 'dv', False) | 2D | 2-ordered Chi path weighted by valence electrons
834 |  | Xp-3dv | Chi('path', 3, 'dv', False) | 2D | 3-ordered Chi path weighted by valence electrons
835 |  | Xp-4dv | Chi('path', 4, 'dv', False) | 2D | 4-ordered Chi path weighted by valence electrons
836 |  | Xp-5dv | Chi('path', 5, 'dv', False) | 2D | 5-ordered Chi path weighted by valence electrons
837 |  | Xp-6dv | Chi('path', 6, 'dv', False) | 2D | 6-ordered Chi path weighted by valence electrons
838 |  | Xp-7dv | Chi('path', 7, 'dv', False) | 2D | 7-ordered Chi path weighted by valence electrons
839 |  | AXp-0dv | Chi('path', 0, 'dv', True) | 2D | 0-ordered averaged Chi path weighted by valence electrons
840 |  | AXp-1dv | Chi('path', 1, 'dv', True) | 2D | 1-ordered averaged Chi path weighted by valence electrons
841 |  | AXp-2dv | Chi('path', 2, 'dv', True) | 2D | 2-ordered averaged Chi path weighted by valence electrons
842 |  | AXp-3dv | Chi('path', 3, 'dv', True) | 2D | 3-ordered averaged Chi path weighted by valence electrons
843 |  | AXp-4dv | Chi('path', 4, 'dv', True) | 2D | 4-ordered averaged Chi path weighted by valence electrons
844 |  | AXp-5dv | Chi('path', 5, 'dv', True) | 2D | 5-ordered averaged Chi path weighted by valence electrons
845 |  | AXp-6dv | Chi('path', 6, 'dv', True) | 2D | 6-ordered averaged Chi path weighted by valence electrons
846 |  | AXp-7dv | Chi('path', 7, 'dv', True) | 2D | 7-ordered averaged Chi path weighted by valence electrons
847 | Constitutional | SZ | ConstitutionalSum('Z') | 2D | sum of constitutional weighted by atomic number
848 |  | Sm | ConstitutionalSum('m') | 2D | sum of constitutional weighted by mass
849 |  | Sv | ConstitutionalSum('v') | 2D | sum of constitutional weighted by vdw volume
850 |  | Sse | ConstitutionalSum('se') | 2D | sum of constitutional weighted by sanderson EN
851 |  | Spe | ConstitutionalSum('pe') | 2D | sum of constitutional weighted by pauling EN
852 |  | Sare | ConstitutionalSum('are') | 2D | sum of constitutional weighted by allred-rocow EN
853 |  | Sp | ConstitutionalSum('p') | 2D | sum of constitutional weighted by polarizability
854 |  | Si | ConstitutionalSum('i') | 2D | sum of constitutional weighted by ionization potential
855 |  | MZ | ConstitutionalMean('Z') | 2D | mean of constitutional weighted by atomic number
856 |  | Mm | ConstitutionalMean('m') | 2D | mean of constitutional weighted by mass
857 |  | Mv | ConstitutionalMean('v') | 2D | mean of constitutional weighted by vdw volume
858 |  | Mse | ConstitutionalMean('se') | 2D | mean of constitutional weighted by sanderson EN
859 |  | Mpe | ConstitutionalMean('pe') | 2D | mean of constitutional weighted by pauling EN
860 |  | Mare | ConstitutionalMean('are') | 2D | mean of constitutional weighted by allred-rocow EN
861 |  | Mp | ConstitutionalMean('p') | 2D | mean of constitutional weighted by polarizability
862 |  | Mi | ConstitutionalMean('i') | 2D | mean of constitutional weighted by ionization potential
863 | CPSA | PNSA1 | PNSA(1) | 3D | partial negative surface area (version 1)
864 |  | PNSA2 | PNSA(2) | 3D | partial negative surface area (version 2)
865 |  | PNSA3 | PNSA(3) | 3D | partial negative surface area (version 3)
866 |  | PNSA4 | PNSA(4) | 3D | partial negative surface area (version 4)
867 |  | PNSA5 | PNSA(5) | 3D | partial negative surface area (version 5)
868 |  | PPSA1 | PPSA(1) | 3D | partial positive surface area (version 1)
869 |  | PPSA2 | PPSA(2) | 3D | partial positive surface area (version 2)
870 |  | PPSA3 | PPSA(3) | 3D | partial positive surface area (version 3)
871 |  | PPSA4 | PPSA(4) | 3D | partial positive surface area (version 4)
872 |  | PPSA5 | PPSA(5) | 3D | partial positive surface area (version 5)
873 |  | DPSA1 | DPSA(1) | 3D | difference in charged partial surface area (version 1)
874 |  | DPSA2 | DPSA(2) | 3D | difference in charged partial surface area (version 2)
875 |  | DPSA3 | DPSA(3) | 3D | difference in charged partial surface area (version 3)
876 |  | DPSA4 | DPSA(4) | 3D | difference in charged partial surface area (version 4)
877 |  | DPSA5 | DPSA(5) | 3D | difference in charged partial surface area (version 5)
878 |  | FNSA1 | FNSA(1) | 3D | fractional charged partial negative surface area (version 1)
879 |  | FNSA2 | FNSA(2) | 3D | fractional charged partial negative surface area (version 2)
880 |  | FNSA3 | FNSA(3) | 3D | fractional charged partial negative surface area (version 3)
881 |  | FNSA4 | FNSA(4) | 3D | fractional charged partial negative surface area (version 4)
882 |  | FNSA5 | FNSA(5) | 3D | fractional charged partial negative surface area (version 5)
883 |  | FPSA1 | FPSA(1) | 3D | fractional charged partial positive surface area (version 1)
884 |  | FPSA2 | FPSA(2) | 3D | fractional charged partial positive surface area (version 2)
885 |  | FPSA3 | FPSA(3) | 3D | fractional charged partial positive surface area (version 3)
886 |  | FPSA4 | FPSA(4) | 3D | fractional charged partial positive surface area (version 4)
887 |  | FPSA5 | FPSA(5) | 3D | fractional charged partial positive surface area (version 5)
888 |  | WNSA1 | WNSA(1) | 3D | surface weighted charged partial negative surface area (version 1)
889 |  | WNSA2 | WNSA(2) | 3D | surface weighted charged partial negative surface area (version 2)
890 |  | WNSA3 | WNSA(3) | 3D | surface weighted charged partial negative surface area (version 3)
891 |  | WNSA4 | WNSA(4) | 3D | surface weighted charged partial negative surface area (version 4)
892 |  | WNSA5 | WNSA(5) | 3D | surface weighted charged partial negative surface area (version 5)
893 |  | WPSA1 | WPSA(1) | 3D | surface weighted charged partial positive surface area (version 1)
894 |  | WPSA2 | WPSA(2) | 3D | surface weighted charged partial positive surface area (version 2)
895 |  | WPSA3 | WPSA(3) | 3D | surface weighted charged partial positive surface area (version 3)
896 |  | WPSA4 | WPSA(4) | 3D | surface weighted charged partial positive surface area (version 4)
897 |  | WPSA5 | WPSA(5) | 3D | surface weighted charged partial positive surface area (version 5)
898 |  | RNCG | RNCG() | 2D | relative negative charge
899 |  | RPCG | RPCG() | 2D | relative positive charge
900 |  | RNCS | RNCS() | 3D | relative negative charge surface area
901 |  | RPCS | RPCS() | 3D | relative positive charge surface area
902 |  | TASA | TASA() | 3D | total hydrophobic surface area
903 |  | TPSA | TPSA() | 3D | total polar surface area
904 |  | RASA | RASA() | 3D | relative hydrophobic surface area
905 |  | RPSA | RPSA() | 3D | relative polar surface area
906 | DetourMatrix | SpAbs_Dt | DetourMatrix('SpAbs') | 2D | graph energy from detourn matrix
907 |  | SpMax_Dt | DetourMatrix('SpMax') | 2D | leading eigenvalue from detourn matrix
908 |  | SpDiam_Dt | DetourMatrix('SpDiam') | 2D | spectral diamiter from detourn matrix
909 |  | SpAD_Dt | DetourMatrix('SpAD') | 2D | spectral absolute diviation from detourn matrix
910 |  | SpMAD_Dt | DetourMatrix('SpMAD') | 2D | spectral mean absolute diviation from detourn matrix
911 |  | LogEE_Dt | DetourMatrix('LogEE') | 2D | Estrada-like index from detourn matrix
912 |  | SM1_Dt | DetourMatrix('SM1') | 2D | spectral moment from detourn matrix
913 |  | VE1_Dt | DetourMatrix('VE1') | 2D | coefficient sum of the last eigenvector from detourn matrix
914 |  | VE2_Dt | DetourMatrix('VE2') | 2D | average coefficient of the last eigenvector from detourn matrix
915 |  | VE3_Dt | DetourMatrix('VE3') | 2D | logarithmic coefficient sum of the last eigenvector from detourn matrix
916 |  | VR1_Dt | DetourMatrix('VR1') | 2D | Randic-like eigenvector-based index from detourn matrix
917 |  | VR2_Dt | DetourMatrix('VR2') | 2D | normalized Randic-like eigenvector-based index from detourn matrix
918 |  | VR3_Dt | DetourMatrix('VR3') | 2D | logarithmic Randic-like eigenvector-based index from detourn matrix
919 |  | DetourIndex | DetourIndex() | 2D | detour index
920 | DistanceMatrix | SpAbs_D | DistanceMatrix('SpAbs') | 2D | graph energy from distance matrix
921 |  | SpMax_D | DistanceMatrix('SpMax') | 2D | leading eigenvalue from distance matrix
922 |  | SpDiam_D | DistanceMatrix('SpDiam') | 2D | spectral diamiter from distance matrix
923 |  | SpAD_D | DistanceMatrix('SpAD') | 2D | spectral absolute diviation from distance matrix
924 |  | SpMAD_D | DistanceMatrix('SpMAD') | 2D | spectral mean absolute diviation from distance matrix
925 |  | LogEE_D | DistanceMatrix('LogEE') | 2D | Estrada-like index from distance matrix
926 |  | SM1_D | DistanceMatrix('SM1') | 2D | spectral moment from distance matrix
927 |  | VE1_D | DistanceMatrix('VE1') | 2D | coefficient sum of the last eigenvector from distance matrix
928 |  | VE2_D | DistanceMatrix('VE2') | 2D | average coefficient of the last eigenvector from distance matrix
929 |  | VE3_D | DistanceMatrix('VE3') | 2D | logarithmic coefficient sum of the last eigenvector from distance matrix
930 |  | VR1_D | DistanceMatrix('VR1') | 2D | Randic-like eigenvector-based index from distance matrix
931 |  | VR2_D | DistanceMatrix('VR2') | 2D | normalized Randic-like eigenvector-based index from distance matrix
932 |  | VR3_D | DistanceMatrix('VR3') | 2D | logarithmic Randic-like eigenvector-based index from distance matrix
933 | EccentricConnectivityIndex | ECIndex | EccentricConnectivityIndex() | 2D | eccentric connectivity index
934 | EState | NsLi | AtomTypeEState('count', 'sLi') | 2D | number of sLi
935 |  | NssBe | AtomTypeEState('count', 'ssBe') | 2D | number of ssBe
936 |  | NssssBe | AtomTypeEState('count', 'ssssBe') | 2D | number of ssssBe
937 |  | NssBH | AtomTypeEState('count', 'ssBH') | 2D | number of ssBH
938 |  | NsssB | AtomTypeEState('count', 'sssB') | 2D | number of sssB
939 |  | NssssB | AtomTypeEState('count', 'ssssB') | 2D | number of ssssB
940 |  | NsCH3 | AtomTypeEState('count', 'sCH3') | 2D | number of sCH3
941 |  | NdCH2 | AtomTypeEState('count', 'dCH2') | 2D | number of dCH2
942 |  | NssCH2 | AtomTypeEState('count', 'ssCH2') | 2D | number of ssCH2
943 |  | NtCH | AtomTypeEState('count', 'tCH') | 2D | number of tCH
944 |  | NdsCH | AtomTypeEState('count', 'dsCH') | 2D | number of dsCH
945 |  | NaaCH | AtomTypeEState('count', 'aaCH') | 2D | number of aaCH
946 |  | NsssCH | AtomTypeEState('count', 'sssCH') | 2D | number of sssCH
947 |  | NddC | AtomTypeEState('count', 'ddC') | 2D | number of ddC
948 |  | NtsC | AtomTypeEState('count', 'tsC') | 2D | number of tsC
949 |  | NdssC | AtomTypeEState('count', 'dssC') | 2D | number of dssC
950 |  | NaasC | AtomTypeEState('count', 'aasC') | 2D | number of aasC
951 |  | NaaaC | AtomTypeEState('count', 'aaaC') | 2D | number of aaaC
952 |  | NssssC | AtomTypeEState('count', 'ssssC') | 2D | number of ssssC
953 |  | NsNH3 | AtomTypeEState('count', 'sNH3') | 2D | number of sNH3
954 |  | NsNH2 | AtomTypeEState('count', 'sNH2') | 2D | number of sNH2
955 |  | NssNH2 | AtomTypeEState('count', 'ssNH2') | 2D | number of ssNH2
956 |  | NdNH | AtomTypeEState('count', 'dNH') | 2D | number of dNH
957 |  | NssNH | AtomTypeEState('count', 'ssNH') | 2D | number of ssNH
958 |  | NaaNH | AtomTypeEState('count', 'aaNH') | 2D | number of aaNH
959 |  | NtN | AtomTypeEState('count', 'tN') | 2D | number of tN
960 |  | NsssNH | AtomTypeEState('count', 'sssNH') | 2D | number of sssNH
961 |  | NdsN | AtomTypeEState('count', 'dsN') | 2D | number of dsN
962 |  | NaaN | AtomTypeEState('count', 'aaN') | 2D | number of aaN
963 |  | NsssN | AtomTypeEState('count', 'sssN') | 2D | number of sssN
964 |  | NddsN | AtomTypeEState('count', 'ddsN') | 2D | number of ddsN
965 |  | NaasN | AtomTypeEState('count', 'aasN') | 2D | number of aasN
966 |  | NssssN | AtomTypeEState('count', 'ssssN') | 2D | number of ssssN
967 |  | NsOH | AtomTypeEState('count', 'sOH') | 2D | number of sOH
968 |  | NdO | AtomTypeEState('count', 'dO') | 2D | number of dO
969 |  | NssO | AtomTypeEState('count', 'ssO') | 2D | number of ssO
970 |  | NaaO | AtomTypeEState('count', 'aaO') | 2D | number of aaO
971 |  | NsF | AtomTypeEState('count', 'sF') | 2D | number of sF
972 |  | NsSiH3 | AtomTypeEState('count', 'sSiH3') | 2D | number of sSiH3
973 |  | NssSiH2 | AtomTypeEState('count', 'ssSiH2') | 2D | number of ssSiH2
974 |  | NsssSiH | AtomTypeEState('count', 'sssSiH') | 2D | number of sssSiH
975 |  | NssssSi | AtomTypeEState('count', 'ssssSi') | 2D | number of ssssSi
976 |  | NsPH2 | AtomTypeEState('count', 'sPH2') | 2D | number of sPH2
977 |  | NssPH | AtomTypeEState('count', 'ssPH') | 2D | number of ssPH
978 |  | NsssP | AtomTypeEState('count', 'sssP') | 2D | number of sssP
979 |  | NdsssP | AtomTypeEState('count', 'dsssP') | 2D | number of dsssP
980 |  | NsssssP | AtomTypeEState('count', 'sssssP') | 2D | number of sssssP
981 |  | NsSH | AtomTypeEState('count', 'sSH') | 2D | number of sSH
982 |  | NdS | AtomTypeEState('count', 'dS') | 2D | number of dS
983 |  | NssS | AtomTypeEState('count', 'ssS') | 2D | number of ssS
984 |  | NaaS | AtomTypeEState('count', 'aaS') | 2D | number of aaS
985 |  | NdssS | AtomTypeEState('count', 'dssS') | 2D | number of dssS
986 |  | NddssS | AtomTypeEState('count', 'ddssS') | 2D | number of ddssS
987 |  | NsCl | AtomTypeEState('count', 'sCl') | 2D | number of sCl
988 |  | NsGeH3 | AtomTypeEState('count', 'sGeH3') | 2D | number of sGeH3
989 |  | NssGeH2 | AtomTypeEState('count', 'ssGeH2') | 2D | number of ssGeH2
990 |  | NsssGeH | AtomTypeEState('count', 'sssGeH') | 2D | number of sssGeH
991 |  | NssssGe | AtomTypeEState('count', 'ssssGe') | 2D | number of ssssGe
992 |  | NsAsH2 | AtomTypeEState('count', 'sAsH2') | 2D | number of sAsH2
993 |  | NssAsH | AtomTypeEState('count', 'ssAsH') | 2D | number of ssAsH
994 |  | NsssAs | AtomTypeEState('count', 'sssAs') | 2D | number of sssAs
995 |  | NsssdAs | AtomTypeEState('count', 'sssdAs') | 2D | number of sssdAs
996 |  | NsssssAs | AtomTypeEState('count', 'sssssAs') | 2D | number of sssssAs
997 |  | NsSeH | AtomTypeEState('count', 'sSeH') | 2D | number of sSeH
998 |  | NdSe | AtomTypeEState('count', 'dSe') | 2D | number of dSe
999 |  | NssSe | AtomTypeEState('count', 'ssSe') | 2D | number of ssSe
1000 |  | NaaSe | AtomTypeEState('count', 'aaSe') | 2D | number of aaSe
1001 |  | NdssSe | AtomTypeEState('count', 'dssSe') | 2D | number of dssSe
1002 |  | NddssSe | AtomTypeEState('count', 'ddssSe') | 2D | number of ddssSe
1003 |  | NsBr | AtomTypeEState('count', 'sBr') | 2D | number of sBr
1004 |  | NsSnH3 | AtomTypeEState('count', 'sSnH3') | 2D | number of sSnH3
1005 |  | NssSnH2 | AtomTypeEState('count', 'ssSnH2') | 2D | number of ssSnH2
1006 |  | NsssSnH | AtomTypeEState('count', 'sssSnH') | 2D | number of sssSnH
1007 |  | NssssSn | AtomTypeEState('count', 'ssssSn') | 2D | number of ssssSn
1008 |  | NsI | AtomTypeEState('count', 'sI') | 2D | number of sI
1009 |  | NsPbH3 | AtomTypeEState('count', 'sPbH3') | 2D | number of sPbH3
1010 |  | NssPbH2 | AtomTypeEState('count', 'ssPbH2') | 2D | number of ssPbH2
1011 |  | NsssPbH | AtomTypeEState('count', 'sssPbH') | 2D | number of sssPbH
1012 |  | NssssPb | AtomTypeEState('count', 'ssssPb') | 2D | number of ssssPb
1013 |  | SsLi | AtomTypeEState('sum', 'sLi') | 2D | sum of sLi
1014 |  | SssBe | AtomTypeEState('sum', 'ssBe') | 2D | sum of ssBe
1015 |  | SssssBe | AtomTypeEState('sum', 'ssssBe') | 2D | sum of ssssBe
1016 |  | SssBH | AtomTypeEState('sum', 'ssBH') | 2D | sum of ssBH
1017 |  | SsssB | AtomTypeEState('sum', 'sssB') | 2D | sum of sssB
1018 |  | SssssB | AtomTypeEState('sum', 'ssssB') | 2D | sum of ssssB
1019 |  | SsCH3 | AtomTypeEState('sum', 'sCH3') | 2D | sum of sCH3
1020 |  | SdCH2 | AtomTypeEState('sum', 'dCH2') | 2D | sum of dCH2
1021 |  | SssCH2 | AtomTypeEState('sum', 'ssCH2') | 2D | sum of ssCH2
1022 |  | StCH | AtomTypeEState('sum', 'tCH') | 2D | sum of tCH
1023 |  | SdsCH | AtomTypeEState('sum', 'dsCH') | 2D | sum of dsCH
1024 |  | SaaCH | AtomTypeEState('sum', 'aaCH') | 2D | sum of aaCH
1025 |  | SsssCH | AtomTypeEState('sum', 'sssCH') | 2D | sum of sssCH
1026 |  | SddC | AtomTypeEState('sum', 'ddC') | 2D | sum of ddC
1027 |  | StsC | AtomTypeEState('sum', 'tsC') | 2D | sum of tsC
1028 |  | SdssC | AtomTypeEState('sum', 'dssC') | 2D | sum of dssC
1029 |  | SaasC | AtomTypeEState('sum', 'aasC') | 2D | sum of aasC
1030 |  | SaaaC | AtomTypeEState('sum', 'aaaC') | 2D | sum of aaaC
1031 |  | SssssC | AtomTypeEState('sum', 'ssssC') | 2D | sum of ssssC
1032 |  | SsNH3 | AtomTypeEState('sum', 'sNH3') | 2D | sum of sNH3
1033 |  | SsNH2 | AtomTypeEState('sum', 'sNH2') | 2D | sum of sNH2
1034 |  | SssNH2 | AtomTypeEState('sum', 'ssNH2') | 2D | sum of ssNH2
1035 |  | SdNH | AtomTypeEState('sum', 'dNH') | 2D | sum of dNH
1036 |  | SssNH | AtomTypeEState('sum', 'ssNH') | 2D | sum of ssNH
1037 |  | SaaNH | AtomTypeEState('sum', 'aaNH') | 2D | sum of aaNH
1038 |  | StN | AtomTypeEState('sum', 'tN') | 2D | sum of tN
1039 |  | SsssNH | AtomTypeEState('sum', 'sssNH') | 2D | sum of sssNH
1040 |  | SdsN | AtomTypeEState('sum', 'dsN') | 2D | sum of dsN
1041 |  | SaaN | AtomTypeEState('sum', 'aaN') | 2D | sum of aaN
1042 |  | SsssN | AtomTypeEState('sum', 'sssN') | 2D | sum of sssN
1043 |  | SddsN | AtomTypeEState('sum', 'ddsN') | 2D | sum of ddsN
1044 |  | SaasN | AtomTypeEState('sum', 'aasN') | 2D | sum of aasN
1045 |  | SssssN | AtomTypeEState('sum', 'ssssN') | 2D | sum of ssssN
1046 |  | SsOH | AtomTypeEState('sum', 'sOH') | 2D | sum of sOH
1047 |  | SdO | AtomTypeEState('sum', 'dO') | 2D | sum of dO
1048 |  | SssO | AtomTypeEState('sum', 'ssO') | 2D | sum of ssO
1049 |  | SaaO | AtomTypeEState('sum', 'aaO') | 2D | sum of aaO
1050 |  | SsF | AtomTypeEState('sum', 'sF') | 2D | sum of sF
1051 |  | SsSiH3 | AtomTypeEState('sum', 'sSiH3') | 2D | sum of sSiH3
1052 |  | SssSiH2 | AtomTypeEState('sum', 'ssSiH2') | 2D | sum of ssSiH2
1053 |  | SsssSiH | AtomTypeEState('sum', 'sssSiH') | 2D | sum of sssSiH
1054 |  | SssssSi | AtomTypeEState('sum', 'ssssSi') | 2D | sum of ssssSi
1055 |  | SsPH2 | AtomTypeEState('sum', 'sPH2') | 2D | sum of sPH2
1056 |  | SssPH | AtomTypeEState('sum', 'ssPH') | 2D | sum of ssPH
1057 |  | SsssP | AtomTypeEState('sum', 'sssP') | 2D | sum of sssP
1058 |  | SdsssP | AtomTypeEState('sum', 'dsssP') | 2D | sum of dsssP
1059 |  | SsssssP | AtomTypeEState('sum', 'sssssP') | 2D | sum of sssssP
1060 |  | SsSH | AtomTypeEState('sum', 'sSH') | 2D | sum of sSH
1061 |  | SdS | AtomTypeEState('sum', 'dS') | 2D | sum of dS
1062 |  | SssS | AtomTypeEState('sum', 'ssS') | 2D | sum of ssS
1063 |  | SaaS | AtomTypeEState('sum', 'aaS') | 2D | sum of aaS
1064 |  | SdssS | AtomTypeEState('sum', 'dssS') | 2D | sum of dssS
1065 |  | SddssS | AtomTypeEState('sum', 'ddssS') | 2D | sum of ddssS
1066 |  | SsCl | AtomTypeEState('sum', 'sCl') | 2D | sum of sCl
1067 |  | SsGeH3 | AtomTypeEState('sum', 'sGeH3') | 2D | sum of sGeH3
1068 |  | SssGeH2 | AtomTypeEState('sum', 'ssGeH2') | 2D | sum of ssGeH2
1069 |  | SsssGeH | AtomTypeEState('sum', 'sssGeH') | 2D | sum of sssGeH
1070 |  | SssssGe | AtomTypeEState('sum', 'ssssGe') | 2D | sum of ssssGe
1071 |  | SsAsH2 | AtomTypeEState('sum', 'sAsH2') | 2D | sum of sAsH2
1072 |  | SssAsH | AtomTypeEState('sum', 'ssAsH') | 2D | sum of ssAsH
1073 |  | SsssAs | AtomTypeEState('sum', 'sssAs') | 2D | sum of sssAs
1074 |  | SsssdAs | AtomTypeEState('sum', 'sssdAs') | 2D | sum of sssdAs
1075 |  | SsssssAs | AtomTypeEState('sum', 'sssssAs') | 2D | sum of sssssAs
1076 |  | SsSeH | AtomTypeEState('sum', 'sSeH') | 2D | sum of sSeH
1077 |  | SdSe | AtomTypeEState('sum', 'dSe') | 2D | sum of dSe
1078 |  | SssSe | AtomTypeEState('sum', 'ssSe') | 2D | sum of ssSe
1079 |  | SaaSe | AtomTypeEState('sum', 'aaSe') | 2D | sum of aaSe
1080 |  | SdssSe | AtomTypeEState('sum', 'dssSe') | 2D | sum of dssSe
1081 |  | SddssSe | AtomTypeEState('sum', 'ddssSe') | 2D | sum of ddssSe
1082 |  | SsBr | AtomTypeEState('sum', 'sBr') | 2D | sum of sBr
1083 |  | SsSnH3 | AtomTypeEState('sum', 'sSnH3') | 2D | sum of sSnH3
1084 |  | SssSnH2 | AtomTypeEState('sum', 'ssSnH2') | 2D | sum of ssSnH2
1085 |  | SsssSnH | AtomTypeEState('sum', 'sssSnH') | 2D | sum of sssSnH
1086 |  | SssssSn | AtomTypeEState('sum', 'ssssSn') | 2D | sum of ssssSn
1087 |  | SsI | AtomTypeEState('sum', 'sI') | 2D | sum of sI
1088 |  | SsPbH3 | AtomTypeEState('sum', 'sPbH3') | 2D | sum of sPbH3
1089 |  | SssPbH2 | AtomTypeEState('sum', 'ssPbH2') | 2D | sum of ssPbH2
1090 |  | SsssPbH | AtomTypeEState('sum', 'sssPbH') | 2D | sum of sssPbH
1091 |  | SssssPb | AtomTypeEState('sum', 'ssssPb') | 2D | sum of ssssPb
1092 |  | MAXsLi | AtomTypeEState('max', 'sLi') | 2D | max of sLi
1093 |  | MAXssBe | AtomTypeEState('max', 'ssBe') | 2D | max of ssBe
1094 |  | MAXssssBe | AtomTypeEState('max', 'ssssBe') | 2D | max of ssssBe
1095 |  | MAXssBH | AtomTypeEState('max', 'ssBH') | 2D | max of ssBH
1096 |  | MAXsssB | AtomTypeEState('max', 'sssB') | 2D | max of sssB
1097 |  | MAXssssB | AtomTypeEState('max', 'ssssB') | 2D | max of ssssB
1098 |  | MAXsCH3 | AtomTypeEState('max', 'sCH3') | 2D | max of sCH3
1099 |  | MAXdCH2 | AtomTypeEState('max', 'dCH2') | 2D | max of dCH2
1100 |  | MAXssCH2 | AtomTypeEState('max', 'ssCH2') | 2D | max of ssCH2
1101 |  | MAXtCH | AtomTypeEState('max', 'tCH') | 2D | max of tCH
1102 |  | MAXdsCH | AtomTypeEState('max', 'dsCH') | 2D | max of dsCH
1103 |  | MAXaaCH | AtomTypeEState('max', 'aaCH') | 2D | max of aaCH
1104 |  | MAXsssCH | AtomTypeEState('max', 'sssCH') | 2D | max of sssCH
1105 |  | MAXddC | AtomTypeEState('max', 'ddC') | 2D | max of ddC
1106 |  | MAXtsC | AtomTypeEState('max', 'tsC') | 2D | max of tsC
1107 |  | MAXdssC | AtomTypeEState('max', 'dssC') | 2D | max of dssC
1108 |  | MAXaasC | AtomTypeEState('max', 'aasC') | 2D | max of aasC
1109 |  | MAXaaaC | AtomTypeEState('max', 'aaaC') | 2D | max of aaaC
1110 |  | MAXssssC | AtomTypeEState('max', 'ssssC') | 2D | max of ssssC
1111 |  | MAXsNH3 | AtomTypeEState('max', 'sNH3') | 2D | max of sNH3
1112 |  | MAXsNH2 | AtomTypeEState('max', 'sNH2') | 2D | max of sNH2
1113 |  | MAXssNH2 | AtomTypeEState('max', 'ssNH2') | 2D | max of ssNH2
1114 |  | MAXdNH | AtomTypeEState('max', 'dNH') | 2D | max of dNH
1115 |  | MAXssNH | AtomTypeEState('max', 'ssNH') | 2D | max of ssNH
1116 |  | MAXaaNH | AtomTypeEState('max', 'aaNH') | 2D | max of aaNH
1117 |  | MAXtN | AtomTypeEState('max', 'tN') | 2D | max of tN
1118 |  | MAXsssNH | AtomTypeEState('max', 'sssNH') | 2D | max of sssNH
1119 |  | MAXdsN | AtomTypeEState('max', 'dsN') | 2D | max of dsN
1120 |  | MAXaaN | AtomTypeEState('max', 'aaN') | 2D | max of aaN
1121 |  | MAXsssN | AtomTypeEState('max', 'sssN') | 2D | max of sssN
1122 |  | MAXddsN | AtomTypeEState('max', 'ddsN') | 2D | max of ddsN
1123 |  | MAXaasN | AtomTypeEState('max', 'aasN') | 2D | max of aasN
1124 |  | MAXssssN | AtomTypeEState('max', 'ssssN') | 2D | max of ssssN
1125 |  | MAXsOH | AtomTypeEState('max', 'sOH') | 2D | max of sOH
1126 |  | MAXdO | AtomTypeEState('max', 'dO') | 2D | max of dO
1127 |  | MAXssO | AtomTypeEState('max', 'ssO') | 2D | max of ssO
1128 |  | MAXaaO | AtomTypeEState('max', 'aaO') | 2D | max of aaO
1129 |  | MAXsF | AtomTypeEState('max', 'sF') | 2D | max of sF
1130 |  | MAXsSiH3 | AtomTypeEState('max', 'sSiH3') | 2D | max of sSiH3
1131 |  | MAXssSiH2 | AtomTypeEState('max', 'ssSiH2') | 2D | max of ssSiH2
1132 |  | MAXsssSiH | AtomTypeEState('max', 'sssSiH') | 2D | max of sssSiH
1133 |  | MAXssssSi | AtomTypeEState('max', 'ssssSi') | 2D | max of ssssSi
1134 |  | MAXsPH2 | AtomTypeEState('max', 'sPH2') | 2D | max of sPH2
1135 |  | MAXssPH | AtomTypeEState('max', 'ssPH') | 2D | max of ssPH
1136 |  | MAXsssP | AtomTypeEState('max', 'sssP') | 2D | max of sssP
1137 |  | MAXdsssP | AtomTypeEState('max', 'dsssP') | 2D | max of dsssP
1138 |  | MAXsssssP | AtomTypeEState('max', 'sssssP') | 2D | max of sssssP
1139 |  | MAXsSH | AtomTypeEState('max', 'sSH') | 2D | max of sSH
1140 |  | MAXdS | AtomTypeEState('max', 'dS') | 2D | max of dS
1141 |  | MAXssS | AtomTypeEState('max', 'ssS') | 2D | max of ssS
1142 |  | MAXaaS | AtomTypeEState('max', 'aaS') | 2D | max of aaS
1143 |  | MAXdssS | AtomTypeEState('max', 'dssS') | 2D | max of dssS
1144 |  | MAXddssS | AtomTypeEState('max', 'ddssS') | 2D | max of ddssS
1145 |  | MAXsCl | AtomTypeEState('max', 'sCl') | 2D | max of sCl
1146 |  | MAXsGeH3 | AtomTypeEState('max', 'sGeH3') | 2D | max of sGeH3
1147 |  | MAXssGeH2 | AtomTypeEState('max', 'ssGeH2') | 2D | max of ssGeH2
1148 |  | MAXsssGeH | AtomTypeEState('max', 'sssGeH') | 2D | max of sssGeH
1149 |  | MAXssssGe | AtomTypeEState('max', 'ssssGe') | 2D | max of ssssGe
1150 |  | MAXsAsH2 | AtomTypeEState('max', 'sAsH2') | 2D | max of sAsH2
1151 |  | MAXssAsH | AtomTypeEState('max', 'ssAsH') | 2D | max of ssAsH
1152 |  | MAXsssAs | AtomTypeEState('max', 'sssAs') | 2D | max of sssAs
1153 |  | MAXsssdAs | AtomTypeEState('max', 'sssdAs') | 2D | max of sssdAs
1154 |  | MAXsssssAs | AtomTypeEState('max', 'sssssAs') | 2D | max of sssssAs
1155 |  | MAXsSeH | AtomTypeEState('max', 'sSeH') | 2D | max of sSeH
1156 |  | MAXdSe | AtomTypeEState('max', 'dSe') | 2D | max of dSe
1157 |  | MAXssSe | AtomTypeEState('max', 'ssSe') | 2D | max of ssSe
1158 |  | MAXaaSe | AtomTypeEState('max', 'aaSe') | 2D | max of aaSe
1159 |  | MAXdssSe | AtomTypeEState('max', 'dssSe') | 2D | max of dssSe
1160 |  | MAXddssSe | AtomTypeEState('max', 'ddssSe') | 2D | max of ddssSe
1161 |  | MAXsBr | AtomTypeEState('max', 'sBr') | 2D | max of sBr
1162 |  | MAXsSnH3 | AtomTypeEState('max', 'sSnH3') | 2D | max of sSnH3
1163 |  | MAXssSnH2 | AtomTypeEState('max', 'ssSnH2') | 2D | max of ssSnH2
1164 |  | MAXsssSnH | AtomTypeEState('max', 'sssSnH') | 2D | max of sssSnH
1165 |  | MAXssssSn | AtomTypeEState('max', 'ssssSn') | 2D | max of ssssSn
1166 |  | MAXsI | AtomTypeEState('max', 'sI') | 2D | max of sI
1167 |  | MAXsPbH3 | AtomTypeEState('max', 'sPbH3') | 2D | max of sPbH3
1168 |  | MAXssPbH2 | AtomTypeEState('max', 'ssPbH2') | 2D | max of ssPbH2
1169 |  | MAXsssPbH | AtomTypeEState('max', 'sssPbH') | 2D | max of sssPbH
1170 |  | MAXssssPb | AtomTypeEState('max', 'ssssPb') | 2D | max of ssssPb
1171 |  | MINsLi | AtomTypeEState('min', 'sLi') | 2D | min of sLi
1172 |  | MINssBe | AtomTypeEState('min', 'ssBe') | 2D | min of ssBe
1173 |  | MINssssBe | AtomTypeEState('min', 'ssssBe') | 2D | min of ssssBe
1174 |  | MINssBH | AtomTypeEState('min', 'ssBH') | 2D | min of ssBH
1175 |  | MINsssB | AtomTypeEState('min', 'sssB') | 2D | min of sssB
1176 |  | MINssssB | AtomTypeEState('min', 'ssssB') | 2D | min of ssssB
1177 |  | MINsCH3 | AtomTypeEState('min', 'sCH3') | 2D | min of sCH3
1178 |  | MINdCH2 | AtomTypeEState('min', 'dCH2') | 2D | min of dCH2
1179 |  | MINssCH2 | AtomTypeEState('min', 'ssCH2') | 2D | min of ssCH2
1180 |  | MINtCH | AtomTypeEState('min', 'tCH') | 2D | min of tCH
1181 |  | MINdsCH | AtomTypeEState('min', 'dsCH') | 2D | min of dsCH
1182 |  | MINaaCH | AtomTypeEState('min', 'aaCH') | 2D | min of aaCH
1183 |  | MINsssCH | AtomTypeEState('min', 'sssCH') | 2D | min of sssCH
1184 |  | MINddC | AtomTypeEState('min', 'ddC') | 2D | min of ddC
1185 |  | MINtsC | AtomTypeEState('min', 'tsC') | 2D | min of tsC
1186 |  | MINdssC | AtomTypeEState('min', 'dssC') | 2D | min of dssC
1187 |  | MINaasC | AtomTypeEState('min', 'aasC') | 2D | min of aasC
1188 |  | MINaaaC | AtomTypeEState('min', 'aaaC') | 2D | min of aaaC
1189 |  | MINssssC | AtomTypeEState('min', 'ssssC') | 2D | min of ssssC
1190 |  | MINsNH3 | AtomTypeEState('min', 'sNH3') | 2D | min of sNH3
1191 |  | MINsNH2 | AtomTypeEState('min', 'sNH2') | 2D | min of sNH2
1192 |  | MINssNH2 | AtomTypeEState('min', 'ssNH2') | 2D | min of ssNH2
1193 |  | MINdNH | AtomTypeEState('min', 'dNH') | 2D | min of dNH
1194 |  | MINssNH | AtomTypeEState('min', 'ssNH') | 2D | min of ssNH
1195 |  | MINaaNH | AtomTypeEState('min', 'aaNH') | 2D | min of aaNH
1196 |  | MINtN | AtomTypeEState('min', 'tN') | 2D | min of tN
1197 |  | MINsssNH | AtomTypeEState('min', 'sssNH') | 2D | min of sssNH
1198 |  | MINdsN | AtomTypeEState('min', 'dsN') | 2D | min of dsN
1199 |  | MINaaN | AtomTypeEState('min', 'aaN') | 2D | min of aaN
1200 |  | MINsssN | AtomTypeEState('min', 'sssN') | 2D | min of sssN
1201 |  | MINddsN | AtomTypeEState('min', 'ddsN') | 2D | min of ddsN
1202 |  | MINaasN | AtomTypeEState('min', 'aasN') | 2D | min of aasN
1203 |  | MINssssN | AtomTypeEState('min', 'ssssN') | 2D | min of ssssN
1204 |  | MINsOH | AtomTypeEState('min', 'sOH') | 2D | min of sOH
1205 |  | MINdO | AtomTypeEState('min', 'dO') | 2D | min of dO
1206 |  | MINssO | AtomTypeEState('min', 'ssO') | 2D | min of ssO
1207 |  | MINaaO | AtomTypeEState('min', 'aaO') | 2D | min of aaO
1208 |  | MINsF | AtomTypeEState('min', 'sF') | 2D | min of sF
1209 |  | MINsSiH3 | AtomTypeEState('min', 'sSiH3') | 2D | min of sSiH3
1210 |  | MINssSiH2 | AtomTypeEState('min', 'ssSiH2') | 2D | min of ssSiH2
1211 |  | MINsssSiH | AtomTypeEState('min', 'sssSiH') | 2D | min of sssSiH
1212 |  | MINssssSi | AtomTypeEState('min', 'ssssSi') | 2D | min of ssssSi
1213 |  | MINsPH2 | AtomTypeEState('min', 'sPH2') | 2D | min of sPH2
1214 |  | MINssPH | AtomTypeEState('min', 'ssPH') | 2D | min of ssPH
1215 |  | MINsssP | AtomTypeEState('min', 'sssP') | 2D | min of sssP
1216 |  | MINdsssP | AtomTypeEState('min', 'dsssP') | 2D | min of dsssP
1217 |  | MINsssssP | AtomTypeEState('min', 'sssssP') | 2D | min of sssssP
1218 |  | MINsSH | AtomTypeEState('min', 'sSH') | 2D | min of sSH
1219 |  | MINdS | AtomTypeEState('min', 'dS') | 2D | min of dS
1220 |  | MINssS | AtomTypeEState('min', 'ssS') | 2D | min of ssS
1221 |  | MINaaS | AtomTypeEState('min', 'aaS') | 2D | min of aaS
1222 |  | MINdssS | AtomTypeEState('min', 'dssS') | 2D | min of dssS
1223 |  | MINddssS | AtomTypeEState('min', 'ddssS') | 2D | min of ddssS
1224 |  | MINsCl | AtomTypeEState('min', 'sCl') | 2D | min of sCl
1225 |  | MINsGeH3 | AtomTypeEState('min', 'sGeH3') | 2D | min of sGeH3
1226 |  | MINssGeH2 | AtomTypeEState('min', 'ssGeH2') | 2D | min of ssGeH2
1227 |  | MINsssGeH | AtomTypeEState('min', 'sssGeH') | 2D | min of sssGeH
1228 |  | MINssssGe | AtomTypeEState('min', 'ssssGe') | 2D | min of ssssGe
1229 |  | MINsAsH2 | AtomTypeEState('min', 'sAsH2') | 2D | min of sAsH2
1230 |  | MINssAsH | AtomTypeEState('min', 'ssAsH') | 2D | min of ssAsH
1231 |  | MINsssAs | AtomTypeEState('min', 'sssAs') | 2D | min of sssAs
1232 |  | MINsssdAs | AtomTypeEState('min', 'sssdAs') | 2D | min of sssdAs
1233 |  | MINsssssAs | AtomTypeEState('min', 'sssssAs') | 2D | min of sssssAs
1234 |  | MINsSeH | AtomTypeEState('min', 'sSeH') | 2D | min of sSeH
1235 |  | MINdSe | AtomTypeEState('min', 'dSe') | 2D | min of dSe
1236 |  | MINssSe | AtomTypeEState('min', 'ssSe') | 2D | min of ssSe
1237 |  | MINaaSe | AtomTypeEState('min', 'aaSe') | 2D | min of aaSe
1238 |  | MINdssSe | AtomTypeEState('min', 'dssSe') | 2D | min of dssSe
1239 |  | MINddssSe | AtomTypeEState('min', 'ddssSe') | 2D | min of ddssSe
1240 |  | MINsBr | AtomTypeEState('min', 'sBr') | 2D | min of sBr
1241 |  | MINsSnH3 | AtomTypeEState('min', 'sSnH3') | 2D | min of sSnH3
1242 |  | MINssSnH2 | AtomTypeEState('min', 'ssSnH2') | 2D | min of ssSnH2
1243 |  | MINsssSnH | AtomTypeEState('min', 'sssSnH') | 2D | min of sssSnH
1244 |  | MINssssSn | AtomTypeEState('min', 'ssssSn') | 2D | min of ssssSn
1245 |  | MINsI | AtomTypeEState('min', 'sI') | 2D | min of sI
1246 |  | MINsPbH3 | AtomTypeEState('min', 'sPbH3') | 2D | min of sPbH3
1247 |  | MINssPbH2 | AtomTypeEState('min', 'ssPbH2') | 2D | min of ssPbH2
1248 |  | MINsssPbH | AtomTypeEState('min', 'sssPbH') | 2D | min of sssPbH
1249 |  | MINssssPb | AtomTypeEState('min', 'ssssPb') | 2D | min of ssssPb
1250 | ExtendedTopochemicalAtom | ETA_alpha | EtaCoreCount(False, False) | 2D | ETA core count
1251 |  | AETA_alpha | EtaCoreCount(True, False) | 2D | averaged ETA core count
1252 |  | ETA_shape_p | EtaShapeIndex('p') | 2D | ETA shape index (type: p)
1253 |  | ETA_shape_y | EtaShapeIndex('y') | 2D | ETA shape index (type: y)
1254 |  | ETA_shape_x | EtaShapeIndex('x') | 2D | ETA shape index (type: x)
1255 |  | ETA_beta | EtaVEMCount('', False) | 2D | valence electron mobile count
1256 |  | AETA_beta | EtaVEMCount('', True) | 2D | averaged valence electron mobile count
1257 |  | ETA_beta_s | EtaVEMCount('s', False) | 2D | sigma contribution to valence electron mobile count
1258 |  | AETA_beta_s | EtaVEMCount('s', True) | 2D | averaged sigma contribution to valence electron mobile count
1259 |  | ETA_beta_ns | EtaVEMCount('ns', False) | 2D | nonsigma contribution to valence electron mobile count
1260 |  | AETA_beta_ns | EtaVEMCount('ns', True) | 2D | averaged nonsigma contribution to valence electron mobile count
1261 |  | ETA_beta_ns_d | EtaVEMCount('ns_d', False) | 2D | delta contribution to valence electron mobile count
1262 |  | AETA_beta_ns_d | EtaVEMCount('ns_d', True) | 2D | averaged delta contribution to valence electron mobile count
1263 |  | ETA_eta | EtaCompositeIndex(False, False, False) | 2D | ETA composite index for reference graph
1264 |  | AETA_eta | EtaCompositeIndex(False, False, True) | 2D | averaged ETA composite index for reference graph
1265 |  | ETA_eta_L | EtaCompositeIndex(False, True, False) | 2D | local ETA composite index for reference graph
1266 |  | AETA_eta_L | EtaCompositeIndex(False, True, True) | 2D | averaged local ETA composite index for reference graph
1267 |  | ETA_eta_R | EtaCompositeIndex(True, False, False) | 2D | ETA composite index for reference graph
1268 |  | AETA_eta_R | EtaCompositeIndex(True, False, True) | 2D | averaged ETA composite index for reference graph
1269 |  | ETA_eta_RL | EtaCompositeIndex(True, True, False) | 2D | local ETA composite index for reference graph
1270 |  | AETA_eta_RL | EtaCompositeIndex(True, True, True) | 2D | averaged local ETA composite index for reference graph
1271 |  | ETA_eta_F | EtaFunctionalityIndex(False, False) | 2D | ETA functionality index
1272 |  | AETA_eta_F | EtaFunctionalityIndex(False, True) | 2D | averaged ETA functionality index
1273 |  | ETA_eta_FL | EtaFunctionalityIndex(True, False) | 2D | local ETA functionality index
1274 |  | AETA_eta_FL | EtaFunctionalityIndex(True, True) | 2D | averaged local ETA functionality index
1275 |  | ETA_eta_B | EtaBranchingIndex(False, False) | 2D | ETA branching index
1276 |  | AETA_eta_B | EtaBranchingIndex(False, True) | 2D | averaged ETA branching index
1277 |  | ETA_eta_BR | EtaBranchingIndex(True, False) | 2D | ETA branching index (use ring count)
1278 |  | AETA_eta_BR | EtaBranchingIndex(True, True) | 2D | averaged ETA branching index (use ring count)
1279 |  | ETA_dAlpha_A | EtaDeltaAlpha('A') | 2D | ETA delta alpha (type: A)
1280 |  | ETA_dAlpha_B | EtaDeltaAlpha('B') | 2D | ETA delta alpha (type: B)
1281 |  | ETA_epsilon_1 | EtaEpsilon(1) | 2D | ETA epsilon (type: 1)
1282 |  | ETA_epsilon_2 | EtaEpsilon(2) | 2D | ETA epsilon (type: 2)
1283 |  | ETA_epsilon_3 | EtaEpsilon(3) | 2D | ETA epsilon (type: 3)
1284 |  | ETA_epsilon_4 | EtaEpsilon(4) | 2D | ETA epsilon (type: 4)
1285 |  | ETA_epsilon_5 | EtaEpsilon(5) | 2D | ETA epsilon (type: 5)
1286 |  | ETA_dEpsilon_A | EtaDeltaEpsilon('A') | 2D | ETA delta epsilon (type: A)
1287 |  | ETA_dEpsilon_B | EtaDeltaEpsilon('B') | 2D | ETA delta epsilon (type: B)
1288 |  | ETA_dEpsilon_C | EtaDeltaEpsilon('C') | 2D | ETA delta epsilon (type: C)
1289 |  | ETA_dEpsilon_D | EtaDeltaEpsilon('D') | 2D | ETA delta epsilon (type: D)
1290 |  | ETA_dBeta | EtaDeltaBeta(False) | 2D | ETA delta beta
1291 |  | AETA_dBeta | EtaDeltaBeta(True) | 2D | averaged ETA delta beta
1292 |  | ETA_psi_1 | EtaPsi() | 2D | ETA psi
1293 |  | ETA_dPsi_A | EtaDeltaPsi('A') | 2D | ETA delta psi (type: A)
1294 |  | ETA_dPsi_B | EtaDeltaPsi('B') | 2D | ETA delta psi (type: B)
1295 | FragmentComplexity | fragCpx | FragmentComplexity() | 2D | fragment complexity
1296 | Framework | fMF | Framework() | 2D | molecular framework ratio
1297 | GeometricalIndex | GeomDiameter | Diameter3D() | 3D | geometric diameter
1298 |  | GeomRadius | Radius3D() | 3D | geometric radius
1299 |  | GeomShapeIndex | GeometricalShapeIndex() | 3D | geometrical shape index
1300 |  | GeomPetitjeanIndex | PetitjeanIndex3D() | 3D | geometric Petitjean index
1301 | GravitationalIndex | GRAV | GravitationalIndex(True, False) | 3D | heavy atom gravitational index
1302 |  | GRAVH | GravitationalIndex(False, False) | 3D | gravitational index
1303 |  | GRAVp | GravitationalIndex(True, True) | 3D | heavy atom pair gravitational index
1304 |  | GRAVHp | GravitationalIndex(False, True) | 3D | pair gravitational index
1305 | HydrogenBond | nHBAcc | HBondAcceptor() | 2D | number of hydrogen bond acceptor
1306 |  | nHBDon | HBondDonor() | 2D | number of hydrogen bond donor
1307 | InformationContent | IC0 | InformationContent(0) | 2D | 0-ordered neighborhood information content
1308 |  | IC1 | InformationContent(1) | 2D | 1-ordered neighborhood information content
1309 |  | IC2 | InformationContent(2) | 2D | 2-ordered neighborhood information content
1310 |  | IC3 | InformationContent(3) | 2D | 3-ordered neighborhood information content
1311 |  | IC4 | InformationContent(4) | 2D | 4-ordered neighborhood information content
1312 |  | IC5 | InformationContent(5) | 2D | 5-ordered neighborhood information content
1313 |  | TIC0 | TotalIC(0) | 2D | 0-ordered neighborhood total information content
1314 |  | TIC1 | TotalIC(1) | 2D | 1-ordered neighborhood total information content
1315 |  | TIC2 | TotalIC(2) | 2D | 2-ordered neighborhood total information content
1316 |  | TIC3 | TotalIC(3) | 2D | 3-ordered neighborhood total information content
1317 |  | TIC4 | TotalIC(4) | 2D | 4-ordered neighborhood total information content
1318 |  | TIC5 | TotalIC(5) | 2D | 5-ordered neighborhood total information content
1319 |  | SIC0 | StructuralIC(0) | 2D | 0-ordered structural information content
1320 |  | SIC1 | StructuralIC(1) | 2D | 1-ordered structural information content
1321 |  | SIC2 | StructuralIC(2) | 2D | 2-ordered structural information content
1322 |  | SIC3 | StructuralIC(3) | 2D | 3-ordered structural information content
1323 |  | SIC4 | StructuralIC(4) | 2D | 4-ordered structural information content
1324 |  | SIC5 | StructuralIC(5) | 2D | 5-ordered structural information content
1325 |  | BIC0 | BondingIC(0) | 2D | 0-ordered bonding information content
1326 |  | BIC1 | BondingIC(1) | 2D | 1-ordered bonding information content
1327 |  | BIC2 | BondingIC(2) | 2D | 2-ordered bonding information content
1328 |  | BIC3 | BondingIC(3) | 2D | 3-ordered bonding information content
1329 |  | BIC4 | BondingIC(4) | 2D | 4-ordered bonding information content
1330 |  | BIC5 | BondingIC(5) | 2D | 5-ordered bonding information content
1331 |  | CIC0 | ComplementaryIC(0) | 2D | 0-ordered complementary information content
1332 |  | CIC1 | ComplementaryIC(1) | 2D | 1-ordered complementary information content
1333 |  | CIC2 | ComplementaryIC(2) | 2D | 2-ordered complementary information content
1334 |  | CIC3 | ComplementaryIC(3) | 2D | 3-ordered complementary information content
1335 |  | CIC4 | ComplementaryIC(4) | 2D | 4-ordered complementary information content
1336 |  | CIC5 | ComplementaryIC(5) | 2D | 5-ordered complementary information content
1337 |  | MIC0 | ModifiedIC(0) | 2D | 0-ordered modified information content
1338 |  | MIC1 | ModifiedIC(1) | 2D | 1-ordered modified information content
1339 |  | MIC2 | ModifiedIC(2) | 2D | 2-ordered modified information content
1340 |  | MIC3 | ModifiedIC(3) | 2D | 3-ordered modified information content
1341 |  | MIC4 | ModifiedIC(4) | 2D | 4-ordered modified information content
1342 |  | MIC5 | ModifiedIC(5) | 2D | 5-ordered modified information content
1343 |  | ZMIC0 | ZModifiedIC(0) | 2D | 0-ordered Z-modified information content
1344 |  | ZMIC1 | ZModifiedIC(1) | 2D | 1-ordered Z-modified information content
1345 |  | ZMIC2 | ZModifiedIC(2) | 2D | 2-ordered Z-modified information content
1346 |  | ZMIC3 | ZModifiedIC(3) | 2D | 3-ordered Z-modified information content
1347 |  | ZMIC4 | ZModifiedIC(4) | 2D | 4-ordered Z-modified information content
1348 |  | ZMIC5 | ZModifiedIC(5) | 2D | 5-ordered Z-modified information content
1349 | KappaShapeIndex | Kier1 | KappaShapeIndex1() | 2D | kappa shape index 1
1350 |  | Kier2 | KappaShapeIndex2() | 2D | kappa shape index 2
1351 |  | Kier3 | KappaShapeIndex3() | 2D | kappa shape index 3
1352 | Lipinski | Lipinski | Lipinski() | 2D | Lipinski rule of five
1353 |  | GhoseFilter | GhoseFilter() | 2D | Ghose filter
1354 | McGowanVolume | VMcGowan | McGowanVolume() | 2D | McGowan volume
1355 | MoeType | LabuteASA | LabuteASA() | 2D | Labute's Approximate Surface Area
1356 |  | PEOE_VSA1 | PEOE_VSA(1) | 2D | MOE Charge VSA Descriptor 1 (-inf < x < -0.30)
1357 |  | PEOE_VSA2 | PEOE_VSA(2) | 2D | MOE Charge VSA Descriptor 2 (-0.30 <= x < -0.25)
1358 |  | PEOE_VSA3 | PEOE_VSA(3) | 2D | MOE Charge VSA Descriptor 3 (-0.25 <= x < -0.20)
1359 |  | PEOE_VSA4 | PEOE_VSA(4) | 2D | MOE Charge VSA Descriptor 4 (-0.20 <= x < -0.15)
1360 |  | PEOE_VSA5 | PEOE_VSA(5) | 2D | MOE Charge VSA Descriptor 5 (-0.15 <= x < -0.10)
1361 |  | PEOE_VSA6 | PEOE_VSA(6) | 2D | MOE Charge VSA Descriptor 6 (-0.10 <= x < -0.05)
1362 |  | PEOE_VSA7 | PEOE_VSA(7) | 2D | MOE Charge VSA Descriptor 7 (-0.05 <= x <  0.00)
1363 |  | PEOE_VSA8 | PEOE_VSA(8) | 2D | MOE Charge VSA Descriptor 8 ( 0.00 <= x <  0.05)
1364 |  | PEOE_VSA9 | PEOE_VSA(9) | 2D | MOE Charge VSA Descriptor 9 ( 0.05 <= x <  0.10)
1365 |  | PEOE_VSA10 | PEOE_VSA(10) | 2D | MOE Charge VSA Descriptor 10 ( 0.10 <= x <  0.15)
1366 |  | PEOE_VSA11 | PEOE_VSA(11) | 2D | MOE Charge VSA Descriptor 11 ( 0.15 <= x <  0.20)
1367 |  | PEOE_VSA12 | PEOE_VSA(12) | 2D | MOE Charge VSA Descriptor 12 ( 0.20 <= x <  0.25)
1368 |  | PEOE_VSA13 | PEOE_VSA(13) | 2D | MOE Charge VSA Descriptor 13 ( 0.25 <= x <  0.30)
1369 |  | SMR_VSA1 | SMR_VSA(1) | 2D | MOE MR VSA Descriptor 1 (-inf < x <  1.29)
1370 |  | SMR_VSA2 | SMR_VSA(2) | 2D | MOE MR VSA Descriptor 2 ( 1.29 <= x <  1.82)
1371 |  | SMR_VSA3 | SMR_VSA(3) | 2D | MOE MR VSA Descriptor 3 ( 1.82 <= x <  2.24)
1372 |  | SMR_VSA4 | SMR_VSA(4) | 2D | MOE MR VSA Descriptor 4 ( 2.24 <= x <  2.45)
1373 |  | SMR_VSA5 | SMR_VSA(5) | 2D | MOE MR VSA Descriptor 5 ( 2.45 <= x <  2.75)
1374 |  | SMR_VSA6 | SMR_VSA(6) | 2D | MOE MR VSA Descriptor 6 ( 2.75 <= x <  3.05)
1375 |  | SMR_VSA7 | SMR_VSA(7) | 2D | MOE MR VSA Descriptor 7 ( 3.05 <= x <  3.63)
1376 |  | SMR_VSA8 | SMR_VSA(8) | 2D | MOE MR VSA Descriptor 8 ( 3.63 <= x <  3.80)
1377 |  | SMR_VSA9 | SMR_VSA(9) | 2D | MOE MR VSA Descriptor 9 ( 3.80 <= x <  4.00)
1378 |  | SlogP_VSA1 | SlogP_VSA(1) | 2D | MOE logP VSA Descriptor 1 (-inf < x < -0.40)
1379 |  | SlogP_VSA2 | SlogP_VSA(2) | 2D | MOE logP VSA Descriptor 2 (-0.40 <= x < -0.20)
1380 |  | SlogP_VSA3 | SlogP_VSA(3) | 2D | MOE logP VSA Descriptor 3 (-0.20 <= x <  0.00)
1381 |  | SlogP_VSA4 | SlogP_VSA(4) | 2D | MOE logP VSA Descriptor 4 ( 0.00 <= x <  0.10)
1382 |  | SlogP_VSA5 | SlogP_VSA(5) | 2D | MOE logP VSA Descriptor 5 ( 0.10 <= x <  0.15)
1383 |  | SlogP_VSA6 | SlogP_VSA(6) | 2D | MOE logP VSA Descriptor 6 ( 0.15 <= x <  0.20)
1384 |  | SlogP_VSA7 | SlogP_VSA(7) | 2D | MOE logP VSA Descriptor 7 ( 0.20 <= x <  0.25)
1385 |  | SlogP_VSA8 | SlogP_VSA(8) | 2D | MOE logP VSA Descriptor 8 ( 0.25 <= x <  0.30)
1386 |  | SlogP_VSA9 | SlogP_VSA(9) | 2D | MOE logP VSA Descriptor 9 ( 0.30 <= x <  0.40)
1387 |  | SlogP_VSA10 | SlogP_VSA(10) | 2D | MOE logP VSA Descriptor 10 ( 0.40 <= x <  0.50)
1388 |  | SlogP_VSA11 | SlogP_VSA(11) | 2D | MOE logP VSA Descriptor 11 ( 0.50 <= x <  0.60)
1389 |  | EState_VSA1 | EState_VSA(1) | 2D | EState VSA Descriptor 1 (-inf < x <  -0.39)
1390 |  | EState_VSA2 | EState_VSA(2) | 2D | EState VSA Descriptor 2 ( -0.39 <= x <  0.29)
1391 |  | EState_VSA3 | EState_VSA(3) | 2D | EState VSA Descriptor 3 ( 0.29 <= x <  0.72)
1392 |  | EState_VSA4 | EState_VSA(4) | 2D | EState VSA Descriptor 4 ( 0.72 <= x <  1.17)
1393 |  | EState_VSA5 | EState_VSA(5) | 2D | EState VSA Descriptor 5 ( 1.17 <= x <  1.54)
1394 |  | EState_VSA6 | EState_VSA(6) | 2D | EState VSA Descriptor 6 ( 1.54 <= x <  1.81)
1395 |  | EState_VSA7 | EState_VSA(7) | 2D | EState VSA Descriptor 7 ( 1.81 <= x <  2.05)
1396 |  | EState_VSA8 | EState_VSA(8) | 2D | EState VSA Descriptor 8 ( 2.05 <= x <  4.69)
1397 |  | EState_VSA9 | EState_VSA(9) | 2D | EState VSA Descriptor 9 ( 4.69 <= x <  9.17)
1398 |  | EState_VSA10 | EState_VSA(10) | 2D | EState VSA Descriptor 10 ( 9.17 <= x <  15.00)
1399 |  | VSA_EState1 | VSA_EState(1) | 2D | VSA EState Descriptor 1 (-inf < x <  4.78)
1400 |  | VSA_EState2 | VSA_EState(2) | 2D | VSA EState Descriptor 2 ( 4.78 <= x <  5.00)
1401 |  | VSA_EState3 | VSA_EState(3) | 2D | VSA EState Descriptor 3 ( 5.00 <= x <  5.41)
1402 |  | VSA_EState4 | VSA_EState(4) | 2D | VSA EState Descriptor 4 ( 5.41 <= x <  5.74)
1403 |  | VSA_EState5 | VSA_EState(5) | 2D | VSA EState Descriptor 5 ( 5.74 <= x <  6.00)
1404 |  | VSA_EState6 | VSA_EState(6) | 2D | VSA EState Descriptor 6 ( 6.00 <= x <  6.07)
1405 |  | VSA_EState7 | VSA_EState(7) | 2D | VSA EState Descriptor 7 ( 6.07 <= x <  6.45)
1406 |  | VSA_EState8 | VSA_EState(8) | 2D | VSA EState Descriptor 8 ( 6.45 <= x <  7.00)
1407 |  | VSA_EState9 | VSA_EState(9) | 2D | VSA EState Descriptor 9 ( 7.00 <= x <  11.00)
1408 | MolecularDistanceEdge | MDEC-11 | MolecularDistanceEdge(1, 1, 'C') | 2D | molecular distance edge between primary C and primary C
1409 |  | MDEC-12 | MolecularDistanceEdge(1, 2, 'C') | 2D | molecular distance edge between primary C and secondary C
1410 |  | MDEC-13 | MolecularDistanceEdge(1, 3, 'C') | 2D | molecular distance edge between primary C and tertiary C
1411 |  | MDEC-14 | MolecularDistanceEdge(1, 4, 'C') | 2D | molecular distance edge between primary C and quaternary C
1412 |  | MDEC-22 | MolecularDistanceEdge(2, 2, 'C') | 2D | molecular distance edge between secondary C and secondary C
1413 |  | MDEC-23 | MolecularDistanceEdge(2, 3, 'C') | 2D | molecular distance edge between secondary C and tertiary C
1414 |  | MDEC-24 | MolecularDistanceEdge(2, 4, 'C') | 2D | molecular distance edge between secondary C and quaternary C
1415 |  | MDEC-33 | MolecularDistanceEdge(3, 3, 'C') | 2D | molecular distance edge between tertiary C and tertiary C
1416 |  | MDEC-34 | MolecularDistanceEdge(3, 4, 'C') | 2D | molecular distance edge between tertiary C and quaternary C
1417 |  | MDEC-44 | MolecularDistanceEdge(4, 4, 'C') | 2D | molecular distance edge between quaternary C and quaternary C
1418 |  | MDEO-11 | MolecularDistanceEdge(1, 1, 'O') | 2D | molecular distance edge between primary O and primary O
1419 |  | MDEO-12 | MolecularDistanceEdge(1, 2, 'O') | 2D | molecular distance edge between primary O and secondary O
1420 |  | MDEO-22 | MolecularDistanceEdge(2, 2, 'O') | 2D | molecular distance edge between secondary O and secondary O
1421 |  | MDEN-11 | MolecularDistanceEdge(1, 1, 'N') | 2D | molecular distance edge between primary N and primary N
1422 |  | MDEN-12 | MolecularDistanceEdge(1, 2, 'N') | 2D | molecular distance edge between primary N and secondary N
1423 |  | MDEN-13 | MolecularDistanceEdge(1, 3, 'N') | 2D | molecular distance edge between primary N and tertiary N
1424 |  | MDEN-22 | MolecularDistanceEdge(2, 2, 'N') | 2D | molecular distance edge between secondary N and secondary N
1425 |  | MDEN-23 | MolecularDistanceEdge(2, 3, 'N') | 2D | molecular distance edge between secondary N and tertiary N
1426 |  | MDEN-33 | MolecularDistanceEdge(3, 3, 'N') | 2D | molecular distance edge between tertiary N and tertiary N
1427 | MolecularId | MID | MolecularId('any', False, 1e-10) | 2D | molecular ID
1428 |  | AMID | MolecularId('any', True, 1e-10) | 2D | averaged molecular ID
1429 |  | MID_h | MolecularId('hetero', False, 1e-10) | 2D | molecular ID on h atoms
1430 |  | AMID_h | MolecularId('hetero', True, 1e-10) | 2D | averaged molecular ID on h atoms
1431 |  | MID_C | MolecularId('C', False, 1e-10) | 2D | molecular ID on C atoms
1432 |  | AMID_C | MolecularId('C', True, 1e-10) | 2D | averaged molecular ID on C atoms
1433 |  | MID_N | MolecularId('N', False, 1e-10) | 2D | molecular ID on N atoms
1434 |  | AMID_N | MolecularId('N', True, 1e-10) | 2D | averaged molecular ID on N atoms
1435 |  | MID_O | MolecularId('O', False, 1e-10) | 2D | molecular ID on O atoms
1436 |  | AMID_O | MolecularId('O', True, 1e-10) | 2D | averaged molecular ID on O atoms
1437 |  | MID_X | MolecularId('X', False, 1e-10) | 2D | molecular ID on halogen atoms
1438 |  | AMID_X | MolecularId('X', True, 1e-10) | 2D | averaged molecular ID on halogen atoms
1439 | MomentOfInertia | MOMI-X | MomentOfInertia('X') | 3D | moment of inertia (axis = X)
1440 |  | MOMI-Y | MomentOfInertia('Y') | 3D | moment of inertia (axis = Y)
1441 |  | MOMI-Z | MomentOfInertia('Z') | 3D | moment of inertia (axis = Z)
1442 | MoRSE | Mor01 | MoRSE(None, 1) | 3D | 3D-MoRSE (distance = 1)
1443 |  | Mor02 | MoRSE(None, 2) | 3D | 3D-MoRSE (distance = 2)
1444 |  | Mor03 | MoRSE(None, 3) | 3D | 3D-MoRSE (distance = 3)
1445 |  | Mor04 | MoRSE(None, 4) | 3D | 3D-MoRSE (distance = 4)
1446 |  | Mor05 | MoRSE(None, 5) | 3D | 3D-MoRSE (distance = 5)
1447 |  | Mor06 | MoRSE(None, 6) | 3D | 3D-MoRSE (distance = 6)
1448 |  | Mor07 | MoRSE(None, 7) | 3D | 3D-MoRSE (distance = 7)
1449 |  | Mor08 | MoRSE(None, 8) | 3D | 3D-MoRSE (distance = 8)
1450 |  | Mor09 | MoRSE(None, 9) | 3D | 3D-MoRSE (distance = 9)
1451 |  | Mor10 | MoRSE(None, 10) | 3D | 3D-MoRSE (distance = 10)
1452 |  | Mor11 | MoRSE(None, 11) | 3D | 3D-MoRSE (distance = 11)
1453 |  | Mor12 | MoRSE(None, 12) | 3D | 3D-MoRSE (distance = 12)
1454 |  | Mor13 | MoRSE(None, 13) | 3D | 3D-MoRSE (distance = 13)
1455 |  | Mor14 | MoRSE(None, 14) | 3D | 3D-MoRSE (distance = 14)
1456 |  | Mor15 | MoRSE(None, 15) | 3D | 3D-MoRSE (distance = 15)
1457 |  | Mor16 | MoRSE(None, 16) | 3D | 3D-MoRSE (distance = 16)
1458 |  | Mor17 | MoRSE(None, 17) | 3D | 3D-MoRSE (distance = 17)
1459 |  | Mor18 | MoRSE(None, 18) | 3D | 3D-MoRSE (distance = 18)
1460 |  | Mor19 | MoRSE(None, 19) | 3D | 3D-MoRSE (distance = 19)
1461 |  | Mor20 | MoRSE(None, 20) | 3D | 3D-MoRSE (distance = 20)
1462 |  | Mor21 | MoRSE(None, 21) | 3D | 3D-MoRSE (distance = 21)
1463 |  | Mor22 | MoRSE(None, 22) | 3D | 3D-MoRSE (distance = 22)
1464 |  | Mor23 | MoRSE(None, 23) | 3D | 3D-MoRSE (distance = 23)
1465 |  | Mor24 | MoRSE(None, 24) | 3D | 3D-MoRSE (distance = 24)
1466 |  | Mor25 | MoRSE(None, 25) | 3D | 3D-MoRSE (distance = 25)
1467 |  | Mor26 | MoRSE(None, 26) | 3D | 3D-MoRSE (distance = 26)
1468 |  | Mor27 | MoRSE(None, 27) | 3D | 3D-MoRSE (distance = 27)
1469 |  | Mor28 | MoRSE(None, 28) | 3D | 3D-MoRSE (distance = 28)
1470 |  | Mor29 | MoRSE(None, 29) | 3D | 3D-MoRSE (distance = 29)
1471 |  | Mor30 | MoRSE(None, 30) | 3D | 3D-MoRSE (distance = 30)
1472 |  | Mor31 | MoRSE(None, 31) | 3D | 3D-MoRSE (distance = 31)
1473 |  | Mor32 | MoRSE(None, 32) | 3D | 3D-MoRSE (distance = 32)
1474 |  | Mor01m | MoRSE('m', 1) | 3D | 3D-MoRSE weighted by mass (distance = 1)
1475 |  | Mor02m | MoRSE('m', 2) | 3D | 3D-MoRSE weighted by mass (distance = 2)
1476 |  | Mor03m | MoRSE('m', 3) | 3D | 3D-MoRSE weighted by mass (distance = 3)
1477 |  | Mor04m | MoRSE('m', 4) | 3D | 3D-MoRSE weighted by mass (distance = 4)
1478 |  | Mor05m | MoRSE('m', 5) | 3D | 3D-MoRSE weighted by mass (distance = 5)
1479 |  | Mor06m | MoRSE('m', 6) | 3D | 3D-MoRSE weighted by mass (distance = 6)
1480 |  | Mor07m | MoRSE('m', 7) | 3D | 3D-MoRSE weighted by mass (distance = 7)
1481 |  | Mor08m | MoRSE('m', 8) | 3D | 3D-MoRSE weighted by mass (distance = 8)
1482 |  | Mor09m | MoRSE('m', 9) | 3D | 3D-MoRSE weighted by mass (distance = 9)
1483 |  | Mor10m | MoRSE('m', 10) | 3D | 3D-MoRSE weighted by mass (distance = 10)
1484 |  | Mor11m | MoRSE('m', 11) | 3D | 3D-MoRSE weighted by mass (distance = 11)
1485 |  | Mor12m | MoRSE('m', 12) | 3D | 3D-MoRSE weighted by mass (distance = 12)
1486 |  | Mor13m | MoRSE('m', 13) | 3D | 3D-MoRSE weighted by mass (distance = 13)
1487 |  | Mor14m | MoRSE('m', 14) | 3D | 3D-MoRSE weighted by mass (distance = 14)
1488 |  | Mor15m | MoRSE('m', 15) | 3D | 3D-MoRSE weighted by mass (distance = 15)
1489 |  | Mor16m | MoRSE('m', 16) | 3D | 3D-MoRSE weighted by mass (distance = 16)
1490 |  | Mor17m | MoRSE('m', 17) | 3D | 3D-MoRSE weighted by mass (distance = 17)
1491 |  | Mor18m | MoRSE('m', 18) | 3D | 3D-MoRSE weighted by mass (distance = 18)
1492 |  | Mor19m | MoRSE('m', 19) | 3D | 3D-MoRSE weighted by mass (distance = 19)
1493 |  | Mor20m | MoRSE('m', 20) | 3D | 3D-MoRSE weighted by mass (distance = 20)
1494 |  | Mor21m | MoRSE('m', 21) | 3D | 3D-MoRSE weighted by mass (distance = 21)
1495 |  | Mor22m | MoRSE('m', 22) | 3D | 3D-MoRSE weighted by mass (distance = 22)
1496 |  | Mor23m | MoRSE('m', 23) | 3D | 3D-MoRSE weighted by mass (distance = 23)
1497 |  | Mor24m | MoRSE('m', 24) | 3D | 3D-MoRSE weighted by mass (distance = 24)
1498 |  | Mor25m | MoRSE('m', 25) | 3D | 3D-MoRSE weighted by mass (distance = 25)
1499 |  | Mor26m | MoRSE('m', 26) | 3D | 3D-MoRSE weighted by mass (distance = 26)
1500 |  | Mor27m | MoRSE('m', 27) | 3D | 3D-MoRSE weighted by mass (distance = 27)
1501 |  | Mor28m | MoRSE('m', 28) | 3D | 3D-MoRSE weighted by mass (distance = 28)
1502 |  | Mor29m | MoRSE('m', 29) | 3D | 3D-MoRSE weighted by mass (distance = 29)
1503 |  | Mor30m | MoRSE('m', 30) | 3D | 3D-MoRSE weighted by mass (distance = 30)
1504 |  | Mor31m | MoRSE('m', 31) | 3D | 3D-MoRSE weighted by mass (distance = 31)
1505 |  | Mor32m | MoRSE('m', 32) | 3D | 3D-MoRSE weighted by mass (distance = 32)
1506 |  | Mor01v | MoRSE('v', 1) | 3D | 3D-MoRSE weighted by vdw volume (distance = 1)
1507 |  | Mor02v | MoRSE('v', 2) | 3D | 3D-MoRSE weighted by vdw volume (distance = 2)
1508 |  | Mor03v | MoRSE('v', 3) | 3D | 3D-MoRSE weighted by vdw volume (distance = 3)
1509 |  | Mor04v | MoRSE('v', 4) | 3D | 3D-MoRSE weighted by vdw volume (distance = 4)
1510 |  | Mor05v | MoRSE('v', 5) | 3D | 3D-MoRSE weighted by vdw volume (distance = 5)
1511 |  | Mor06v | MoRSE('v', 6) | 3D | 3D-MoRSE weighted by vdw volume (distance = 6)
1512 |  | Mor07v | MoRSE('v', 7) | 3D | 3D-MoRSE weighted by vdw volume (distance = 7)
1513 |  | Mor08v | MoRSE('v', 8) | 3D | 3D-MoRSE weighted by vdw volume (distance = 8)
1514 |  | Mor09v | MoRSE('v', 9) | 3D | 3D-MoRSE weighted by vdw volume (distance = 9)
1515 |  | Mor10v | MoRSE('v', 10) | 3D | 3D-MoRSE weighted by vdw volume (distance = 10)
1516 |  | Mor11v | MoRSE('v', 11) | 3D | 3D-MoRSE weighted by vdw volume (distance = 11)
1517 |  | Mor12v | MoRSE('v', 12) | 3D | 3D-MoRSE weighted by vdw volume (distance = 12)
1518 |  | Mor13v | MoRSE('v', 13) | 3D | 3D-MoRSE weighted by vdw volume (distance = 13)
1519 |  | Mor14v | MoRSE('v', 14) | 3D | 3D-MoRSE weighted by vdw volume (distance = 14)
1520 |  | Mor15v | MoRSE('v', 15) | 3D | 3D-MoRSE weighted by vdw volume (distance = 15)
1521 |  | Mor16v | MoRSE('v', 16) | 3D | 3D-MoRSE weighted by vdw volume (distance = 16)
1522 |  | Mor17v | MoRSE('v', 17) | 3D | 3D-MoRSE weighted by vdw volume (distance = 17)
1523 |  | Mor18v | MoRSE('v', 18) | 3D | 3D-MoRSE weighted by vdw volume (distance = 18)
1524 |  | Mor19v | MoRSE('v', 19) | 3D | 3D-MoRSE weighted by vdw volume (distance = 19)
1525 |  | Mor20v | MoRSE('v', 20) | 3D | 3D-MoRSE weighted by vdw volume (distance = 20)
1526 |  | Mor21v | MoRSE('v', 21) | 3D | 3D-MoRSE weighted by vdw volume (distance = 21)
1527 |  | Mor22v | MoRSE('v', 22) | 3D | 3D-MoRSE weighted by vdw volume (distance = 22)
1528 |  | Mor23v | MoRSE('v', 23) | 3D | 3D-MoRSE weighted by vdw volume (distance = 23)
1529 |  | Mor24v | MoRSE('v', 24) | 3D | 3D-MoRSE weighted by vdw volume (distance = 24)
1530 |  | Mor25v | MoRSE('v', 25) | 3D | 3D-MoRSE weighted by vdw volume (distance = 25)
1531 |  | Mor26v | MoRSE('v', 26) | 3D | 3D-MoRSE weighted by vdw volume (distance = 26)
1532 |  | Mor27v | MoRSE('v', 27) | 3D | 3D-MoRSE weighted by vdw volume (distance = 27)
1533 |  | Mor28v | MoRSE('v', 28) | 3D | 3D-MoRSE weighted by vdw volume (distance = 28)
1534 |  | Mor29v | MoRSE('v', 29) | 3D | 3D-MoRSE weighted by vdw volume (distance = 29)
1535 |  | Mor30v | MoRSE('v', 30) | 3D | 3D-MoRSE weighted by vdw volume (distance = 30)
1536 |  | Mor31v | MoRSE('v', 31) | 3D | 3D-MoRSE weighted by vdw volume (distance = 31)
1537 |  | Mor32v | MoRSE('v', 32) | 3D | 3D-MoRSE weighted by vdw volume (distance = 32)
1538 |  | Mor01se | MoRSE('se', 1) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 1)
1539 |  | Mor02se | MoRSE('se', 2) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 2)
1540 |  | Mor03se | MoRSE('se', 3) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 3)
1541 |  | Mor04se | MoRSE('se', 4) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 4)
1542 |  | Mor05se | MoRSE('se', 5) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 5)
1543 |  | Mor06se | MoRSE('se', 6) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 6)
1544 |  | Mor07se | MoRSE('se', 7) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 7)
1545 |  | Mor08se | MoRSE('se', 8) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 8)
1546 |  | Mor09se | MoRSE('se', 9) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 9)
1547 |  | Mor10se | MoRSE('se', 10) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 10)
1548 |  | Mor11se | MoRSE('se', 11) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 11)
1549 |  | Mor12se | MoRSE('se', 12) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 12)
1550 |  | Mor13se | MoRSE('se', 13) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 13)
1551 |  | Mor14se | MoRSE('se', 14) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 14)
1552 |  | Mor15se | MoRSE('se', 15) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 15)
1553 |  | Mor16se | MoRSE('se', 16) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 16)
1554 |  | Mor17se | MoRSE('se', 17) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 17)
1555 |  | Mor18se | MoRSE('se', 18) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 18)
1556 |  | Mor19se | MoRSE('se', 19) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 19)
1557 |  | Mor20se | MoRSE('se', 20) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 20)
1558 |  | Mor21se | MoRSE('se', 21) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 21)
1559 |  | Mor22se | MoRSE('se', 22) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 22)
1560 |  | Mor23se | MoRSE('se', 23) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 23)
1561 |  | Mor24se | MoRSE('se', 24) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 24)
1562 |  | Mor25se | MoRSE('se', 25) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 25)
1563 |  | Mor26se | MoRSE('se', 26) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 26)
1564 |  | Mor27se | MoRSE('se', 27) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 27)
1565 |  | Mor28se | MoRSE('se', 28) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 28)
1566 |  | Mor29se | MoRSE('se', 29) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 29)
1567 |  | Mor30se | MoRSE('se', 30) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 30)
1568 |  | Mor31se | MoRSE('se', 31) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 31)
1569 |  | Mor32se | MoRSE('se', 32) | 3D | 3D-MoRSE weighted by sanderson EN (distance = 32)
1570 |  | Mor01p | MoRSE('p', 1) | 3D | 3D-MoRSE weighted by polarizability (distance = 1)
1571 |  | Mor02p | MoRSE('p', 2) | 3D | 3D-MoRSE weighted by polarizability (distance = 2)
1572 |  | Mor03p | MoRSE('p', 3) | 3D | 3D-MoRSE weighted by polarizability (distance = 3)
1573 |  | Mor04p | MoRSE('p', 4) | 3D | 3D-MoRSE weighted by polarizability (distance = 4)
1574 |  | Mor05p | MoRSE('p', 5) | 3D | 3D-MoRSE weighted by polarizability (distance = 5)
1575 |  | Mor06p | MoRSE('p', 6) | 3D | 3D-MoRSE weighted by polarizability (distance = 6)
1576 |  | Mor07p | MoRSE('p', 7) | 3D | 3D-MoRSE weighted by polarizability (distance = 7)
1577 |  | Mor08p | MoRSE('p', 8) | 3D | 3D-MoRSE weighted by polarizability (distance = 8)
1578 |  | Mor09p | MoRSE('p', 9) | 3D | 3D-MoRSE weighted by polarizability (distance = 9)
1579 |  | Mor10p | MoRSE('p', 10) | 3D | 3D-MoRSE weighted by polarizability (distance = 10)
1580 |  | Mor11p | MoRSE('p', 11) | 3D | 3D-MoRSE weighted by polarizability (distance = 11)
1581 |  | Mor12p | MoRSE('p', 12) | 3D | 3D-MoRSE weighted by polarizability (distance = 12)
1582 |  | Mor13p | MoRSE('p', 13) | 3D | 3D-MoRSE weighted by polarizability (distance = 13)
1583 |  | Mor14p | MoRSE('p', 14) | 3D | 3D-MoRSE weighted by polarizability (distance = 14)
1584 |  | Mor15p | MoRSE('p', 15) | 3D | 3D-MoRSE weighted by polarizability (distance = 15)
1585 |  | Mor16p | MoRSE('p', 16) | 3D | 3D-MoRSE weighted by polarizability (distance = 16)
1586 |  | Mor17p | MoRSE('p', 17) | 3D | 3D-MoRSE weighted by polarizability (distance = 17)
1587 |  | Mor18p | MoRSE('p', 18) | 3D | 3D-MoRSE weighted by polarizability (distance = 18)
1588 |  | Mor19p | MoRSE('p', 19) | 3D | 3D-MoRSE weighted by polarizability (distance = 19)
1589 |  | Mor20p | MoRSE('p', 20) | 3D | 3D-MoRSE weighted by polarizability (distance = 20)
1590 |  | Mor21p | MoRSE('p', 21) | 3D | 3D-MoRSE weighted by polarizability (distance = 21)
1591 |  | Mor22p | MoRSE('p', 22) | 3D | 3D-MoRSE weighted by polarizability (distance = 22)
1592 |  | Mor23p | MoRSE('p', 23) | 3D | 3D-MoRSE weighted by polarizability (distance = 23)
1593 |  | Mor24p | MoRSE('p', 24) | 3D | 3D-MoRSE weighted by polarizability (distance = 24)
1594 |  | Mor25p | MoRSE('p', 25) | 3D | 3D-MoRSE weighted by polarizability (distance = 25)
1595 |  | Mor26p | MoRSE('p', 26) | 3D | 3D-MoRSE weighted by polarizability (distance = 26)
1596 |  | Mor27p | MoRSE('p', 27) | 3D | 3D-MoRSE weighted by polarizability (distance = 27)
1597 |  | Mor28p | MoRSE('p', 28) | 3D | 3D-MoRSE weighted by polarizability (distance = 28)
1598 |  | Mor29p | MoRSE('p', 29) | 3D | 3D-MoRSE weighted by polarizability (distance = 29)
1599 |  | Mor30p | MoRSE('p', 30) | 3D | 3D-MoRSE weighted by polarizability (distance = 30)
1600 |  | Mor31p | MoRSE('p', 31) | 3D | 3D-MoRSE weighted by polarizability (distance = 31)
1601 |  | Mor32p | MoRSE('p', 32) | 3D | 3D-MoRSE weighted by polarizability (distance = 32)
1602 | PathCount | MPC2 | PathCount(2, False, False, False) | 2D | 2-ordered path count
1603 |  | MPC3 | PathCount(3, False, False, False) | 2D | 3-ordered path count
1604 |  | MPC4 | PathCount(4, False, False, False) | 2D | 4-ordered path count
1605 |  | MPC5 | PathCount(5, False, False, False) | 2D | 5-ordered path count
1606 |  | MPC6 | PathCount(6, False, False, False) | 2D | 6-ordered path count
1607 |  | MPC7 | PathCount(7, False, False, False) | 2D | 7-ordered path count
1608 |  | MPC8 | PathCount(8, False, False, False) | 2D | 8-ordered path count
1609 |  | MPC9 | PathCount(9, False, False, False) | 2D | 9-ordered path count
1610 |  | MPC10 | PathCount(10, False, False, False) | 2D | 10-ordered path count
1611 |  | TMPC10 | PathCount(10, False, True, False) | 2D | 10-ordered total path count
1612 |  | piPC1 | PathCount(1, True, False, True) | 2D | 1-ordered pi-path count (log scale)
1613 |  | piPC2 | PathCount(2, True, False, True) | 2D | 2-ordered pi-path count (log scale)
1614 |  | piPC3 | PathCount(3, True, False, True) | 2D | 3-ordered pi-path count (log scale)
1615 |  | piPC4 | PathCount(4, True, False, True) | 2D | 4-ordered pi-path count (log scale)
1616 |  | piPC5 | PathCount(5, True, False, True) | 2D | 5-ordered pi-path count (log scale)
1617 |  | piPC6 | PathCount(6, True, False, True) | 2D | 6-ordered pi-path count (log scale)
1618 |  | piPC7 | PathCount(7, True, False, True) | 2D | 7-ordered pi-path count (log scale)
1619 |  | piPC8 | PathCount(8, True, False, True) | 2D | 8-ordered pi-path count (log scale)
1620 |  | piPC9 | PathCount(9, True, False, True) | 2D | 9-ordered pi-path count (log scale)
1621 |  | piPC10 | PathCount(10, True, False, True) | 2D | 10-ordered pi-path count (log scale)
1622 |  | TpiPC10 | PathCount(10, True, True, True) | 2D | 10-ordered total pi-path count (log scale)
1623 | Polarizability | apol | APol(False) | 2D | atomic polarizability
1624 |  | bpol | BPol(False) | 2D | bond polarizability
1625 | RingCount | nRing | RingCount(None, False, False, None, None) | 2D | ring count
1626 |  | n3Ring | RingCount(3, False, False, None, None) | 2D | 3-membered ring count
1627 |  | n4Ring | RingCount(4, False, False, None, None) | 2D | 4-membered ring count
1628 |  | n5Ring | RingCount(5, False, False, None, None) | 2D | 5-membered ring count
1629 |  | n6Ring | RingCount(6, False, False, None, None) | 2D | 6-membered ring count
1630 |  | n7Ring | RingCount(7, False, False, None, None) | 2D | 7-membered ring count
1631 |  | n8Ring | RingCount(8, False, False, None, None) | 2D | 8-membered ring count
1632 |  | n9Ring | RingCount(9, False, False, None, None) | 2D | 9-membered ring count
1633 |  | n10Ring | RingCount(10, False, False, None, None) | 2D | 10-membered ring count
1634 |  | n11Ring | RingCount(11, False, False, None, None) | 2D | 11-membered ring count
1635 |  | n12Ring | RingCount(12, False, False, None, None) | 2D | 12-membered ring count
1636 |  | nG12Ring | RingCount(12, True, False, None, None) | 2D | 12-or-greater-membered ring count
1637 |  | nHRing | RingCount(None, False, False, None, True) | 2D | hetero ring count
1638 |  | n3HRing | RingCount(3, False, False, None, True) | 2D | 3-membered hetero ring count
1639 |  | n4HRing | RingCount(4, False, False, None, True) | 2D | 4-membered hetero ring count
1640 |  | n5HRing | RingCount(5, False, False, None, True) | 2D | 5-membered hetero ring count
1641 |  | n6HRing | RingCount(6, False, False, None, True) | 2D | 6-membered hetero ring count
1642 |  | n7HRing | RingCount(7, False, False, None, True) | 2D | 7-membered hetero ring count
1643 |  | n8HRing | RingCount(8, False, False, None, True) | 2D | 8-membered hetero ring count
1644 |  | n9HRing | RingCount(9, False, False, None, True) | 2D | 9-membered hetero ring count
1645 |  | n10HRing | RingCount(10, False, False, None, True) | 2D | 10-membered hetero ring count
1646 |  | n11HRing | RingCount(11, False, False, None, True) | 2D | 11-membered hetero ring count
1647 |  | n12HRing | RingCount(12, False, False, None, True) | 2D | 12-membered hetero ring count
1648 |  | nG12HRing | RingCount(12, True, False, None, True) | 2D | 12-or-greater-membered hetero ring count
1649 |  | naRing | RingCount(None, False, False, True, None) | 2D | aromatic ring count
1650 |  | n3aRing | RingCount(3, False, False, True, None) | 2D | 3-membered aromatic ring count
1651 |  | n4aRing | RingCount(4, False, False, True, None) | 2D | 4-membered aromatic ring count
1652 |  | n5aRing | RingCount(5, False, False, True, None) | 2D | 5-membered aromatic ring count
1653 |  | n6aRing | RingCount(6, False, False, True, None) | 2D | 6-membered aromatic ring count
1654 |  | n7aRing | RingCount(7, False, False, True, None) | 2D | 7-membered aromatic ring count
1655 |  | n8aRing | RingCount(8, False, False, True, None) | 2D | 8-membered aromatic ring count
1656 |  | n9aRing | RingCount(9, False, False, True, None) | 2D | 9-membered aromatic ring count
1657 |  | n10aRing | RingCount(10, False, False, True, None) | 2D | 10-membered aromatic ring count
1658 |  | n11aRing | RingCount(11, False, False, True, None) | 2D | 11-membered aromatic ring count
1659 |  | n12aRing | RingCount(12, False, False, True, None) | 2D | 12-membered aromatic ring count
1660 |  | nG12aRing | RingCount(12, True, False, True, None) | 2D | 12-or-greater-membered aromatic ring count
1661 |  | naHRing | RingCount(None, False, False, True, True) | 2D | aromatic hetero ring count
1662 |  | n3aHRing | RingCount(3, False, False, True, True) | 2D | 3-membered aromatic hetero ring count
1663 |  | n4aHRing | RingCount(4, False, False, True, True) | 2D | 4-membered aromatic hetero ring count
1664 |  | n5aHRing | RingCount(5, False, False, True, True) | 2D | 5-membered aromatic hetero ring count
1665 |  | n6aHRing | RingCount(6, False, False, True, True) | 2D | 6-membered aromatic hetero ring count
1666 |  | n7aHRing | RingCount(7, False, False, True, True) | 2D | 7-membered aromatic hetero ring count
1667 |  | n8aHRing | RingCount(8, False, False, True, True) | 2D | 8-membered aromatic hetero ring count
1668 |  | n9aHRing | RingCount(9, False, False, True, True) | 2D | 9-membered aromatic hetero ring count
1669 |  | n10aHRing | RingCount(10, False, False, True, True) | 2D | 10-membered aromatic hetero ring count
1670 |  | n11aHRing | RingCount(11, False, False, True, True) | 2D | 11-membered aromatic hetero ring count
1671 |  | n12aHRing | RingCount(12, False, False, True, True) | 2D | 12-membered aromatic hetero ring count
1672 |  | nG12aHRing | RingCount(12, True, False, True, True) | 2D | 12-or-greater-membered aromatic hetero ring count
1673 |  | nARing | RingCount(None, False, False, False, None) | 2D | aliphatic ring count
1674 |  | n3ARing | RingCount(3, False, False, False, None) | 2D | 3-membered aliphatic ring count
1675 |  | n4ARing | RingCount(4, False, False, False, None) | 2D | 4-membered aliphatic ring count
1676 |  | n5ARing | RingCount(5, False, False, False, None) | 2D | 5-membered aliphatic ring count
1677 |  | n6ARing | RingCount(6, False, False, False, None) | 2D | 6-membered aliphatic ring count
1678 |  | n7ARing | RingCount(7, False, False, False, None) | 2D | 7-membered aliphatic ring count
1679 |  | n8ARing | RingCount(8, False, False, False, None) | 2D | 8-membered aliphatic ring count
1680 |  | n9ARing | RingCount(9, False, False, False, None) | 2D | 9-membered aliphatic ring count
1681 |  | n10ARing | RingCount(10, False, False, False, None) | 2D | 10-membered aliphatic ring count
1682 |  | n11ARing | RingCount(11, False, False, False, None) | 2D | 11-membered aliphatic ring count
1683 |  | n12ARing | RingCount(12, False, False, False, None) | 2D | 12-membered aliphatic ring count
1684 |  | nG12ARing | RingCount(12, True, False, False, None) | 2D | 12-or-greater-membered aliphatic ring count
1685 |  | nAHRing | RingCount(None, False, False, False, True) | 2D | aliphatic hetero ring count
1686 |  | n3AHRing | RingCount(3, False, False, False, True) | 2D | 3-membered aliphatic hetero ring count
1687 |  | n4AHRing | RingCount(4, False, False, False, True) | 2D | 4-membered aliphatic hetero ring count
1688 |  | n5AHRing | RingCount(5, False, False, False, True) | 2D | 5-membered aliphatic hetero ring count
1689 |  | n6AHRing | RingCount(6, False, False, False, True) | 2D | 6-membered aliphatic hetero ring count
1690 |  | n7AHRing | RingCount(7, False, False, False, True) | 2D | 7-membered aliphatic hetero ring count
1691 |  | n8AHRing | RingCount(8, False, False, False, True) | 2D | 8-membered aliphatic hetero ring count
1692 |  | n9AHRing | RingCount(9, False, False, False, True) | 2D | 9-membered aliphatic hetero ring count
1693 |  | n10AHRing | RingCount(10, False, False, False, True) | 2D | 10-membered aliphatic hetero ring count
1694 |  | n11AHRing | RingCount(11, False, False, False, True) | 2D | 11-membered aliphatic hetero ring count
1695 |  | n12AHRing | RingCount(12, False, False, False, True) | 2D | 12-membered aliphatic hetero ring count
1696 |  | nG12AHRing | RingCount(12, True, False, False, True) | 2D | 12-or-greater-membered aliphatic hetero ring count
1697 |  | nFRing | RingCount(None, False, True, None, None) | 2D | fused ring count
1698 |  | n4FRing | RingCount(4, False, True, None, None) | 2D | 4-membered fused ring count
1699 |  | n5FRing | RingCount(5, False, True, None, None) | 2D | 5-membered fused ring count
1700 |  | n6FRing | RingCount(6, False, True, None, None) | 2D | 6-membered fused ring count
1701 |  | n7FRing | RingCount(7, False, True, None, None) | 2D | 7-membered fused ring count
1702 |  | n8FRing | RingCount(8, False, True, None, None) | 2D | 8-membered fused ring count
1703 |  | n9FRing | RingCount(9, False, True, None, None) | 2D | 9-membered fused ring count
1704 |  | n10FRing | RingCount(10, False, True, None, None) | 2D | 10-membered fused ring count
1705 |  | n11FRing | RingCount(11, False, True, None, None) | 2D | 11-membered fused ring count
1706 |  | n12FRing | RingCount(12, False, True, None, None) | 2D | 12-membered fused ring count
1707 |  | nG12FRing | RingCount(12, True, True, None, None) | 2D | 12-or-greater-membered fused ring count
1708 |  | nFHRing | RingCount(None, False, True, None, True) | 2D | fused hetero ring count
1709 |  | n4FHRing | RingCount(4, False, True, None, True) | 2D | 4-membered fused hetero ring count
1710 |  | n5FHRing | RingCount(5, False, True, None, True) | 2D | 5-membered fused hetero ring count
1711 |  | n6FHRing | RingCount(6, False, True, None, True) | 2D | 6-membered fused hetero ring count
1712 |  | n7FHRing | RingCount(7, False, True, None, True) | 2D | 7-membered fused hetero ring count
1713 |  | n8FHRing | RingCount(8, False, True, None, True) | 2D | 8-membered fused hetero ring count
1714 |  | n9FHRing | RingCount(9, False, True, None, True) | 2D | 9-membered fused hetero ring count
1715 |  | n10FHRing | RingCount(10, False, True, None, True) | 2D | 10-membered fused hetero ring count
1716 |  | n11FHRing | RingCount(11, False, True, None, True) | 2D | 11-membered fused hetero ring count
1717 |  | n12FHRing | RingCount(12, False, True, None, True) | 2D | 12-membered fused hetero ring count
1718 |  | nG12FHRing | RingCount(12, True, True, None, True) | 2D | 12-or-greater-membered fused hetero ring count
1719 |  | nFaRing | RingCount(None, False, True, True, None) | 2D | aromatic fused ring count
1720 |  | n4FaRing | RingCount(4, False, True, True, None) | 2D | 4-membered aromatic fused ring count
1721 |  | n5FaRing | RingCount(5, False, True, True, None) | 2D | 5-membered aromatic fused ring count
1722 |  | n6FaRing | RingCount(6, False, True, True, None) | 2D | 6-membered aromatic fused ring count
1723 |  | n7FaRing | RingCount(7, False, True, True, None) | 2D | 7-membered aromatic fused ring count
1724 |  | n8FaRing | RingCount(8, False, True, True, None) | 2D | 8-membered aromatic fused ring count
1725 |  | n9FaRing | RingCount(9, False, True, True, None) | 2D | 9-membered aromatic fused ring count
1726 |  | n10FaRing | RingCount(10, False, True, True, None) | 2D | 10-membered aromatic fused ring count
1727 |  | n11FaRing | RingCount(11, False, True, True, None) | 2D | 11-membered aromatic fused ring count
1728 |  | n12FaRing | RingCount(12, False, True, True, None) | 2D | 12-membered aromatic fused ring count
1729 |  | nG12FaRing | RingCount(12, True, True, True, None) | 2D | 12-or-greater-membered aromatic fused ring count
1730 |  | nFaHRing | RingCount(None, False, True, True, True) | 2D | aromatic fused hetero ring count
1731 |  | n4FaHRing | RingCount(4, False, True, True, True) | 2D | 4-membered aromatic fused hetero ring count
1732 |  | n5FaHRing | RingCount(5, False, True, True, True) | 2D | 5-membered aromatic fused hetero ring count
1733 |  | n6FaHRing | RingCount(6, False, True, True, True) | 2D | 6-membered aromatic fused hetero ring count
1734 |  | n7FaHRing | RingCount(7, False, True, True, True) | 2D | 7-membered aromatic fused hetero ring count
1735 |  | n8FaHRing | RingCount(8, False, True, True, True) | 2D | 8-membered aromatic fused hetero ring count
1736 |  | n9FaHRing | RingCount(9, False, True, True, True) | 2D | 9-membered aromatic fused hetero ring count
1737 |  | n10FaHRing | RingCount(10, False, True, True, True) | 2D | 10-membered aromatic fused hetero ring count
1738 |  | n11FaHRing | RingCount(11, False, True, True, True) | 2D | 11-membered aromatic fused hetero ring count
1739 |  | n12FaHRing | RingCount(12, False, True, True, True) | 2D | 12-membered aromatic fused hetero ring count
1740 |  | nG12FaHRing | RingCount(12, True, True, True, True) | 2D | 12-or-greater-membered aromatic fused hetero ring count
1741 |  | nFARing | RingCount(None, False, True, False, None) | 2D | aliphatic fused ring count
1742 |  | n4FARing | RingCount(4, False, True, False, None) | 2D | 4-membered aliphatic fused ring count
1743 |  | n5FARing | RingCount(5, False, True, False, None) | 2D | 5-membered aliphatic fused ring count
1744 |  | n6FARing | RingCount(6, False, True, False, None) | 2D | 6-membered aliphatic fused ring count
1745 |  | n7FARing | RingCount(7, False, True, False, None) | 2D | 7-membered aliphatic fused ring count
1746 |  | n8FARing | RingCount(8, False, True, False, None) | 2D | 8-membered aliphatic fused ring count
1747 |  | n9FARing | RingCount(9, False, True, False, None) | 2D | 9-membered aliphatic fused ring count
1748 |  | n10FARing | RingCount(10, False, True, False, None) | 2D | 10-membered aliphatic fused ring count
1749 |  | n11FARing | RingCount(11, False, True, False, None) | 2D | 11-membered aliphatic fused ring count
1750 |  | n12FARing | RingCount(12, False, True, False, None) | 2D | 12-membered aliphatic fused ring count
1751 |  | nG12FARing | RingCount(12, True, True, False, None) | 2D | 12-or-greater-membered aliphatic fused ring count
1752 |  | nFAHRing | RingCount(None, False, True, False, True) | 2D | aliphatic fused hetero ring count
1753 |  | n4FAHRing | RingCount(4, False, True, False, True) | 2D | 4-membered aliphatic fused hetero ring count
1754 |  | n5FAHRing | RingCount(5, False, True, False, True) | 2D | 5-membered aliphatic fused hetero ring count
1755 |  | n6FAHRing | RingCount(6, False, True, False, True) | 2D | 6-membered aliphatic fused hetero ring count
1756 |  | n7FAHRing | RingCount(7, False, True, False, True) | 2D | 7-membered aliphatic fused hetero ring count
1757 |  | n8FAHRing | RingCount(8, False, True, False, True) | 2D | 8-membered aliphatic fused hetero ring count
1758 |  | n9FAHRing | RingCount(9, False, True, False, True) | 2D | 9-membered aliphatic fused hetero ring count
1759 |  | n10FAHRing | RingCount(10, False, True, False, True) | 2D | 10-membered aliphatic fused hetero ring count
1760 |  | n11FAHRing | RingCount(11, False, True, False, True) | 2D | 11-membered aliphatic fused hetero ring count
1761 |  | n12FAHRing | RingCount(12, False, True, False, True) | 2D | 12-membered aliphatic fused hetero ring count
1762 |  | nG12FAHRing | RingCount(12, True, True, False, True) | 2D | 12-or-greater-membered aliphatic fused hetero ring count
1763 | RotatableBond | nRot | RotatableBondsCount() | 2D | rotatable bonds count
1764 |  | RotRatio | RotatableBondsRatio() | 2D | rotatable bonds ratio
1765 | SLogP | SLogP | SLogP() | 2D | Wildman-Crippen LogP
1766 |  | SMR | SMR() | 2D | Wildman-Crippen MR
1767 | TopologicalCharge | GGI1 | TopologicalCharge('raw', 1) | 2D | 1-ordered raw topological charge
1768 |  | GGI2 | TopologicalCharge('raw', 2) | 2D | 2-ordered raw topological charge
1769 |  | GGI3 | TopologicalCharge('raw', 3) | 2D | 3-ordered raw topological charge
1770 |  | GGI4 | TopologicalCharge('raw', 4) | 2D | 4-ordered raw topological charge
1771 |  | GGI5 | TopologicalCharge('raw', 5) | 2D | 5-ordered raw topological charge
1772 |  | GGI6 | TopologicalCharge('raw', 6) | 2D | 6-ordered raw topological charge
1773 |  | GGI7 | TopologicalCharge('raw', 7) | 2D | 7-ordered raw topological charge
1774 |  | GGI8 | TopologicalCharge('raw', 8) | 2D | 8-ordered raw topological charge
1775 |  | GGI9 | TopologicalCharge('raw', 9) | 2D | 9-ordered raw topological charge
1776 |  | GGI10 | TopologicalCharge('raw', 10) | 2D | 10-ordered raw topological charge
1777 |  | JGI1 | TopologicalCharge('mean', 1) | 2D | 1-ordered mean topological charge
1778 |  | JGI2 | TopologicalCharge('mean', 2) | 2D | 2-ordered mean topological charge
1779 |  | JGI3 | TopologicalCharge('mean', 3) | 2D | 3-ordered mean topological charge
1780 |  | JGI4 | TopologicalCharge('mean', 4) | 2D | 4-ordered mean topological charge
1781 |  | JGI5 | TopologicalCharge('mean', 5) | 2D | 5-ordered mean topological charge
1782 |  | JGI6 | TopologicalCharge('mean', 6) | 2D | 6-ordered mean topological charge
1783 |  | JGI7 | TopologicalCharge('mean', 7) | 2D | 7-ordered mean topological charge
1784 |  | JGI8 | TopologicalCharge('mean', 8) | 2D | 8-ordered mean topological charge
1785 |  | JGI9 | TopologicalCharge('mean', 9) | 2D | 9-ordered mean topological charge
1786 |  | JGI10 | TopologicalCharge('mean', 10) | 2D | 10-ordered mean topological charge
1787 |  | JGT10 | TopologicalCharge('global', 10) | 2D | 10-ordered global topological charge
1788 | TopologicalIndex | Diameter | Diameter() | 2D | topological diameter
1789 |  | Radius | Radius() | 2D | topological radius
1790 |  | TopoShapeIndex | TopologicalShapeIndex() | 2D | topological shape index
1791 |  | PetitjeanIndex | PetitjeanIndex() | 2D | Petitjean index
1792 | TopoPSA | TopoPSA(NO) | TopoPSA(True) | 2D | topological polar surface area (use only nitrogen and oxygen)
1793 |  | TopoPSA | TopoPSA(False) | 2D | topological polar surface area
1794 | VdwVolumeABC | Vabc | VdwVolumeABC() | 2D | ABC van der waals volume
1795 | VertexAdjacencyInformation | VAdjMat | VertexAdjacencyInformation() | 2D | vertex adjacency information
1796 | WalkCount | MWC01 | WalkCount(1, False, False) | 2D | walk count (leg-1)
1797 |  | MWC02 | WalkCount(2, False, False) | 2D | walk count (leg-2)
1798 |  | MWC03 | WalkCount(3, False, False) | 2D | walk count (leg-3)
1799 |  | MWC04 | WalkCount(4, False, False) | 2D | walk count (leg-4)
1800 |  | MWC05 | WalkCount(5, False, False) | 2D | walk count (leg-5)
1801 |  | MWC06 | WalkCount(6, False, False) | 2D | walk count (leg-6)
1802 |  | MWC07 | WalkCount(7, False, False) | 2D | walk count (leg-7)
1803 |  | MWC08 | WalkCount(8, False, False) | 2D | walk count (leg-8)
1804 |  | MWC09 | WalkCount(9, False, False) | 2D | walk count (leg-9)
1805 |  | MWC10 | WalkCount(10, False, False) | 2D | walk count (leg-10)
1806 |  | TMWC10 | WalkCount(10, True, False) | 2D | total walk count (leg-10)
1807 |  | SRW02 | WalkCount(2, False, True) | 2D | walk count (leg-2, only self returning walk)
1808 |  | SRW03 | WalkCount(3, False, True) | 2D | walk count (leg-3, only self returning walk)
1809 |  | SRW04 | WalkCount(4, False, True) | 2D | walk count (leg-4, only self returning walk)
1810 |  | SRW05 | WalkCount(5, False, True) | 2D | walk count (leg-5, only self returning walk)
1811 |  | SRW06 | WalkCount(6, False, True) | 2D | walk count (leg-6, only self returning walk)
1812 |  | SRW07 | WalkCount(7, False, True) | 2D | walk count (leg-7, only self returning walk)
1813 |  | SRW08 | WalkCount(8, False, True) | 2D | walk count (leg-8, only self returning walk)
1814 |  | SRW09 | WalkCount(9, False, True) | 2D | walk count (leg-9, only self returning walk)
1815 |  | SRW10 | WalkCount(10, False, True) | 2D | walk count (leg-10, only self returning walk)
1816 |  | TSRW10 | WalkCount(10, True, True) | 2D | total walk count (leg-10, only self returning walk)
1817 | Weight | MW | Weight(False) | 2D | molecular weight
1818 |  | AMW | Weight(True) | 2D | averaged molecular weight
1819 | WienerIndex | WPath | WienerIndex(False) | 2D | Wiener index
1820 |  | WPol | WienerIndex(True) | 2D | Wiener polarity index
1821 | ZagrebIndex | Zagreb1 | ZagrebIndex(1, 1) | 2D | Zagreb index (version 1)
1822 |  | Zagreb2 | ZagrebIndex(2, 1) | 2D | Zagreb index (version 2)
1823 |  | mZagreb1 | ZagrebIndex(1, -1) | 2D | modified Zagreb index (version 1)
1824 |  | mZagreb2 | ZagrebIndex(2, -1) | 2D | modified Zagreb index (version 2)
