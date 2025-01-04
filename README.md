# vogels_group_rotation_project

This repository comprises all the reasonable jupyther notebooks I produced during my internship at Vogels group at ISTA. The report write-up is available here [report](https://www.overleaf.com/read/mgntgtqkjqtv#b04397)

## The project
I am building upon the work of Richard Gao et al. [Deep inverse modeling reveals dynamic-dependent invariances in neural circuit mechanisms](https://www.biorxiv.org/content/10.1101/2024.08.21.608969v1)
I started from code available at the corresponding [github page](https://github.com/mackelab/automind/tree/main) and worked with the [Demo-1](https://github.com/mackelab/automind/blob/main/notebooks/demo-1_automind_inference_workflow.ipynb) and helped to create [Demo-2](https://github.com/mackelab/automind/blob/main/notebooks/demo-2_automind_inference_from_spikes.ipynb) after finding bugs in Demo-1 when I tried to use it with my raw dataset. In Demo-2, we added targeting to a real experimental recording. Specifically, we want to discover circuit models that can reproduce a multi-electrode array recording from the organoid dataset. 

I am posting notebooks:
- a simple example code of how the Demo-1 worked when I did not have the inference running and was just trying to find the closest match within the samples from the posterior already presampled by Richard to my target input data statistics [Simple Example-1](https://github.com/TerezaZuskinova/vogels_group_rotation_project/blob/main/Simple_search_in_DGM%7Cbursts.ipynb) from posterior conditioned on bursts 
- and [Simple Example-2](https://github.com/TerezaZuskinova/vogels_group_rotation_project/blob/main/Simple_search_in_DGM%7CPSD.ipynb) working the same way as [Simple Example-1]((https://github.com/TerezaZuskinova/vogels_group_rotation_project/blob/main/Simple_search_in_DGM%7Cbursts.ipynb)) but conditioned on multiple bursts stats, plus also adjusting the parameters of the burst detection function
- [Demo-2-simulating multiple samples](https://github.com/TerezaZuskinova/vogels_group_rotation_project/blob/main/demo-2_automind_inference_from_spikes_my_automated_run.ipynb) Building upon the Demo-2 from AutoMIND, but this is a dedicated notebook for just running multiple simulations and saving the spike trains for further analysis
- [Demo-2-analysis](https://github.com/TerezaZuskinova/vogels_group_rotation_project/blob/main/demo-2_automind_inference_from_spikes_analysis.ipynb) - creating plots and analysis that I have put in the [report](https://www.overleaf.com/read/mgntgtqkjqtv#b04397)
