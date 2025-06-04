# Monkeypox-Vaccine-Design
Multi-epitope vaccine design against Monkeypox virus using reverse vaccinology

# Multi-Epitope Vaccine Design Against the Monkeypox Virus

**Author**: Dinesh Davagandhi  
**Student ID**: 012021021569  
**Course**: Bachelor’s in Bioinformatics  
**Faculty**: Health and Life Sciences  
**Lecturer**: Dr. Suresh Kumar  
**Project Due Date**: 22/12/2022

## 🧪 Overview 
This project applies reverse vaccinology and bioinformatics techniques to design a multi-epitope vaccine against the Monkeypox virus (MPXV). With the rise in global MPX cases and no clinically approved vaccines available, computational approaches provide a rapid and cost-effective strategy to design potential vaccine candidates.

## 📍 Objectives
- Identify antigenic and virulent proteins from the MPXV genome
- Predict B-cell and T-cell epitopes from selected proteins
- Design a multi-epitope vaccine construct
- Analyze immune stimulation and docking affinity with TLR4 immune receptors

## 🛠 Tools & Databases Used
- **UniProt**: Protein sequence retrieval
- **VaxiJen v2.0**: Antigenicity prediction
- **VirulentPred**: Virulence assessment
- **IEDB**: B-cell and T-cell epitope prediction
- **IFNepitope**: Interferon gamma epitope prediction
- **PatchDock & FireDock**: Molecular docking and refinement

## 🦠 Target Proteins from MPXV
1. **A33R** - Viral particle transfer protein  
2. **H3L** - Heparin-binding surface protein  
3. **M1R** - Envelope protein involved in cell entry  
4. **L1R** - Membrane-bound virion component

## 🔬 Methodology Summary
1. **Protein Retrieval**: Sequences fetched from UniProt.  
2. **Antigenicity & Virulence Analysis**: All four proteins passed thresholds for antigenicity (>0.4) and virulence.  
3. **Epitope Prediction**:
   - B-cell epitopes via Bepipred 2.0  
   - MHC Class I and II epitopes via IEDB  
   - IFN-γ epitopes via IFNepitope  
4. **Vaccine Construct Design**:
   - Overlapping B-cell, MHC-I, MHC-II, and IFN-γ epitopes selected  
   - Constructs evaluated for immunogenic response  
5. **Docking Analysis**:
   - Docked with TLR4 (PDB ID: 4G8A)  
   - FireDock used to refine docking results

## 📊 Results Summary
- **Best Protein Candidate**: MPXV M1R  
- **Docking Score**: M1R showed the lowest global binding energy (-23.79 kcal/mol) with TLR4, indicating high affinity  
- **Conclusion**: M1R-based multi-epitope vaccine is a promising candidate, pending in-vitro and in-vivo validation

## 📄 Conclusion
This in-silico study supports the potential of multi-epitope vaccines using bioinformatics tools. While promising, the predicted vaccine candidates must undergo experimental validation to assess efficacy and safety.

## 📚 References
Please refer to the `MONKEYPOX FINAL PROJECT.docx` for a comprehensive list of references and data tables used in this research.

---

> _Note: This project was submitted as part of an undergraduate major project in Bioinformatics._
