# Lab Projects

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

**BENCHMARKS**

- CYBERSECURITY BENCHMARK
    - A set of synthesized and real-life prompts for user query binary classification: malicious/non-malicious prompts. See the data snippet at [HuggingFace Datasets](https://huggingface.co/datasets/hse-llm/prompt-injections) 
- GRAMMATICALITY JUDGEMENT BENCHMARK
    - A set of grammatical and their non-grammatical variations for binary classification and assessing the model linguistic competernce. See the data snippet at [HuggingFace Datasets](https://huggingface.co/datasets/missvector/multi-wiki-grammar)
- CONTRADICTIONS BENCHMARK
    - A set if two-fold utterances containing truthfull and false information for assessing LLM hallucinations' impact. See the data snippet at [HuggingFace Datasets](https://huggingface.co/datasets/missvector/nli-questions)

**FIREWALL**

- INFORMATION RETRIEVAL
- ADVERSARIAL CLASSIFIER
    - PRE-TRAINED MODEL
    - TRAINING A CUSTOM MODEL*
- CACHING
- BLOCKCHAIN STORAGE

**USER INTERFACE GENERATORS**

- ACCESSIBLE INTERFACE GENERATOR
- COMMAND LINE INTERFACE
- STANDARD GRAPHICAL USER INTERFACE

**VECTOR DATABASE**

- RELATIONAL DATABASE
- NON-RELATIONAL DATABASE
- GRAPH DATABASE

**COMPRESSION & INTERPRETABILITY**

- CONVOLUTIONAL COMPRESSION*
- FORMAL GRAMMAR SYNTACTIC PROBING
- GRAPH THEORY SEMANTIC PROBING

**TOKENIZATION**

- FINE-GRANED TOKENIZER*
- MULTIMODAL TOKENIZER*

**MULTIAGENT**

- REINFORCEMENT LEARNING META-ALGORITHM
- STATISTICAL META-ALGORITHM
- GENERATIVE META-ALGORITHM

*The module is not available if you connect through API.

