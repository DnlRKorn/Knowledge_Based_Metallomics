# Knowledge_Based_Metallomics

All of our files are stored in the <i>Data</i> directory.

There are the following files:
<ul>
  <li><b>All_ROBOKOP_Pathways.csv</b>:ROBOKOP provided 127026 answers to the AOP-like queries (labelled as groups a-e) described in <b>Figure 1</b>, using metal and disease search terms described in <b>Table 1</b>. The count of co-mentioning abstracts for metal-protein, metal-disease, protein-disease, and metal-protein-disease term groups is appended to each ROBOKOP answer.</li>
    <li><b>Unique_Metal-Gene-Disease_Triplets.csv</b>:The results compiled in Table S1 were grouped to yield 2170 unique combinations of metal, gene, and disease terms, which are enumerated in this spreadsheet. The count of co-mentioning abstracts for metal-protein, metal-disease, protein-disease, and metal-protein-disease term groups is appended to each unique metal-gene-disease combination. MetalPDB identifiers are also appended to each combination, where applicable.</li>
    <li><b>List_of_MetalPDB_Protein_Metal_Complexes.xlsx</b>:Analysis of the MetalPDB database and selection of human proteins uncovered 56 PDB entries for cobalt, 1 for chromium, 1 for molybdenum, 118 for nickel and 1 for titanium. This workbook contains a PDB ID, DOI link, structure title, gene name, macromolecule name, and chain ID for the metal-binding protein chain, where applicable. Additionally, entries for copper, iron, and zinc were collected and included in Table S3, but were not used for the current study.</li>
    <li><b>Imputed_Metal-Gene_Connections.csv</b>If a metal species was connected to a particular disease in ROBOKOP, a gene was also connected to that disease, and both of these connections were supported by at least one co-mentioning abstract in PubMed, then a connection between the metal and gene was imputed. 402 imputed metal-gene connections were compiled and the count of co-mentioning abstracts was appended. 243 of the 402 imputed connections were supported by at least one co-mentioning abstract in PubMed.</li>
      <li><b>Secreted_Genes_and_Metal-Gene-Disease_Connections.csv</b>:All results in <b>Table S2</b> were cross-referenced with <b>Table S6</b> and 72 genes with secreted proteins were identified. All unique metal species and disease terms connected to the genes were concatenated along with the numbers of abstracts co-mentioning the metal or disease term with secreted gene product.</li>
    <li><b>Human_Protein_Atlas_Sectretome.csv</b>:All data about secreted proteins collected from the Human Protein Atlas is available in  Table S6. This data is also available online: https://www.proteinatlas.org/humanproteome/blood/secretome.</li>
  
  <li><b>Protein_Metal_Complex_Structures</b>: A folder containing nine CSVs of metal pdb structures for each of the following metal species: Co, Cr, Cu, Fe, Mn, Mo, Ni, Ti, Zn.</li>
</ul>

