# LITERATURE REVIEW: AI Video Generation  
**Shahied Rustin 230500226**  
*(Video summarisation path)*  

---

## Relevant Research  

### Summary of Approaches:  
The main objective is to provide a way for long-form video content to be condensed into concise short-form video content. This research topic requires an understanding of AI video generation overview. Researchers are currently exploring various AI techniques for video generation. Foundational methods include Generative Adversarial Networks (GANs) and, more recently, Diffusion Models, often combined with Large Language Models (LLMs) or Multimodal Large Language Models (MLLMs) for better prompt understanding and control.  

The general approach involves training these models on large datasets of video (or image sequences) to learn patterns of motion, appearance, and temporal consistency. Some approaches focus on specific tasks like text-to-video, image-to-video, or generating longer, coherent video sequences. LLMs are also being integrated not just for generation but also for video understanding (analyzing content), which will be crucial to this project’s main objective for video summarisation.  

---

## Comparison of Solutions Found So Far:  
Many solutions are still being developed as this is a cutting-edge research topic. Most advancements are hosted on actively developing open-source GitHub repositories, with little to no documentation published as academic journals or articles. However, the following two surveys are the most relevant to the topic:  

### Reviewed Surveys:  

| **Reference**                           | **Method / Approach**                                                                                   | **Tools / Tech Mentioned**                                            | **Findings**                                                                                                                                                             | **Limitations / Gaps**                                                                                                                                                      |
|-----------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Waseem & Shahzad (Dec 2024)**         | Survey/Review focusing on long video generation techniques.                                             | GANs, Diffusion Models, MLLMs, Video Generation Strategies, Datasets, Quality Metrics | Significant progress via MLLMs, but long video generation is complex. Challenges include planning, story development, and consistency. Divide-and-conquer approaches suggested. | Difficulty maintaining spatial/temporal consistency over long durations. Challenges in narrative planning and story development. Scalability issues for generating extended videos. |
| **ResearchGate Survey (Feb 2024)**      | Survey/Review focusing on GenAI & LLMs for video generation, understanding, streaming.                  | Generative AI (GANs, Diffusion implied), LLMs                         | GenAI/LLMs significantly advance video realism, understanding (info extraction), and streaming efficiency/personalization. Highlights innovative uses across the video lifecycle. | Highlights ongoing challenges and need for future research to fully integrate AI/video tech. Mentions potential ethical issues. Less specific focus on long video challenges.   |

---

## Critique  

### Strengths and Weaknesses of Existing Solutions:  

#### Strengths:  
- Current AI models (especially Diffusion Models guided by LLMs) demonstrate remarkable capabilities in generating short, visually impressive video clips with good adherence to text prompts (noted by both surveys).  
- The integration of LLMs has improved semantic understanding and control over generated content.  
- Potential for automation in content creation, summarisation, and streaming optimization.  

#### Weaknesses:  
- **Waseem & Shahzad**: Strongly emphasize struggles with long-term consistency (spatial and temporal) and the lack of sophisticated narrative understanding or planning capabilities in current models, making coherent long video generation a major hurdle.  
- **ResearchGate Survey**: Points to the need for better integration across video tasks (generation, understanding, streaming) and raises ethical concerns, critical weaknesses in broader application contexts.  
- Computational hardware requirements for training and deploying state-of-the-art models remain a significant barrier.  

---

## Influence on Project Direction:  
The insights from these surveys suggest several potential project directions:  
1. **Bridging Generation and Understanding**: Inspired by the ResearchGate survey's broader scope, a project could explore feedback loops where AI video understanding models analyze generated content to iteratively refine the generation process for better quality or specific attribute control.  
2. **Efficiency and Accessibility**: While not the primary focus of these surveys, the implicit limitation of computational hardware cost suggests value in projects focused on creating more efficient models or techniques (like model distillation or quantization, although that’s a separate research area) to make advanced video generation more accessible.  

Based on these sources, tackling the challenge of AI video summarisation appears to be a particularly relevant and impactful area for future work. A significant factor to keep in mind is the rapid development of research in this area, where new models and techniques are released daily, meaning that these research papers become outdated but still relevant to how AI video generation aids video summarisation today.  

---

## References:  
1. **Waseem, F. and Shahzad, M. (2024).** "Video Is Worth a Thousand Images: Exploring the Latest Trends in Long Video Generation." [Online] Available at: [http://arxiv.org/abs/2412.18688](http://arxiv.org/abs/2412.18688) [Accessed 25 Apr. 2025].  
2. **Zhou, P. Y., Wang, L., Liu, Z., Hao, Y., Hui, P., Tarkoma, S. and Kangasharju, J. (2024).** "A Survey on Generative AI and LLM for Video Generation, Understanding, and Streaming." [Online] Available at: [https://doi.org/10.13140/RG.2.2.20978.89283](https://doi.org/10.13140/RG.2.2.20978.89283) [Accessed 25 Apr. 2025].  

---

## Additional Tools and Resources:  
- **Ltx Video GitHub**  
- **Mochi GitHub**  
- **TensorFlow**  
- **Matrix Library**  
- **Mendeley Reference**  
