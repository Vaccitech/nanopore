# Super basecalling
Vaccitech in house nanopore sequencing, recalling .fast5 files with super accurate guppy.

- Open command prompt: type "command prompt" in the windows search bar.
- Open EPI2ME labs, may have to open docker first.
- Open a tutorial: Click tutorials in the top right, click any of the available tutorials.
- Open `super_basecalling.ipynb`: File>Open from URL... `https://raw.githubusercontent.com/Vaccitech/nanopore/main/super_basecalling.ipynb`.
- Make a folder contain **all** .fast5 files (pass AND fail).
- Run the first code cell: click the arrow in it's top right corner.
- Fill the form with the path of the folder containing the .fast5 files, folder to output fastq files to, guppy config file (based on sample and flowcell).
- Click `>Enter`
- Run the next code cell, check that the printed lines are correct.
- Run the final code cell.
- Copy and paste it's output into command prompt.

## Share with Bioinformatics
- Add flowcell reports to output folder: copy and paste all extra reports from original sequencing folder e.g. `final_summary_*.txt`, `report_*.html`, `barcode_alignment_*.tsv`
- Zip the folder with all the .fastq and summary files.
- Upload to sharedrive `S:\Research & Development\Bioinformatics`.
- Let Bioinformatics know what kind of analysis you'd like run.
- :sunglasses:
