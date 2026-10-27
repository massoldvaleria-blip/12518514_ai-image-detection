
# Detecting AI-Generated Images: How Well Do Detectors Age?

## Project idea

**Project type:** Bring your own method

I want to train a deep learning model to distinguish real images from AI-generated images. Then I want to test how well it works on images from newer image generators. The main question is whether a detector trained on older AI images becomes less reliable as image generation improves.

## Planned approach

I plan to use an existing convolutional neural network (CNN) for image classification (real or AI-generated). I will train it on older AI-generated images and evaluate it on both familiar and newer image data. I also plan to try a small change to the model or its training and compare the results using accuracy and F1-score.

## Datasets

- **Training:** [CIFAKE](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images) contains 60,000 real images and 60,000 images generated with Stable Diffusion 1.4. The images are 32 × 32 pixels.
- **Testing:** I plan to use the CIFAKE test set and a subset of [MS COCOAI](https://huggingface.co/datasets/Rajarshi-Roy-research/Defactify_Image_Dataset), which contains real images and images from newer generators, including Stable Diffusion 3, DALL-E 3 and Midjourney v6.

The datasets also differ in image content and resolution, so a performance difference would not necessarily be caused only by the newer generators.

## Related papers

1. Bird, J. J., & Lotfi, A. (2024). *CIFAKE: Image Classification and Explainable Identification of AI-Generated Synthetic Images.* IEEE Access. https://doi.org/10.1109/ACCESS.2024.3356122

2. Park, J., & Owens, A. (2025). *Community Forensics: Using Thousands of Generators to Train Fake Image Detectors.* CVPR. https://openaccess.thecvf.com/content/CVPR2025/html/Park_Community_Forensics_Using_Thousands_of_Generators_to_Train_Fake_Image_CVPR_2025_paper.html

## Work plan

| Task | Estimated time |
| --- | ---: |
| Read papers and plan the project | 4 h |
| Get and prepare the datasets | 5 h |
| Select and adapt a neural network | 6 h |
| Train and fine-tune the model | 9 h |
| Test and compare results | 5 h |
| Build a small demo | 3 h |
| Write the final report | 5 h |
| Prepare the presentation | 3 h |
| **Total** | **40 h** |

## AI assistance

I used ChatGPT to brainstorm project ideas and Deep Research to find relevant datasets and scientific papers.
