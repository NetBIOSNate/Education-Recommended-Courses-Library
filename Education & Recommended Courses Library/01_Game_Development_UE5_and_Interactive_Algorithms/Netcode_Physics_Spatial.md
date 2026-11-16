# 1D. Multiplayer Netcode, Deterministic Physics & Spatial Game Algorithms

**Area of Study:** 01\. Game Development, Unreal Engine 5 & Interactive Algorithms  
**Providers:** Gaffer on Games (Glenn Fiedler) & Red Blob Games (Amit Patel)  
**Email Digest Coverage:** August 1, 2026 – November 15, 2026

---

## 1\. Multiplayer Netcode & Networked Physics (Gaffer on Games)

### \[GAME-NET-01\] Deterministic Game Physics & Timestep Decoupling: "Fix Your Timestep\!"

* **Dates Recommended:** October 23, 2026  
* **Direct Link:** [Fix Your Timestep\! \- Gaffer on Games](https://gafferongames.com/post/fix_your_timestep/)  
* **Expected Learning Outcome:** Master semi-implicit Euler integration, accumulator-based fixed delta time loops, and state interpolation to eliminate physics stutter and simulation instability.  
* **Search Tags:** `#Netcode` `#GamePhysics` `#FixedTimestep` `#EulerIntegration` `#GafferOnGames`

### \[GAME-NET-02\] Multiplayer Netcode & Physics: Snapshot Interpolation

* **Dates Recommended:** October 28, 2026  
* **Direct Link:** [Snapshot Interpolation \- Gaffer on Games](https://gafferongames.com/post/snapshot_interpolation/)  
* **Expected Learning Outcome:** Master networking server-authoritative physics simulations, building circular snapshot jitter buffers, interpolating between past server states, and masking latency in real-time multiplayer games.  
* **Search Tags:** `#Netcode` `#SnapshotInterpolation` `#JitterBuffer` `#LatencyMasking`

### \[GAME-NET-03\] Multiplayer Netcode & Physics: State Synchronization

* **Dates Recommended:** October 29, 2026  
* **Direct Link:** [State Synchronization \- Gaffer on Games](https://gafferongames.com/post/state_synchronization/)  
* **Expected Learning Outcome:** Master server-authoritative state synchronization, delta compression, quantizing rigid body transforms, and jitter buffer management for networked multiplayer physics.  
* **Search Tags:** `#Netcode` `#StateSynchronization` `#DeltaCompression` `#ServerAuthoritative`

### \[GAME-NET-04\] Multiplayer Netcode & Physics: Deterministic Lockstep Simulation

* **Dates Recommended:** October 30, 2026  
* **Direct Link:** [Deterministic Lockstep \- Gaffer on Games](https://gafferongames.com/post/deterministic_lockstep/)  
* **Expected Learning Outcome:** Master synchronized turn-based and continuous lockstep architectures, floating-point determinism issues, managing input latency buffers, and eliminating desyncs in RTS and MOBA games.  
* **Search Tags:** `#Netcode` `#DeterministicLockstep` `#FloatingPointDeterminism` `#RTS` `#MOBA`

### \[GAME-NET-05\] Multiplayer Netcode & Physics: Snapshot Compression

* **Dates Recommended:** October 31, 2026  
* **Direct Link:** [Snapshot Compression \- Gaffer on Games](https://gafferongames.com/post/snapshot_compression/)  
* **Expected Learning Outcome:** Master bitpacking, bounding box coordinate range encoding, quantizing floating-point vectors and orientation quaternions, and drastically reducing UDP packet bandwidth for networked games.  
* **Search Tags:** `#Netcode` `#SnapshotCompression` `#Bitpacking` `#QuaternionQuantization` `#UDP`

---

## 2\. Interactive Pathfinding, Grids, Visibility & Splines (Red Blob Games)

### \[GAME-ALG-01\] Introduction to the A\* Pathfinding Algorithm

* **Dates Recommended:** November 14, 2026  
* **Direct Link:** [Introduction to A\* \- Red Blob Games](https://www.redblobgames.com/pathfinding/a-star/introduction.html)  
* **Expected Learning Outcome:** Master interactive graph search mechanics comparing Breadth-First Search, Dijkstra's Algorithm, Greedy Best-First Search, and A\* heuristics for game AI navigation.  
* **Search Tags:** `#GameAlgorithms` `#AStar` `#Pathfinding` `#Dijkstra` `#BFS` `#RedBlobGames`

### \[GAME-ALG-02\] Hexagonal Grids Geometry & Cube Coordinates

* **Dates Recommended:** November 14, 2026  
* **Direct Link:** [Hexagonal Grids \- Red Blob Games](https://www.redblobgames.com/grids/hexagons/)  
* **Expected Learning Outcome:** Master 3D cube coordinate math (\$x \+ y \+ z \= 0\$), axial/offset conversions, distance calculations, and range intersections for tactical strategy and hex-based maps.  
* **Search Tags:** `#GameAlgorithms` `#HexGrids` `#CubeCoordinates` `#AxialCoordinates` `#TacticalGames`

### \[GAME-ALG-03\] 2D Visibility & Line-of-Sight Polygon Algorithms

* **Dates Recommended:** November 15, 2026  
* **Direct Link:** [2D Visibility \- Red Blob Games](https://www.redblobgames.com/articles/visibility/)  
* **Expected Learning Outcome:** Master additive 2D visibility algorithms using angular ray-sweeping and wall-segment intersection to build fog-of-war, stealth sight cones, and 2D lighting in games.  
* **Search Tags:** `#GameAlgorithms` `#2DVisibility` `#LineOfSight` `#FogOfWar` `#StealthCones`

### \[GAME-ALG-04\] Curved Paths, Circular Arcs & Spline Continuity

* **Dates Recommended:** November 15, 2026  
* **Direct Link:** [Curved Paths \- Red Blob Games](https://www.redblobgames.com/articles/curved-paths/)  
* **Expected Learning Outcome:** Master the math behind Bezier splines, circular arcs, signed curvature, and G0/G1/G2 continuity for smooth road networks, projectile arcs, and vehicle trajectories.  
* **Search Tags:** `#GameAlgorithms` `#BezierSplines` `#CircularArcs` `#Curvature` `#Trajectories`