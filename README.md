<div align="center">
<h2 align="center">
    <b>Global Prior Meets Local Consistency: Dual-Memory Augmented  
     <br />  Vision-Language-Action Model for Efficient Robotic Manipulation
   <br /> <font size=3>CVPR 2026 </font></b> 
</h2>
<div>
<a target="_blank" href="https://scholar.google.com/citations?user=TDBF2UoAAAAJ&hl=en&oi=ao">Zaijing&#160;Li</a><sup>1 2</sup>,
<a target="_blank" href="https://scholar.google.com/citations?user=rxaiRMUAAAAJ&hl=en">Bing&#160;Hu</a><sup>1</sup>,
<a target="_blank" href="https://scholar.google.com/citations?user=9Vc--XsAAAAJ&hl=en&oi=ao">Rui&#160;Shao</a><sup>1 3&#9993</sup>,
<a target="_blank" href="https://scholar.google.com/citations?user=Mpg0w3cAAAAJ&hl=en&oi=ao">Gongwei&#160;Chen</a><sup>1</sup>,
<br>
<a target="_blank" href="https://scholar.google.com/citations?hl=en&user=Awsue7sAAAAJ">Dongmei&#160;Jiang</a><sup>2&#9993</sup>,
 <a target="_blank" href="https://scholar.google.com/citations?hl=en&user=yywVMhUAAAAJ">Liqiang&#160;Nie</a><sup>1</sup>
</div>
<sup>1</sup>Harbin Institute of Technology, Shenzhen&#160&#160&#160</span>
<sup>2</sup>PengCheng Laboratory, Shenzhen&#160&#160&#160</span>
<sup>3</sup>Shenzhen Loop Area Institute</span>
<br />
<sup>&#9993&#160;</sup>Corresponding author&#160;&#160;</span>
<br/>
<div align="center">
    <a href="https://arxiv.org/abs/2408.03615" target="_blank">
    <img src="https://img.shields.io/badge/Paper-arXiv-deepgreen" alt="Paper arXiv"></a>
    <a href="https://cybertronagent.github.io/OptimusVLA.github.io/" target="_blank">
    <img src="https://img.shields.io/badge/Project-OptimusVLA-9cf" alt="Project Page"></a>
</div>
</div>



## :new: Updates
- [02/2026] :fire: OptimusVLA is accepted to **CVPR 2026**!
- [02/2026] :fire: [Project page](https://cybertronagent.github.io/OptimusVLA.github.io/) released.
- [02/2026] :fire: [Arxiv paper](https://arxiv.org/abs/2408.03615) released.




## :balloon: OptimusVLA Framework
Overview of OptimusVLA framework. Given a task and the current observation, the Vision–Language backbone first encodes the inputs into a multimodal representation. GPM then retrieves a task-level prior based on this representation, while LBM dynamically encodes the historical action sequence to produce a consistency constraint. Finally, the flow policy denoises the initialization with an adaptive NFEs schedule to generate the action chunk.
<img src="./assets/fig1.png" >

## :smile_cat: Evaluation results on Real World
We evaluate OptimusVLA on Generalization Tasks and Long-horizon Tasks via GALAXEA R1 Lite robot.
<img src="./assets/fig2.png" >




