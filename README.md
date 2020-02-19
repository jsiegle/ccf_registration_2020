# CCF Registration Competition

In collaboration with the [BRAIN Inititative Cell Census Network](biccn.org) (BICCN), 
the [Brain Imaging Library](https://www.brainimagelibrary.org/) (BIL), 
the [Penn Image Computing and Science Lab](PICSL) (http://picsl.upenn.edu/), 
we are running first [Allen Institute for Brain Science](https://portal.brain-map.org/) 
CCF registration competition! 


A brief description of the competition motivation, format, and next steps is below
Motivation

The Allen Mouse Common Coordinate Framework (CCF) defines anatomical locations within an annotated population averaged mouse brain. This resource is already valuable to the field, providing a 3D reference framework for the mouse brain. Enhanced impact is possible if new 3D datasets can be routinely aligned into the CCF space. This enables comparison of results across experiments with a common and objective reference for mouse brain anatomy. Large-scale resources can be built systematically by leveraging automated alignment into a common spatial framework.

Achieving this vision requires robust alignment of new image data into the CCF space, regardless of acquisition modality. The field has produced many options for this task, but unbiased comparison of these techniques does not exist. To benchmark various approaches, and to encourage researchers to share available resources, we propose the Allen Institute for Brain Science organize a competition between CCF alignment tools sourced from the global neuroscience and image processing community.

Competition Format

The Allen Institute for Brain Science will provide image datasets drawn from existing data production pipelines. These may include:

Serial sectioning two photon tomography datasets from the Allen Mouse Connectivity Atlas

Optical projection tomography datasets from the Neuropixels pipeline

fMOST datasets from the whole-brain morphology project

Single-plane slice images with fluorescent nuclear stain from the in-vitro single cell characterization pipeline

Examples of each type with validated annotations are readily available. Further types of annotated data may be sourced from Allen Institute or Brain Initiative Cell Census Network (BICCN)-affiliated projects.

Training sets including data and annotations will be released to competitors ahead of submission deadline. Additional competition test data will be released but annotations withheld by the organizers for results evaluation. Data will be deposited in a cloud storage location accessible to prospective competitors.

Competitors will provide a cloud environment capable of command line execution of their submitted code. The organizers will be responsible for executing each submitted software within its environment and measuring performance. Evaluation criteria will be released prior to the competition and will include global and local alignment accuracy, execution time (both unsupervised and supervised), and robustness to data and parameter inputs. Organizers will publish competitor’s performance comparisons in a peer-reviewed, open-access journal as well as on the Allen Institute website.

Next Steps

Competition start is tentatively scheduled for summer 2020. We will release details regarding datasets, scoring, and entrance details as they become available.

If you have a potential entry, feel free to start work on code optimization and documentation. All code must be executable by the organizers in a cloud environment.

Be sure to keep an eye on this page for updates regarding the competition format and timing. Looking forward to a competition that benefits all of those using the CCF!
