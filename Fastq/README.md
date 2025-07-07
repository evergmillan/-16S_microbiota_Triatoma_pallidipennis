# FASTQ files — Gut microbiota of *Triatoma pallidipennis*

This folder contains raw 16S rRNA sequencing reads (paired-end FASTQ files) from gut samples of *Triatoma pallidipennis* under various experimental conditions.

## Sample code structure

Each file name follows the format:
### Condition codes

| Code     | Description                                                |
|----------|------------------------------------------------------------|
| **SAyTCn** | Wild (Silvestre) – Unfed – *T. cruzi* negative         |
| **SATCn**  | Wild – Blood-fed – *T. cruzi* negative                   |
| **SATCp**  | Wild – Blood-fed – *T. cruzi* positive                   |
| **SAyTCp** | Wild – Unfed – *T. cruzi* positive                     |
| **IAyTCn** | Insectary – Fasting – *T. cruzi* negative                |
| **IATCn**  | Insectary – Blood-fed – *T. cruzi* negative              |
| **IATCp**  | Insectary – Blood-fed – *T. cruzi* positive              |
| **IAyTCp** | Insectary – Fasting – *T. cruzi* positive                |

### Organ codes

| Code | Organ      |
|------|------------|
| **E**  | Stomach    |
| **I**  | Intestine  |
| **R**  | Rectum     |

### Read direction

| Suffix        | Meaning         |
|---------------|-----------------|
| `_R1_001.fastq.gz` | Forward read  |
| `_R2_001.fastq.gz` | Reverse read  |

---

### Example
IATCn-EA10-54_S19_L001_R1_001.fastq.gz
Breakdown:
- `IATCn`: Insectary, blood-fed, *T. cruzi* negative
- `E`: Stomach
- `A10-54`: Sample identifier
- `S19`: Sequencing sample ID
- `R1`: Forward read

---
