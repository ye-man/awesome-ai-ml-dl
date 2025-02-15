### Cloud, DevOps, Infra

#### System / Infra

  - [serveo.net](serveo.net) - Serveo is an SSH server just for remote port forwarding. When a user connects to Serveo, they get a public URL that anybody can use to connect to their localhost server. See link for other SSH and related alternatives, useful to be able to serve resources across devices i.e. access GPU or other hardware accelerators from another device remotely.

#### Compute & Storage
  
  - [Cray Computers](https://www.cray.com/ai)
  - [GraphCore's IPU](README.md#ipu)
  - [Lambda Labs](https://lambdalabs.com/)

#### Cloud services

  - [vast.ai](about-vast.ai.md) - GPU Sharing Economy. One simple interface to find the best cloud GPU rentals. Reduce cloud compute costs by 3X to 5X
  - [paperspace](https://www.paperspace.com/) - The first cloud built for the future. Powering next-generation applications and cloud ML/AI pipelines. Paperspace is built to scale with your team - pay as you go option for individuals.
  - [valohai](https://www.valohai.com/) | [docs](https://docs.valohai.com/) - Valohai is a machine learning platform. It runs your experiments in the cloud, tracks your experiment history and streamlines data science workflows. DEEP LEARNING MANAGEMENT PLATFORM. Machine Orchestration, Version Control and Pipeline Management for Deep Learning.
  - [Lambda Cloud GPU Instances](https://lambdalabs.com/service/gpu-cloud) - GPU Instances for Deep Learning & Machine Learning

#### Tools
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) - The Snakemake workflow management system is a tool to create reproducible and scalable data analyses. [Slides](https://slides.com/johanneskoester/snakemake-talk-40min#) | [PyPi](https://pypi.org/project/snakemake/)
  - [plz](http://github.com/prodo-ai/plz) - Plz (pronounced "please") runs your jobs storing code, input, outputs and results so that they can be queried programmatically.
  - [Seldon](https://www.seldon.io/open-source/) - Model deployment platform, on kubernetes clusters. | [docs](https://docs.seldon.io/projects/seldon-core/en/latest/) | [github](https://github.com/SeldonIO/seldon-core/blob/master/readme.md) | [use-cases](https://www.seldon.io/use-cases/) | [blogs](https://www.seldon.io/blog/) | [videos](https://www.youtube.com/channel/UCZq33lhQWAsd-8NDqOdjN_g/videos?view_as=subscriber)
  - [Lambda Stack](https://lambdalabs.com/lambda-stack-deep-learning-software) - One-line installation of TensorFlow, Keras, Caffe, Caffe, CUDA, cuDNN, and NVIDIA Drivers for Ubuntu 16.04 and 18.04.
  - [Apache Airflow](https://airflow.apache.org/) - Airflow is a platform to programmatically author, schedule and monitor workflows. Use airflow to author workflows as directed acyclic graphs (DAGs) of tasks. The airflow scheduler executes your tasks on an array of workers while following the specified dependencies.
  - [Nextflow](https://www.nextflow.io/) - Data-driven computational pipelines. Nextflow enables scalable and reproducible scientific workflows using software containers. It allows the adaptation of pipelines written in the most common scripting languages.
  - [StackHPC suites of repositories: AI, ML, DL, Cloud, HPC](https://github.com/stackhpc) | [StackHPC](http://stackhpc.com/)

#### CPU
  - Probing the CPU (Linux/MacOS)
      - [libcpuid](http://libcpuid.sourceforge.net/index.html)
      + Zero overhead performance capturing: use `/proc/interrupts` and `/proc/softirqs`
      + Non-zero overhead, less accurate: use the PMU (capture on- and off-core events)
  - Probing the CPU (Windows)
      - [perfview](https://github.com/Microsoft/perfview) - general profiling on Windows
      - [perfview for .net](https://www.infoq.com/presentations/perfview-net) - excellent overview by Sasha Goldshtein
 
 _Thanks to the great minds on the [mechanical sympathy](https://groups.google.com/forum/#!forum/mechanical-sympathy) mailing list for their responses to my queries on CPU probing._

#### GPU
  - [Know your GPU](https://gist.github.com/neomatrix369/256913dcf77cdbb5855dd2d7f5d81b84)
  - [GPU Server 1 of 2](./gpus/GPU-Server-side-1-of-2.jpg) | [GPU Server 2 of 2](./gpus/GPU-Server-side-2-of-2.jpg) | [Applications of GPU servers](./gpus/Applications\ of\ GPU\ Server.jpg) - [checkout the manufacturers](http://manli.com.hk)
  - [Embedded Vision Solutions for NVIDIA Jetson Series](https://www.avermedia.com/professional/category/nvidia_jetson_solutions) | [Embedded Vision Family Brochure](http://storage.avermedia.com/web_release_www/Solutions/Embedded_Vision_Solutions_brochure_20190429.pdf)

#### TPU
  - [How to harness the Powers of the Cloud TPU](https://medium.com/bitgrit-data-science-publication/how-to-harness-the-powers-of-the-cloud-tpu-3939dc363d9f)

#### IPU
  - [GraphCore](http://graphcore.ai) | Videos: [Simon Knowles - More complex models and more powerful machines](https://www.youtube.com/watch?v=dLvkF_TmyAc&feature=youtu.be) | [Graphcore tech Concept](https://youtu.be/cSXbhEsUUGo?t=916) | [A new kind of hardware designed for machine intelligence - GraphCore Presentations](http://www.bristol.bcs.org.uk/2017/graphcore.pdf) | [V‍ID‌EO‌‍: SCA‌LING‌‍ THRO‌UG‍HP‌‍U‌T P‍R‌O‍C‍ESSO‌‍RS FO‌‍R‍ MAC‌HINE INTELLIG‌ENC‌‍E](https://www.graphcore.ai/posts/video-scaling-throughput-processors-for-machine-intelligence)

# Contributing

Contributions are very welcome, please share back with the wider community (and get credited for it)!

Please have a look at the [CONTRIBUTING](../CONTRIBUTING.md) guidelines, also have a read about our [licensing](../LICENSE.md) policy.

---

Back to [main page (table of contents)](../README.md)