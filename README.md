# AI Inventory Vision

On-edge learning system for real-time inventory classification and quantification. Hybrid AI approach combining multiple vision models with human-in-the-loop annotation for continuous improvement.

## Background

This project builds upon the initial work from [EdaxShifu](https://github.com/dako2/edaxshifu), developed during the hackathon at [https://partiful.com/e/hUU7NyM8EjHLxjMuJROs](https://partiful.com/e/hUU7NyM8EjHLxjMuJROs). The original system demonstrated self-classifying/learning capabilities with camera inputs, which we're now extending for commercial inventory management applications.

## Technical Architecture

### Core Vision Pipeline
- **YOLO**: Real-time object detection and localization for inventory items
- **ResNet/CNN**: Deep classification networks for fine-grained item recognition
- **Gemini**: Multimodal AI for complex scene understanding and contextual analysis
- **Human Annotation**: Active learning loop with human validators for edge cases and model improvement

### On-Edge Learning Capabilities
- **Adaptive Classification**: Models continuously learn new inventory items without cloud dependency
- **Self-Improving Accuracy**: Human annotations feed back into training pipeline
- **Multi-Model Ensemble**: Combines strengths of YOLO's speed, ResNet's accuracy, and Gemini's reasoning
- **Edge Deployment**: Full inference and learning happens on-device for privacy and latency

## Key Features

- **Hybrid AI Stack**: YOLO + ResNet/CNN + Gemini working in concert
- **Active Learning Loop**: Human annotators improve model performance over time
- **On-Edge Processing**: No cloud dependency for core operations
- **Real-time Classification**: Instant item identification and quantity estimation
- **Continuous Learning**: Models adapt to new products and packaging without retraining from scratch

## Use Cases

### Restaurant Inventory (B2B)
- Automated stock counts with visual verification
- Portion size monitoring and consistency tracking
- Waste reduction through predictive analytics
- Labor cost savings on manual inventory tasks

### Future Expansion (B2C)
- Home pantry management
- Small business inventory tracking

## Tags

`yolo` `resnet` `cnn` `gemini-ai` `edge-computing` `on-device-learning` `active-learning` `human-in-the-loop` `computer-vision` `inventory-management` `restaurant-tech` `b2b-saas` `object-detection` `multimodal-ai` `ensemble-learning` `continuous-learning` `python` `real-time-inference`