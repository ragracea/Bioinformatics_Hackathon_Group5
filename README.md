[b0293145-34f6-4e29-bf2f-ff9f812f450f.txt](https://github.com/user-attachments/files/17994646/b0293145-34f6-4e29-bf2f-ff9f812f450f.txt)# Bioinformatics_Hackathon_Group5

# Task A. Connect with your team.

Group Members: Emily Bernabe, Taylor Nutzman, Zoe Vickery, Rachel Anderson, and Julia Bertarelli

# Task B. Select a disease to study.

Sickle cell disease (SCD) is a genetic condition that affects red blood cells. Symptoms, diagnosis, treatment

# Task C. Find a gene underlying the disease.

The underlying cause of sickle cell disease is a single mutation in the β-globin gene (HBB). The mutation is a single nucleotide change, GAG to GTG, in the sixth codon of this gene. This mutation results in an amino acid change from glutamic acid to valine, which results in the production of hemoglobin S (HbS). The HBB gene is located on chromosome 11 and codes for the β-globin protein, which is an essential component of hemoglobin. In addition to HBB, other genes can modify the appearance and severity of SCD. Some of these genes include fetal hemoglobin (HbF) related genes like BCL11A, α-Thalassemia genes like HBA1 and HBA2, and inflammatory and adhesion molecule genes like VCAM1 and IL-4.

# Task D. Build a protein:protein interaction (PPI) network using the known gene protein product(s) as seeds.
![IntAct Network - HBB](https://github.com/user-attachments/assets/f2e800a5-a852-40f7-b982-84bb26ac2256)
[UploadCategory	ID	Name	Source	p-value	q-value Bonferroni	q-value FDR B&H	q-value FDR B&Y	Hit Count in Query List	Hit Count in Genome	Hit in Query List
Human Phenotype	HP:0004840	Hypochromic microcytic anemia	 	4.172E-15	1.498E-12	1.498E-12	9.679E-12	6	23	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0001935	Microcytic anemia	 	5.779E-13	2.075E-10	1.037E-10	6.704E-10	6	49	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0008346	Increased red cell sickling tendency	 	2.676E-12	9.605E-10	2.016E-10	1.303E-9	4	5	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0045047	HbS hemoglobin	 	2.676E-12	9.605E-10	2.016E-10	1.303E-9	4	5	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0001931	Hypochromic anemia	 	2.808E-12	1.008E-9	2.016E-10	1.303E-9	6	63	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0034336	Splenic infarction	 	1.872E-11	6.719E-9	1.120E-9	7.237E-9	4	7	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0011902	Abnormal hemoglobin	 	4.084E-11	1.466E-8	2.095E-9	1.353E-8	6	97	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0011895	Anemia due to reduced life span of red cells	 	1.267E-9	4.550E-7	5.687E-8	3.675E-7	6	170	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0010972	Anemia of inadequate production	 	3.511E-9	1.260E-6	1.400E-7	9.049E-7	6	201	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0011904	Persistence of hemoglobin F	 	3.499E-8	1.256E-5	1.256E-6	8.116E-6	4	37	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0001923	Reticulocytosis	 	9.419E-8	3.381E-5	3.074E-6	1.986E-5	4	47	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0002113	Pulmonary infiltrates	 	2.079E-7	7.465E-5	6.221E-6	4.020E-5	4	57	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0031850	Abnormal hematocrit	 	2.586E-7	9.285E-5	7.143E-6	4.615E-5	3	13	HBA2,KLF1,HBA1
Human Phenotype	HP:0032169	Severe infection	 	6.362E-7	2.284E-4	1.631E-5	1.054E-4	4	75	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0001744	Splenomegaly	 	8.291E-7	2.977E-4	1.984E-5	1.282E-4	6	496	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0004312	Abnormal reticulocyte morphology	 	1.007E-6	3.615E-4	2.170E-5	1.403E-4	4	84	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0020061	Abnormal hemoglobin concentration	 	1.028E-6	3.690E-4	2.170E-5	1.403E-4	3	20	HBA2,KLF1,HBA1
Human Phenotype	HP:0001746	Asplenia	 	1.392E-6	4.996E-4	2.776E-5	1.794E-4	4	91	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0010451	Aplasia/Hypoplasia of the spleen	 	1.877E-6	6.738E-4	3.546E-5	2.292E-4	4	98	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0025408	Abnormal spleen morphology	 	2.972E-6	1.067E-3	5.335E-5	3.447E-4	6	613	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0005511	Heinz body anemia	 	3.467E-6	1.245E-3	5.927E-5	3.830E-4	2	3	HBA2,HBA1
Human Phenotype	HP:0001743	Abnormality of the spleen	 	3.853E-6	1.383E-3	6.287E-5	4.063E-4	6	640	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0001903	Anemia	 	5.453E-6	1.958E-3	8.512E-5	5.500E-4	6	678	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0011907	Reduced alpha/beta synthesis ratio	 	6.931E-6	2.488E-3	9.953E-5	6.431E-4	2	4	HBA2,HBA1
Human Phenotype	HP:0011903	HbH hemoglobin	 	6.931E-6	2.488E-3	9.953E-5	6.431E-4	2	4	HBA2,HBA1
Human Phenotype	HP:0000488	Retinopathy	 	8.317E-6	2.986E-3	1.105E-4	7.142E-4	4	142	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0012130	Abnormal erythroid lineage cell morphology	 	9.236E-6	3.316E-3	1.105E-4	7.142E-4	6	740	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0010973	Abnormality of erythroid lineage cell	 	9.236E-6	3.316E-3	1.105E-4	7.142E-4	6	740	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0020047	Abnormal myeloid cell morphology	 	9.236E-6	3.316E-3	1.105E-4	7.142E-4	6	740	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0001877	Abnormal erythrocyte morphology	 	9.236E-6	3.316E-3	1.105E-4	7.142E-4	6	740	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0005560	Imbalanced hemoglobin synthesis	 	1.155E-5	4.145E-3	1.306E-4	8.439E-4	2	5	HBA2,HBA1
Human Phenotype	HP:0003271	Visceromegaly	 	1.164E-5	4.179E-3	1.306E-4	8.439E-4	6	769	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0031983	Abnormal pulmonary thoracic imaging finding	 	1.242E-5	4.459E-3	1.351E-4	8.731E-4	4	157	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0100763	Abnormality of the lymphatic system	 	1.401E-5	5.028E-3	1.479E-4	9.557E-4	6	793	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0012119	Methemoglobinemia	 	1.731E-5	6.214E-3	1.726E-4	1.115E-3	2	6	HBG2,HBA1
Human Phenotype	HP:0020082	Heinz bodies	 	1.731E-5	6.214E-3	1.726E-4	1.115E-3	2	6	HBA2,HBA1
Human Phenotype	HP:0000980	Pallor	 	2.012E-5	7.223E-3	1.952E-4	1.261E-3	5	417	HBA2,KLF1,HBG1,HBG2,HBA1
Human Phenotype	HP:0005561	Abnormal bone marrow cell morphology	 	2.298E-5	8.250E-3	2.171E-4	1.403E-3	6	861	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0002829	Arthralgia	 	3.728E-5	1.338E-2	3.431E-4	2.217E-3	4	207	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0001930	Nonspherocytic hemolytic anemia	 	4.148E-5	1.489E-2	3.722E-4	2.405E-3	2	9	HBA2,HBA1
Human Phenotype	HP:0020080	Erythrocyte inclusion bodies	 	6.330E-5	2.272E-2	5.411E-4	3.496E-3	2	11	HBA2,HBA1
Human Phenotype	HP:0001899	Increased hematocrit	 	6.330E-5	2.272E-2	5.411E-4	3.496E-3	2	11	HBA2,HBA1
Human Phenotype	HP:0001900	Increased circulating hemoglobin concentration	 	1.046E-4	3.754E-2	8.730E-4	5.641E-3	2	14	HBA2,HBA1
Human Phenotype	HP:0002240	Hepatomegaly	 	2.032E-4	7.296E-2	1.658E-3	1.071E-2	5	667	HBA2,KLF1,HBG1,HBG2,HBA1
Human Phenotype	HP:0025142	Constitutional symptom	 	2.449E-4	8.790E-2	1.953E-3	1.262E-2	6	1276	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0001789	Hydrops fetalis	 	2.799E-4	1.005E-1	2.184E-3	1.412E-2	3	126	HBA2,KLF1,HBA1
Human Phenotype	HP:0100602	Preeclampsia	 	2.894E-4	1.039E-1	2.200E-3	1.422E-2	2	23	HBA2,HBA1
Human Phenotype	HP:0002027	Abdominal pain	 	2.942E-4	1.056E-1	2.200E-3	1.422E-2	4	350	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0100603	Toxemia of pregnancy	 	4.312E-4	1.548E-1	3.159E-3	2.041E-2	2	28	HBA2,HBA1
Human Phenotype	HP:0001901	Polycythemia	 	6.379E-4	2.290E-1	4.530E-3	2.927E-2	2	34	HBA2,HBA1
Human Phenotype	HP:0001878	Hemolytic anemia	 	6.436E-4	2.310E-1	4.530E-3	2.927E-2	3	167	HBA2,KLF1,HBA1
Human Phenotype	HP:0001701	Pericarditis	 	8.841E-4	3.174E-1	6.104E-3	3.944E-2	2	40	HBA2,HBA1
Human Phenotype	HP:0033281	Circulating nucleated red blood cells	 	1.178E-3	4.229E-1	7.978E-3	5.156E-2	1	1	KLF1
Human Phenotype	HP:0410042	Abnormal liver morphology	 	1.344E-3	4.825E-1	8.887E-3	5.743E-2	5	984	HBA2,KLF1,HBG1,HBG2,HBA1
Human Phenotype	HP:0003135	Abnormal hematological laboratory findings	 	1.362E-3	4.888E-1	8.887E-3	5.743E-2	4	520	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0009906	Aplasia/Hypoplasia of the earlobes	 	1.551E-3	5.569E-1	9.945E-3	6.427E-2	2	53	HBA2,HBA1
Human Phenotype	HP:0001871	Abnormality of blood and blood-forming tissues	 	1.709E-3	6.135E-1	1.076E-2	6.955E-2	6	1763	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0010978	Abnormality of immune system physiology	 	1.995E-3	7.162E-1	1.235E-2	7.980E-2	6	1809	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0009891	Underdeveloped supraorbital ridges	 	2.119E-3	7.607E-1	1.289E-2	8.331E-2	2	62	HBA2,HBA1
Human Phenotype	HP:0031851	Reduced hematocrit	 	2.355E-3	8.453E-1	1.401E-2	9.054E-2	1	2	KLF1
Human Phenotype	HP:0001367	Abnormal joint morphology	 	2.381E-3	8.547E-1	1.401E-2	9.054E-2	6	1863	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0000006	Autosomal dominant inheritance	 	3.412E-3	1.000E0	1.976E-2	1.277E-1	6	1978	HBA2,KLF1,BCL11A,HBG1,HBG2,HBA1
Human Phenotype	HP:0001392	Abnormality of the liver	 	3.548E-3	1.000E0	2.022E-2	1.307E-1	5	1205	HBA2,KLF1,HBG1,HBG2,HBA1
Human Phenotype	HP:0001697	Abnormal pericardium morphology	 	3.682E-3	1.000E0	2.065E-2	1.335E-1	2	82	HBA2,HBA1
Human Phenotype	HP:0034058	Abnormal fetal morphology	 	3.889E-3	1.000E0	2.148E-2	1.388E-1	3	310	HBA2,KLF1,HBA1
Human Phenotype	HP:0031965	Increased RBC distribution width	 	4.704E-3	1.000E0	2.484E-2	1.605E-1	1	4	KLF1
Human Phenotype	HP:0004611	Anterior concavity of thoracic vertebrae	 	4.704E-3	1.000E0	2.484E-2	1.605E-1	1	4	BCL11A
Human Phenotype	HP:0020062	Decreased hemoglobin concentration	 	4.704E-3	1.000E0	2.484E-2	1.605E-1	1	4	KLF1
Human Phenotype	HP:0045073	Serositis	 	5.760E-3	1.000E0	2.997E-2	1.937E-1	2	103	HBA2,HBA1
Human Phenotype	HP:0000278	Retrognathia	 	6.692E-3	1.000E0	3.432E-2	2.218E-1	3	375	HBA2,BCL11A,HBA1
Human Phenotype	HP:0000047	Hypospadias	 	6.794E-3	1.000E0	3.435E-2	2.220E-1	3	377	HBA2,KLF1,HBA1
Human Phenotype	HP:0001831	Short toe	 	7.264E-3	1.000E0	3.572E-2	2.308E-1	2	116	HBA2,HBA1
Human Phenotype	HP:0100538	Abnormality of the supraorbital ridges	 	7.264E-3	1.000E0	3.572E-2	2.308E-1	2	116	HBA2,HBA1
Human Phenotype	HP:0000961	Cyanosis	 	7.386E-3	1.000E0	3.583E-2	2.315E-1	2	117	HBG2,HBA1
Human Phenotype	HP:0100627	Displacement of the urethral meatus	 	7.863E-3	1.000E0	3.764E-2	2.432E-1	3	397	HBA2,KLF1,HBA1
Human Phenotype	HP:0032076	Abnormal male urethral meatus morphology	 	7.976E-3	1.000E0	3.767E-2	2.434E-1	3	399	HBA2,KLF1,HBA1
Human Phenotype	HP:0012531	Pain	 	8.548E-3	1.000E0	3.985E-2	2.575E-1	4	846	KLF1,BCL11A,HBG1,HBG2
Human Phenotype	HP:0000363	Abnormal earlobe morphology	 	1.003E-2	1.000E0	4.618E-2	2.984E-1	2	137	HBA2,HBA1
Human Phenotype	HP:0001991	Aplasia/Hypoplasia of toe	 	1.046E-2	1.000E0	4.754E-2	3.072E-1	2	140	HBA2,HBA1
ing b0293145-34f6-4e29-bf2f-ff9f812f450f.txt…]()

# Task E. Find tissue-specific eQTLs DNA polymorphisms that could alter the expression of the candidate genes.
HBB eQTLs:
ENSG00000244734.4: 
chr11_6196858_A_G_b38
chr11_6189369_T_C_b38
chr11_6189365_C_A_b38
chr11_6188908_A_G_b38
chr11_6185920_C_A_b38
chr11_6185511_C_A_b38
chr11_6185478_A_G_b38
chr11_6185418_T_C_b38
chr11_6185411_G_C_b38
chr11_6183604_A_T_b38

HBG1 eQTLs:
ENSG00000213934.9:
chr11_5273171_C_T_b38
chr11_5237199_T_C_b38
chr11_5248569_A_C_b38
chr11_5270962_C_T_b38
chr11_5257923_T_C_b38
chr11_5258097_C_G_b38
chr11_5258125_C_A_b38
chr11_5262817_G_A_b38
chr11_5272395_A_T_b38
chr11_5247910_C_A_b38

HBG2 eQTLs:
ENSG00000196565.15
chr11_5259609_TA_T_b38
chr11_5256061_C_T_b38
chr11_5262780_T_C_b38
chr11_5268823_C_T_b38
chr11_5250441_C_T_b38
chr11_5261227_A_C_b38
chr11_5242453_C_T_b38
chr11_5253948_T_C_b38
chr11_5269140_C_G_b38
chr11_5253222_G_GT_b38

# Task F. Construct an hypothesis that the genes caused the disease phenotype by mechanism X.
