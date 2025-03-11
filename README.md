# FoG-Trigger Dataset

## **Citation**  
If you use this dataset in your research, please cite our paper:  

```
Chen Qian, Chuntian Chi, John Clapham, Jiarui Qi, Zherui Zhang, GinaMari Blackwell, Ingrid Pretzer-Aboff, Leslie Cloud, Meiyi Ma, Gang Zhou, and Huajie Shao. Trigger-Finder: A Real-Time Freezing-of-Gait Trigger Detection System Using an Instruction-Tuned Multimodal Large Language Model. CHASE 2025. DOI: https://doi.org/10.1145/3721201.3721387
``` 

## **Description**  
The FoG (Freezing of Gait) Trigger Dataset contains images annotated with potential triggers that may contribute to Freezing of Gait in individuals with Parkinson’s disease. The dataset includes labeled examples of five key triggers:  
- **Floor Pattern Changes**
  This label refers to situations where sudden or significant changes in floor patterns occur, such as transitions from one surface type to another (e.g., carpet to tile).
  Example of Floor Pattern Changes
  
  ![Alt text](examples/floor_pattern_changes_1.pdf)

- **Tight Turns**
  This label refers to situations where the individual encounters a scenario requiring a tight turn, such as making a pivot greater than 90-degree.
  Example of Tight Turns
  
  ![Alt text](examples/tight_turn_4.png)
  
- **Narrow Passages**
  This label refers to scenarios where the individual passes through a confined space, such as a doorway, hallway, or between closely positioned obstacles.
  Example of Narrow Passages
  
  ![Alt text](examples/narrow_passage_4.png)
  
- **Distraction**
  This label refers to situations where the individual encounters sudden visual or auditory distractions that may interrupt their walking pattern.
  Example of Narrow Passages
  
  ![Alt text](examples/distraction_4.png)
  
- **Dual-Tasking**
  This label applies when the individual is engaged in two or more tasks simultaneously, such as opening the door and entering.
  Example of Dual-Tasking
  ![Alt text](examples/dual_tasking_3.png)

Each image is paired with ground truth labels and reasoning descriptions to facilitate research in explainable AI for FoG trigger detection. The raw images and labels can be found in the corresponding sub-folders with names indicating the location which images were captured. The entire data corpus in trainable format can be found in the all_labeled_dataset json file.

## **Files**

## **Download**  
The dataset can be accessed at:  
[https://drive.google.com/file/d/1ZNQXpISN5c4p2l5HV5gzTrr02ZjZE4B4/view?usp=sharing]  



## **Terms of Use for FoG-Trigger Dataset**
You need to read and agree to the following terms of use to download and use the FoG-Trigger Dataset.
```
1. Definitions
```
The following terms, unless the context requires otherwise, have the following meanings:

“Data Team”: means the employees and students at William & Mary who are working on the FoG-Trigger Dataset;

“FoG-Trigger Dataset”: means the images containing potential FoG triggers collected by the Data Team;

“Licensee”, “You”, “Yours”: means the person or entity acquiring a license hereunder for access to and use of the FoG-Trigger Dataset.
```
2. Grant of License
```
William & Mary hereby grants to You a non-exclusive, non-transferable, revocable license to use the FoG-Trigger Dataset solely for Your non-commercial, educational, and research purposes only, but without any right to copy or reproduce, publish or otherwise make available to the public or communicated to the public, sell, rent or lend the whole or any constituent part of the FoG-Trigger Dataset thereof. The FoG-Trigger Dataset shall not be redistributed without the express written prior approval of William & Mary. You agree not to reverse engineer, separate or otherwise tamper with the FoG-Trigger Dataset so that data can be extracted and used outside the scope of that permitted in this Agreement.

You agree to acknowledge the source of the FoG-Trigger Dataset in all of Your publications and presentations based wholly or in part on the FoG-Trigger Dataset. You agree to provide a disclaimer in any publication or presentation to the effect that William & Mary does not bear any responsibility for Your analysis or interpretation of the Dataset.

You agree and acknowledge that William & Mary may hold, process, and store any personal data submitted by You for validation and statistical purposes and the purposes of the administration and management of the FoG-Trigger dataset. You agree that any personal data submitted by You is accurate to the best of his or her knowledge.

William & Mary provides the FoG-Trigger Dataset “AS IS,” without any warranty or promise of technical support, and disclaims any liability of any kind for any damages whatsoever resulting from use of the FoG-Trigger Dataset.

WILLIAM & MARY MAKES NO WARRANTIES, EXPRESS OR IMPLIED WITH RESPECT TO THE FOG-TRIGGER DATASET, INCLUDING ANY IMPLIED WARRANTY OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE, WHICH ARE HEREBY EXPRESSLY DISCLAIMED.

Your acceptance and use of the FoG-Trigger Dataset binds you to the terms and conditions of this License as stated herein.
