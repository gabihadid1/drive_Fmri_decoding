# drive_Fmri_decoding

![header](https://capsule-render.vercel.app/api?type=waving&height=300&color=A5BECC&fontColor=365486&text=From%20Fragments%20to%20Meaning:%20-nl-fMRI%20Decoding%20of%20Partial%20Sentences&desc=Final%20Project&fontAlign=50&descSize=30&descAlign=50&fontAlignY=31&fontSize=43&descAlignY=63)

![header](https://capsule-render.vercel.app/api?type=transparent&color=A5BECC&height=65&reversal=true&fontSize=24&fontColor=365486&text=The%20Faculty%20of%20Data%20and%20Decisions%20Science%20-nl-%20&desc=%20Technion%20-%20Israel%20Institute%20of%20Technology&descSize=18&descAlignY=73&fontAlign=50&animation=fadeIn&textBg=false&section=header&stroke=243A73&strokeWidth=0&theme=holi)

![footer](https://capsule-render.vercel.app/api?type=waving&color=A5BECC&height=100&section=footer&text=%20-nl-%20Spring%202024/25%20%20&fontSize=16&fontAlign=50&fontColor=365486&theme=holi)

![header](https://capsule-render.vercel.app/api?type=soft&color=293B5F&height=45&section=header2&text=Authors&fontSize=28&fontAlign=7&fontColor=EEF5FF&reversal=false&theme=holi)
> Gabriela Cohen-Hadid gabriela.c@campus.technion.ac.il
> 
> Eden Sadgiani eden.sa@technion.ac.il
> 

![header](https://capsule-render.vercel.app/api?type=soft&color=293B5F&height=45&section=header&text=Background&fontSize=28&fontAlign=10&fontColor=EEF5FF&reversal=true&theme=holi)

This project investigates how the human brain encodes meaning when processing **partial sentences**.  
Using **fMRI data** from two studies, we compare **static embeddings (GloVe)** with **contextualized embeddings (BERT)**,  
and introduce a **fragment-based analysis** to examine the contribution of different sentence segments to neural representations.


![header](https://capsule-render.vercel.app/api?type=soft&color=293B5F&height=45&section=header&text=Key%20Findings:&fontSize=28&fontAlign=11&fontColor=EEF5FF&reversal=true&theme=holi)

- **BERT consistently outperforms GloVe** in decoding accuracy across both full and partial inputs.  
- The first **50–75%** of a sentence retains more than **98%** of the full-sentence decoding performance.  
- Brain regions exhibit different preferences: e.g., **LH IFGorb** favors final fragments,  
  while **LH PostTemp** and **LH netw** prefer earlier fragments.

![header](https://capsule-render.vercel.app/api?type=soft&color=293B5F&height=45&section=header&text=Datasets&fontSize=28&fontAlign=7&fontColor=EEF5FF&reversal=true&theme=holi)

- **Pereira et al., 2018** – sentence-level fMRI  
- **Tuckute et al., 2024** – ROI-level fMRI


![header](https://capsule-render.vercel.app/api?type=soft&color=293B5F&height=45&section=header&text=Acknowledgment&fontSize=28&fontAlign=14&fontColor=EEF5FF&reversal=true&theme=holi)

Developed for the Language, Computation and Cognition course supervised by Yevgeni Berzak, Technion. <br>
All Rights Reserved.
