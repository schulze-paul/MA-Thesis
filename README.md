<h1 align=center>Computational Models for the Growth of Closed Bacterial Cell Envelopes</h1>

<h5 align=center>Python, Cython, C++, Rust, Maturin, NumPy, SciPy, Matplotlib, TensorBoard<h5>


<h6 align="center"><a href="https://schulze-paul.github.io">Paul Schulze</a></h6>

<h6 align=center>Technical University of Munich</h6>
	
<p align=center>
	<a href="https://raw.githubusercontent.com/schulze-paul/MA-Thesis/master/3812049557.pdf">Thesis</a> • <a href="https://raw.githubusercontent.com/schulze-paul/MA-Thesis/master/Paul_schulze_master_final_presentation.pdf">Presentation</a>

<div align="center">
    <img height=600 src="https://github.com/schulze-paul/MA-Thesis/blob/main/cylinder-random.png?raw=true">
</div>

<h1 align=center >Abstract</h1>
Bacterial shape plays a crucial role in their survival and function. The shape
of bacteria is mainly determined by the cell wall, a polymeric envelope providing structural support and protection to the cell. Interestingly, bacteria
maintain their distinct shape with outstanding precision and its morphology
is highly robust to perturbations of the external conditions. While the proteins involved in the growth of the cell wall have been studied extensively,
how the local properties of the cell envelope direct the growth process to
achieve such precise morphological control remains a puzzle. In this context,
mechanical and geometrical cues have been proposed as potential feedback
mechanisms contributing to robust shape preservation.
The central objective of this thesis is to explore bacterial shell growth
driven by mechanical and geometrical laws. To this end, a specialized simulation framework is developed. We model the cell wall as a linear elastic
material and shell growth as a stochastic process with rates defined in terms
on the local mechanical or geometrical properties.
Two models of the bacterial shell are implemented. First, a springbased model is developed. This model is computationally efficient and provides a simplified framework to understand cell wall growth. This model
however shows undesired deviations from linear elasticity. This motivated
the development of an alternative model based on finite elements (FEM).
The model introduces localized growth to the classical mechanics finite element framework and shows the expected response of linear elastic material.
Both models are integrated into a unified simulation package. The computational package provides a practical and insightful tool to explore cell
envelope growth, thus contributing to the study and the understanding of
bacteria and their remarkable adaptability.
We use the FEM setup to study growth in spherical and rod-shaped vessels. We find that a strain-dependent growth law reduces the roughness of
the surface and surface stresses compared to purely random growth. Furthermore, inspired by the observations in rod-shaped bacteria, we find a
growth law combining strain and curvature information leading to robust
lengthening of the cell with no change in the cell’s radius.
This thesis reinforces the role of strain sensing in shape preservation and
offers valuable insights into the operation of strain-based growth.
