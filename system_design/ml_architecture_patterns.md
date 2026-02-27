Offline vs Online systems

Training vs Inference

Batch vs Real-time inference

Data pipelines

Feature engineering pipeline

Model lifecycle

Resources

Google ML Systems Design
https://developers.google.com/machine-learning/guides/rules-of-ml

Full Stack Deep Learning (Free course)
https://fullstackdeeplearning.com/

Made With ML
https://madewithml.com/

2️⃣ End-to-End ML Architecture
Topics

Data collection

Data validation

Feature store

Model training

Model evaluation

Model registry

Model deployment

Monitoring & feedback loop

Resources

ML System Design (Chip Huyen)
https://huyenchip.com/ml-system-design/

MLOps Guide
https://ml-ops.org/

3️⃣ Common ML Architecture Patterns
🔹 Batch Inference Pattern

Topics:

Scheduled model runs

Large dataset scoring

ETL + Model pipeline

Resources:
https://developers.google.com/machine-learning/crash-course

🔹 Online Inference Pattern

Topics:

Real-time API prediction

Low-latency serving

Feature retrieval at request time

Caching predictions

Resources:
https://www.tensorflow.org/tfx

🔹 Streaming ML Pattern

Topics:

Real-time feature updates

Event-driven pipelines

Kafka + ML pipeline

Resources:
https://kafka.apache.org/documentation/

🔹 Microservices ML Pattern

Topics:

Model as a service

REST/gRPC serving

Horizontal scaling

Autoscaling inference

Resources:
https://kubernetes.io/docs/concepts/services-networking/service/

4️⃣ Model Serving Architectures
Topics

TensorFlow Serving

TorchServe

ONNX Runtime

Triton Inference Server

Containerized model deployment

Canary deployment

A/B testing

Resources

TensorFlow Serving
https://www.tensorflow.org/tfx/guide/serving

TorchServe
https://pytorch.org/serve/

NVIDIA Triton
https://developer.nvidia.com/nvidia-triton-inference-server

5️⃣ Feature Store Architecture
Topics

Offline vs online feature store

Consistency between training & serving

Feature versioning

Point-in-time correctness

Feature reuse

Resources

Feast Feature Store
https://docs.feast.dev/

Feature Store Concepts
https://www.tecton.ai/blog/what-is-a-feature-store/

6️⃣ MLOps Patterns
Topics

CI/CD for ML

Model versioning

Data versioning

Experiment tracking

Model registry

Reproducibility

Rollback strategy

Resources

MLflow
https://mlflow.org/docs/latest/index.html

DVC
https://dvc.org/doc

Kubeflow
https://www.kubeflow.org/docs/

7️⃣ Monitoring & Drift Detection
Topics

Data drift

Concept drift

Model performance decay

Prediction monitoring

Feature distribution monitoring

Alerting thresholds

Resources

Evidently AI (Open source monitoring)
https://docs.evidentlyai.com/

Google ML Monitoring
https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning

8️⃣ Scalability Patterns in ML
Topics

Distributed training

Data parallelism

Model parallelism

GPU scaling

Auto-scaling inference

Load balancing

Caching predictions

Batch vs stream tradeoffs

Resources

PyTorch Distributed
https://pytorch.org/tutorials/intermediate/ddp_tutorial.html

Horovod
https://horovod.ai/

9️⃣ Failure Handling in ML Systems
Topics

Model rollback

Canary releases

Feature fallback

Graceful degradation

Handling missing features

Handling skewed data

Retraining triggers

Resources

Google ML Production Best Practices
https://developers.google.com/machine-learning/guides/rules-of-ml

🔟 Real-World Case Studies
Topics

Recommendation systems architecture

Fraud detection pipeline

Search ranking system

Real-time personalization system

LLM serving architecture

Resources

Netflix ML Platform
https://netflixtechblog.com/

Uber Michelangelo Platform
https://eng.uber.com/michelangelo/

Airbnb ML Infrastructure
https://medium.com/airbnb-engineering

🧠 Hands-On Projects

Build batch inference pipeline

Deploy model as REST API

Implement A/B testing for model

Add monitoring dashboard

Simulate data drift

Build feature store prototype

Implement model version rollback

✅ Mastery Checklist

You’re strong in ML architecture when you can:

Design end-to-end ML system

Choose batch vs online correctly

Handle model versioning cleanly

Detect drift early

Scale inference safely

Design monitoring loop
