# OSOCR-News
## 29th, OCT, 2023
NG framework will be delayed for a while due to all kinds of paperwork, writing, and relocation preparations...  The framework itself is 80% done, but I have no time and resources to deploy and tune it. 

Spoiler: The NG framework will natively support multi-GPU parallel training but in a really weird way. 

(you can have your guess now, we will hopefully ship that part in late 2024 if smooth.)

10GB cards will be supported till 2025. 

## 1st, OCT, 2023i

We *will* drop the support of 8Gib GPUs for training in future iterations. We will try to make regular models fit into 10Gib cards for training (we will know by halloween)...


----------------------------------

## 29th, May, 2023

We recommend moving to 24Gb+ GPUs, like x090s, P40s, and M40s.

Considering the prices of P40s and M40s are pretty affordable these days, we will gradually drop training supports for 8Gib GPUs.

The training bar for future regular models would be 10Gib (p102, 1080tis, M40s), and 20Gib for large models.

The inferencing cost will also go up, however, we will make sure to support inference on 6G cards like P106-100s.


----------------------------------
Hi community,

We are going to make a new multi-lingual OSOCR benchmark set. 

We want to collect some ideas for the language list that people may want to recognize.

If you have a specific language in mind, please open an issue. We will pick some of the suggested languages to collect data and annotate. 
