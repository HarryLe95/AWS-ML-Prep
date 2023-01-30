# Amazon Rekognition
- Service to identify objects, people, text, scenes, activities in images and videos and detect inappropriate contents.
- Facial analysis, faicla serach, etc 

# AWS DeepLens
- Deep learning-enabled video camera. Integrate with AWS ML services and can perform local inference against deployed models provisioned from AWS Cloud. 
- Can use AWS DeepLens dev environment to train CNN then deploy to AWS DeepLens device. 

# AWS Forecast
- Fully managed service to do forecasting on timeseries data 

# AWS Fraud Detector 
- Fully managed fraudetection service - automatically detect potential fraud activities online 

# AWS Comprehend 
- NLP tool to extract insights about the content of documents
- Develop inishgts by recognising the entities, key phrases, language sentiments in a document
- Example use cases 
     - Find documents about a subject using topic modeling - i.e. scan a set of docs to find topics discussed then find relevant documents.
     - Find how customers feel about a product from user comments.


# AWS Translate
- Text translation servie to provide high-quality translation on demand 
- Use-cases: 
    - Enable multilingual UX 

# AWS Transcribe 
- Automatic speech recognition to convert audio to text 

# AWS Deep Learning AMIs
- Deep learning AMI for EC2 instances 
- Features: 
    - With Conda 
    - Base AMI - only has CUDA 


# AWS Polly 
- AWS text to speech service 

# AWS Lex 
- Conversational service NLP - Alexa
- Chatbot services 

# AWS Textract 
- Amazon Textract is a fully managed machine learning service that automatically extracts printed text, handwriting, and other data from scanned documents that goes beyond simple optical character recognition (OCR) to identify, understand, and extract data from forms and tables


# AWS ECR 
- Fully managed Docker container registry to store, manage and deploy Docker images 


# AWS FSx
- Amazon FSx provides fully managed third-party file systems. A file server is a computer responsible for the storage and management of data files so that other computers on the same network can access the files. It enables users to share information over a network without having to physically transfer files.
- Automates the time-consuming administration tasks such as hardware provisioning, software configuration, patching, and backups.
- Use cases:
    - Migrate workloads to cloud - use cloud storage for file share, database and application workload w/o changing code or how data is managed.
    - HPC applications - provides scalable file storage that supports large clusters 
    - Manage backups and long-term data retentions





# Sagemaker Built in Algorithms 
## Factorisation Machine 


## Random Cut Forect 



## Latent Dirichlet Allocation 





# Sagemaker Security 
## Access control
    - For Sagemaker notebook: by default, users logging in to SM nb has root access to install tools and packages. Can access and edit all files on a notebook instance. Possible to set RootAccess to Disabled for notebook instances. 