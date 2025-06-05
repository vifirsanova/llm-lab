# LLM Lab

The lab supervisor and crazy idea generator: Victoria vifirsanova_gmail.com

## Our Projects

1. [TranscribePro](#1-transcribepro)
2. [Accessibility-Focused Virtual Assistant](#2-accessibility-focused-virtual-assistant)
3. [Linguistic Approaches to Explainable AI](#3-linguistic-approaches-to-explainable-ai)
4. [Firewall](#4-firewall)
5. [LLM Toolkit](#5-llm-toolkit)

### 1. TranscribePro
**Time Period**: Ongoing  

**Technologies**: Kotlin, Whisper.cpp, JNI, LLMs, IPA transcription  

#### Description
Mobile application for professional-grade audio transcription with linguistic analysis features, designed for language learners and phoneticians. Provides multiple transcription variants including IPA notation, pauses, intonation markers, and other linguistic metadata.

#### Media
- [Application Demo Video](https://drive.google.com/file/d/1kCYCH-I-2egPyZYEXa04k4qwf66LbvZs/view?usp=sharing) (Detailed overview)

#### Key Features
- Audio recording and file processing
- Multi-format transcription output (standard + linguistic)
- Educational focus for phonetics study

#### Current Tasks
- [Synthetic dataset](https://github.com/vifirsanova/synth-dataset/) generation using LLMs
- ASR model fine-tuning
- Kotlin/JNI intдатасетegration for ML models
- UI restoration from prototype
- Evaluation (WER & other metric scores) and reports

#### Repositories
- [Initial Prototype (UI Only)](https://github.com/vifirsanova/TranscribePro)
- [Current Version (Whisper.cpp Integration)](https://github.com/pseudoerr/TranscribePro)

#### Technical Challenges
- Bridging native ML models with Kotlin via JNI
- Maintaining linguistic accuracy in transcriptions
- Reconstructing UI from prototype version

### 2. Accessibility-Focused Virtual Assistant
**Time Period**: Ongoing

**Technologies**: Python, LLMs, WCAG 2.2, Web Development  

#### Description
AI assistant generating adaptive web interfaces for neurodivergent students (ASD, ADHD). Goes beyond text generation by creating WCAG-compliant outputs with:
- Semantic highlighting
- Contextual hyperlinks
- Interactive tooltips
- Dynamic content adaptation

#### Demo & Code
- [System Walkthrough Video](https://drive.google.com/file/d/1wiWQ-B_36F-i5PtzgUMMPaxF72zD-l7R/view?usp=sharing)
- [Anonymous Repository](https://github.com/Anonymous-Submitting/anonymous-submission) (under peer review)

#### Current Progress
- Completed:  
  - Core generation algorithms  
  - GUI prototypes
  - User surveys (target group: 50+ participants)  
- In Progress:  
  - LLM benchmarking (speed/quality)  
  - Accessibility metrics framework
  - WCAG compliance validator  
- Perspectives:
  - Web app deployment
  - Mobile version (Flutter)  
  - Browser extension  

#### Research Perspectives
- Dynamic interface adaptation based on:
  - User's cognitive profile
  - Content complexity analysis
- Optimizing model performance

### 3. Linguistic Approaches to Explainable AI
**Time Period**: Ongoing

**Technologies**: Python, PyTorch, Transformers, Graph Theory, RAG architectures  

#### Description
Novel XAI framework combining formal linguistics with graph-based semantic analysis. Two complementary tools:
1. **Formal Syntax Modeling**  
   - LLM-based syntactic structure prediction  
   - Rule-based validation system  
   - [GitHub Repository](https://github.com/vifirsanova/llm-syntax/)  

2. **Graph Semantic Analyzer**  
   - Dynamic knowledge graph construction  
   - Relation extraction using linguistic theory  
   - [GitHub Repository](https://github.com/vifirsanova/aggile/)  

#### Research Objectives
- Develop quantifiable metrics for AI interpretability  
- Bridge formal linguistics with modern NLP systems  
- Create industry-applicable RAG integration protocols  

#### Current Tasks
- LLM API adapters 
- Benchmarking suite and evaluation framework, metric tables, comparative analysis reports
- RAG pipeline integration prototypes, case studies

#### Key Features
- Parse tree visualization interface  
- Dynamic semantic graph modeling
- Explainability score calculation (in perspective)

### 4. Firewall
**Time Period**: Ongoing

**Technologies**: Python, PyTorch, Cryptographic Hashing  

#### Core Components
1. **Information Retrieval**  from cybersecurity ontology (fully synthetic wiki-like graph ontology generated with [AGGILE](https://github.com/vifirsanova/AGGILE/))
2. **Adversarial Classifier**  based on GAN and LoRA architectures
3. **Alternative Storages**: сaching system and blockchain 
  
#### Benchmarks
- Dataset: [Prompt Injections Dataset @ HuggingFace](https://huggingface.co/datasets/hse-llm/prompt-injections)

### 5. LLM Toolkit

- [Custom tokenizer](https://github.com/vifirsanova/stat-llm)
- [Convolution-based model compression algorithm](https://github.com/vifirsanova/convolutional_quantization)
- GRAMMATICALITY JUDGEMENT BENCHMARK
    - A set of grammatical and their non-grammatical variations for binary classification and assessing the model linguistic competernce. See the data snippet at [HuggingFace Datasets](https://huggingface.co/datasets/missvector/multi-wiki-grammar)
- CONTRADICTIONS BENCHMARK
    - A set if two-fold utterances containing truthfull and false information for assessing LLM hallucinations' impact. See the data snippet at [HuggingFace Datasets](https://huggingface.co/datasets/missvector/nli-questions)
