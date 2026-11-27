# Luis Torres, PhD

Medical physicist turned scientific solutions engineer. I build imaging and machine-learning tools for medical research, and I help build open-source perfusion MRI software with [OSIPI](https://osipi.ismrm.org/).

[Website](https://luigibytes.com/) · [LinkedIn](https://www.linkedin.com/in/luigibytes/) · [Google Scholar](https://scholar.google.com/citations?user=EfaQZA8AAAAJ&hl=en) · [GitLab](https://gitlab.com/luistorres2)

## About me

I'm a Senior Scientific Solutions Engineer at [Flywheel](https://flywheel.io/). I work with pharma and academic research teams to turn their imaging questions into automated pipelines: curation, quality control, scan classification, de-identification, segmentation and quantitative analysis across MR, CT and PET. More and more of that work is deep-learning models and LLM tooling.

Before Flywheel I did my PhD in Medical Physics at the University of Wisconsin–Madison, working on quantitative lung MRI: perfusion imaging, ultrashort echo time imaging, and motion-compensated reconstruction on GPUs.

I'm originally from New Mexico and now live in Chapel Hill, North Carolina.

## What I'm working on

- **[osipy](https://github.com/OSIPI/osipy)**: OSIPI's open Python library for perfusion MRI analysis. I designed its architecture and lead the task force that builds it, with the goal of making perfusion imaging more reproducible. I also lead OSIPI's website and technical support task force, and mentored Google Summer of Code students in 2024 and 2025.
- **Scan classification from physics**: working out what an MR, CT or PET series actually is from how it was acquired, not from what someone named it. I presented the open-source fw-classification package at ISMRM 2024.
- **Machine learning for imaging**: putting 3D segmentation models into research pipelines, retraining them for new populations, and fine-tuning vision-language foundation models for imaging tasks.
- **LLM tooling**: retrieval-augmented documentation assistants, agent pipelines in CI, and MCP servers that let agents work with scientific data platforms.

## Code you'll find here

- **[pydemons](https://github.com/ltorres6/pydemons)**: the demons registration algorithm written on SigPy, so it runs on GPUs.
- **[imoco](https://github.com/ltorres6/imoco)**: a Python version of iMoCo, the motion-compensated reconstruction method developed by Xucheng Zhu and the [PulmonaryMRI](https://github.com/PulmonaryMRI/imoco_recon) group.
- **[ltorres6.github.io](https://github.com/ltorres6/ltorres6.github.io)**: the source for my website.

Most of my day-to-day code lives in Flywheel's GitLab, so the contribution graph here is quieter than my actual week.

## Toolbox

- **Languages**: Python (NumPy/CuPy, SigPy, PyTorch), C++/CUDA, MATLAB, R
- **Imaging**: ITK, ANTs, BART, non-Cartesian and compressed-sensing reconstruction, registration, segmentation
- **Infrastructure**: Docker, Kubernetes, GitLab CI/CD, Slurm and HTCondor, Azure, AWS, GCP

## Outside of work

I tinker with a homelab and with local, self-hosted voice assistants for Home Assistant, which explains some of the forks.

## Get in touch

I'm always glad to talk about medical image processing, machine learning in healthcare, and open-source scientific software, and I enjoy mentoring through programs like Google Summer of Code. LinkedIn is the best way to reach me.
