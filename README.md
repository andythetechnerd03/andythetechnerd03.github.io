# Portfolio
Likes to do research and application in AI, also likes watching random stuff on YouTube and buys lots of books but never reads them. Currently working on graduate thesis on medicine.

## Education
### FPT University | _2021 - 2025_ 
- Graduated (as **Valedictorian**): _Nov 2025_
- Bachelor of Engineering in Artificial Intelligence.
- GPA: 9.12 / 10

### VNU-HCM High School for the Gifted | _2018 - 2021_
- High School Diploma - Specialized English Class.
- GPA: 9.0 / 10

## Work Experience
### AI Engineer @ FPT Software AI Center | _August 2024 - Present_
- Built and experimented with reasoning-driven legal document review and auto-edit with over 80% detection and edit accuracy.
- Spearheaded design and implementation of project metric forecasting on historical data, which is then wrapped in an agentic workflow supercharged with on-premise LLM.
- A key member in development of MS Teams chatbot for supporting PMs (serving 1K+ projects). Incorporated advanced RAG techniques and robust tool calling for QnA of company and project files.
- Achievements: Top 1 Learner in AI Augmented Engineer Program of Q3/2025 (2 NVIDIA Certificates)

### Data Engineer @ FPT Software | _November 2023 - August 2024_
- Built data pipeline for a large-scale data processing system, complex visualization and predictive modeling (raw data approximately > 10GB).
- Learned and implemented a powerful low-code [Data Science platform](https://www.dataiku.com/), which helped the team automate the data pipeline flow and reduce the time to finalize the project.
- Cut down data processing time and memory footprint by several times by optimizing the data type, asynchronous programming, and accelerated hardware.
- Addressed chatbot limitations such as topic drift and datetime reasoning using clustering and function calling. The chatbot ended up winning the [iKhiến 2024 competition](https://chungta.vn/i-khien/synnex-fpt-gianh-giai-vang-ikhien-2024-ngay-san-pham-thi-dau-tien-1139019.html) for new initiatives.
- Prepared question-answer data pairs to fine-tune a Large Multimodal Model on face description system.

### AI Intern @ Quy Nhon AI Center | _September 2023 - December 2023_
- Trained and evaluated a table recognition model on synthetically generated data, plus Streamlit application demo on Docker.
- Developed and published a Python [package](https://pypi.org/project/table-transformer/) for table recognition and data synthesis tool.
- Handled and peer-reviewed 100+ OCR and KIE image labeling images per day (as part of ML project) using PaddleOCR labeling tool.
- Turned model into a containerized REST API for easy deployment.

### AI Bootcamp Student @ Cinnamon AI | _May 2023 - August 2023_
- Successfully completed a 3-month intensive Full-Stack AI Bootcamp through various exercises and final project.
- Exercises include:
    - Model Compression using Quantization and Pruning. Achieved a 40% smaller model while only sacrificing less than 5% reduction of accuracy on CIFAR-100 Dataset. [code](https://github.com/andythetechnerd03/Compressing-GoogleNet)
    - Building a Basic Calculator web application using React and Bootstrap. [code](https://github.com/andythetechnerd03/simple-calculator-app)
    - Continuous Integration / Delivery with GitHub / GitHub Action.
    - DataOps with Data Version Control - DVC.
    - NLP - BERT model fine-tuning.
- **Final Project**: Deployment of [3D Body Pose Estimation and Motion Capture](https://github.com/facebookresearch/frankmocap) on a cloud-based web application. [code](https://github.com/vhbaoduy/motion_capture).

### YouTuber @ DNATech | _2013 - 2023_
- Created and edited videos on technology, smartphones, and shared hacking tutorials.
- In 2023, the channel also served as a platform for teaching Mathematics for Machine Learning to FPT University students. [Playlist](https://youtube.com/playlist?list=PLvt7Q4KDA-3wpG5Q__9QrjykAFx_m_jGE&si=Qw8JivWoqAA48T48)
- Reached 1.9K subscribers and over 100k views.
- Link: [DNATech](https://www.youtube.com/@dnatech8524).


## Projects
### KAN It Play Flappy Bird | _May 2024 - August 2024_
![KAN](assets\projects\model.drawio.png)
- Built a Flappy Bird game-playing AI using Reinforcement Learning, but replaces traditional Multi-Layer Perceptron (MLP) with **Kolmogorov-Arnold Network (KAN)**. Achieved faster convergence and equivalent high score.
- Sucessfully merged with the [AwesomeKAN](https://github.com/mintisan/awesome-kan) repository which showcases awesome KAN projects.
- *Tech Stack*: Python, Pygame, PyTorch, Streamlit.

[Code & Report](https://github.com/andythetechnerd03/KAN-It-Play-Flappy-Bird)

### Soccer Match Outcome Prediction | _May 2024 - August 2024_
![Soccer](assets\projects\ManeChanceTrack.webp)
Source: [SoccerMatics](https://soccermatics.readthedocs.io/en/latest/lesson2/GeometryOfShooting.html)
- *Role*: Data Scientist.
- Performed complex feature engineering using **spatial / temporal** data.
- Developed a model to predict the probability of goal event using 2018-19 Top 5 European Leagues data.
- *Tech Stack*: Python, scikit-learn, Pandas, Matplotlib, Gradio.

[Report](assets/projects/Final-Report%20DSP391m%20Group%205.pdf)

### Vietnamese Text Summarization in Poem Format | _January 2024 - April 2024_
![VistralPoem](assets\projects\poem.png)
- *Role*: Team Leader, AI Engineer.
- Developed and fine-tuned a `Vistral-7B-Chat` LLM model for Vietnamese text summarization in five-word poem.
- Utilized prompt engineering to tell a story using pre-existing Vietnamese poems to be used as training and testing data.
- Optimized training time by seven-fold using various LLM fine-tuning techniques, such as FlashAttention, QLoRA, etc.
- Further cut down inference time by 10x on CPU using C++ conversion and GGUF quantization.
- *Tech Stack*: Python, Hugging Face, PyTorch, C++, Axolotl, Gradio.

[Code](https://github.com/andythetechnerd03/Vietnamese-Text-Summarization-Poem) | [HuggingFace](https://huggingface.co/andythetechnerd03/VistralPoem5) | [Report](https://docs.google.com/document/d/1rF63ua9QoVLhvKQZmrTLT9VwsssyTrZ_/edit?usp=sharing&ouid=101433844092514499329&rtpof=true&sd=true) | [Demo](assets\projects\vistralpoem.mp4)

### IELTS Writing Task 2 Next Sentence Prediction | _Jan 2023 - May 2023_
![IELTS](assets\projects\ielts.png)
- *Role*: Researcher
- Researched on methods of Data Augmentation using Paraphrasing and Back-Translation for IELTS Writing Task 2.
- Presented and gave demo to the judges of the FPT Edu Research Festival.
- *Tech Stack*: Python, PyTorch, Hugging Face, Gradio.

[code](https://github.com/andythetechnerd03/ielts_writing_gen)

### Face Recognition System using Contrastive Learning | _Jul 2023 - Aug 2023_
![Face](<assets\projects\face.png>)![Face](<assets\projects\face2.png>)
- Trained a Siamese Network on AT&T Dataset using Contrastive Learning to encode and differentiate faces.
- Deployed model on Python and achieved roughly 25 FPS on CPU and ONNX optimization.
- *Tech Stack*: Python, PyTorch, ONNX, OpenCV.

[code](https://github.com/andythetechnerd03/Face-Recognition-with-MediaPipe-and-Siamese)

### Coursera Quiz Scraper | _Mar 2023 - Aug 2024_
- Developed a Python script to scrape Coursera quizzes and answers using BeautifulSoup, followed by reformatting and upload to Quizlet.
- Helped hundreds of FPT University students majoring in AI to prepare for exams and achieve high scores.
- *Tech Stack*: Python, BeautifulSoup.

[Quizlet](https://quizlet.com/user/dinhngocan102003/sets) | [code](https://github.com/andythetechnerd03/Coursera_to_Quizlet)

## Awards

**Honor** | **Issuer** | **Date**
⭐ Consolidation Prize (Top 10) | FPT Edu Research Festival Finale | _Aug 2024_.
⭐ 4x Excellent Student (Top 1%) | Faculty of Engineering - FPT University | _Spring 2022, Fall 2022, Spring 2023, Summer 2024_.
🥇 Most Outstanding Student (Top 0.1%) | Faculty of Engineering - FPT University | _Sep 2023_.
🥈 Silver Medal | Vietnam Mathematical Olympiad - Calculus Section | _Apr 2023_.
🥈 Runner-Up | TopCV English Contest | _Jun 2022_.
🥈 Runner-Up | Hanoi Online Math Modeling Contest | _Sep 2021_.
🥈 Second Prize | Ho Chi Minh City-level Excellent Student Competition (English) | _Mar 2021_.

## Publications
	
[1] Van Phuc Phan, Dat Nguyen Minh, **An Dinh Ngoc**, and Huy Phan Thanh. “Rx Strategist: Prescription Verification Using LLM Agents System,” September 5, 2024. [paper](https://arxiv.org/abs/2409.03440v1).


## Certificates

I have a lot more, but these are just a few notable ones.

**Name** | **Issuer** | **Date** | **Link**
**Dataiku Expert AI Consultant** | Dataiku | _Apr 2024_ | [Link](https://verify.skilljar.com/c/xrs49wj9sm7d)
**TensorFlow Developer Certificate** | Google | _Mar 2024_ | [Link](https://www.credential.net/9b445af0-b4d2-4dae-b2e8-0e9d07467d8c#gs.65l5z3)
**Advanced Natural Language Processing 04** | New Turing Institute | _Mar 2024_ | [Link](assets/certificates/vietai_nlp.jpg)
**Big Data Specialization** | University of California, San Diego | _Aug 2023_ | [Link](https://www.coursera.org/account/accomplishments/specialization/certificate/AY7NHEZ3KFFA)
**Deep Learning Specialization** | DeepLearning.AI | _Jun 2023_ | [Link](https://www.coursera.org/account/accomplishments/specialization/certificate/62V4UCBGSLAJ)


