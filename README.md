# Awesome-Procedure-Knowledge-Extraction

![](https://img.shields.io/badge/Status-building-brightgreen)

## Contributor

Resource Contributed by [Jingqi Kang](https://github.com/JingqiKang), [Rongyi Chen](https://github.com/shinymoon99).

## Quick path
- [Resources](#resources)
- [Dataset](#dataset)

## Resources
1. **EaT-PIM (Embedding and Transforming Procedural Instructions for Modification)** `ISWC 2022` [[pdf]](https://github.com/boschresearch/EaT-PIM/blob/main/docs/ISWC_EaT_PIM.pdf) [[code]](https://https://github.com/boschresearch/EaT-PIM) 
2. **Learning Procedures from Text: Codifying How-to Procedures in Deep Neural Networks** `WWW Track 2018` [[pdf]](https://dl.acm.org/doi/fullHtml/10.1145/3184558.3186347) 
3. **Leveraging Inter-step Dependencies for Information Extraction from Procedural Task Instructions** `TSD 2021` [[pdf]](https://dl.acm.org/doi/abs/10.1007/978-3-030-83527-9_29) 
4. **Reasoning about Procedures with Natural Language Processing: A Tutorial** `Arxiv 2022` [[pdf]](https://arxiv.org/abs/2205.07455) 
5. **Show Me More Details:Discovering Hierarchies of Procedures from Semi-structured Web Data** `ACL 2022` [[pdf]](https://aclanthology.org/2022.acl-long.214/) [[code]](https://github.com/shuyanzhou/wikihow_hierarchy)
# Dataset
<div style="overflow-x: auto; overflow-y: auto; height: auto; width:100%;">
<table style="width:100%" border="2">
<thead>
  <tr>
    <th>Name</th>
    <th>Intro</th>
    <th>Links</th>
    <th>Detail</th>
    <th>Size & Stats</th>
  </tr>
</thead>
<tbody >


<tr>
	<td><code> RAW_recipes.csv</code> </td>
    <td> containing crawled data from Food.com. This dataset was published in Bodhisattwa Prasad Majumder, Shuyang Li, Jianmo Ni, Julian McAuley, Generating Personalized Recipes from Historical User Preferences, EMNLP, 2019 </td>
    <td> Download:<br/>1.https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions   <br/> </td>
    <td>  </td>
    <td>                  </td>
</tr>
<tr>
	<td><code> wikihow</code> </td>
    <td> wikihow includes abundant informative contents about procedures in many domains such as recipes, finance, cars, education, health, hobbies, personal care, and etc. </td>
    <td> Download:         1.https://github.com/WikiTeam/wikiteam                </td>
    <td> In total, 198,163 articles were downloaded using the wikiTeam data processing interface. We only used articles which have at least one of each of these entities of interest: goal, method, task, and subtask. </td>
    <td>                  </td>
</tr>
<tr>
	<td><code> MyFixit dataset</code> </td>
    <td>  a semi-structured dataset scraped from the iFixit website. In the MyFixit data, all manuals have been divided into their constituent steps, where at each step,
the user typically disassembles one particular device component. </td>
    <td> Download:         1.https://github.com/rub-ksv/MyFixit-Dataset             </td>
    <td>In total, 1,497 manuals with 36,973 steps have human annotations. The MyFixit
data instructions are often longer than 512 word tokens, with an average size of 944 words per manual and a maximum manual length of 3509 words. </td>
    <td>                  </td>
</tr>
<tr>
    <td><code>Recipe named entities dataset</code></td>
    <td>It contains 300 cooking recipes from the Allrecipes UK/Ireland
website, which are annotated for recipe named entities. The annotation tags of this
dataset include Food (F), Tool (T), Duration (D), Quantity (Q), Action by chef (Ac),
Action by food (Af), Action by tool (At), Food state (Sf), and Tool state (St).</td>
    <td>Download:https://sites.google.com/view/yy-lab/resource/english-recipe-ner</td>
    <td>The instructions in r NEs are often shorter than those in the MyFixit dataset, with an average
size of 132 words per recipe and a maximum size of 444 words.</td>
</tr>
<tr>
    <td><code>Howto100M</code></td>
    <td>HowTo100M is a large-scale dataset of narrated videos with an emphasis on instructional videos where content creators teach complex tasks with an explicit intention of explaining the visual content on screen. </td>
    <td>Download:https://www.di.ens.fr/willow/research/howto100m/</td>
    <td>HowTo100M features a total of:

136M video clips with captions sourced from 1.2M Youtube videos (15 years of video)
23k activities from domains such as cooking, hand crafting, personal care, gardening or fitness
Each video is associated with a narration available as subtitles automatically downloaded from Youtube.</td>
</tr>
</tbody >
</table>
</div>
