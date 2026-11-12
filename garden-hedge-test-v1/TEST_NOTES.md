# Pawprint hedge test 1

Based on garden-maze-v43-2/index.html. Original v43-2 and main entry page remain unchanged.

Eight exposed wall cells nearest Pryanik's starting location use the repaired Meshy hedge. The comparison button restores their original visuals. Existing camera occlusion is applied to replacement walls. Grid and collision boundaries, player/NPC logic, dog assets and animations, Monge, audio and 78% camera default are unchanged.

Asset: 8,805 triangles; 1,222,204 bytes; 2048px JPEG texture embedded. Removed 167 stretched triangles from source, added closed inner shell (512 triangles), retained outer foliage and paw geometry. Shell UVs reuse green-only regions of original texture. Texture JPEG quality 85 for web delivery. No skeleton or animation added.

Separate model.html viewer provides general, top, and side views. Manual iPhone validation still required for performance, seams, first-person clearance and comparison visibility. Paw shapes and angular leaf silhouettes are inherited limitations of the source.
