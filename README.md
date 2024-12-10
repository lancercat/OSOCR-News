# OSOCR-News
## 10, Dec, 2024
The next release still needs to wait. 

We are refactoring the full framework for a more elegant implement of [something]. 
ETA one or two months. Please also expect a big performance leap :)

Framework NG-> NG+


## 17, Sep, 2024
The next release will support bf16 and multi-gpu inference. 

Multi-gpu training will be delayed to a future release (in a less usual manner).


## ⑨, ⑨, 2024
The next release is scheduled in November, with more languages and better model flexibility. 


## CIH day, June, 2024
Datasets start being added. Tuning for performance.


## ⑨ th, June, 2024
It's happening (maybe). 


## 28th, May, 2024
Proceeding to adopt new datasets like FudanVI, Union14M, and others. 

Now we have some powerful devices. Time to scale up. 

## 5th, May, 2024
Due to a specific application need, C4-family may receive a weird DLC (object ~~282~~ 305) in the next months, 

which means we may or may not get the first of the "far more intresting stuffs" finished befor the AAAI ddl.

I would not say it is not interesting, it is, 

but it still would only concern the OCR community, hence not that significant. 

## 2nd, May, 2024
C4/LSCT family will be finally coming to light if I can pull off the Major Revision. 

The stage has been set, buckle up.

And from stage 2 of the NG framework we are considering to stop support for GPUs with less than 16 GiB of VRAM

## 22th, Apr, 2024
Code cleaned up and verified for Moose. 

Start documentation process and quality check procedure.

Once done, we will start uploading things onto kaggle and github (hopefully before mayday).


## 18th, Apr, 2024
OAPR released. Note it is still built with the first generation framework. The NG framework starts with Moose.

## 12th, Apr, 2024
We started to tidy up and will release the first version of the NG-framework (likely before May). 

See you in ICDAR24.

BTW, the whole NG framework is current going towards version two, and there will be a planned version 3 by halloween.

Hope we can show you ppl some thing far more interesting than this in near future. 



## ⑨ th, Apr, 2024
Another project is about to reach training stage (coding is mostly done), which brings some interesting new features.

Hope we can get some results in May.

Happy the ⑨th day of a month~

## 29th, Mar, 2024
The QA DLC will be delayed, as we find few benchmarks for an open-end VQA model. 

The next relase will still be solely single-gpu OCR. 

But changes are indeed happening, they are just slower than expected (partially bcs I am still adapting to the new lifestyle).


## 28th, Feb, 2024
Allow me to expand this repo to QA a bit, before we resume on the multi-gpu approach.

The next revision will hopefully be ready by April Fool's day.


## 10th, Feb, 2024
The core of the NG framework is taking shape. 

## 1st, Feb, 2024
The NG framework will come with a lot of DLCs, so expect some weird [optional] dependencies :-)

## 18th, Jan, 2024
~~The NG framework may require pytorch>=2.1~~
The sparsity feature is not used in the end. The first method based on the NG framework is under ablative, see you ppl soon. 
## 29th, OCT, 2023
NG framework will be delayed for a while due to all kinds of paperwork, writing, and relocation preparations...  The framework itself is 80% done (usable if you don't need multigpu that is), but I have no time and resources to deploy and tune it. 

Spoiler: The NG framework will natively support multi-GPU parallel training but in a really weird way. 

(you can have your guess now, we will hopefully ship that part in late 2024 if smooth.)

~~10GB cards will be supported till 2025.~~

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
