# Awesome-Procedure-Knowledge-Extraction

![](https://img.shields.io/badge/Status-building-brightgreen)

## Contributor

Resource Contributed by [Jingqi Kang](https://github.com/JingqiKang), [Rongyi Chen](https://github.com/shinymoon99).

## Quick path
- [Resources](#resources)
- [Dataset](#dataset)

## Resources
1. **Automatically Extracting Procedural Knowledge from Instructional Texts using Natural Language Processing** `2012 LREC` [[pdf]](http://www.lrec-conf.org/proceedings/lrec2012/pdf/244_Paper.pdf)
2. **Extraction of procedural knowledge from the web: a comparison of two workflow extraction approaches** `2012 WWW` [[pdf]](https://www.researchgate.net/publication/239761847_Extraction_of_procedural_knowledge_from_the_Web_A_comparison_of_two_workflow_extraction_approaches)
3. **Extracting and enriching workflows from text** `2013 IEEE IRI` [[pdf]](https://ieeexplore.ieee.org/document/6642484)
4. **Extracting control-flow from text** `2014 IEEE IRI` [[pdf]](https://ieeexplore.ieee.org/document/7051891)
5. **EaT-PIM (Embedding and Transforming Procedural Instructions for Modification)** `ISWC 2022` [[pdf]](https://github.com/boschresearch/EaT-PIM/blob/main/docs/ISWC_EaT_PIM.pdf) [[code]](https://https://github.com/boschresearch/EaT-PIM) 
6. **Learning Procedures from Text: Codifying How-to Procedures in Deep Neural Networks** `WWW Track 2018` [[pdf]](https://dl.acm.org/doi/fullHtml/10.1145/3184558.3186347) 
7. **Leveraging Inter-step Dependencies for Information Extraction from Procedural Task Instructions** `TSD 2021` [[pdf]](https://dl.acm.org/doi/abs/10.1007/978-3-030-83527-9_29) 
8. **Reasoning about Procedures with Natural Language Processing: A Tutorial** `Arxiv 2022` [[pdf]](https://arxiv.org/abs/2205.07455) 
9. **Show Me More Details:Discovering Hierarchies of Procedures from Semi-structured Web Data** `ACL 2022` [[pdf]](https://aclanthology.org/2022.acl-long.214/) [[code]](https://github.com/shuyanzhou/wikihow_hierarchy)
# Dataset
<div style="overflow-x: auto; overflow-y: auto; height: auto; width:100%;">
<table border="0" cellpadding="0" cellspacing="0" width="1080" style="border-collapse: 
 collapse;table-layout:fixed;width:810pt">
 <colgroup><col width="72" style="width:54pt">
 <col width="224" style="mso-width-source:userset;width:168pt">
 <col width="72" style="width:54pt">
 <col width="434" style="mso-width-source:userset;width:325.5pt">
 <col width="206" style="mso-width-source:userset;width:154.5pt">
 <col width="72" style="width:54pt">
 </colgroup><tbody><tr height="20" style="mso-height-source:userset;height:15pt" id="r0">
<td height="18" class="x24" width="72" style="height:13.5pt;width:54pt;">相关工作</td>
<td class="x24" width="224" style="width:168pt;">数据来源</td>
<td class="x24" width="72" style="width:54pt;">适用任务</td>
<td class="x24" width="434" style="width:325.5pt;">数据规模</td>
<td class="x24" width="206" style="width:154.5pt;">备注</td>
<td class="x26" width="72" style="width:54pt;">下载</td>
 </tr>
 <tr height="168" style="mso-height-source:userset;height:126pt" id="r1">
<td height="166" class="x22" style="height:124.5pt;">相关工作5&nbsp;</td>
<td class="x22">作者只使用wikihow文章中那些至少有一个其感兴趣的实体(目标、方法、任务和子任务)的文章。<br></td>
<td class="x22">判断步骤间关系</td>
<td class="x25"></td>
<td class="x23">"目标 "来自文章中程序性描述中的主要描述的第一句话。而方法、任务、子任务的识别可以用mediaWiki固有的结构来识别（例如，新的子章节的开始）。<span style="mso-spacerun:yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>数据集ground-truth<br><span style="mso-spacerun:yes;">&nbsp;&nbsp; </span>关系三元组，用于表示一篇文章</td>
<td class="x28"><a href="https://github.com/WikiTeam/wikiteam" target="_parent"><span style="font-size:11pt;color:#0563C1;font-weight:400;text-decoration: underline;text-line-through:none;text-underline-style:single;font-family:&quot;等线&quot;;">https://github.com/WikiTeam/wikiteam</span></a></td>
 </tr>
 <tr height="120" style="mso-height-source:userset;height:90pt" id="r2">
<td height="118" class="x22" style="height:88.5pt;">相关工作6&nbsp;</td>
<td class="x22">MyFixit dataset<br>作者用于评估自己模型的第一组数据是MyFixit数据集的有人工注释部分，标注了标注了步骤所需的工具、拆卸的部件和拆卸动词。</td>
<td class="x22">标注关键元素</td>
<td class="x22">总共有1,497本手册，36,973个步骤。数据说明通常长于512个字的标记，每本手册的平均大小为944个字，最大的手册长度为3509个字</td>
<td class="x22">。</td>
<td class="x28"><a href="https://github.com/rub-ksv/MyFixit-Dataset" target="_parent"><span style="font-size:11pt;color:#0563C1;font-weight:400;text-decoration: underline;text-line-through:none;text-underline-style:single;font-family:&quot;等线&quot;;">https://github.com/rub-ksv/MyFixit-Dataset </span></a></td>
 </tr>
 <tr height="149" style="mso-height-source:userset;height:112pt" id="r3">
<td height="147" class="x22" style="height:110.5pt;">相关工作6&nbsp;</td>
<td class="x22">Recipe named entities dataset(r NEs)<span style="mso-spacerun:yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>r NEs数据集包含了来自Allrecipes UK/Ireland网站的300个烹饪食谱，这些食谱注释了食谱中的命名实体。</td>
<td class="x22">标注关键元素</td>
<td class="x22">每个食谱的平均大小为132个字，最大大小为444个字。</td>
<td class="x22"></td>
<td class="x28"><a href="https://sites.google.com/view/yy-lab/resource/english-recipe-ner" target="_parent"><span style="font-size:11pt;color:#0563C1;font-weight:400;text-decoration: underline;text-line-through:none;text-underline-style:single;font-family:&quot;等线&quot;;">https://sites.google.com/view/yy-lab/resource/english-recipe-ner</span></a></td>
 </tr>
 <tr height="149" style="mso-height-source:userset;height:112pt" id="r4">
<td height="147" class="x22" style="height:110.5pt;">相关工作8</td>
<td class="x22">食谱流程图语料库（r-FG语料库）<br></td>
<td class="x22">生成流程图</td>
<td class="x25"></td>
<td class="x23">r-FG语料库包含从一个存储用户发布的食谱的互联网网站上随机提取的208条食谱。这些菜谱被注释了以下信息。1. 词语边界2. 食谱术语3. 流程图<span style="mso-spacerun:yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>输入：食谱的构成要素，包括步骤、食材、标签<br>输出：流程图的构成要素</td>
<td class="x27">None</td>
 </tr>
 <tr height="56" style="mso-height-source:userset;height:42pt" id="r5">
<td height="54" class="x22" style="height:40.5pt;">相关工作8</td>
<td class="x22">来自 Food.com 的食谱数据</td>
<td class="x22">生成实体替换</td>
<td class="x22">选择了一个由 20,000 个食谱组成的数据子集，其中包括 6,142 种不同的成分。</td>
<td class="x23">输入：食谱的构成要素，包括步骤、食材、标签<br>输出：食材的替换</td>
<td class="x28"><a href="http://www.food.com/" target="_parent"><span style="font-size:11pt;color:#0563C1;font-weight:400;text-decoration: underline;text-line-through:none;text-underline-style:single;font-family:&quot;等线&quot;;">www.food.com</span></a></td>
 </tr>
 <tr height="120" style="mso-height-source:userset;height:90pt" id="r6">
<td height="118" class="x22" style="height:88.5pt;">相关工作9</td>
<td class="x22">在wikiHow中，大约有21000个步骤已经有一个超链接，将其重定向到另一篇wikiHow文章，由编辑填写。我们把链接文章的标题作为该步骤的真实目标。</td>
<td class="x22">获取过程知识文本集合的知识层次结构</td>
<td class="x25"></td>
<td class="x23">1输入：一组过程性知识文本<br>2输出：每个知识文本中的步骤最相似的文章目标。</td>
<td></td>
 </tr>
<!--[if supportMisalignedColumns]-->
 <tr height="0" style="display:none">
  <td width="72" style="width:54pt"></td>
  <td width="224" style="width:168pt"></td>
  <td width="72" style="width:54pt"></td>
  <td width="434" style="width:325.5pt"></td>
  <td width="206" style="width:154.5pt"></td>
  <td width="72" style="width:54pt"></td>
 </tr>
 <!--[endif]-->
</tbody></table>
</div>
