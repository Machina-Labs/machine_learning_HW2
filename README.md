# Generative Modeling of 3D Point Clouds for Metrology Using Diffusion Models
## Objective
In metrology, precise measurements of manufactured parts are essential for quality control. Laser scanners generate 3D point clouds representing these parts, but scanning limitations can result in missing data, noise, or artifacts. Collecting a diverse dataset of defective and non-defective parts is also challenging. The goal is to develop a generative diffusion model to:

- Reconstruct and denoise point clouds by filling missing regions and removing noise.
- Generate synthetic defective point clouds for training machine learning models in automated inspection.

## Assignment Tasks
1. Problem Understanding and Requirement Analysis
Deliverable:
Discuss issues like incomplete data, noise, and limited defective part data.
Justify model selection for reconstruction, denoising, and synthetic data generation.
2. Data Acquisition and Exploration
Dataset Creation:

Use a publicly available dataset (e.g., ShapeNet) or simulate laser scans of CAD models, introducing noise and missing data patterns.

### Deliverable:
Summary of dataset acquisition or simulation.
Visualizations of sample point clouds with defects and noise.
Scripts or notebooks for preprocessing.
Description of preprocessing steps and parameters.

### Design and Implementation of the Model
#### Model Objectives:
- Train the model to reconstruct missing regions and denoise point clouds.
- Generate realistic defective point clouds for training defect detection models.
- Source code with detailed comments.
- Explanation of architectural choices and how they address the problem.
- Define loss functions (e.g., Chamfer Distance, Earth Mover's Distance).
- Set hyperparameters (learning rate, batch size, epochs).
- Evaluate reconstruction and denoising using metrics like Chamfer Distance.
- Assess the realism of synthetic defective point clouds.
#### Deliverable:
- Evaluation scripts and a report with quantitative results and visual comparisons.
- Integration with Metrology Applications
- Use synthetic data to train or augment a defect detection model.

## Submission
In order to submit the assignment, do the following:
1. Navigate to GitHub's project import page: [https://github.com/new/import](https://github.com/new/import)
2. In the box titled "Your old repository's clone URL", paste the homework repository's link: [https://github.com/Machina-Labs/machine_learning_hw2](https://github.com/Machina-Labs/machine_learning_HW2)
3. In the box titled "Repository Name", add a name for your local homework (ex. `machine_learning_soln`)
4. Set privacy level to "Public", then click "Begin Import" button at bottom of the page.
5. Develop your homework solution in the cloned repository and push it to Github when you're done. Extra points for good Git hygiene.
6. Send us the link to your repository.
