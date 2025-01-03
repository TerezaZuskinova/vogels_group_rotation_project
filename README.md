# vogels_group_rotation_project

This repository comprises all the reasonable jupyther notebooks I produced during my internship at Vogels group at ISTA. The report write-up is available at https://www.overleaf.com/read/mgntgtqkjqtv#b04397

## The project
I am building upon the work of Richard Gao et al. [Deep inverse modeling reveals dynamic-dependent invariances in neural circuit mechanisms](https://www.biorxiv.org/content/10.1101/2024.08.21.608969v1)
I started from code available at the corresponding [github page](https://github.com/mackelab/automind/tree/main) and worked with the [Demo-1](https://github.com/mackelab/automind/blob/main/notebooks/demo-1_automind_inference_workflow.ipynb) and helped to create [Demo-2](https://github.com/mackelab/automind/blob/main/notebooks/demo-2_automind_inference_from_spikes.ipynb) after finding bugs in Demo-1 when I tried to use it with my raw dataset. In Demo-2, we added targeting to a real experimental recording. Specifically, we want to discover circuit models that can reproduce a multi-electrode array recording from the organoid dataset. 

I am posting notebooks:
- an example code how the Demo-1 worked when I did not have the inference running and was just trying to find the closest match withing the samples from the posterior already presampled by Richard to my target stats [Example]
- 
