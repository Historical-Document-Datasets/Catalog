# Historical Document Datasets Catalog

Welcome to the **Historical Document Datasets Catalog** repository! This repository collects and organizes information about various document datasets. The catalog is openly maintained, and we welcome contributions from the community to expand and improve the collection. 

You can view the list of all the datasets present in this repo here 👉 [https://www.document-datasets.org/](https://www.document-datasets.org/)

## 📌 How to Contribute
You can contribute by adding new datasets to the catalog. Each dataset consists of:

- A `.bib` file containing the dataset's bibliographic reference
- A `.yaml` file containing metadata about the dataset

### 1️⃣ **Fork the Repository**
Start by forking this repository and cloning it to your local machine.

```bash
# Clone your fork
git clone https://github.com/your-username/Catalog.git
cd Catalog
```

### 2️⃣ **Create a New Dataset Folder**
Each dataset has its own folder inside the repository. The folder should be named appropriately (e.g., `Dataset_Name/`). Inside this folder, you need to create two files:

#### **Example Folder Structure:**
```
Dataset_Name /
 ├── Dataset_Name.bib
 ├── Dataset_Name.yaml
```

### 3️⃣ **Create the .bib File**
The `.bib` file contains the dataset's reference in BibTeX format. Here’s an example:

```bibtex
@inproceedings{Maarand2022Comprehensive,
	address = {Cham},
	author = {Maarand, Martin and Beyer, Yngvil and K\textbackslash{}aasen, Andre and Fosseide, Knut T. and Kermorvant, Christopher},
	booktitle = {Document {Analysis} {Systems}},
	editor = {Uchida, Seiichi and Barney, Elisa and Eglin, V{\' e}ronique},
	isbn = {978-3-031-06555-2},
	year = {2022},
	pages = {399--413},
	organization = {Springer International Publishing},
	title = {A {Comprehensive} {Comparison} of {Open}-{Source} {Libraries} for {Handwritten} {Text} {Recognition} in {Norwegian}},
}
```

### 4️⃣ **Create the .yaml File**
The `.yaml` file should contain structured metadata about the dataset. You can use [this form](https://www.document-datasets.org/contribute) to generate the correctly formatted YAML or use the following template as a guide:

```yaml
---
name: Dataset Name
statistics: X documents, Y pages, Z words
class: [Class1, Class2, Class3]
task:
  - Task1
  - Task2
language:
  - Language1
  - Language2
document_type: Description of the type of documents in the dataset
mode:
  - Color/Grayscale
resolution: Resolution details (if applicable)
format:
  - File format (e.g., JPEG, PDF)
reference: DOI or citation key from the .bib file
description: |
  A detailed description of the dataset, including its purpose, structure, and how it was created.
  You may also include references to models or methods used for processing the dataset.
```

### 5️⃣ **Submit a Pull Request (PR)**
Once you've added your dataset, commit the changes and push them to your fork:

```bash
git add Dataset_Name/
git commit -m "Added Dataset_Name dataset"
git push origin main
```

Then, go to the original repository and open a **Pull Request (PR)**. Provide a short description of your dataset and how it contributes to the catalog.

---

## 🛠 Additional Notes
- Ensure your `.yaml` and `.bib` files follow the correct format.
- Keep dataset descriptions clear and concise.
- If you need help, feel free to open an issue in the repository.

Thank you for contributing! 🚀

