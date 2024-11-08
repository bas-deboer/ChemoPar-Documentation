Interactions
============

The `interaction` page in ChemoPar-db provides a detailed view of the molecular interactions between a specific chemokine chain and any binding partner(s) in the structure.

Interaction info page
---------------------

Each interaction page includes several key sections to assist in the exploration and analysis of chemokine-partner interactions:

1. **3D view**:
    - Displays a 3D representation of the chemokine-partner complex, highlighting interacting residues.
    - Users can interact with the structure by rotating, zooming, and focusing on specific contact points, enabling a detailed examination of the binding interface.

2. **Chemokine diagram**:
    - Displays a 2D representation of the chemokine sequence with the option to highlight interacting residues per partner.

3. **Residue interaction table**:
    - Lists all residues in the chemokine that interact with the binding partner, along with the specific type of interaction for each residue.
    - This table can be downloaded in Excel format.

4. **Interaction fingerprint (IFP) similarity search**:
    - Each chemokine-partner pair is annotated with a IFP bitstring, summarizing the contact pattern between the chemokine and partner as a bitstring.
    - This bitstring representation allows easy comparison of interaction profiles across different chemokine-partner complexes in ChemoPar-db.
    - Allows users to perform a similarity search based on the IFP, comparing the current complex to other complexes in ChemoPar-db.
    - Displays similarity scores using the Tanimoto coefficient, making it easy to identify other complexes with similar interaction patterns.

5. **Ligand interaction network (if applicable)**:
    - If the complex involves a small molecule or other ligand, an interaction network visualization is generated.
    - This network illustrates the specific contacts between the chemokine, its binding partner, and the ligand.
