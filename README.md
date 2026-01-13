# Welcome!

My name is Samantha Chan and I am currently a Health Data Science Master's student at University of California, San Francisco (UCSF). Primarily using Python and R programming, my work focuses on image processing, quantitative analysis, statistical modeling, and machine learning to extract insights from health and biomedical datasets. My current research utilizes CT and MRI image processing to investigate how the trajectory of deep brain stimulation (DBS) leads affects outcomes in patients with Parkinson’s disease.

## Projects
### Da Vinci Nerve Fiber Microscopy Image Analysis
[Github Repository](https://github.com/Gomez-Lab/Neuronal-Image-Processing)

The nerve segmentation analysis involved developing a comprehensive image analysis pipeline to quantify nerve fibers in pig skin microscopy images. Approximately 100 raw z-stack tissue images were first preprocessed to enhance quality and consistency, testing multiple denoising and normalization methods to determine optimal approaches. Downstream analyses extracted quantitative metrics such as fiber density, length, and orientation. The pipeline integrated image preprocessing, segmentation, and statistical analysis, allowing reproducible and scalable evaluation of nerve morphology for research and computational modeling.

### DermaMNIST Multi_Class Classification

[View Project Here](https://samkchan815.github.io/projects/DermaMNIST_Multiclass_Classification.html)

Using the DermaMNIST dataset, this project uses a convolutional neural network to classify dermatological images into seven skin lesion categories. The dataset contains approximately 10,000 dermatoscope images. The CNN utilizes convolutional and pooling layers for hierarchical feature extraction, combined with activation functions and dropout layers to improve learning and prevent overfitting.


### Parkinson's Telemonitoring

[View Report Here](https://samkchan815.github.io/projects/Parkinsons_Telemonitoring_SVR.ipynb)

This project analyzes the Parkinson’s Telemonitoring dataset, which consists of biomedical voice measurements collected from 42 individuals with early-stage Parkinson’s disease enrolled in a six-month remote monitoring trial. Through feature selection and exploratory data analysis, key vocal biomarkers associated with disease severity were identified. Support Vector Regression (SVR) was then applied to predict the Total Unified Parkinson’s Disease Rating Scale (UPDRS) score, demonstrating the potential of voice-based signals for tracking disease progression in a telehealth setting.


### Musical Instrument Major and Minor Chord Classification

[Github Repository]()

This project explores deep learning–based classification of guitar chords using audio-derived spectrograms. I designed and implemented an end-to-end pipeline that converts raw audio recordings into time–frequency representations and trains a convolutional neural network to distinguish between major and minor chords. The current implementation focuses on isolated chord samples to establish a reliable baseline model and evaluation framework. Future extensions of this work will expand the model to operate on full song audio, incorporating temporal segmentation and sliding-window inference to predict chord progressions over time.


## Education								       		
- M.S., Health Data Science	| University of California, San Francisco (_June 2026_)	 			        		
- B.S., Biomolecular Engineering and Bioinformatics | University of California, Santa Cruz (_June 2024_)


## Work Experience
**Graduate Researcher @ University of California - San Francisco Morrison Lab (_May 2025 - Present_)**
- Mapped imaging-derived features onto a standardized brain atlas and applied regularized regression models (Lasso and Ridge) to generate
and evaluate predictive associations between brain regions and outcome measures.
- Developed an image pre-processing workflow to ensure consistent orientation, spacing, and coordinate frame mapping between multimodal
medical images using ANTs and ITK Python packages.
- Generated deep brain stimulation electrode segmentations in postoperative CT scans of Parkinson's patients using ITK-SNAP, including manual electrode delineation to establish ground truth and perform QA validation, enabling accurate downstream computational models.

**Graduate Reseacher @ University of California - San Francisco Wilder Lab (_January 2025 - March 2025_)**
- Integrated large-scale ChIP-seq and RNA-seq datasets using Python and Bash and developed interactive gene expression visualizations that
accelerated identification of regulatory dynamics across time points.
- Automated RNA-seq analysis using Pandas, Matplotlib, and reproducible Python workflows.

**Microscopy Data Analyst @ University of California - Santa Cruz Gomez Lab (_January 2024 - March 2025_)**
- Developed a TensorFlow deep learning model with a CNN architecture, skip connections, and dice loss to segment nerve fibers in pig tissue
images, achieving accurate segmentation that enabled downstream quantitative analysis.
- Conducted comprehensive image analysis using Python programming to determine optimal denoising filters to improve image quality,
leveraging a combination of filters and deep learning methods.
- Processed nerve cell images with thresholding to extract pixel-density metrics and create visualizations for computational analysis using
Matplotlib.
- Created a preprocessing pipeline for the analysis of fiber lengths and angles in microscopy images. Extracted, cleaned, processed, and
analyzed collagen fiber data using Python Pandas package and created visualizations and plots using matplotlib.

**Machine Learning Undergraduate Researcher @ University of California - Santa Cruz Braingeneers Group (_September 2023 - March 2024_)**
- Built an internal Python-based LLM system using PyTorch and Retrieval-Augmented Generation (RAG) to surface lab-specific
documentation and experimental knowledge, reducing time spent searching for internal resources.
- Implemented an MQTT bridge between Slack and a large language model to allow for AI responses through Slack channels.

**Machine Learning Intern @ Immergo Labs (_June 2023 - August 2023_)**
- Developed and validated a long short-term memory (LSTM) model for forward simulation and backward look-ahead in time-series physical
therapy data, improving predictive performance for movement trajectories.
- Optimized and validated biomechanics machine learning models using statistical models in Scikit-learn.
- Created Python 3D visualization tools with Matplotlib and NumPy on Ubuntu to plot positional and rotational vectors and trajectories,
enabling faster analysis of VR and physical therapy biomechanics data.

## Teaching
**Teaching Assistant @ University of California San Francisco(Winter 2026)**
DATASCI 223: Applied Data Science with Python

**Private Tutor (March 2023 - Present)**
Provide targeted English reading, speaking, and listening instruction that helped two students successfully pass the California English Language Proficiency Assessments (ELPAC).

