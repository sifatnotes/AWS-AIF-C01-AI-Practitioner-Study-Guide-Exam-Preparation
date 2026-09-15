# AWS-AIF-C01-AI-Practitioner-Study-Guide-Exam-Preparation
Independent AWS AIF-C01 study guide covering AI/ML fundamentals, generative AI, foundation models, responsible AI, security, compliance, AWS AI services, labs, and exam preparation.
# AWS AIF-C01: AWS Certified AI Practitioner Study Guide

## Introduction

This repository is an independent study guide for **AWS Certified AI Practitioner (AIF-C01)**. It covers AI/ML fundamentals, generative AI, foundation models, responsible AI, security, compliance, governance, AWS AI services, practical labs, and exam preparation.

AIF-C01 is a foundational certification for people who use or work with AI/ML technologies on AWS without necessarily building AI/ML solutions themselves.

> **Current exam:** AWS published AIF-C01 Exam Guide version 1.1 on April 30, 2026. Always check the latest AWS exam guide before scheduling the exam.

## Exam Overview

| Item | Details |
|---|---|
| Vendor | Amazon Web Services (AWS) |
| Certification | AWS Certified AI Practitioner |
| Exam | AIF-C01 |
| Level | Foundational |
| Purpose | Validate foundational AI, ML, generative AI, and AWS AI-service knowledge |
| Target candidates | Professionals exploring AI/ML on AWS across cloud, development, data, IT, AI/ML, and business roles |
| Duration | 90 minutes |
| Questions | 65 total: 50 scored + 15 unscored |
| Question types | Multiple choice, multiple response, ordering, and matching |
| Passing score | 700/1000 |
| Exam delivery | Pearson VUE testing center or online proctored |
| Prerequisites | None |
| Validity | 3 years |

AWS recommends familiarity with core AWS services such as Amazon EC2, Amazon S3, AWS Lambda, Amazon Bedrock, and Amazon SageMaker AI, along with IAM, the AWS Shared Responsibility Model, and AWS pricing.

The exam focuses on foundational knowledge. Developing AI/ML models, feature engineering, hyperparameter tuning, building AI/ML infrastructure, and advanced mathematical/statistical analysis are outside the target candidate scope.

## Who Should Take It?

AIF-C01 is suitable for:

- Cloud professionals adding AI skills
- IT professionals
- Developers and software professionals
- Data professionals
- Business and line-of-business professionals
- Students beginning AI on AWS
- Professionals evaluating generative AI use cases

AWS describes the target candidate as having up to six months of exposure to AI/ML technologies on AWS and using, but not necessarily building, AI/ML solutions.

## Exam Objectives / Domains

The current AIF-C01 exam has five domains:

### 1. Fundamentals of AI and ML — 20%

Study:

- AI, ML, deep learning, neural networks
- Computer vision
- Natural language processing
- Models and algorithms
- Training and inference
- Bias and fairness
- LLMs
- Generative AI
- Agentic AI
- Batch and real-time inference
- Structured and unstructured data
- Supervised, unsupervised, and reinforcement learning
- AI/ML use cases
- Regression, classification, and clustering
- ML lifecycle
- MLOps fundamentals
- Model and business metrics

### 2. Fundamentals of Generative AI — 24%

Study:

- Generative AI concepts
- Foundation models
- Large language models
- Tokens
- Embeddings
- Prompt engineering
- Context
- Inference
- Model limitations
- Hallucinations
- AWS infrastructure for GenAI
- Amazon Bedrock
- Generative AI application architecture
- Model selection

### 3. Applications of Foundation Models — 28%

Study:

- Foundation model use cases
- Prompt techniques
- Retrieval-augmented generation (RAG)
- Knowledge bases
- Agents
- Fine-tuning concepts
- Model customization
- Model evaluation
- Inference parameters
- Foundation-model application development
- Amazon Bedrock capabilities
- AWS AI/ML services relevant to foundation models

### 4. Guidelines for Responsible AI — 14%

Study:

- Bias
- Fairness
- Inclusivity
- Robustness
- Safety
- Veracity
- Transparency
- Explainability
- Model selection
- Sustainability
- Intellectual-property risks
- Hallucinations
- Customer trust
- Human oversight
- Amazon Bedrock Guardrails

### 5. Security, Compliance, and Governance for AI Solutions — 14%

Study:

- IAM permissions
- Encryption
- Data protection
- Amazon Macie
- AWS PrivateLink
- AWS Shared Responsibility Model
- Amazon Bedrock security features
- Guardrails
- Data lineage
- Data cataloging
- Model documentation
- Data quality
- Privacy
- Data access control
- Data integrity
- AI governance and compliance

## Detailed Study Notes

### AI vs ML vs Generative AI

**Artificial Intelligence (AI)** is the broad field of creating systems capable of performing tasks associated with human intelligence.

**Machine Learning (ML)** uses data and algorithms to learn patterns and make predictions or decisions.

**Generative AI** creates new content such as text, images, audio, or code.

**Agentic AI** can use models, tools, and workflows to accomplish tasks with a greater degree of autonomy.

### Training vs Inference

**Training** is the process of learning patterns from data.

**Inference** is using a trained model to produce predictions or outputs.

Common inference patterns include real-time, batch, asynchronous, and serverless approaches.

### Foundation Models

Foundation models are broadly trained models that can be adapted to many tasks.

Important concepts include:

- Tokens
- Embeddings
- Context
- Prompting
- Inference
- Fine-tuning
- Retrieval
- Model evaluation

### Prompt Engineering

A useful prompt should clearly communicate the task and relevant context.

**Weak:**
`Summarize this.`

**Better:**
`Summarize this report for a senior business audience in five bullet points. Highlight financial risks and recommended actions.`

Prompt quality can affect the usefulness and consistency of model output.

### RAG

Retrieval-Augmented Generation combines information retrieval with generative AI.

Typical flow:

`User Query → Retrieve Relevant Data → Add Context → Foundation Model → Response`

RAG can help a model use organization-specific information without requiring the model to be retrained for every new document set.

### Amazon Bedrock

Amazon Bedrock provides managed access to foundation models and capabilities for building generative AI applications.

Study its role in:

- Model selection
- Prompting
- Knowledge bases
- Agents
- Guardrails
- Model customization
- Generative AI application development

### Responsible AI

AI systems should be evaluated for:

- Bias
- Fairness
- Safety
- Robustness
- Transparency
- Explainability
- Privacy
- Accuracy
- Inclusivity

AI-generated content should be reviewed before important business decisions are made.

### AI Security

Protect AI workloads using appropriate identity, permissions, encryption, network controls, data protection, and service-specific safeguards.

Important concepts include IAM, encryption, PrivateLink, Macie, Bedrock Guardrails, data lineage, and secure data access.

## Important Concepts

- AI vs ML vs GenAI
- Deep learning
- Neural networks
- Supervised learning
- Unsupervised learning
- Reinforcement learning
- Classification
- Regression
- Clustering
- Training vs inference
- LLMs
- Foundation models
- Tokens
- Embeddings
- Prompt engineering
- RAG
- Knowledge bases
- AI agents
- Fine-tuning
- Model evaluation
- Amazon Bedrock
- Amazon SageMaker AI
- Responsible AI
- Bias and fairness
- Explainability
- Hallucinations
- IAM
- Encryption
- Data lineage
- AI governance

## Practical Examples / Labs

Use AWS Skill Builder, AWS Builder Labs, or an authorized AWS environment.

1. Explore Amazon Bedrock concepts and available foundation models.
2. Practice writing structured prompts.
3. Compare zero-shot and few-shot prompting.
4. Create a simple RAG architecture diagram.
5. Explore embeddings and vector-search concepts.
6. Compare traditional ML and foundation-model use cases.
7. Examine model evaluation metrics.
8. Explore Amazon SageMaker AI at a conceptual level.
9. Review IAM permissions for an AI workload.
10. Explore responsible AI and Bedrock Guardrails.
11. Design an AI application with protected data.
12. Identify potential hallucination, bias, privacy, and security risks.

Never upload confidential information or test against AWS resources without authorization.

## Study Strategy

Start with the official AIF-C01 Exam Guide and prioritize the largest domains:

1. Applications of Foundation Models — 28%
2. Fundamentals of GenAI — 24%
3. Fundamentals of AI and ML — 20%
4. Responsible AI — 14%
5. Security, Compliance, and Governance — 14%

Focus on **concepts and AWS service use cases**, not coding or advanced mathematical ML.

AWS recommends its Exam Prep Plan, Official Practice Question Set, Official Pretest, Builder Labs, Cloud Quest, AWS Jam, SimuLearn, and Official Practice Exam.

Do not use exam dumps, leaked questions, or recalled-question collections.

## 30-Day Study Plan

| Days | Focus |
|---|---|
| 1–5 | AI/ML fundamentals and terminology |
| 6–8 | ML types, use cases, lifecycle and metrics |
| 9–13 | Generative AI and foundation-model concepts |
| 14–18 | Amazon Bedrock, prompting, RAG and knowledge bases |
| 19–22 | Foundation-model applications and customization |
| 23–25 | Responsible AI, bias, fairness, explainability |
| 26–27 | Security, compliance, governance and IAM |
| 28 | Full domain revision |
| 29 | Official practice questions/pretest |
| 30 | Official practice exam + weak-area review |

## Common Mistakes

- Confusing AI, ML, deep learning, and GenAI.
- Memorizing AWS services without understanding their use cases.
- Assuming generative AI always produces accurate information.
- Ignoring hallucinations and responsible AI.
- Confusing RAG with fine-tuning.
- Over-focusing on coding despite the foundational exam scope.
- Ignoring security and data-protection concepts.
- Confusing training with inference.
- Ignoring business metrics when evaluating AI solutions.
- Using exam dumps instead of legitimate resources.

## Exam-Day Tips

- Read the entire scenario before selecting an answer.
- Identify whether the question concerns AI fundamentals, GenAI, foundation models, responsible AI, or security.
- Look for requirements involving cost, accuracy, privacy, scalability, explainability, or human oversight.
- For service-selection questions, choose the AWS service that best matches the stated use case.
- For multiple-response questions, select all answers required by the question.
- Unanswered questions are scored as incorrect, but AWS states there is no penalty for guessing.
- Manage the 90-minute exam carefully.

## Final Checklist

- [ ] Understand AI/ML fundamentals
- [ ] Know supervised, unsupervised, and reinforcement learning
- [ ] Understand GenAI and foundation models
- [ ] Practice prompt engineering
- [ ] Understand RAG and embeddings
- [ ] Review Amazon Bedrock
- [ ] Review SageMaker AI
- [ ] Understand responsible AI
- [ ] Review hallucinations and bias
- [ ] Understand AI security and IAM
- [ ] Review compliance and governance
- [ ] Complete official practice resources
- [ ] Check the latest AWS exam guide

## Official Resources

- AWS Certified AI Practitioner: https://aws.amazon.com/certification/certified-ai-practitioner/
- AIF-C01 Exam Guide: https://docs.aws.amazon.com/aws-certification/latest/ai-practitioner-01/ai-practitioner-01.html
- AIF-C01 Exam Guide PDF: https://docs.aws.amazon.com/pdfs/aws-certification/latest/ai-practitioner-01/ai-practitioner-01.pdf
- AWS Certification Exam Guides: https://docs.aws.amazon.com/aws-certification/latest/examguides/aws-certification-exam-guides.html
- AWS Skill Builder: https://skillbuilder.aws/
- Amazon Bedrock: https://aws.amazon.com/bedrock/
- Amazon SageMaker AI: https://aws.amazon.com/sagemaker/

## Voucher / Discount

Learn SecByte provides certification voucher options and discounts where available.

**AWS AIF-C01 voucher:**

https://learn.secbyte.org/vouchers/aws-aif-c01

Check the current voucher offer, pricing, eligibility, expiration, and availability before purchasing. Voucher terms may change.

## Disclaimer

This is an independent/community study guide and is not affiliated with or endorsed by Amazon Web Services. AWS, Amazon Bedrock, Amazon SageMaker, Amazon S3, Amazon EC2, AWS Lambda, and related names are trademarks of Amazon Web Services, Inc.

Exam objectives, AWS services, pricing, exam policies, languages, and availability may change. Candidates should verify current information with AWS before registering or purchasing a voucher.

This repository contains educational material only and does **not** contain exam dumps, leaked questions, or recalled exam questions.
