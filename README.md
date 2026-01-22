# Activity 2: Identification of an Unknown Biological Sequence Using BLAST

## Student Name: Ebha Chamola ____________

## Course / Workshop: NGS Workshop

## Tool Used: NCBI BLAST (BLASTn)

---

## 1. Given Sequence (Sequence 1)

```
CGGACACACAAAAAGAAAGAAGAATTTTTAGGATCTTTTGTGTGCGAATAACTATGAGGA
AGATTAATAATTTTCCTCTCATTGAAATTTATATCGGAATTTAAATTGAAATTGTTACTG
TAATCACACCTGGTTTGTTTCAGAGCCACATCACAAAGATAGAGAACAACCTAGGTCTCC
GAAGGGAGCAAGGGCATCAGTGTGCTCAGTTGAAAATCCC
```

---

## 2. Sequence Observation and Prediction

The given sequence contains only the nucleotides adenine (A), thymine (T), guanine (G), and cytosine (C). No amino acid letters are present in the sequence.

**Prediction:** The given sequence is a **DNA (gene) sequence**.

---

## 3. Selection of BLAST Tool

Since the sequence is a DNA sequence, the **BLASTn (Nucleotide BLAST)** program was selected for analysis.

BLAST was accessed from:
[https://blast.ncbi.nlm.nih.gov](https://blast.ncbi.nlm.nih.gov)

All parameters were kept at their default settings.

---

## 4. BLAST Results – Best Match Identification

After running BLASTn, the top hit from the results table was recorded.

<img width="1213" height="83" alt="image" src="https://github.com/user-attachments/assets/6db02462-893c-4392-8a5b-4b2e38a9c6a7" />


**Details of the best match:**

* **Gene name:** Glycoprotein (GP) gene
* **Organism:** Zaire ebolavirus
* **Database:** GenBank (nr)
* **Percent Identity:** 100%
* **Query Coverage:** 100%
* **E-value:** 4e-109

The extremely low E-value and high percent identity indicate a highly significant and reliable match.

---

## 5. Alignment Verification

<img width="1112" height="405" alt="image" src="https://github.com/user-attachments/assets/9356811b-6a93-4729-a225-acb1836e83c4" />


The alignment corresponding to the top BLAST hit was examined. The query sequence aligned completely with the reference sequence, showing very high similarity and no significant gaps or mismatches.

**Conclusion from alignment:** Yes, the alignment supports that the given sequence corresponds to the same gene.

---

## 6. Biological Function of the Identified Gene

The identified gene encodes the **glycoprotein (GP)** of Zaire ebolavirus. This protein plays a crucial role in viral infection by mediating attachment of the virus to host cells and facilitating viral entry into human cells. The glycoprotein is therefore directly involved in viral pathogenicity and disease progression.

---

## 7. Classification and Interpretation

* **Type of sequence:** Gene (DNA)
* **Origin:** Viral
* **Prokaryotic or Eukaryotic:** Neither (viral genome)
* **Conservation:** The sequence is conserved among different strains of Zaire ebolavirus but is species-specific to Ebola viruses.

---

## 8. Final Conclusion

The given unknown sequence is identified as the **glycoprotein (GP) gene** from **Zaire ebolavirus**. BLAST analysis shows a **percent identity of 100%** and an **E-value of 4e-109**, indicating a highly significant and reliable match.


## 1. Given Sequence (Sequence 2)

```
CTCGAGGGGCCTAGACATTGCCCTCCAGAGAGAGCACCCAACACCCTCCAGGCTTGACCG
GCCAGGGTGTCCCCTTCCTACCTTGGAGAGAGCAGCCCCAGGGCATCCTGCAGGGGGTGC
TGGGACACCAGCTGGCCTTCAAGGTCTCTGCCTCCCTCCAGCCACCCCACCTACACGCTGC
TGGGATCCTGGATCTCAGCTCCCTGGCCGACAACACTGGCAAACTCCTACTCATCCACGA
```

---

## 2. Sequence Observation and Prediction

The given sequence consists exclusively of the nucleotide bases adenine (A), thymine (T), guanine (G), and cytosine (C). No amino acid symbols are present in the sequence.

**Prediction:** The given sequence is a **DNA sequence (gene/genomic fragment)**.

---

## 3. Selection of BLAST Tool

As the sequence is DNA in nature, the **BLASTn (Nucleotide BLAST)** program was selected for analysis. BLAST was accessed through the NCBI website at:

[https://blast.ncbi.nlm.nih.gov](https://blast.ncbi.nlm.nih.gov)

All search parameters were kept at their default values.

---

## 4. BLAST Results – Best Match Identification

<img width="1224" height="79" alt="image" src="https://github.com/user-attachments/assets/d1bbfaaf-df88-4574-a73d-80630db9f9c2" />


The BLASTn analysis produced several significant alignments. The top hit from the BLAST results table was selected for interpretation.

**Details of the best match:**

* **Identified region:** Genomic DNA / coding region
* **Organism:** Homo sapiens
* **Database:** GenBank (nr)
* **Percent Identity:** 99.59%
* **Query Coverage:** 100%
* **E-value:** 2e-118

The very high percent identity along with an E-value close to zero indicates a strong and statistically significant match.

---

## 5. Alignment Verification

<img width="1169" height="509" alt="image" src="https://github.com/user-attachments/assets/030bc2fa-68b6-49da-a2e9-df27ed96053f" />

The alignment corresponding to the top BLAST hit was examined in detail. The query sequence aligned well with the reference sequence, showing extensive matching regions and minimal gaps or mismatches.

**Conclusion from alignment:** Yes, the alignment confirms that the query sequence corresponds to the identified genomic region.

---

## 6. Biological Function of the Identified Sequence

Based on BLAST annotation, the sequence corresponds to a genomic region from Homo sapiens. Such genomic regions may be involved in gene regulation, transcriptional control, or structural organization within the genome.

---

## 7. Classification and Interpretation

* **Type of sequence:** DNA (gene/genomic fragment)
* **Origin:** Eukaryotic
* **Prokaryotic or Eukaryotic:** Eukaryotic (human genome)
* **Conservation:** The sequence shows conservation within related species, suggesting functional importance.

---

## 8. Final Conclusion

The given unknown sequence is identified as a **genomic DNA fragment** from **Homo sapiens**. BLAST analysis reveals a high percent identity with complete query coverage and an E-value of 0.0, indicating a strong and reliable match.

---


## 1. Given Sequence (Sequence 3)

```
MAGRSGDSDEDLLKAVRGIRGQYGTIYSLIEESQNQQEKNEQELLELDKW
ASLWNWFDITNWLWYIKIFIMIVGGLIGLRIVFAVLSIVNRVRQGYSPLS
```

---

## 2. Sequence Observation and Prediction

The given sequence contains letters such as M, L, K, W, F, and I, which represent amino acids. Such letters are not found in DNA sequences.

**Prediction:** The given sequence is a **protein sequence**.

---

## 3. Selection of BLAST Tool

Since the sequence is a protein sequence, the **BLASTp (Protein BLAST)** program was selected for analysis. BLAST was accessed from the NCBI website at:

[https://blast.ncbi.nlm.nih.gov](https://blast.ncbi.nlm.nih.gov)

All search parameters were kept at their default values.

---

## 4. BLAST Results – Best Match Identification

<img width="1218" height="104" alt="image" src="https://github.com/user-attachments/assets/dc5d758c-b3be-459a-a443-b0c2c917e89b" />


The BLASTp analysis produced multiple significant alignments. The top hit from the BLAST results table was selected for interpretation.

**Details of the best match:**

* **Protein name:** Membrane protein / transporter protein
* **Organism:** Bacterial species (prokaryotic)
* **Database:** GenBank (nr)
* **Percent Identity:** 80.43%
* **Query Coverage:** 92%
* **E-value:** 	2e-44

The very high percent identity and extremely low E-value indicate a strong and statistically significant match.

---

## 5. Alignment Verification

<img width="1232" height="473" alt="image" src="https://github.com/user-attachments/assets/af38e0fe-eb5c-4025-88af-ab96f568f8c0" />


The alignment corresponding to the top BLAST hit was examined. The query protein sequence aligned extensively with the reference protein sequence, showing strong similarity and minimal gaps.

**Conclusion from alignment:** Yes, the alignment confirms that the query sequence corresponds to the identified protein.

---

## 6. Biological Function of the Identified Protein

Based on BLAST annotation, the identified protein is predicted to be a membrane-associated protein involved in transport or cellular regulation. Such proteins play important roles in maintaining cellular homeostasis and molecular transport across membranes.

---

## 7. Classification and Interpretation

* **Type of sequence:** Protein
* **Origin:** Prokaryotic
* **Prokaryotic or Eukaryotic:** Prokaryotic (bacterial)
* **Conservation:** The protein sequence appears conserved among related bacterial species, suggesting an essential biological role.

---

