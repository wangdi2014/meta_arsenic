## June 2-5, 2017
These are the files I am downloading from MG-RAST and performing FastQC on:
#### 1. Iowa_corn  
ProjectID: mgp6369
* Sample1: mgm4539522.3;  fastq file, has the 2nd bp in the project (the file with the most bp is not in fastq format), <30% failed QC
  * FastQC: Sequence length 31-100, failed Kmer, everything else looks good
* Sample2: mgm4539523.3;   fastq file, has the 3rd most bp in the project, <30% failed QC
  * FastQC: Sequence length 31-100, failed Kmer, everything else looks good
* Metadata from this project

#### 2. Iowa_agricultural
ProjectID: mgp2592
* Sample1: mgm4509400.3; fastq file, has the most bp, 23% failed QC
  * FastQC: Sanger/Illumina 1.9, failed per base sequence quality, everything else looks good
* Sample2: mgm4509401.3; fastq file, has the 3rd most bp (the data with 2nd most bp has a failed QC of 38% so it is not used), 11% failed QC
* Metadata from this project

#### 3. Mangrove
ProjectID: mgp11628
* Sample1: mgm4603402.3; fastq file, has the most bp, 3.65% failed QC
* Sample2: mgm4603270.3; fastq file, has the 2nd most bp, 3.1% failed QC
* Metadata from this project

#### 4. Permafrost_Russia
ProjectID: mgp7176
* Sample1: mgm4546812.3; fastq file, has the most bp (tied with Sample2), 12% failed QC
* Sample2: mgm4546813.3; fastq file, has the most bp (tied with Sample1), 15% failed QC
* Metadata from this project

#### 5. Iowa_prairie
ProjectID: mgp6377
* Sample1: mgm4539575.3; fastq file, has the most bp, 14% failed QC
* Sample2: mgm4539572.3; fastq file, has the 2nd most bp, 14% failed QC
* Metadata from this project

#### 6. Brazilian_forest
ProjectID: mgp3731
* Sample1: mgm4546395.3; fastq file, has the most bp, 7% failed QC
* Sample2: mgm4536139.3; fast1 file, has the 2nd most bp, 9% failed QC
* Metadata from this project

#### 7. Illinois_soybean
ProjectID: mgp2076
* Sample1: mgm4502542.3; fastq file, has the most bp, 26% failed QC
* Sample2: mgm4502540.3; fastq file, has the 2nd most bp, 11% failed QC
* Metadata from this project

#### 8. Minnesota_creek
ProjectID: mgp5588
* Sample1: mgm4541646.3; fastq file, has the most bp, 2.55% failed QC
* Sample2:mgm4541645.3; fastq file, has the 2nd most bp, 2.58% failed QC
* Metadata from this project

#### 9. Disney_preserve
ProjectID: mgp13948
* Sample1: mgm4664918.3; fastq file, most bp, .05% failed QC
* Sample2: mgm4664925.3; fastq file, 2nd most bp, 
  * FastQC: seq. length 12-190, failed per tile sequence qual., per base sequence content not very good from 1-8
* Metadata from this project

#### 10. California_grassland
ProjectID: mgp1992
* Sample1: mgm4511061.3; fastq file, most bp, 19% failed QC
 * NOTE: *Failed to process file California_grassland_4511061.3.fastq uk.ac.babraham.FastQC.Sequence.SequenceFormatException: Ran out of data in the middle of a fastq entry.  Your file is probably truncated* 

* Sample2: mgm4511115.3; fastq file, 2nd most bp, 10% failed QC
  * FastQC: Sanger/Illumina 1.9, Per base sequence quality not very good from position ~70-100, flag on per base sequence content, failed per sequence GC content, failed Kmer content
* Metadata from this project

#### 11. Illinois_soil
ProjectID: mgp14596
* Sample1: mgm4653791.3; fastq file, most bp, .05% failed QC
  * FastQC: seq. length 12-190, Sanger/Illumina 1.9, per base seq. content not very good below 9 and above 160, everything else looks good
* Sample2: mgm4653788.3; fastq file, 2nd most bp, .06% failed QC
  * FastQC: Sanger/Illumina 1.9, seq. length 12-190, per base seq. content not very good below position 9, everything else looks good
* Metadata for this project

#### 12. Wyoming_soil
ProjectID: mgp15600
* Sample1: mgm4670122.3; fastq file, most bp, 6% failed QC
  * FastQC: Sanger/Illumina 1.9, per base sequence count is a little skewed from position 1-8, everything else looks good
* Sample2: mgm4670120.3; fastq file, 2nd most bp, 6% failed QC
* Metadata for this project

#### 13. Permafrost_Canada
ProjectID: mgp252
* Sample1: mgm4523778.3; fastq file, most bp, 8% failed QC
* Sample2: mgm4523023.3; fastq file, 2nd most bp, 10% failed QC
* Metadata for this project

#### 14. Permafrost_USA 
ProjectID: mgp11953
* Sample1: mgm4469340.3; fq file, 2nd most bp in project (samplew ith most bp is fna format), 5% failed QC
* Sample2: mgm4470009.3; fq file, 6th most bp, 0% failed QC
* Metadata for this project

#### Note: Contaminated_Canada files are all in fna format, so I did not download
ProjectID: mgp79868

#### Note: Contaminated_China file is in fna format, so I did not download
ProjectID: mgp13736